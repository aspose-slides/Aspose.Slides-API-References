---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for classes which receive warning
type: docs
url: /hi/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

चेतावनी प्राप्त करने वाली कक्षाओं के लिए इंटरफ़ेस
## विधियां

| विधि | विवरण |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | कॉलबैक विधि जो चेतावनी प्राप्त करती है और तय करती है कि कार्य को समाप्त किया जाना चाहिए या नहीं। |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


कॉलबैक विधि जो चेतावनी प्राप्त करती है और तय करती है कि कार्य को समाप्त किया जाना चाहिए या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | प्रक्रिया के लिए चेतावनी। |

**रिटर्न मान:**
int - रोकने का निर्णय [ReturnAction](../../com.aspose.slides/returnaction).