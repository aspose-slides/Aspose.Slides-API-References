---
title: Captions
second_title: Aspose.Slides for Java API संदर्भ
description: WebVTT बंद कैप्शन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/captions/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

WebVTT बंद कैप्शन का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | बंद कैप्शन का ग्लोबली यूनिक पहचानकर्ता (GUID) लौटाता है। |
| [getLabel()](#getLabel--) | बंद कैप्शन का लेबल लौटाता है या सेट करता है। |
| [setLabel(String value)](#setLabel-java.lang.String-) | बंद कैप्शन का लेबल लौटाता है या सेट करता है। |
| [getBinaryData()](#getBinaryData--) | बंद कैप्शन का बाइनरी डेटा लौटाता है। |
| [getDataAsString()](#getDataAsString--) | UTF-8 एन्कोडेड स्ट्रिंग के रूप में बंद कैप्शन डेटा लौटाता है। केवल-पढ़ने योग्य String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


बंद कैप्शन का ग्लोबली यूनिक पहचानकर्ता (GUID) लौटाता है। केवल-पढ़ने योग्य java.util.UUID.

**रिटर्न:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


बंद कैप्शन का लेबल लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


बंद कैप्शन का लेबल लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


बंद कैप्शन का बाइनरी डेटा लौटाता है। केवल-पढ़ने योग्य byte[] .

**रिटर्न:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


UTF-8 एन्कोडेड स्ट्रिंग के रूप में बंद कैप्शन डेटा लौटाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**
java.lang.String