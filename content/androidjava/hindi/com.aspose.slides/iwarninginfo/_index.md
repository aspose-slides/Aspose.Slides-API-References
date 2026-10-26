---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /hi/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

सभी चेतावनियों के लिए एक आधार इंटरफ़ेस का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | यदि रिसीवर null नहीं है तो निर्दिष्ट रिसीवर को चेतावनी समाप्त करता है और यदि रिसीवर ने ऑपरेशन को रोकने का निर्णय लिया तो AbortRequestedException फेंकता है। |
| [getWarningType()](#getWarningType--) | चेतावनी का प्रकार लौटाता है। |
| [getDescription()](#getDescription--) | इस चेतावनी का मानव पठनीय विवरण लौटाता है। |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

यदि रिसीवर null नहीं है तो निर्दिष्ट रिसीवर को चेतावनी समाप्त करता है और यदि रिसीवर ने ऑपरेशन को रोकने का निर्णय लिया तो AbortRequestedException फेंकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | रिसीवर ऑब्जेक्ट [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

चेतावनी का प्रकार लौटाता है। केवल पढ़ने योग्य [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType)。

**रिटर्न:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

इस चेतावनी का मानव पठनीय विवरण लौटाता है। केवल पढ़ने योग्य String।

**रिटर्न:**
java.lang.String