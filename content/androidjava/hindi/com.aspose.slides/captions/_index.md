---
title: Captions
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
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
| [getCaptionId()](#getCaptionId--) | बंद कैप्शन का वैश्विक रूप से अद्वितीय पहचानकर्ता (GUID) वापस करता है। केवल पढ़ने के लिए java.util.UUID. |
| [getLabel()](#getLabel--) | बंद कैप्शन का लेबल वापस करता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [setLabel(String value)](#setLabel-java.lang.String-) | बंद कैप्शन का लेबल वापस करता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [getBinaryData()](#getBinaryData--) | बंद कैप्शन का बाइनरी डेटा वापस करता है। केवल पढ़ने के लिए byte[] . |
| [getDataAsString()](#getDataAsString--) | बंद कैप्शन डेटा को UTF-8 एन्कोडेड स्ट्रिंग के रूप में वापस करता है। केवल पढ़ने के लिए String. |

### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

बंद कैप्शन का वैश्विक रूप से अद्वितीय पहचानकर्ता (GUID) वापस करता है। केवल पढ़ने के लिए java.util.UUID.

**वापसी:**  
java.util.UUID

### getLabel() {#getLabel--}
```
public final String getLabel()
```

बंद कैप्शन का लेबल वापस करता है या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

बंद कैप्शन का लेबल वापस करता है या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

बंद कैप्शन का बाइनरी डेटा वापस करता है। केवल पढ़ने के लिए byte[] .

**वापसी:**  
byte[]

### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

बंद कैप्शन डेटा को UTF-8 एन्कोडेड स्ट्रिंग के रूप में वापस करता है। केवल पढ़ने के लिए String.

**वापसी:**  
java.lang.String