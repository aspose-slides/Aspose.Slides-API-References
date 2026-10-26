---
title: ForEach
second_title: Aspose.Slides for Android via Java API 參考
description: 代表一組旨在遍歷不同模型對象的方法。
type: docs
url: /zh-hant/com.aspose.slides/foreach/
---
**Inheritance:**
java.lang.Object
```
public class ForEach
```

表示一組旨在遍歷不同 [Presentation](../../com.aspose.slides/presentation) 模型對象的方法。如果您需要遍歷並更改某些 Presentation 元素的格式或內容，例如更改每個 portion 的格式，這些方法會非常有用。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```
## 建構子

| 建構式 | 說明 |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)。 |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)。 |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback)。 |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Shape](../../com.aspose.slides/shape)。 |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個  Shape 。 |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍歷 [BaseSlide](../../com.aspose.slides/baseslide) 中的每個 [Shape](../../com.aspose.slides/shape)。 |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Paragraph](../../com.aspose.slides/paragraph)。 |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Paragraph](../../com.aspose.slides/paragraph)。 |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Portion](../../com.aspose.slides/portion)。 |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | 遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Portion](../../com.aspose.slides/portion)。 |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷投影片的 Presentation |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | 會在每張投影片上被呼叫的回呼函式 |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷主投影片的 Presentation |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | 會在每個主投影片上被呼叫的回呼函式 |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷版面投影片的 Presentation |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | 會在每個版面投影片上被呼叫的回呼函式 |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Shape](../../com.aspose.slides/shape)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷版面形狀的 Presentation |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 會在每個形狀上被呼叫的回呼函式

形狀將在所有類型的投影片中被遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 以及 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個  Shape 。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷版面形狀的 Presentation |
| includeNotes | boolean | 指示是否應將 NotesSlides 包含在處理中的旗標。 |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 會在每個形狀上被呼叫的回呼函式

形狀將在所有類型的投影片中被遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)、\#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 以及如有需要的 [NotesSlide](../../com.aspose.slides/notesslide)。

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

遍歷 [BaseSlide](../../com.aspose.slides/baseslide) 中的每個 [Shape](../../com.aspose.slides/shape)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | 用於遍歷版面形狀的 Slide |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 會在每個形狀上被呼叫的回呼函式

[BaseSlide](../../com.aspose.slides/baseslide) 是 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 以及 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 的基礎類型。

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Paragraph](../../com.aspose.slides/paragraph)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷段落的 Presentation |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 會在每個段落上被呼叫的回呼函式

段落將在所有類型的投影片中被遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 以及 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Paragraph](../../com.aspose.slides/paragraph)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷段落的 Presentation |
| includeNotes | boolean | 指示是否應將 NotesSlides 包含在處理中的旗標。 |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 會在每個段落上被呼叫的回呼函式

段落將在所有類型的投影片中被遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)、\#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 以及 [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Portion](../../com.aspose.slides/portion)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷 portions 的 Presentation |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 會在每個 portion 上被呼叫的回呼函式

Portion 將在所有類型的投影片中被遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 以及 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

遍歷 [Presentation](../../com.aspose.slides/presentation) 中的每個 [Portion](../../com.aspose.slides/portion)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷 portions 的 Presentation |
| includeNotes | boolean | 指示是否應將 NotesSlides 包含在處理中的旗標。 |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 會在每個 portion 上被呼叫的回呼函式

Portion 將在所有類型的投影片中被遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)、\#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 以及 [NotesSlide](../../com.aspose.slides/notesslide) |