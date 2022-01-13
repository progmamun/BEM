# BEM (Block, Element, Modifier)

- [BEM](https://en.bem.info/methodology/quick-start/) (Block, Element, Modifier) is a component-based approach to web development. The idea behind it is to divide the user interface into independent blocks. This makes interface development easy and fast even with a complex UI, and it allows reuse of existing code without copying and pasting.
- methodology BEM was invented at Yandex to develop sites which should be launched fast and supported for a long time. It helps to create extendable and reusable interface components.

---

# BEM

- Block: standalone component that is meaningful on its own.
- Element: part of a block that has no standalone meaning.
- Modifier: a different version of a block or an element.

```
.block {}
.block__element {}
.block__element--modifier {}

```

---

1. Think
2. Build

3. Architect

- 7-1 Pattern introduced by Hugo Giraudel.
  `7 different folders for partial Sass files, and 1 main Sass file to import all other files into a compiled CSS stylesheet`

### The 7 folders

- base/
- components/
- layout/
- pages/
- themes/
- abstracts/
- vendors/
