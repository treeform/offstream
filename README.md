# Offstream

Offstream is a collection of uncommon CSS themes. The goal is to make themes
that sit outside common mainstream web design, with each one feeling quirky,
specific, and interesting in its own way.

The main use case is reference. You should be able to point an AI at one of
these examples and say, "make it like that." Each theme includes a CSS file
and an HTML page that acts as both a showcase and a usage guide.

The themes try to use very minimal CSS. They rely mostly on plain HTML tag
names like `h1`, `p`, `blockquote`, `table`, `form`, `button`, and `nav`
instead of large sets of CSS classes. Classes are only used when plain tags
are not enough.

## Themes

- [`2001`](https://treeform.github.io/offstream/2001/) - A HAL 9000 inspired interface theme.
- [`tufte`](https://treeform.github.io/offstream/tufte/) - A sparse document style inspired by Edward Tufte.
- [`bb05`](https://treeform.github.io/offstream/bb05/) - An experimental theme.

## Publishing

GitHub Pages serves these files directly from the repo. There is no build
step. The Pages workflow copies the static files into a deploy artifact and
publishes them whenever `master` changes.
