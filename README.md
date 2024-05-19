# HDA GitHub Repository

This repository is dedicated to storing and managing Houdini Digital Assets (HDAs) using Git version control.

## Folder Structure
HDA/
│
├── HDAs/                               # Directory for HDAs (tracked by Git)
│   ├── Grid2Hemisphere.hda
│   └── .Grid2Hemisphere/               # Directory named after the HDA
│       ├── Grid2Hemisphere.hip         # Scene file
│       └── .Backup/                    # Hidden backup directory for the scene file
│           └── Grid2Hemisphere_backup1.hip   # Backup of the scene file
│
└── README.md                           # Project README file


- **HDAs/**: This directory contains the HDAs (Houdini Digital Assets) tracked by Git.
  - `Grid2Hemisphere.hda`: Example HDA file.
  - **.Grid2Hemisphere/**: Directory named after the HDA.
    - `Grid2Hemisphere.hip`: Scene file associated with the HDA.
    - **.Backup/**: Hidden backup directory for the scene file.
      - `Grid2Hemisphere_backup1.hip`: Backup of the scene file.

## Usage

1. Clone this repository to your local machine.
2. Place your HDAs in the `HDAs/` directory.
3. Each HDA should have its own directory with the same name preceded by a dot (e.g., `.HDAName/`).
4. Place associated scene files within the corresponding HDA directory.
5. Houdini will automatically create and manage backups in the `.Backup/` directory.

## Contributing

- If you have HDAs to contribute, feel free to fork this repository and submit a pull request.
- Ensure that each HDA has its own directory within the `HDAs/` folder and follows the specified structure.

## License

This project is licensed under the [MIT License](LICENSE).
