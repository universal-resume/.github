# 🌐 Universal Resume

**Universal Resume** is an open-source initiative to **standardize resume content** using [JSON Schema](https://json-schema.org/) and to build tools on top of it — from validators and type-safe libraries to renderers and templates.  

---

## 🚀 Why Universal Resume?

### Why use a JSON file for your resume?
- 🔓 **Ownership & portability** — your resume is just data. No lock-in to a private service or proprietary tool.  
- 🔄 **Separation of content & design** — maintain the content once, render it into multiple formats (HTML, PDF, Markdown, etc.) with different templates.  
- 🛠 **Automated workflows** — integrate your resume into CI/CD pipelines, generate updated versions automatically, or even pull experience data from other sources.  
- 📊 **Machine-readable** — easy to parse, search, and integrate into job boards, ATS systems, or HR tools.  
- ✅ **Consistency & validation** — enforce required fields and enums so your data is always complete and well-structured.  
- 🌍 **Community-driven** — benefit from an open ecosystem of tools, templates, and validators instead of relying on closed platforms.  

### Why Universal Resume?
- **Standardized structure** — define resumes in a consistent, language-agnostic JSON format.  
- **Type-safety & validation** — ensure data integrity with required fields, enums, and validators.  
- **Ecosystem of tools** — libraries, renderers, and templates for developers and end-users.  
- **Open-source & community-driven** — contributions welcome!  

We are inspired by [json-resume](https://github.com/jsonresume) but diverged to fix long-standing issues, enforce stronger typing, add missing properties (See [details](https://github.com/universal-resume/json-schema?tab=readme-ov-file#differences-with-json-resume))
---

## 📦 Repositories

- **[json-schema](https://github.com/universal-resume/json-schema)**  
  The core [JSON Schema](https://json-schema.org/) definition of a resume.  
  Includes a dedicated section explaining differences from `json-resume`.

- **[ts-schema](https://github.com/universal-resume/ts-schema)**  
  A TypeScript implementation of the schema, written with [Effect](https://effect.website).  
  Provides both runtime validation and static typing. The JSON Schema is generated from this source of truth.

- **[html-renderer](https://github.com/universal-resume/html-renderer)**  
  A lightweight, self-hosted tool to render resumes from JSON into **printable HTML/PDF**.  
  Template-based: contribute your own themes or tweak existing ones.  

---

## 🛠️ Roadmap
- Fix and improve the schema in order to have a stable production ready version ASAP.
- Grow the ecosystem of **renderers** (web, mobile, CLI).  
- Add schema implementations for other languages (Python, Go, Rust…).  
- Provide **starter templates** for common use cases.  
- Encourage adoption as a **community-driven standard**.  

---

## 🤝 Contributing
We’d love your help! Whether it’s fixing a typo, adding new templates, proposing schema improvements, or porting the schema to another language — contributions are very welcome.  

👉 Check each repository’s README for contribution guidelines.

---

## 📜 License
All repositories under **Universal Resume** are open-sourced under the [MIT License](./LICENSE).
