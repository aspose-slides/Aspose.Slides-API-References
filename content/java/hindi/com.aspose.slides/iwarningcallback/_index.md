---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: चेतावनी प्राप्त करने वाली कक्षाओं के लिए इंटरफ़ेस
type: docs
url: /hi/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

चेतावनी प्राप्त करने वाली कक्षाओं के लिए इंटरफ़ेस
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | कोलबैक मेथड जो चेतावनी प्राप्त करता है और निर्धारित करता है कि ऑपरेशन को रद्द किया जाना चाहिए या नहीं। |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

कोलबैक मेथड जो चेतावनी प्राप्त करता है और निर्धारित करता है कि ऑपरेशन को रद्द किया जाना चाहिए या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | प्रोसेस करने के लिए चेतावनी। |

**रिटर्न:**
int - रद्दीकरण निर्णय [ReturnAction](../../com.aspose.slides/returnaction).