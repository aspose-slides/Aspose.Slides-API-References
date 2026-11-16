---
title: ForEach
second_title: مرجع API لـ Aspose.Sildes على .NET
description: يمثل مجموعة من الأساليب المصممة للتكرار عبر كائنات نموذج Presentation../aspose.slides/presentation المختلفة. يمكن أن تكون هذه الأساليب مفيدة إذا كنت بحاجة إلى التكرار وتغيير تنسيق بعض عناصر Presentation أو محتواها، على سبيل المثال تغيير تنسيق كل جزء.
type: docs
weight: 7920
url: /ar/aspose.slides.lowcode/foreach/
---
## ForEach فئة

Represents a group of methods intended to iterate over different [`Presentation`](../../aspose.slides/presentation) model objects. These methods can be useful if you need to iterate and change some Presentation' elements formatting or content, e.g. change each portion formatting.

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
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | تكرار كل [`Portion`](./portion) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأقسام في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | تكرار كل [`Portion`](./portion) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأقسام في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) هو النوع الأساسي لـ [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | تكرار كل [`Shape`](./shape) في [`Presentation`](../../aspose.slides/presentation). سيتم تكرار الأشكال في جميع أنواع الشرائح - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) إذا لزم الأمر. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | تكرار كل [`Slide`](./slide) في [`Presentation`](../../aspose.slides/presentation). |

## الأعضاء الأخرى

| الاسم | الوصف |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | رد نداء سيتم استدعاؤه لكل [`LayoutSlide`](./layoutslide) في [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | رد نداء سيتم استدعاؤه لكل [`MasterSlide`](./masterslide) في [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | رد نداء سيتم استدعاؤه لكل [`Paragraph`](./paragraph) على [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | رد نداء سيتم استدعاؤه لكل [`Portion`](./portion) في [`Paragraph`](./paragraph) على [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | رد نداء سيتم استدعاؤه لكل [`Shape`](./shape) في [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | رد نداء سيتم استدعاؤه لكل [`Slide`](./slide) في [`Presentation`](../../aspose.slides/presentation). |

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

* مساحة اسم [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* مجموعة تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->