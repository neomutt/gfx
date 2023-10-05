# Striped Highlighting

Since 2023-08-01, NeoMutt has supported striped highlighting of the Help Screen.
It's enabled by default, using alternate lines of bold for emphasis.

### disable.rc

```sh
color pager_even default default
color pager_odd  default default
```

![plain.png](https://github.com/neomutt/gfx/raw/main/stripes/plain.png)

---

### reverse.rc

```sh
color pager_even reverse default default
color pager_odd          default default
```

![reverse.png](https://github.com/neomutt/gfx/raw/main/stripes/reverse.png)

---

### bold.rc

```sh
color pager_even bold default default
color pager_odd       default default
```

![bold.png](https://github.com/neomutt/gfx/raw/main/stripes/bold.png)

---

### underline.rc

```sh
color pager_even underline default default
color pager_odd            default default
```

![underline.png](https://github.com/neomutt/gfx/raw/main/stripes/underline.png)

---

### colour.rc

```sh
color pager_odd  blue  cyan
color pager_even black white
```

![colour.png](https://github.com/neomutt/gfx/raw/main/stripes/colour.png)

---

### light-grey.rc

```sh
color pager_even default color253
color pager_odd  default default
```

![light-grey.png](https://github.com/neomutt/gfx/raw/main/stripes/light-grey.png)

---

### dark-grey.rc

```sh
color pager_even default color234
color pager_odd  default default
```

![dark-grey.png](https://github.com/neomutt/gfx/raw/main/stripes/dark-grey.png)

