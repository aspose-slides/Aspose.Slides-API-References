---
title: ForEach
second_title: Aspose.Slides Java API 参考
description: 表示一组旨在遍历不同模型对象的方法。
type: docs
url: /zh/com.aspose.slides/foreach/
---
**继承：**
java.lang.Object
```
public class ForEach
```

表示一组旨在遍历不同 [Presentation](../../com.aspose.slides/presentation) 模型对象的方法。如果您需要遍历并更改某些 Presentation' 元素的格式或内容，例如更改每个部分的格式，这些方法会很有用。

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)。 |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)。 |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback)。 |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Shape](../../com.aspose.slides/shape)。 |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 Shape。 |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | 遍历 [BaseSlide](../../com.aspose.slides/baseslide) 中的每个 [Shape](../../com.aspose.slides/shape)。 |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Paragraph](../../com.aspose.slides/paragraph)。 |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Paragraph](../../com.aspose.slides/paragraph)。 |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Portion](../../com.aspose.slides/portion)。 |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | 遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Portion](../../com.aspose.slides/portion)。 |

### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于遍历幻灯片的 Presentation |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | 将在每个幻灯片上调用的回调 |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于遍历母版幻灯片的 Presentation |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | 将在每个母版幻灯片上调用的回调 |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于遍历布局幻灯片的 Presentation |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | 将在每个布局幻灯片上调用的回调 |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Shape](../../com.aspose.slides/shape)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于遍历布局形状的 Presentation |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 将在每个形状上调用的回调

形状将在所有类型的幻灯片中遍历 —— \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 和 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback)。

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 Shape。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于遍历布局形状的 Presentation |
| includeNotes | boolean | 指示是否应在处理时包括 NotesSlides 的标志 |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 将在每个 shape 上调用的回调 |

--------------------

将在所有类型的幻灯片中遍历 Shape - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) and [NotesSlide](../../com.aspose.slides/notesslide) if needed. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

遍历 [BaseSlide](../../com.aspose.slides/baseslide) 中的每个 [Shape](../../com.aspose.slides/shape)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | 用于遍历布局形状的 Slide |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 将在每个 shape 上调用的回调 |

--------------------

[BaseSlide](../../com.aspose.slides/baseslide) 是以下的基类型： \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) and \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Paragraph](../../com.aspose.slides/paragraph)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于遍历段落的 Presentation |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 将在每个 paragraph 上调用的回调 |

--------------------

将在所有类型的幻灯片中遍历 Shape - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) and \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Paragraph](../../com.aspose.slides/paragraph)。
> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, (para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", para.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于迭代段落的 Presentation |
| includeNotes | boolean | 指示是否应在处理时包含 NotesSlides 的标志。 |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 将在每个段落上调用的回调 |

--------------------

在所有类型的幻灯片中将迭代 Shapes - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) and [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Portion](../../com.aspose.slides/portion)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于迭代部分的 Presentation |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 将在每个部分上调用的回调 |

--------------------

在所有类型的幻灯片中将迭代 Portions - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) and \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

遍历 [Presentation](../../com.aspose.slides/presentation) 中的每个 [Portion](../../com.aspose.slides/portion)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于迭代部分的 Presentation |
| includeNotes | boolean | 指示是否应在处理时包含 NotesSlides 的标志。 |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 将在每个部分上调用的回调 |

--------------------

在所有类型的幻灯片中将迭代 Portions - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) and [NotesSlide](../../com.aspose.slides/notesslide) |