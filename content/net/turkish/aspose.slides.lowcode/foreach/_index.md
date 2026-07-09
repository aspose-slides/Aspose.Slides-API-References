---
title: ForEach
second_title: Aspose.Sildes için .NET API Referansı
description: Farklı Presentation../aspose.slides/presentation model nesneleri üzerinde yineleme yapmak için tasarlanmış bir grup yöntemi temsil eder. Bu yöntemler, bazı Presentation öğelerinin biçimlendirmesini veya içeriğini yineleyip değiştirmeniz gerektiğinde faydalı olabilir; örneğin her bölümün biçimini değiştirmek.
type: docs
weight: 7900
url: /tr/aspose.slides.lowcode/foreach/
---
## ForEach sınıf

Farklı [`Presentation`](../../aspose.slides/presentation) model nesneleri üzerinde yineleme yapmak için tasarlanmış bir grup yöntemi temsil eder. Bu yöntemler, bir Presentation öğesinin biçimlendirmesini veya içeriğini yineleyip değiştirmeniz gerektiğinde faydalı olabilir; örneğin her bölümün biçimini değiştirmek.

```csharp
public static class ForEach
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Her [`LayoutSlide`](./layoutslide) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Her [`MasterSlide`](./masterslide) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Her [`Paragraph`](./paragraph) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. Şekiller, aşağıdaki slayt türlerinin tümünde yineleyecektir - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Her [`Paragraph`](./paragraph) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. Şekiller, aşağıdaki slayt türlerinin tümünde yineleyecektir - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide). |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Her [`Portion`](./portion) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. Bölümler, aşağıdaki slayt türlerinin tümünde yineleyecektir - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide). |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Her [`Portion`](./portion) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. Bölümler, aşağıdaki slayt türlerinin tümünde yineleyecektir - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide). |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Her [`Shape`](./shape) öğesini [`BaseSlide`](../../aspose.slides/baseslide) içinde yinele. [`BaseSlide`](../../aspose.slides/baseslide) , [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide) için temel türdür. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Her [`Shape`](./shape) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. Şekiller, aşağıdaki slayt türlerinin tümünde yineleyecektir - [`Slide`](./slide), [`MasterSlide`](./masterslide) ve [`LayoutSlide`](./layoutslide). |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Her [`Shape`](./shape) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. Şekiller, aşağıdaki slayt türlerinin tümünde yineleyecektir - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) ve [`NotesSlide`](../../aspose.slides/notesslide) gerektiğinde. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Her [`Slide`](./slide) öğesini [`Presentation`](../../aspose.slides/presentation) içinde yinele. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Her [`LayoutSlide`](./layoutslide) öğesi için [`Presentation`](../../aspose.slides/presentation) içinde tetiklenecek geri çağırma. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Her [`MasterSlide`](./masterslide) öğesi için [`Presentation`](../../aspose.slides/presentation) içinde tetiklenecek geri çağırma. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Her [`Paragraph`](./paragraph) öğesi için [`BaseSlide`](../../aspose.slides/baseslide) üzerinde tetiklenecek geri çağırma. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Her [`Portion`](./portion) öğesi için [`Paragraph`](./paragraph) içinde [`BaseSlide`](../../aspose.slides/baseslide) üzerinde tetiklenecek geri çağırma. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Her [`Shape`](./shape) öğesi için [`Presentation`](../../aspose.slides/presentation) içinde tetiklenecek geri çağırma. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Her [`Slide`](./slide) öğesi için [`Presentation`](../../aspose.slides/presentation) içinde tetiklenecek geri çağırma. |

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

### Bkz

* ad alanı [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->