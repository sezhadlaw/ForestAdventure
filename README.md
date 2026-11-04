# Forest Adventure

A 2D mobile platformer by **Serzhan Karishal**, developed in Unity.
Explore forest levels, jump between platforms, collect coins and reach the exit.

## Open the project

1. Clone this repository.
2. In Unity Hub, add the repository folder as a project.
3. Use Unity **6000.6.1f1**, as recorded in `ProjectSettings/ProjectVersion.txt`.
4. Open `Assets/MainMenu.unity` and enter Play mode.

Unity generates its Library folder locally. Assets, Packages and ProjectSettings
are versioned; Library, Temp, Logs, UserSettings and builds are excluded.

## Scenes and controls

- `MainMenu`: Play and Quit.
- `Level1`, `Level2`, `Level3`: gameplay levels.
- Mobile controls: movement joystick and jump button.
- Pause: Resume, Restart and Menu. The pause script stops gameplay time.

The scene list includes MainMenu and all three levels. Project settings use
Visible Meta Files and Force Text serialization.

## Design and validation

The proposed target is Android in landscape orientation. The draft design
document is in `Docs/Forest_Adventure_GDD_Draft.pdf`.

Before submission, manually check menu navigation, pause/resume, restart and
level progression. Capture the HUD on a 16:9 phone, a notch phone and a 4:3
tablet in Device Simulator. These runtime and device checks have not been
performed as part of this repository upload.

The GDD still needs confirmation of asset authors/source links and final scope.
See `AI_LOG.txt` for disclosed AI assistance.
