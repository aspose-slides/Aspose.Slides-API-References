---
title: ForEach
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: विभिन्न Presentation../aspose.slides/presentation मॉडल ऑब्जेक्ट्स पर इटरेट करने के लिए अभिप्रेत मेथड्स का समूह दर्शाता है। ये मेथड्स तब उपयोगी हो सकते हैं जब आपको कुछ Presentation तत्वों की फ़ॉर्मेटिंग या सामग्री को इटरेट करके बदलना हो, उदाहरण के लिए प्रत्येक पोर्शन की फ़ॉर्मेटिंग बदलना।
type: docs
weight: 7900
url: /hi/aspose.slides.lowcode/foreach/
---
## ForEach क्लास

विभिन्न [`Presentation`](../../aspose.slides/presentation) मॉडल ऑब्जेक्ट्स पर इटरेट करने के लिए इरादा वाले मेथड्स का समूह दर्शाता है। ये मेथड्स तब उपयोगी हो सकते हैं जब आपको कुछ Presentation के तत्वों के फ़ॉर्मेटिंग या कंटेंट को बदलना हो, उदाहरण के लिए प्रत्येक पोर्शन का फ़ॉर्मेटिंग बदलना।

```csharp
public static class ForEach
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | प्रत्येक [`LayoutSlide`](./layoutslide) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | प्रत्येक [`MasterSlide`](./masterslide) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | प्रत्येक [`Paragraph`](./paragraph) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। शेप्स सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | प्रत्येक [`Paragraph`](./paragraph) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। शेप्स सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | प्रत्येक [`Portion`](./portion) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। पोर्शन सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | प्रत्येक [`Portion`](./portion) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। पोर्शन सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | प्रत्येक [`Shape`](./shape) को [`BaseSlide`](../../aspose.slides/baseslide) में दोहराएँ। [`BaseSlide`](../../aspose.slides/baseslide) [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) का बेस टाइप है |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | प्रत्येक [`Shape`](./shape) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। शेप्स सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide) और [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | प्रत्येक [`Shape`](./shape) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। शेप्स सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) और [`NotesSlide`](../../aspose.slides/notesslide) यदि आवश्यक हो। |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | प्रत्येक [`Slide`](./slide) को [`Presentation`](../../aspose.slides/presentation) में दोहराएँ। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | प्रत्येक [`LayoutSlide`](./layoutslide) के लिए कॉल-बैक को [`Presentation`](../../aspose.slides/presentation) में बुलाया जाएगा। |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | प्रत्येक [`MasterSlide`](./masterslide) के लिए कॉल-बैक को [`Presentation`](../../aspose.slides/presentation) में बुलाया जाएगा। |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | प्रत्येक [`Paragraph`](./paragraph) के लिए कॉल-बैक को [`BaseSlide`](../../aspose.slides/baseslide) पर बुलाया जाएगा। |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | प्रत्येक [`Portion`](./portion) के लिए कॉल-बैक को [`Paragraph`](./paragraph) में [`BaseSlide`](../../aspose.slides/baseslide) पर बुलाया जाएगा। |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | प्रत्येक [`Shape`](./shape) के लिए कॉल-बैक को [`Presentation`](../../aspose.slides/presentation) में बुलाया जाएगा। |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | प्रत्येक [`Slide`](./slide) के लिए कॉल-बैक को [`Presentation`](../../aspose.slides/presentation) में बुलाया जाएगा। |

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

### देखें भी

* नेमस्पेस [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->