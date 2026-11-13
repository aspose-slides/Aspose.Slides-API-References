---
title: ForEach
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: विभिन्न Presentation../aspose.slides/presentation मॉडल ऑब्जेक्ट्स पर पुनरावृति करने के लिए अभिप्रेत मेथड्स के समूह को दर्शाता है। यदि आपको कुछ Presentation तत्वों के स्वरूप या सामग्री को बदलना हो, जैसे प्रत्येक भाग के स्वरूप को बदलना, तो ये मेथड्स उपयोगी हो सकते हैं।
type: docs
weight: 7920
url: /hi/aspose.slides.lowcode/foreach/
---
## ForEach क्लास

विभिन्न [`Presentation`](../../aspose.slides/presentation) मॉडल ऑब्जेक्ट्स पर पुनरावृति करने के लिए अभिप्रेत मेथड्स का समूह दर्शाता है। ये मेथड्स तब उपयोगी होते हैं जब आपको कुछ Presentation तत्वों के स्वरूप या सामग्री को बदलना हो, उदाहरण के लिए प्रत्येक भाग के स्वरूप को बदलना।

```csharp
public static class ForEach
```

## मेथड्स

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`LayoutSlide`](./layoutslide) को दोहराएँ। |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`MasterSlide`](./masterslide) को दोहराएँ। |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Paragraph`](./paragraph) को दोहराएँ। Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Paragraph`](./paragraph) को दोहराएँ। Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Portion`](./portion) को दोहराएँ। Portions सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Portion`](./portion) को दोहराएँ। Portions सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | [`BaseSlide`](../../aspose.slides/baseslide) में प्रत्येक [`Shape`](./shape) को दोहराएँ। [`BaseSlide`](../../aspose.slides/baseslide) [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) के लिए आधार प्रकार है। |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Shape`](./shape) को दोहराएँ। Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Shape`](./shape) को दोहराएँ। Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide) यदि आवश्यक हो। |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Slide`](./slide) को दोहराएँ। |

## अन्य सदस्य

| Name | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback जो [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`LayoutSlide`](./layoutslide) के लिए बुलाया जाएगा। |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback जो [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`MasterSlide`](./masterslide) के लिए बुलाया जाएगा। |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback जो [`BaseSlide`](../../aspose.slides/baseslide) पर प्रत्येक [`Paragraph`](./paragraph) के लिए बुलाया जाएगा। |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback जो [`BaseSlide`](../../aspose.slides/baseslide) पर [`Paragraph`](./paragraph) में प्रत्येक [`Portion`](./portion) के लिए बुलाया जाएगा। |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback जो [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Shape`](./shape) के लिए बुलाया जाएगा। |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback जो [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Slide`](./slide) के लिए बुलाया जाएगा। |

### उदाहरण

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

### संबंधित देखें

* नेमस्पेस [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->