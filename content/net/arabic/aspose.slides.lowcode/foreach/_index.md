---
title: ForEach
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من الطرق المصممة للتكرار على كائنات نموذج Presentation../aspose.slides/presentation المختلفة. يمكن أن تكون هذه الطرق مفيدة إذا كنت بحاجة إلى التكرار وتغيير تنسيق أو محتوى بعض عناصر Presentation مثل تغيير تنسيق كل جزء.
type: docs
weight: 7900
url: /ar/aspose.slides.lowcode/foreach/
---
## ForEach فئة

يمثل مجموعة من الطرق المصممة للتكرار على كائنات نموذج [`Presentation`](../../aspose.slides/presentation) المختلفة. يمكن أن تكون هذه الطرق مفيدة إذا كنت بحاجة إلى التكرار وتغيير تنسيق أو محتوى بعض عناصر Presentation'، على سبيل المثال تغيير تنسيق كل جزء.

```csharp
public static class ForEach
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | تكرار كل [`LayoutSlide`](./layoutslide) في [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | تكرار كل [`MasterSlide`](./masterslide) في [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | تكرار كل [`Paragraph`](./paragraph) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | تكرار كل [`Paragraph`](./paragraph) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | تكرار كل [`Portion`](./portion) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأجزاء في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | تكرار كل [`Portion`](./portion) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأجزاء في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) هو النوع الأساسي لـ [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) إذا لزم الأمر. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | تكرار كل [`Slide`](./slide) في [`Presentation`](../../aspose.slides/presentation). |

## أعضاء أخرى

| الاسم | الوصف |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | ستتم استدعاء رد النداء لكل [`LayoutSlide`](./layoutslide) في [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | ستتم استدعاء رد النداء لكل [`MasterSlide`](./masterslide) في [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | ستتم استدعاء رد النداء لكل [`Paragraph`](./paragraph) على [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | ستتم استدعاء رد النداء لكل [`Portion`](./portion) في [`Paragraph`](./paragraph) على [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | ستتم استدعاء رد النداء لكل [`Shape`](./shape) في [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | ستتم استدعاء رد النداء لكل [`Slide`](./slide) في [`Presentation`](../../aspose.slides/presentation). |

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

### انظر أيضا

* مساحة الاسم [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->