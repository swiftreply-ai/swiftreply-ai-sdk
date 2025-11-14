# SwiftReply AI — Official SDK

The official **JavaScript/TypeScript SDK** for interacting with the SwiftReply AI API.  
Designed to be lightweight, strongly typed, and developer-friendly.

---

## 🚀 Features

- ⚡ Simple, intuitive client
- 🧩 Fully typed request/response models
- 🔁 Auto-retry, timeouts & error handling
- 🌐 Works with Node.js, Deno, Next.js, Bun
- 📡 Supports streaming (SSE) responses
- 🔐 Secure by default

---

## 📦 Installation

```bash
npm install @swiftreply-ai/sdk
```

## 🔧 Quickstart
```bash
import SwiftReply from "@swiftreply-ai/sdk";

const client = new SwiftReply({
  apiKey: process.env.SR_API_KEY,
});

const result = await client.reply({
  prompt: "Generate a customer-friendly response:",
});

console.log(result.output);
```
## 📚 Documentation

Full API Reference → https://swiftreply.ai/docs

Usage Guide → docs/usage.md

JS Examples → /examples/basic-js

## 🧪 Example (Node.js)

```bash
cd examples/basic-js
npm install
node index.js
```
## 🛠 Project Structure
```bash
swiftreply-ai-sdk/
├─ packages/
│  ├─ javascript/
│  │  ├─ src/
│  │  │  ├─ client.ts
│  │  │  ├─ types.ts
│  │  │  └─ utils.ts
│  │  ├─ test/
│  │  ├─ package.json
│  │  └─ README.md
│  ├─ python/ (optional)
│  │  ├─ swiftreply/
│  │  └─ README.md
├─ examples/
│  └─ basic-js/
├─ docs/
│  └─ usage.md
├─ .github/
│  ├─ ISSUE_TEMPLATE.md
│  └─ PULL_REQUEST_TEMPLATE.md
└─ README.md

```

## 🤝 Contributing

We welcome SDK-level improvements (types, examples, linting, bug fixes).
Open an issue before major API changes.

## 📄 License
MIT © SwiftReply AI


