---
title: ForEach
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر گروهی از متدهاست که برای تکرار بر روی اشیاء مدل Presentation../aspose.slides/presentation مختلف طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر نیاز به تکرار و تغییر قالب‌بندی یا محتوای برخی عناصر Presentation داشته باشید، به عنوان مثال تغییر قالب‌بندی هر بخش.
type: docs
weight: 7900
url: /fa/aspose.slides.lowcode/foreach/
---
## ForEach کلاس

نمایانگر گروهی از متدهاست که برای تکرار بر روی اشیاء مدل [`Presentation`](../../aspose.slides/presentation) مختلف طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر لازم باشد بر روی عناصر Presentation حلقه بزنید و قالب‌بندی یا محتوا را تغییر دهید، به عنوان مثال قالب‌بندی هر بخش را تغییر دهید.

```csharp
public static class ForEach
```

## متدها

| نام | توضیح |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | تکرار هر [`LayoutSlide`](./layoutslide) در [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | تکرار هر [`MasterSlide`](./masterslide) در [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | تکرار هر [`Paragraph`](./paragraph) در [`Presentation`](../../aspose.slides/presentation). اشکال در تمام انواع اسلایدها تکرار می‌شوند - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | تکرار هر [`Paragraph`](./paragraph) در [`Presentation`](../../aspose.slides/presentation). اشکال در تمام انواع اسلایدها تکرار می‌شوند - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | تکرار هر [`Portion`](./portion) در [`Presentation`](../../aspose.slides/presentation). بخش‌ها در تمام انواع اسلایدها تکرار می‌شوند - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | تکرار هر [`Portion`](./portion) در [`Presentation`](../../aspose.slides/presentation). بخش‌ها در تمام انواع اسلایدها تکرار می‌شوند - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | تکرار هر [`Shape`](./shape) در [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) نوع پایه برای [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) است |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | تکرار هر [`Shape`](./shape) در [`Presentation`](../../aspose.slides/presentation). اشکال در تمام انواع اسلایدها تکرار می‌شوند - [`Slide`](./slide), [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | تکرار هر [`Shape`](./shape) در [`Presentation`](../../aspose.slides/presentation). اشکال در تمام انواع اسلایدها تکرار می‌شوند - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) در صورت نیاز. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | تکرار هر [`Slide`](./slide) در [`Presentation`](../../aspose.slides/presentation). |

## سایر اعضا

| نام | توضیح |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback که برای هر [`LayoutSlide`](./layoutslide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی می‌شود. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback که برای هر [`MasterSlide`](./masterslide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی می‌شود. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback که برای هر [`Paragraph`](./paragraph) در [`BaseSlide`](../../aspose.slides/baseslide) فراخوانی می‌شود. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback که برای هر [`Portion`](./portion) در [`Paragraph`](./paragraph) روی [`BaseSlide`](../../aspose.slides/baseslide) فراخوانی می‌شود. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback که برای هر [`Shape`](./shape) در [`Presentation`](../../aspose.slides/presentation) فراخوانی می‌شود. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback که برای هر [`Slide`](./slide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی می‌شود. |

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

### همچنین ببینید

* فضای نام [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* اسمبل [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->