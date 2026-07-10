---
title: ForEach
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一组旨在遍历不同模型对象的方法。
type: docs
url: /zh/com.aspose.slides/foreach/
---
**继承：**
java.lang.Object
```
public class ForEach
```

表示一组旨在遍历不同 [Presentation](../../com.aspose.slides/presentation) 模型对象的方法。如果您需要遍历并更改某些 Presentation 元素的格式或内容，例如更改每个部分的格式，这些方法会很有用。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## Methods

| Method | Description |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | Iterate each \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) in the [Presentation](../../com.aspose.slides/presentation). |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | Iterate each \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) in the [Presentation](../../com.aspose.slides/presentation). |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | Iterate each \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) in the [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterate each [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterate each  Shape  in the [Presentation](../../com.aspose.slides/presentation). |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterate each [Shape](../../com.aspose.slides/shape) in the [BaseSlide](../../com.aspose.slides/baseslide). |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Iterate each [Paragraph](../../com.aspose.slides/paragraph) in the [Presentation](../../com.aspose.slides/presentation). |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Iterate each [Paragraph](../../com.aspose.slides/paragraph) in the [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | Iterate each [Portion](../../com.aspose.slides/portion) in the [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | Iterate each [Portion](../../com.aspose.slides/portion) in the [Presentation](../../com.aspose.slides/presentation). |
### ForEach() {#ForEach--}
```
public ForEach()
```


### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

Iterate each \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to iterate slides |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Callback that will be invoked for each slide |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

Iterate each \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to iterate master slides |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Callback that will be invoked for each master slide |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

Iterate each \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to iterate layout slides |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Callback that will be invoked for each layout slide |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

Iterate each [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to iterate layout shapes |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback that will be invoked for each shape

--------------------

Shapes will be iterated in all type of slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) and \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

Iterate each  Shape  in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to iterate layout shapes |
| includeNotes | boolean | Flag that indicates whether NotesSlides should be included in processing. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback that will be invoked for each shape

--------------------

Shapes will be iterated in all type of slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) and [NotesSlide](../../com.aspose.slides/notesslide) if needed. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

Iterate each [Shape](../../com.aspose.slides/shape) in the [BaseSlide](../../com.aspose.slides/baseslide).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide to iterate layout shapes |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback that will be invoked for each shape

--------------------

[BaseSlide](../../com.aspose.slides/baseslide) is the base type for \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) and \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

Iterate each [Paragraph](../../com.aspose.slides/paragraph) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to iterate paragraphs |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback that will be invoked for each paragraph

--------------------

Shapes will be iterated in all type of slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) and \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

Iterate each [Paragraph](../../com.aspose.slides/paragraph) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to iterate paragraphs |
| includeNotes | boolean | Flag that indicates whether NotesSlides should be included in processing. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback that will be invoked for each paragraph

--------------------

Shapes will be iterated in all type of slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) and [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

Iterate each [Portion](../../com.aspose.slides/portion) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to iterate portions |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback that will be invoked for each portion

--------------------

Portions will be iterated in all type of slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) and \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)

遍历 [Presentation](../../com.aspose.slides/presentation) 中的 [Portion](../../com.aspose.slides/portion)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于遍历部分的 Presentation |
| includeNotes | boolean | 指示是否应在处理时包括 NotesSlides 的标志。 |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 将在每个部分被调用的回调 |

--------------------

将在所有类型的幻灯片中遍历部分 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 和 [NotesSlide](../../com.aspose.slides/notesslide) |