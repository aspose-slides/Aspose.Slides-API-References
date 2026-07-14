---
title: ForEach
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من الطرق المصممة للتكرار عبر كائنات نموذج مختلفة.
type: docs
url: /ar/com.aspose.slides/foreach/
---
**Inheritance:**
java.lang.Object
```
public class ForEach
```

يمثل مجموعة من الطرق المصممة للتكرار عبر كائنات نموذج [Presentation](../../com.aspose.slides/presentation) المختلفة. يمكن أن تكون هذه الطرق مفيدة إذا كنت بحاجة إلى التكرار وتغيير تنسيق أو محتوى بعض عناصر Presentation، مثل تغيير تنسيق كل جزء.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

## المُنشئات

| Constructor | Description |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## الطرق

| Method | Description |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | قُم بالتكرار على كل \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) في [Presentation](../../com.aspose.slides/presentation). |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | قُم بالتكرار على كل \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) في [Presentation](../../com.aspose.slides/presentation). |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | قُم بالتكرار على كل \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) في [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | قُم بالتكرار على كل [Shape](../../com.aspose.slides/shape) في [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | قُم بالتكرار على كل  Shape  في [Presentation](../../com.aspose.slides/presentation). |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | قُم بالتكرار على كل [Shape](../../com.aspose.slides/shape) في [BaseSlide](../../com.aspose.slides/baseslide). |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | قُم بالتكرار على كل [Paragraph](../../com.aspose.slides/paragraph) في [Presentation](../../com.aspose.slides/presentation). |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | قُم بالتكرار على كل [Paragraph](../../com.aspose.slides/paragraph) في [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | قُم بالتكرار على كل [Portion](../../com.aspose.slides/portion) في [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | قُم بالتكرار على كل [Portion](../../com.aspose.slides/portion) في [Presentation](../../com.aspose.slides/presentation). |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

قُم بالتكرار على كل \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الشرائح |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل slide |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

قُم بالتكرار على كل \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الشرائح الرئيسية |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل master slide |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

قُم بالتكرار على كل \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الشرائح ذات التخطيط |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل layout slide |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

قُم بالتكرار على كل [Shape](../../com.aspose.slides/shape) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الأشكال داخل التخطيط |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل shape |

الأشكال سيتم تكرارها في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

قُم بالتكرار على كل  Shape  في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الأشكال داخل التخطيط |
| includeNotes | boolean | علم يشير إلى ما إذا كان يجب تضمين NotesSlides في المعالجة. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل shape |

الأشكال سيتم تكرارها في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)، \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) إذا لزم الأمر. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

قُم بالتكرار على كل [Shape](../../com.aspose.slides/shape) في [BaseSlide](../../com.aspose.slides/baseslide).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | شريحة لتكرار الأشكال داخل التخطيط |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل shape |

[BaseSlide](../../com.aspose.slides/baseslide) هو النوع الأساسي لـ \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

قُم بالتكرار على كل [Paragraph](../../com.aspose.slides/paragraph) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الفقرات |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل paragraph |

الأشكال سيتم تكرارها في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

قُم بالتكرار على كل [Paragraph](../../com.aspose.slides/paragraph) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الفقرات |
| includeNotes | boolean | علم يشير إلى ما إذا كان يجب تضمين NotesSlides في المعالجة. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل paragraph |

الأشكال سيتم تكرارها في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

قُم بالتكرار على كل [Portion](../../com.aspose.slides/portion) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الأجزاء |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل portion |

الأجزاء سيتم تكرارها في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

قُم بالتكرار على كل [Portion](../../com.aspose.slides/portion) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation لتكرار الأجزاء |
| includeNotes | boolean | علم يشير إلى ما إذا كان يجب تضمين NotesSlides في المعالجة. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | استدعاء رد الاتصال الذي سيتم استدعاؤه لكل portion |

الأجزاء سيتم تكرارها في جميع أنواع الشرائح - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)، \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) |