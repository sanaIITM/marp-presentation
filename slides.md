---
marp: true
title: Product Documentation with Marp
author: Sana Bint Salim
theme: gaia
paginate: true
---

<!-- _class: lead -->

# 📑 Product Documentation with Marp

**Author:** Sana Bint Salim  
**Email:** 24f1000823@ds.study.iitm.ac.in  

---

## ✨ Why Marp?

- Write slides in **Markdown**
- Keep docs **maintainable in Git**
- Export to **HTML / PDF / PPTX / Images**
- Great for **technical teams**

---

## ⚙️ Installation

```bash
npm install -g @marp-team/marp-cli
```

Or one-time usage:

```bash
npx @marp-team/marp-cli@latest
```

---

## 📂 File Organization

```plaintext
presentation/
 ├── slides.md
 ├── images/
 ├── themes/
 └── package.json
```

- `slides.md` → Main presentation  
- `images/` → Assets (logos, diagrams)  
- `themes/` → Custom themes  

---

<!-- _backgroundImage: url('https://picsum.photos/1200/800?blur') -->
<!-- _backgroundSize: cover -->
<!-- _color: white -->

# 🌄 Background Image Example

This slide has a full **background image**  
with **custom white text** overlay.

---

## 📐 Mathematical Example

We can include math with KaTeX:

Algorithmic complexity of Merge Sort:

$$
T(n) = 2T\left(\frac{n}{2}\right) + O(n) \\
\Rightarrow T(n) = O(n \log n)
$$

---

## 🎨 Custom Styling Example

<style>
h1 {
  color: #d33682;
}
blockquote {
  font-style: italic;
  color: #555;
}
</style>

# Styled Header

> This blockquote uses custom CSS!

---

## 📬 Contact

For queries, reach me at:

**✉️ 24f1000823@ds.study.iitm.ac.in**

---
