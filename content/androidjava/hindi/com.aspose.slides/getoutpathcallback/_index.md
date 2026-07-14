---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hi/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | प्रत्येक [Slide](../../com.aspose.slides/slide) के लिए कॉल बैक आवाहन किया जाएगा, आउटपुट पथ लौटाया जाना अपेक्षित है। |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

प्रत्येक [Slide](../../com.aspose.slides/slide) के लिए कॉल बैक आवाहन किया जाएगा, आउटपुट पथ लौटाया जाना अपेक्षित है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | वर्तमान पुनरावर्तित स्लाइड |
| index | int | वर्तमान स्लाइड का इंडेक्स |

**रिटर्न:**
java.lang.String