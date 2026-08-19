---
title: ForEach
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایان‌گر یک گروه از روش‌هاست که برای تکرار بر روی اشیای مدل مختلف طراحی شده‌اند.
type: docs
url: /fa/com.aspose.slides/foreach/
---
**ارث‌بری:**  
java.lang.Object  
```
public class ForEach
```

نمایش یک گروه از روش‌ها که برای تکرار بر روی اشیای مدل مختلف [Presentation](../../com.aspose.slides/presentation) هدف‌گذاری شده‌اند. این روش‌ها می‌توانند مفید باشند اگر نیاز به تکرار و تغییر قالب‌بندی یا محتوای برخی عناصر Presentation داشته باشید، به عنوان مثال تغییر قالب‌بندی هر portion.

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
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## روش‌ها

| روش | توضیح |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) را تکرار کنید. |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) را تکرار کنید. |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) را تکرار کنید. |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر [Shape](../../com.aspose.slides/shape) را تکرار کنید. |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر  Shape  را تکرار کنید. |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | در [BaseSlide](../../com.aspose.slides/baseslide) هر [Shape](../../com.aspose.slides/shape) را تکرار کنید. |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر [Paragraph](../../com.aspose.slides/paragraph) را تکرار کنید. |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر [Paragraph](../../com.aspose.slides/paragraph) را تکرار کنید. |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر [Portion](../../com.aspose.slides/portion) را تکرار کنید. |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | در [Presentation](../../com.aspose.slides/presentation) هر [Portion](../../com.aspose.slides/portion) را تکرار کنید. |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

در [Presentation](../../com.aspose.slides/presentation) هر \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اسلایدها |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Callback که برای هر اسلاید فراخوانی می‌شود |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

در [Presentation](../../com.aspose.slides/presentation) هر \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اسلایدهای اصلی |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Callback که برای هر اسلاید اصلی فراخوانی می‌شود |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

در [Presentation](../../com.aspose.slides/presentation) هر \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اسلایدهای طرح |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Callback که برای هر اسلاید طرح فراخوانی می‌شود |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

در [Presentation](../../com.aspose.slides/presentation) هر [Shape](../../com.aspose.slides/shape) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اشکال طرح |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback که برای هر Shape فراخوانی می‌شود |

Shapes در تمام انواع اسلایدها تکرار می‌شوند - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

در [Presentation](../../com.aspose.slides/presentation) هر  Shape  را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اشکال طرح |
| includeNotes | boolean | پرچمی که نشان می‌دهد آیا NotesSlides باید در پردازش گنجانده شوند یا نه. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback که برای هر Shape فراخوانی می‌شود |

Shapes در تمام انواع اسلایدها تکرار می‌شوند - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) در صورت نیاز. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

در [BaseSlide](../../com.aspose.slides/baseslide) هر [Shape](../../com.aspose.slides/shape) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide برای تکرار اشکال طرح |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback که برای هر Shape فراخوانی می‌شود |

[BaseSlide](../../com.aspose.slides/baseslide) نوع پایه برای \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

در [Presentation](../../com.aspose.slides/presentation) هر [Paragraph](../../com.aspose.slides/paragraph) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار پاراگراف‌ها |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback که برای هر پاراگراف فراخوانی می‌شود |

Shapes در تمام انواع اسلایدها تکرار می‌شوند - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

در [Presentation](../../com.aspose.slides/presentation) هر [Paragraph](../../com.aspose.slides/paragraph) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار پاراگراف‌ها |
| includeNotes | boolean | پرچمی که نشان می‌دهد آیا NotesSlides باید در پردازش گنجانده شوند یا نه. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback که برای هر پاراگراف فراخوانی می‌شود |

Shapes در تمام انواع اسلایدها تکرار می‌شوند - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

در [Presentation](../../com.aspose.slides/presentation) هر [Portion](../../com.aspose.slides/portion) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار بخش‌ها |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback که برای هر portion فراخوانی می‌شود |

Portions در تمام انواع اسلایدها تکرار می‌شوند - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

در [Presentation](../../com.aspose.slides/presentation) هر [Portion](../../com.aspose.slides/portion) را تکرار کنید.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار بخش‌ها |
| includeNotes | boolean | پرچمی که نشان می‌دهد آیا NotesSlides باید در پردازش گنجانده شوند یا نه. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback که برای هر portion فراخوانی می‌شود |

Portions در تمام انواع اسلایدها تکرار می‌شوند - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) |