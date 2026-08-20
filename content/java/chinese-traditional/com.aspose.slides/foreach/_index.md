---
title: ForEach
second_title: Aspose.Slides for Java API 參考文件
description: 表示一組旨在遍歷不同模型物件的方法。
type: docs
url: /zh-hant/com.aspose.slides/foreach/
---
**繼承：**
java.lang.Object
```
public class ForEach
```

代表一組旨在遍歷不同 [Presentation](../../com.aspose.slides/presentation) 模型對象的方法。如果您需要遍歷並更改某些 Presentation 元素的格式或內容，例如更改每個部分的格式，這些方法會很有用。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, (portion, para, slide, index) ->
>          portion.getPortionFormat().setLatinFont(new FontData("Times New Roman")));
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 建構子

| Constructor | Description |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## 方法

| Method | Description |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | 遍歷每個 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation)。 |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | 遍歷每個 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation)。 |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | 遍歷每個 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation)。 |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍歷每個 [Shape](../../com.aspose.slides/shape) 在 [Presentation](../../com.aspose.slides/presentation)。 |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍歷每個  Shape  在 [Presentation](../../com.aspose.slides/presentation)。 |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍歷每個 [Shape](../../com.aspose.slides/shape) 在 [BaseSlide](../../com.aspose.slides/baseslide)。 |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | 遍歷每個 [Paragraph](../../com.aspose.slides/paragraph) 在 [Presentation](../../com.aspose.slides/presentation)。 |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | 遍歷每個 [Paragraph](../../com.aspose.slides/paragraph) 在 [Presentation](../../com.aspose.slides/presentation)。 |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | 遍歷每個 [Portion](../../com.aspose.slides/portion) 在 [Presentation](../../com.aspose.slides/presentation)。 |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | 遍歷每個 [Portion](../../com.aspose.slides/portion) 在 [Presentation](../../com.aspose.slides/presentation)。 |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

遍歷每個 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, (slide, index) ->
>          slide.setName(String.format("Slide #%d", index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷投影片的 Presentation |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | 將對每個投影片呼叫的回呼 |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

遍歷每個 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, (slide, index) ->
>          slide.setName(String.format("Master Slide #%d", index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷母投影片的 Presentation |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | 將對每個母投影片呼叫的回呼 |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

遍歷每個 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, (layoutSlide, index) ->
>          layoutSlide.setName(String.format("Layout Slide #%d", index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷版面投影片的 Presentation |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | 將對每個版面投影片呼叫的回呼 |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

遍歷每個 [Shape](../../com.aspose.slides/shape) 在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, (shape, slide, index) ->
>          System.out.println(String.format("%s, index: %d", shape.getName(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷版面形狀的 Presentation |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 將對每個形狀呼叫的回呼 |

Shapes 將在所有類型的投影片中遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 和 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

遍歷每個  Shape  在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, (shape, slide, index) ->
>          System.out.println(String.format("%s, index: %d", shape.getName(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷版面形狀的 Presentation |
| includeNotes | boolean | 指示是否應在處理時包含 NotesSlides 的旗標。 |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 將對每個形狀呼叫的回呼 |

Shapes 將在所有類型的投影片中遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 和 [NotesSlide](../../com.aspose.slides/notesslide) 如有需要。

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

遍歷每個 [Shape](../../com.aspose.slides/shape) 在 [BaseSlide](../../com.aspose.slides/baseslide)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, (slide, index) ->
>          ForEach.shape(slide, (shape, baseSlide, shapeIndex) ->
>                  System.out.println(String.format("%s, index: %d", shape.getName(), shapeIndex))));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | 用於遍歷版面形狀的 Slide |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 將對每個形狀呼叫的回呼 |

[BaseSlide](../../com.aspose.slides/baseslide) 是 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 和 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 的基礎類型。

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

遍歷每個 [Paragraph](../../com.aspose.slides/paragraph) 在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, (para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", para.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷段落的 Presentation |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 將對每個段落呼叫的回呼 |

Shapes 將在所有類型的投影片中遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 和 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

遍歷每個 [Paragraph](../../com.aspose.slides/paragraph) 在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, (para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", para.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷段落的 Presentation |
| includeNotes | boolean | 指示是否應在處理時包含 NotesSlides 的旗標。 |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 將對每個段落呼叫的回呼 |

Shapes 將在所有類型的投影片中遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 和 [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

遍歷每個 [Portion](../../com.aspose.slides/portion) 在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, (portion, para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", portion.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷部分的 Presentation |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 將對每個部分呼叫的回呼 |

Portions 將在所有類型的投影片中遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 和 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

遍歷每個 [Portion](../../com.aspose.slides/portion) 在 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, (portion, para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", portion.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於遍歷部分的 Presentation |
| includeNotes | boolean | 指示是否應在處理時包含 NotesSlides 的旗標。 |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 將對每個部分呼叫的回呼 |

Portions 將在所有類型的投影片中遍歷 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 和 [NotesSlide](../../com.aspose.slides/notesslide) |