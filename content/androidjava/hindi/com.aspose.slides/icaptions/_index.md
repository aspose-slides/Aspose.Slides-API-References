---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /hi/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

WebVTT बंद कैप्शन का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | बंद कैप्शन का वैश्विक अद्वितीय पहचानकर्ता (GUID) लौटाता है। |
| [getLabel()](#getLabel--) | बंद कैप्शन के लेबल को लौटाता है या सेट करता है। |
| [setLabel(String value)](#setLabel-java.lang.String-) | बंद कैप्शन के लेबल को लौटाता है या सेट करता है। |
| [getBinaryData()](#getBinaryData--) | बंद कैप्शन का बाइनरी डेटा लौटाता है। |
| [getDataAsString()](#getDataAsString--) | बंद कैप्शन डेटा को UTF-8 एन्कोडेड स्ट्रिंग के रूप में लौटाता है। केवल-पढ़ने योग्य String। |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


बंद कैप्शन का वैश्विक अद्वितीय पहचानकर्ता (GUID) लौटाता है। केवल-पढ़ने योग्य java.util.UUID।

**वापसी:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


बंद कैप्शन के लेबल को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


बंद कैप्शन के लेबल को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


बंद कैप्शन का बाइनरी डेटा लौटाता है। केवल-पढ़ने योग्य byte[]।

**वापसी:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


बंद कैप्शन डेटा को UTF-8 एन्कोडेड स्ट्रिंग के रूप में लौटाता है। केवल-पढ़ने योग्य String।

**वापसी:**
java.lang.String