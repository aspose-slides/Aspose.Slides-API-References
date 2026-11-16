---
title: ForEach
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایش می‌دهد یک گروه از متدها که برای تکرار بر روی انواع مختلف Presentation../aspose.slides/presentation مدل شیء طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر نیاز به تکرار و تغییر قالب‌بندی یا محتوای برخی عناصر Presentation داشته باشید، به عنوان مثال تغییر قالب‌بندی هر بخش.
type: docs
weight: 7920
url: /fa/aspose.slides.lowcode/foreach/
---
## ForEach کلاس

نمایش می‌دهد یک گروه از متدها که برای تکرار بر روی انواع مختلف [`Presentation`](../../aspose.slides/presentation) مدل آبجکت‌ها طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر نیاز به تکرار و تغییر قالب‌بندی یا محتویات برخی از عناصر Presentation داشته باشید، به عنوان مثال تغییر قالب‌بندی هر بخش.

```csharp
public static class ForEach
```

## متدها

| نام | توضیح |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | تکرار هر [`LayoutSlide`](./layoutslide) در [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | تکرار هر [`MasterSlide`](./masterslide) در [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | تکرار هر [`Paragraph`](./paragraph) در [`Presentation`](../../aspose.slides/presentation). Shapes در تمام انواع اسلایدها تکرار خواهد شد - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | تکرار هر [`Paragraph`](./paragraph) در [`Presentation`](../../aspose.slides/presentation). Shapes در تمام انواع اسلایدها تکرار خواهد شد - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | تکرار هر [`Portion`](./portion) در [`Presentation`](../../aspose.slides/presentation). Portions در تمام انواع اسلایدها تکرار خواهد شد - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | تکرار هر [`Portion`](./portion) در [`Presentation`](../../aspose.slides/presentation). Portions در تمام انواع اسلایدها تکرار خواهد شد - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | تکرار هر [`Shape`](./shape) در [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) نوع پایه برای [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) است |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | تکرار هر [`Shape`](./shape) در [`Presentation`](../../aspose.slides/presentation). Shapes در تمام انواع اسلایدها تکرار خواهد شد - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | تکرار هر [`Shape`](./shape) در [`Presentation`](../../aspose.slides/presentation). Shapes در تمام انواع اسلایدها تکرار خواهد شد - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) در صورت نیاز. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | تکرار هر [`Slide`](./slide) در [`Presentation`](../../aspose.slides/presentation). |

## سایر اعضا

| نام | توضیح |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback که برای هر [`LayoutSlide`](./layoutslide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی خواهد شد. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback که برای هر [`MasterSlide`](./masterslide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی خواهد شد. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback که برای هر [`Paragraph`](./paragraph) بر روی [`BaseSlide`](../../aspose.slides/baseslide) فراخوانی خواهد شد. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback که برای هر [`Portion`](./portion) در [`Paragraph`](./paragraph) بر روی [`BaseSlide`](../../aspose.slides/baseslide) فراخوانی خواهد شد. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback که برای هر [`Shape`](./shape) در [`Presentation`](../../aspose.slides/presentation) فراخوانی خواهد شد. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback که برای هر [`Slide`](./slide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی خواهد شد. |

### مثال‌ها

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

### مراجع

* فضای‌نام [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->