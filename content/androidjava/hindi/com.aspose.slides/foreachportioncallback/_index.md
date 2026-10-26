---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hi/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | कॉलबैक जो प्रत्येक #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) पर [BaseSlide](../../com.aspose.slides/baseslide) को बुलाया जाएगा। |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

कॉलबैक जो प्रत्येक #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) पर [BaseSlide](../../com.aspose.slides/baseslide) को बुलाया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | वर्तमान पुनरावृत्त भाग |
| para | [Paragraph](../../com.aspose.slides/paragraph) | वर्तमान पुनरावृत्त अनुच्छेद |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | वर्तमान पुनरावृत्त स्लाइड |
| index | int | स्लाइड पर वर्तमान अनुच्छेद का सूचकांक |