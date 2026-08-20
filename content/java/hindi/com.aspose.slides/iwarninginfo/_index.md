---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /hi/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

सभी चेतावनियों के लिए एक बेस इंटरफ़ेस का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | यदि receiver null नहीं है तो निर्दिष्ट receiver को चेतावनी समाप्त करता है और AbortRequestedException फेंकता है यदि receiver ऑपरेशन को रोकने का निर्णय लेता है। |
| [getWarningType()](#getWarningType--) | एक चेतावनी का प्रकार लौटाता है। |
| [getDescription()](#getDescription--) | इस चेतावनी का मानवीय पठनीय विवरण लौटाता है। |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

यदि receiver null नहीं है तो निर्दिष्ट receiver को चेतावनी समाप्त करता है और AbortRequestedException फेंकता है यदि receiver ऑपरेशन को रोकने का निर्णय लेता है।

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | प्राप्तकर्ता वस्तु [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

एक चेतावनी का प्रकार लौटाता है। केवल-पढ़ने-योग्य [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType)।

**वापसी:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

इस चेतावनी का मानव-पाठ्यवाच्य विवरण लौटाता है। केवल-पढ़ने-योग्य String।

**वापसी:**
java.lang.String