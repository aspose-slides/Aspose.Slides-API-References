---
title: CustomXmlPart
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: कस्टम XML भाग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/customxmlpart/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

कस्टम XML भाग का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getXmlData()](#getXmlData--) | XML डेटा को पुनः प्राप्त या सेट करता है। |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML डेटा को पुनः प्राप्त या सेट करता है। |
| [getXmlAsString()](#getXmlAsString--) | XML डेटा को UTF-8 स्ट्रिंग के रूप में पुनः प्राप्त या सेट करता है। |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | XML डेटा को UTF-8 स्ट्रिंग के रूप में पुनः प्राप्त या सेट करता है। |
| [getItemId()](#getItemId--) | एक वैश्विक रूप से अद्वितीय पहचानकर्ता (GUID) निर्दिष्ट करता है जो Office Open XML दस्तावेज़ में एकल कस्टम XML भाग को विशिष्ट रूप से पहचानता है। |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | एक वैश्विक रूप से अद्वितीय पहचानकर्ता (GUID) निर्दिष्ट करता है जो Office Open XML दस्तावेज़ में एकल कस्टम XML भाग को विशिष्ट रूप से पहचानता है। |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | कस्टम XML भाग से संबंधित संग्रह XML स्कीमाओं को पुनः प्राप्त करता है। |
| [remove()](#remove--) | प्रेज़ेंटेशन से कस्टम XML भाग को हटाता है। |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


XML डेटा को पुनः प्राप्त या सेट करता है। पढ़ें/लिखें byte[].

**रिटर्न:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


XML डेटा को पुनः प्राप्त या सेट करता है। पढ़ें/लिखें byte[].

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


XML डेटा को UTF-8 स्ट्रिंग के रूप में पुनः प्राप्त या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


XML डेटा को UTF-8 स्ट्रिंग के रूप में पुनः प्राप्त या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


एक वैश्विक रूप से अद्वितीय पहचानकर्ता (GUID) निर्दिष्ट करता है जो Office Open XML दस्तावेज़ में एकल कस्टम XML भाग को विशिष्ट रूप से पहचानता है। केवल-पढ़ने योग्य java.util.UUID.

**रिटर्न:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


एक वैश्विक रूप से अद्वितीय पहचानकर्ता (GUID) निर्दिष्ट करता है जो Office Open XML दस्तावेज़ में एकल कस्टम XML भाग को विशिष्ट रूप से पहचानता है। केवल-पढ़ने योग्य java.util.UUID.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


कस्टम XML भाग से संबंधित संग्रह XML स्कीमाओं को पुनः प्राप्त करता है। केवल-पढ़ने योग्य String[].

**रिटर्न:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


प्रेज़ेंटेशन से कस्टम XML भाग को हटाता है।