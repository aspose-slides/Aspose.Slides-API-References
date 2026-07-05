---
title: ForEach
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: विभिन्न Presentation../aspose.slides/presentation मॉडल ऑब्जेक्ट्स पर इटरेट करने के लिए अभिप्रेत मेथड्स का एक समूह दर्शाता है। ये मेथड्स तब उपयोगी होते हैं जब आपको Presentation तत्वों का स्वरूप या सामग्री बदलनी हो, जैसे प्रत्येक portion का स्वरूप बदलना।
type: docs
weight: 7900
url: /hi/aspose.slides.lowcode/foreach/
---
## ForEach क्लास

विभिन्न [`Presentation`](../../aspose.slides/presentation) मॉडल ऑब्जेक्ट्स पर इटरेट करने के लिए अभिप्रेत मेथड्स का एक समूह दर्शाता है। ये मेथड्स तब उपयोगी होते हैं जब आपको Presentation के कुछ तत्वों का स्वरूप या सामग्री बदलनी हो, जैसे प्रत्येक portion का स्वरूप बदलना।

```csharp
public static class ForEach
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`LayoutSlide`](./layoutslide) को इटरेट करें। |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`MasterSlide`](./masterslide) को इटरेट करें। |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Paragraph`](./paragraph) को इटरेट करें। Shapes सभी प्रकार की स्लाइड्स में इटरेट किए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide)। |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Paragraph`](./paragraph) को इटरेट करें। Shapes सभी प्रकार की स्लाइड्स में इटरेट किए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide)। |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Portion`](./portion) को इटरेट करें। Portions सभी प्रकार की स्लाइड्स में इटरेट किए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide)। |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Portion`](./portion) को इटरेट करें। Portions सभी प्रकार की स्लाइड्स में इटरेट किए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide)। |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | [`BaseSlide`](../../aspose.slides/baseslide) में प्रत्येक [`Shape`](./shape) को इटरेट करें। [`BaseSlide`](../../aspose.slides/baseslide) [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) के लिए बेस टाइप है। |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Shape`](./shape) को इटरेट करें। Shapes सभी प्रकार की स्लाइड्स में इटरेट किए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide)। |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Shape`](./shape) को इटरेट करें। Shapes सभी प्रकार की स्लाइड्स में इटरेट किए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide) यदि आवश्यक हो। |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Slide`](./slide) को इटरेट करें। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`LayoutSlide`](./layoutslide) के लिए कॉलबैक को चलाया जाएगा। |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`MasterSlide`](./masterslide) के लिए कॉलबैक को चलाया जाएगा। |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | [`BaseSlide`](../../aspose.slides/baseslide) पर प्रत्येक [`Paragraph`](./paragraph) के लिए कॉलबैक को चलाया जाएगा। |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | [`BaseSlide`](../../aspose.slides/baseslide) पर [`Paragraph`](./paragraph) में प्रत्येक [`Portion`](./portion) के लिए कॉलबैक को चलाया जाएगा। |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Shape`](./shape) के लिए कॉलबैक को चलाया जाएगा। |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | [`Presentation`](../../aspose.slides/presentation) में प्रत्येक [`Slide`](./slide) के लिए कॉलबैक को चलाया जाएगा। |

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

* नामस्थान [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->