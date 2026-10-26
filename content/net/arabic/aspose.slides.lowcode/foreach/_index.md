---
title: ForEach
second_title: مرجع API Aspose.Sildes لـ .NET
description: يمثّل مجموعة من الطرق المصممة لتكرار كائنات نموذج Presentation../aspose.slides/presentation المختلفة. هذه الطرق يمكن أن تكون مفيدة إذا كنت بحاجة إلى تكرار وتغيير تنسيق أو محتوى بعض عناصر Presentation، على سبيل المثال تغيير تنسيق كل جزء.
type: docs
weight: 7900
url: /ar/aspose.slides.lowcode/foreach/
---
## ForEach الفئة

يمثل مجموعة من الطرق المصممة لتكرار كائنات نموذج [`Presentation`](../../aspose.slides/presentation) المختلفة. قد تكون هذه الطرق مفيدة إذا كنت بحاجة إلى تكرار وتغيير تنسيق أو محتوى بعض عناصر Presentation، مثل تغيير تنسيق كل جزء.

```csharp
public static class ForEach
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | تكرار كل [`LayoutSlide`](./layoutslide) في الـ [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | تكرار كل [`MasterSlide`](./masterslide) في الـ [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | تكرار كل [`Paragraph`](./paragraph) في الـ [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | تكرار كل [`Paragraph`](./paragraph) في الـ [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide)، [`MasterSlide`](./masterslide)، [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | تكرار كل [`Portion`](./portion) في الـ [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأجزاء في جميع أنواع الشرائح - [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | تكرار كل [`Portion`](./portion) في الـ [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأجزاء في جميع أنواع الشرائح - [`Slide`](./slide)، [`MasterSlide`](./masterslide)، [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في الـ [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) هو النوع الأساسي لـ [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في الـ [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في الـ [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide)، [`MasterSlide`](./masterslide)، [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) إذا لزم الأمر. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | تكرار كل [`Slide`](./slide) في الـ [`Presentation`](../../aspose.slides/presentation). |

## الأعضاء الأخرى

| الاسم | الوصف |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | دالة رد نداء سيتم استدعاؤها لكل [`LayoutSlide`](./layoutslide) في الـ [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | دالة رد نداء سيتم استدعاؤها لكل [`MasterSlide`](./masterslide) في الـ [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | دالة رد نداء سيتم استدعاؤها لكل [`Paragraph`](./paragraph) على الـ [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | دالة رد نداء سيتم استدعاؤها لكل [`Portion`](./portion) في الـ [`Paragraph`](./paragraph) على الـ [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | دالة رد نداء سيتم استدعاؤها لكل [`Shape`](./shape) في الـ [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | دالة رد نداء سيتم استدعاؤها لكل [`Slide`](./slide) في الـ [`Presentation`](../../aspose.slides/presentation). |

### أمثلة

```csharp
using (Presentation presentation = new Presentation("pres.pptx"))
{
   ForEach.Portion(presentation, (portion, para, slide, index) =>
   {
       portion.PortionFormat.LatinFont = new FontData("Times New Roman");
   });
  
   presentation.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* النطاق [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->