---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /hi/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | प्रत्येक [Slide](../../com.aspose.slides/slide) के लिए कॉल किया जाने वाला कॉलबैक, अपेक्षित आउटपुट पथ वापसी किया जाना चाहिए। |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


प्रत्येक [Slide](../../com.aspose.slides/slide) के लिए कॉल किया जाने वाला कॉलबैक, अपेक्षित आउटपुट पथ वापसी किया जाना चाहिए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | वर्तमान क्रमबद्ध slide |
| index | int | वर्तमान slide का सूचकांक |

**वापसी मान:**
java.lang.String