### 1. **Open Command Palette**

Press `Cmd` + `Shift` + `P` to open the Command Palette.

### 2. **Choose Install from VSIX**

Type `Extensions: Install from VSIX...` and select it.

### 3. **Select the VSIX File**

It's located in _extension

A file picker will appear. Navigate to the location of your `.vsix` file, select it, and click **Open**.

The extension will be installed automatically.

---

To build the extension yourself:
1. `npm i` in the root and _extension folder
2. go to _extension
    a. `npm run build` 
    b. `npm run bundle`
    c. `npx vsce package`