# Go Development & Debugging in VS Code Dev Container

## Quick Start

1. **Open your project in VS Code.**
2. **Add the files below to your repository.**
3. **Rebuild your Dev Container:**  
   - Press `F1` → `Dev Containers: Rebuild Container`
4. **Open `main.go`, set breakpoints, and press `F5` to debug!**

## Files Included

- `.devcontainer/devcontainer.json` — Adds Go support.
- `.devcontainer/Dockerfile` — Installs Go (if you want Dockerfile-based setup).
- `.vscode/launch.json` — Debug configuration for Go.
- `main.go` — Sample Go code for debugging.

## Troubleshooting

- Make sure Delve (`dlv`) is installed (`go install github.com/go-delve/delve/cmd/dlv@latest`).
- If breakpoints don’t hit, use `"mode": "debug"` in your launch config.
- Permissions: On Linux/Mac, ensure VS Code and dlv have permission to debug (run as admin if needed).