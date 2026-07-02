---
title: AlignShapes
second_title: Aspose.Sildes برای .NET مرجع API
description: موقعیت تمام اشکال روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.
type: docs
weight: 10
url: /fa/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

موقعیت تمام اشکال روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | تعیین می‌کند که کدام نوع هم‌ترازی اعمال خواهد شد. |
| alignToSlide | Boolean | اگر مقدار true باشد، اشکال نسبت به لبه‌های اسلاید هم‌تراز می‌شوند. |
| slide | IBaseSlide | اسلاید والد. |

### مثال‌ها

مثال:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### همچنین ببینید

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* رابط [IBaseSlide](../../../aspose.slides/ibaseslide)
* کلاس [SlideUtil](../../slideutil)
* فضای‌نام [Aspose.Slides.Util](../../slideutil)
* مجمع [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

موقعیت اشکال انتخاب‌شده روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | تعیین می‌کند که کدام نوع هم‌ترازی اعمال خواهد شد. |
| alignToSlide | Boolean | اگر مقدار true باشد، اشکال نسبت به لبه‌های اسلاید هم‌تراز می‌شوند. |
| slide | IBaseSlide | اسلاید والد. |
| shapeIndexes | Int32[] | شاخص‌های اشکالی که باید هم‌تراز شوند. |

### مثال‌ها

مثال:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   ISlide slide = pres.Slides[0];
   IShape shape1 = slide.Shapes[0];
   IShape shape2 = slide.Shapes[1]; 

   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, false, pres.Slides[0], new int[]
   {
      slide.Shapes.IndexOf(shape1),
      slide.Shapes.IndexOf(shape2)
   });
}
```

### همچنین ببینید

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* رابط [IBaseSlide](../../../aspose.slides/ibaseslide)
* کلاس [SlideUtil](../../slideutil)
* فضای‌نام [Aspose.Slides.Util](../../slideutil)
* مجمع [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

موقعیت تمام اشکال درون شکل گروهی را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | تعیین می‌کند که کدام نوع هم‌ترازی اعمال خواهد شد. |
| alignToSlide | Boolean | اگر مقدار true باشد، اشکال نسبت به لبه‌های اسلاید هم‌تراز می‌شوند. |
| groupShape | IGroupShape | شکل گروهی والد. |

### مثال‌ها

مثال:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### همچنین ببینید

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* رابط [IGroupShape](../../../aspose.slides/igroupshape)
* کلاس [SlideUtil](../../slideutil)
* فضای‌نام [Aspose.Slides.Util](../../slideutil)
* مجمع [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

موقعیت اشکال انتخاب‌شده درون شکل گروهی را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | تعیین می‌کند که کدام نوع هم‌ترازی اعمال خواهد شد. |
| alignToSlide | Boolean | اگر مقدار true باشد، اشکال نسبت به لبه‌های اسلاید هم‌تراز می‌شوند. |
| groupShape | IGroupShape | شکل گروهی والد. |
| shapeIndexes | Int32[] | شاخص‌های اشکالی که باید هم‌تراز شوند. |

### مثال‌ها

مثال:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### همچنین ببینید

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* رابط [IGroupShape](../../../aspose.slides/igroupshape)
* کلاس [SlideUtil](../../slideutil)
* فضای‌نام [Aspose.Slides.Util](../../slideutil)
* مجمع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->