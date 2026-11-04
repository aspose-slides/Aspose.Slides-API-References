---
title: ForEach
second_title: Aspose.Sildes için .NET API Referansı
description: Farklı Presentation../aspose.slides/presentation model nesneleri üzerinde yineleme yapmak için tasarlanmış bir yöntem grubunu temsil eder. Bu yöntemler, bazı Presentation öğelerinin biçimlendirmesini veya içeriğini yinelemek ve değiştirmek gerektiğinde faydalı olabilir, örn. her bölümün biçimlendirmesini değiştirmek.
type: docs
weight: 7920
url: /tr/aspose.slides.lowcode/foreach/
---
## ForEach sınıf

Farklı [`Presentation`](../../aspose.slides/presentation) model nesneleri üzerinde yineleme yapmak için tasarlanmış bir yöntem grubunu temsil eder. Bu yöntemler, bir Presentation öğesinin biçimlendirmesini veya içeriğini yinelemek ve değiştirmek gerektiğinde yararlı olabilir, örn. her bölümün biçimlendirmesini değiştirmek.

```csharp
public static class ForEach
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Her [`LayoutSlide`](./layoutslide)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Her [`MasterSlide`](./masterslide)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Her [`Paragraph`](./paragraph)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. Şekiller tüm slayt türlerinde - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide) - yineleyecektir. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Her [`Paragraph`](./paragraph)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. Şekiller tüm slayt türlerinde - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide) - yineleyecektir. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Her [`Portion`](./portion)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. Bölümler tüm slayt türlerinde - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide) - yineleyecektir. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Her [`Portion`](./portion)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. Bölümler tüm slayt türlerinde - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide) - yineleyecektir. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Her [`Shape`](./shape)'yi [`BaseSlide`](../../aspose.slides/baseslide) içinde yinele. [`BaseSlide`](../../aspose.slides/baseslide), [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide) için temel türdür. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Her [`Shape`](./shape)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. Şekiller tüm slayt türlerinde - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide) - yineleyecektir. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Her [`Shape`](./shape)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. Şekiller tüm slayt türlerinde - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide) - gerektiğinde yineleyecektir. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Her [`Slide`](./slide)'yi [`Presentation`](../../aspose.slides/presentation) içinde yinele. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Her [`LayoutSlide`](./layoutslide) için [`Presentation`](../../aspose.slides/presentation) içinde çağrılacak geri arama. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Her [`MasterSlide`](./masterslide) için [`Presentation`](../../aspose.slides/presentation) içinde çağrılacak geri arama. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Her [`Paragraph`](./paragraph) için [`BaseSlide`](../../aspose.slides/baseslide) üzerinde çağrılacak geri arama. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Her [`Portion`](./portion) için [`Paragraph`](./paragraph) üzerindeki [`BaseSlide`](../../aspose.slides/baseslide) içinde çağrılacak geri arama. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Her [`Shape`](./shape) için [`Presentation`](../../aspose.slides/presentation) içinde çağrılacak geri arama. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Her [`Slide`](./slide) için [`Presentation`](../../aspose.slides/presentation) içinde çağrılacak geri arama. |

### Örnekler

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

### Ayrıca Bakınız

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->