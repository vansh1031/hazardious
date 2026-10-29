# Hazardous Zone Detector — notes for Claude

## Ownership and credits (always)
- Developer / author of this project: **Vanshraj Singh Rathore — vanshraj.rathore.05227@gmail.com**.
- Use exactly this name wherever the project names an author or developer (README "Author", docs,
  about dialogs such as the launcher's About window, licence headers, new files).
- Do not add anyone else's name as author. If another person's name appears as author or developer
  (e.g. "Somya" from the original copy), replace it with the name above and tell the user.

## Platforms
- Runs on the NVIDIA Jetson Orin (Linux ARM64); keep Windows working too where the code allows
  (paths via `os.path`, text files opened with `encoding="utf-8"`, no hard-coded `/home/...` paths).
