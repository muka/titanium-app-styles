Titanium app.tss styles
===

Collection of classes I frequently use in Titanium

Mostly inspired by Foundation

Grid
---
A grid fitting at 100% splitted in 12 pieces. The sum must be 12

- `.row`
- `.grid[1-12]`

A sample menu item

```
<View class="row">
  <View class="grid2">
    <Label class="spacer" />
    <Label icon="fa-map" />
    <Label class="spacer" />
  </View>
  <View class="grid8">
    <Label class="hfit text-center" text="Menu item" />
  </View>
  <View class="grid2 absolute">
    <Label class="right" icon="fa-angle-right" />
    <Label class="spacer">
  </View>
</View>
```

Layouts
---

- `.absolute`
- `.horizontal`
- `.vertical`

Containers
---

- `.container`
- `.fit` or `.hfit` + `.vfit`
- `.wrapper` fit horizontally with a 2% padding on left/right

Text
---

- `.text-left`
- `.text-center`
- `.text-right`
- `.hr` Horizontal grey ruler

Text colors

- `.white`
- `.lightgrey`
- `.grey`
- `.darkgrey`
- `.black`

Text sizes

- `.title`
- `.bold`
- `.bigger`
- `.big`
- `.medium`
- `.small`
- `.smaller`

Spacers
---

[h]orizontal or [v]ertical spacer for layouts

- `.[h|v]spacer` spaces 5%
- `.[h|v]spacer[1-5]` from 10% to 50%

Positioning
---

Position with a 10 unit margin

- `.top`
- `.right`
- `.bottom`
- `.left`

Blocks
---

fixed heights blocks

- `.block` height 40
- `.block2` height 80
- `.block3` height 120

- `.block40` height 40%
- `.block80` height 80%
- `.block100` height 100%
