---
title: ForEach
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل مجموعة من الطرق المصممة للتكرار على كائنات النموذج المختلفة.
type: docs
url: /ar/com.aspose.slides/foreach/
---
**الوراثة:**
java.lang.Object
```
public class ForEach
```

يمثل مجموعة من الطرق المصممة لتكرار كائنات نموذج [Presentation](../../com.aspose.slides/presentation) مختلفة. يمكن أن تكون هذه الطرق مفيدة إذا كنت بحاجة إلى تكرار وتغيير تنسيق أو محتوى بعض عناصر الـ Presentation، مثل تغيير تنسيق كل جزء.

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

## الإنشاءات

| Constructor | Description |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## الأساليب

| Method | Description |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | تكرار كل \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) في الـ [Presentation](../../com.aspose.slides/presentation). |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | تكرار كل \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) في الـ [Presentation](../../com.aspose.slides/presentation). |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | تكرار كل \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) في الـ [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | تكرار كل [Shape](../../com.aspose.slides/shape) في الـ [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | تكرار كل  Shape  في الـ [Presentation](../../com.aspose.slides/presentation). |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | تكرار كل [Shape](../../com.aspose.slides/shape) في الـ [BaseSlide](../../com.aspose.slides/baseslide). |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | تكرار كل [Paragraph](../../com.aspose.slides/paragraph) في الـ [Presentation](../../com.aspose.slides/presentation). |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | تكرار كل [Paragraph](../../com.aspose.slides/paragraph) في الـ [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | تكرار كل [Portion](../../com.aspose.slides/portion) في الـ [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | تكرار كل [Portion](../../com.aspose.slides/portion) في الـ [Presentation](../../com.aspose.slides/presentation). |
### ForEach() {#ForEach--}
```
public ForEach()
```


### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```


تكرار كل \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) في الـ [Presentation](../../com.aspose.slides/presentation).

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

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الشرائح |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | رد نداء سيتم استدعاؤه لكل شريحة |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```


تكرار كل \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) في الـ [Presentation](../../com.aspose.slides/presentation).

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

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الشرائح الرئيسية |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | رد نداء سيتم استدعاؤه لكل شريحة رئيسية |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```


تكرار كل \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) في الـ [Presentation](../../com.aspose.slides/presentation).

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


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار شرائح التخطيط |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | رد نداء سيتم استدعاؤه لكل شريحة تخطيط |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```


تكرار كل [Shape](../../com.aspose.slides/shape) في الـ [Presentation](../../com.aspose.slides/presentation).

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

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار أشكال التخطيط |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | رد نداء سيتم استدعاؤه لكل شكل

--------------------

سيتم تكرار الأشكال في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```


تكرار كل  Shape  في الـ [Presentation](../../com.aspose.slides/presentation).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض لتكرار أشكال التخطيط |
| includeNotes | boolean | علامة تشير إلى ما إذا كان يجب تضمين شرائح الملاحظات في المعالجة. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | استدعاء سيتم تنفيذه لكل شكل |

--------------------

سيتم تكرار الأشكال في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) إذا لزم الأمر. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

تكرار كل [Shape](../../com.aspose.slides/shape) في [BaseSlide](../../com.aspose.slides/baseslide).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | شريحة لتكرار أشكال التخطيط |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | استدعاء سيتم تنفيذه لكل شكل |

[BaseSlide](../../com.aspose.slides/baseslide) هو النوع الأساسي لـ \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

تكرار كل [Paragraph](../../com.aspose.slides/paragraph) في [Presentation](../../com.aspose.slides/presentation).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض لتكرار الفقرات |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | استدعاء سيتم تنفيذه لكل فقرة |

سيتم تكرار الأشكال في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

تكرار كل [Paragraph](../../com.aspose.slides/paragraph) في [Presentation](../../com.aspose.slides/presentation).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض لتكرار الفقرات |
| includeNotes | boolean | علامة تشير إلى ما إذا كان يجب تضمين شرائح الملاحظات في المعالجة. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | استدعاء سيتم تنفيذه لكل فقرة |

سيتم تكرار الأشكال في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

تكرار كل [Portion](../../com.aspose.slides/portion) في [Presentation](../../com.aspose.slides/presentation).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض لتكرار الأجزاء |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | استدعاء سيتم تنفيذه لكل جزء |

الأجزاء ستُكرَّر في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

تكرار كل [Portion](../../com.aspose.slides/portion) في [Presentation](../../com.aspose.slides/presentation).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض لتكرار الأجزاء |
| includeNotes | boolean | علامة تشير إلى ما إذا كان يجب تضمين شرائح الملاحظات في المعالجة. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | استدعاء سيتم تنفيذه لكل جزء |

الأجزاء ستُكرَّر في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) |