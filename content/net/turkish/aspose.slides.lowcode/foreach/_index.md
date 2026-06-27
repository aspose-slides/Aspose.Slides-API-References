---
title: ForEach
second_title: Aspose.Sildes için .NET API Referansı
description: Farklı Presentation../aspose.slides/presentation model nesneleri üzerinde yineleme yapmayı amaçlayan bir grup yöntemi temsil eder. Bu yöntemler, bazı Presentation öğelerinin biçimlendirmesini veya içeriğini yinelemek ve değiştirmek gerektiğinde yararlı olabilir; ör. her bölümün biçimlendirmesini değiştirmek.
type: docs
weight: 7880
url: /tr/aspose.slides.lowcode/foreach/
---
## ForEach sınıfı

Farklı [`Presentation`](../../aspose.slides/presentation) model nesneleri üzerinde yineleme yapmayı amaçlayan bir grup yöntemi temsil eder. Bu yöntemler, bazı Presentation öğelerinin biçimlendirmesini veya içeriğini yinelemek ve değiştirmek gerektiğinde yararlı olabilir, ör. her bölümün biçimlendirmesini değiştirmek.

```csharp
public static class ForEach
```

## Yöntemler

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`LayoutSlide`](./layoutslide)'yi yinele. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`MasterSlide`](./masterslide)'yi yinele. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`Paragraph`](./paragraph)'yi yinele. Şekiller, tüm slayt tiplerinde yineleyecek - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`Paragraph`](./paragraph)'yi yinele. Şekiller, tüm slayt tiplerinde yineleyecek - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide). |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`Portion`](./portion)'yi yinele. Bölümler, tüm slayt tiplerinde yineleyecek - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide). |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`Portion`](./portion)'yi yinele. Bölümler, tüm slayt tiplerinde yineleyecek - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide). |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | [`BaseSlide`](../../aspose.slides/baseslide) içinde her bir [`Shape`](./shape)'yi yinele. [`BaseSlide`](../../aspose.slides/baseslide), [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide) için temel türdür. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`Shape`](./shape)'yi yinele. Şekiller, tüm slayt tiplerinde yineleyecek - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide). |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`Shape`](./shape)'yi yinele. Şekiller, tüm slayt tiplerinde yineleyecek - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide) gerektiğinde. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | [`Presentation`](../../aspose.slides/presentation) içinde her bir [`Slide`](./slide)'yi yinele. |

## Diğer Üyeler

| Name | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Her bir [`LayoutSlide`](./layoutslide) için [`Presentation`](../../aspose.slides/presentation) içinde çağrılacak geri arama. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Her bir [`MasterSlide`](./masterslide) için [`Presentation`](../../aspose.slides/presentation) içinde çağrılacak geri arama. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Her bir [`Paragraph`](./paragraph) için [`BaseSlide`](../../aspose.slides/baseslide) içinde çağrılacak geri arama. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Her bir [`Portion`](./portion) için [`Paragraph`](./paragraph) içinde [`BaseSlide`](../../aspose.slides/baseslide) üzerinde çağrılacak geri arama. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Her bir [`Shape`](./shape) için [`Presentation`](../../aspose.slides/presentation) içinde çağrılacak geri arama. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Her bir [`Slide`](./slide) için [`Presentation`](../../aspose.slides/presentation) içinde çağrılacak geri arama. |

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

### İlgili

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->