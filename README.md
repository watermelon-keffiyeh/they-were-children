# They Were Children — Gaza Memorial

A documentary website recording children killed in Gaza since October 2023.

---

## Purpose

This site exists to resist the flattening of human lives into statistics.
Every number was a child. This is an attempt to hold that.

---

## Deploying to GitHub Pages

1. Fork or create a new repository
2. Place `index.html` at the root (or in a `/docs` folder)
3. Go to **Settings → Pages**
4. Set source to `main` branch, root folder (or `/docs`)
5. Your site will be live at `https://yourusername.github.io/repo-name`

---

## Adding Names

Names are stored in the `data` folder.
Each entry follows this structure:

```js
{
  name: "Child's full name",
  age: 7,
  detail: "One or two sentences. A specific detail, not a description of how they died.",
  source: "source",
  photo: null   // or: "photos/filename.jpg"
}
```

**Adding a photo:**
1. Place the image in a `/photos` folder in the repository
2. Set `photo: "photos/filename.jpg"`
3. Photos should be sourced from verified public reports or family-consented sources only

**Via GitHub:**
- Open a Pull Request with the new entry
- Or open an Issue with the information and a maintainer will add it

---

## Principles

- **Accuracy over comprehensiveness** — a smaller verified record is better than a large unverified one
- **Open source** — anyone can verify, correct, or contribute

---

## License

Content: CC BY 4.0 (share with attribution)
Code: MIT
