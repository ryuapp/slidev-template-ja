# 複数のエントリー

`src` 属性を使用して、slides.md を複数のファイルに分割し、必要に応じて整理できます。

#### `slides.md`

```markdown
# ページ1

メインエントリーからのページ2

---
src: ./subpage.md
---
```

<br>

#### `subpage.md`

```markdown
# ページ2

別ファイルからのページ2 .
```

[詳しくはこちら](https://ja.sli.dev/guide/syntax.html#multiple-entries)
