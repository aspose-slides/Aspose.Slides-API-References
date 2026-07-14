---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hi/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | कॉलबैक जिसे प्रत्येक \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) पर [BaseSlide](../../com.aspose.slides/baseslide) के लिए बुलाया जाएगा। |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```


कॉलबैक जिसे प्रत्येक \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) पर [BaseSlide](../../com.aspose.slides/baseslide) के लिए बुलाया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | वर्तमान पुनरावृत्त पैराग्राफ |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | वर्तमान पुनरावृत्त स्लाइड |
| index | int | स्लाइड पर वर्तमान पैराग्राफ का अनुक्रमांक |