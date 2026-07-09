---
title: ForEach
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایشگر یک گروه از متدهاست که برای پیمایش اشیای مدل Presentation../aspose.slides/presentation مختلف طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر نیاز به پیمایش و تغییر قالب‌بندی یا محتوای برخی از عناصر Presentation داشته باشید، برای مثال تغییر قالب‌بندی هر بخش.
type: docs
weight: 7900
url: /fa/aspose.slides.lowcode/foreach/
---
## ForEach کلاس

نمایشگر یک گروه از متدها است که برای پیمایش اشیای مدل [`Presentation`](../../aspose.slides/presentation) مختلف طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر نیاز به پیمایش و تغییر قالب‌بندی یا محتوای برخی از عناصر Presentation داشته باشید، مثلاً قالب‌بندی هر بخش را تغییر دهید.

```csharp
public static class ForEach
```

## متدها

| نام | توضیح |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | هر [`LayoutSlide`](./layoutslide) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | هر [`MasterSlide`](./masterslide) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | هر [`Paragraph`](./paragraph) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. اشکال در تمام انواع اسلایدها - [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) پیمایش خواهند شد. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | هر [`Paragraph`](./paragraph) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. اشکال در تمام انواع اسلایدها - [`Slide`](./slide)، [`MasterSlide`](./masterslide)، [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) پیمایش خواهند شد. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | هر [`Portion`](./portion) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. بخش‌ها در تمام انواع اسلایدها - [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) پیمایش خواهند شد. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | هر [`Portion`](./portion) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. بخش‌ها در تمام انواع اسلایدها - [`Slide`](./slide)، [`MasterSlide`](./masterslide)، [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) در صورت نیاز پیمایش خواهند شد. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | هر [`Shape`](./shape) را در [`BaseSlide`](../../aspose.slides/baseslide) پیمایش کنید. [`BaseSlide`](../../aspose.slides/baseslide) نوع پایه برای [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) است. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | هر [`Shape`](./shape) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. اشکال در تمام انواع اسلایدها - [`Slide`](./slide)، [`MasterSlide`](./masterslide) و [`LayoutSlide`](./layoutslide) پیمایش خواهند شد. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | هر [`Shape`](./shape) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. اشکال در تمام انواع اسلایدها - [`Slide`](./slide)، [`MasterSlide`](./masterslide)، [`LayoutSlide`](./layoutslide) و [`NotesSlide`](../../aspose.slides/notesslide) در صورت نیاز پیمایش خواهند شد. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | هر [`Slide`](./slide) را در [`Presentation`](../../aspose.slides/presentation) پیمایش کنید. |

## سایر اعضا

| نام | توضیح |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | کال‌بکی که برای هر [`LayoutSlide`](./layoutslide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی می‌شود. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | کال‌بکی که برای هر [`MasterSlide`](./masterslide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی می‌شود. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | کال‌بکی که برای هر [`Paragraph`](./paragraph) روی [`BaseSlide`](../../aspose.slides/baseslide) فراخوانی می‌شود. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | کال‌بکی که برای هر [`Portion`](./portion) در [`Paragraph`](./paragraph) روی [`BaseSlide`](../../aspose.slides/baseslide) فراخوانی می‌شود. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | کال‌بکی که برای هر [`Shape`](./shape) در [`Presentation`](../../aspose.slides/presentation) فراخوانی می‌شود. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | کال‌بکی که برای هر [`Slide`](./slide) در [`Presentation`](../../aspose.slides/presentation) فراخوانی می‌شود. |

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

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->