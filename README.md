# DevKit — Developer Toolbox

**Small tools. Faster workflows.**

DevKit is a modern, browser-based collection of essential developer utilities designed to make everyday development tasks faster and easier. It brings commonly used tools into one clean, responsive interface without requiring a backend, installation, or account.

Built with HTML5, CSS3, and vanilla JavaScript, DevKit runs directly in your browser and is designed for simple deployment through GitHub Pages.

## ✨ Features

### 🧩 JSON Formatter & Validator
- Format and beautify JSON data.
- Minify JSON for compact output.
- Validate JSON syntax.
- Display helpful syntax error information.
- Copy formatted output to the clipboard.
- Download formatted JSON files.
- Choose indentation settings.

### 🔐 Base64 Encoder & Decoder
- Encode text into Base64.
- Decode Base64 into readable text.
- Support Unicode text, including Bangla and emoji.
- Validate malformed input.
- Copy or transfer converted output.
- Clear input and output when needed.

Base64 is an encoding format, not an encryption method.

### 🆔 UUID Generator
- Generate UUID version 4 identifiers.
- Generate multiple UUIDs in one operation.
- Copy individual identifiers.
- Copy all generated identifiers.
- Configure the number of identifiers.
- Display generated IDs in a readable format.

### 🎨 Color & Gradient Studio
- Pick colors using a native color picker.
- Work with HEX, RGB, and HSL color formats.
- Preview colors in real time.
- Create custom CSS gradients.
- Adjust gradient direction and angle.
- Use gradient presets.
- Copy generated CSS directly into your project.

### 🔗 URL Encoder & Decoder
- Encode URL components.
- Decode encoded URL components.
- Parse valid absolute URLs.
- Inspect protocol, hostname, pathname, query string, and hash.
- Handle special characters and Unicode.
- Validate malformed URLs and encoding sequences.

### 📝 Text Tools
- Count characters and words.
- Count lines and paragraphs.
- Count characters without spaces.
- Convert text to uppercase or lowercase.
- Convert text to title case or sentence case.
- Remove unnecessary whitespace.
- Trim leading and trailing whitespace.
- Remove duplicate lines.
- Sort lines alphabetically.
- Reverse text.
- Copy transformed output.

### ⏱️ Timestamp Converter
- Convert Unix timestamps into readable dates.
- Support seconds and milliseconds.
- Convert date and time values into Unix timestamps.
- Display UTC and local browser time.
- Generate ISO 8601 date strings.
- View the current Unix timestamp.
- Copy individual timestamp results.

### 🔎 Global Tool Search
- Search available tools by name or keyword.
- Find utilities quickly.
- Navigate directly to the selected tool.
- Access tools from a unified interface.

### 🌗 Modern User Interface
- Premium dark theme.
- Light theme option.
- Responsive desktop, tablet, and mobile layouts.
- Sidebar navigation.
- Interactive dashboard.
- Recently used tools.
- Smooth transitions and clear visual feedback.
- Toast notifications and inline validation messages.
- Keyboard-accessible controls.

### 🔒 Privacy-Focused Design
- Core operations are designed to run locally in the browser.
- No backend or database is required.
- No API keys or user accounts are needed.
- User-entered tool data is not intentionally sent to external services.
- Local storage can be used for interface preferences and recent tools.

Avoid entering sensitive information into any online tool unless you understand its implementation and security limitations.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, responsive layouts, and themes |
| Vanilla JavaScript | Tool functionality and interactions |
| Browser APIs | Clipboard, UUID generation, dates, encoding, and local storage |
| GitHub Pages | Static website hosting |

DevKit does not require a JavaScript framework, package manager, build process, or backend server.

## 📂 Project Structure

The project is designed to use a single HTML file.

```text
DevKit/
├── index.html
└── README.md
```

- `index.html` contains the application's HTML, CSS, and JavaScript.
- `README.md` documents the project for GitHub visitors.

## 🚀 Getting Started

### Option 1: Run Locally

1. Clone the repository.

   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   ```

2. Open the project folder.

   ```bash
   cd YOUR-REPOSITORY
   ```

3. Open `index.html` in your browser.

No installation or build command is required.

Some browser APIs, particularly clipboard access, may behave differently when opening a file directly. Test those features through a local development server or HTTPS if necessary.

### Option 2: Deploy with GitHub Pages

1. Create a repository on GitHub.
2. Upload `index.html` and `README.md` to the repository root.
3. Open the repository's **Settings**.
4. Select **Pages** from the sidebar.
5. Under the build and deployment settings, select **Deploy from a branch**.
6. Select your deployment branch, usually `main`.
7. Select the `/ (root)` folder.
8. Click **Save**.
9. Wait for GitHub Pages to publish the website.

Your website will be available at a URL similar to:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

Replace the placeholders with your actual GitHub username and repository name.

For a user or organization repository named `YOUR-USERNAME.github.io`, the published address follows a different format.

See the official [GitHub Pages documentation](https://docs.github.com/en/pages) for additional configuration details.

## 💡 How to Use DevKit

1. Open the website in your browser.
2. Select a tool from the sidebar or dashboard.
3. Enter your data in the input field.
4. Choose the desired operation.
5. Review the output and any validation messages.
6. Copy or download the result where supported.

Each utility is designed to perform its core task without a separate backend service.

## 🧪 Compatibility

DevKit is intended for modern browsers that support the required JavaScript and browser APIs.

Recommended browsers:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Apple Safari

Some features may depend on browser permissions, secure contexts, or API support. A deployed HTTPS website generally provides a more consistent environment for clipboard functionality than opening a local HTML file.

## 🎯 Project Goals

DevKit aims to:

- Bring common developer utilities together in one place.
- Reduce repetitive development tasks.
- Provide a clean and intuitive user experience.
- Keep the application lightweight and easy to deploy.
- Demonstrate practical frontend development using vanilla JavaScript.
- Provide useful tools without requiring an account or backend.

## 🔮 Future Improvements

Potential future enhancements include:

- Additional developer utilities.
- JSON tree visualization.
- JWT structure inspection without server-side verification.
- Hash generation using the Web Crypto API.
- QR code generation.
- CSS box-shadow generator.
- HTML entity encoder and decoder.
- Color palette generation.
- Downloadable text and configuration files.
- Improved keyboard shortcuts.
- More customizable interface settings.

These are possible future additions and should not be considered implemented until they are actually added to the application.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a new branch for your changes.
3. Implement and test your improvements.
4. Commit your changes.
5. Open a pull request describing the changes.

Please keep the application lightweight and preserve its single-file architecture unless the project requirements change.

## 📄 License

Choose and add an appropriate open-source license before distributing the project for reuse. If no license has been added, the repository should not be assumed to grant general permission to reuse, modify, or redistribute its code.

## 👨‍💻 Author

**Sahriar Ekhlas**

- GitHub: [@shadhinsahriar](https://github.com/shadhinsahriar)

---

**DevKit — Small tools. Faster workflows.**

Built for developers who value simplicity, speed, and a better workflow.
