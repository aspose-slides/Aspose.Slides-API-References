---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Represents custom xml part.
type: docs
url: /hi/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

कस्टम XML भाग को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | XML डेटा को UTF-8 स्ट्रिंग के रूप में वापस करता है या सेट करता है। |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | XML डेटा को UTF-8 स्ट्रिंग के रूप में वापस करता है या सेट करता है। |
| [getXmlData()](#getXmlData--) | XML डेटा को वापस करता है या सेट करता है। |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML डेटा को वापस करता है या सेट करता है। |
| [getItemId()](#getItemId--) | एक ग्लोबली यूनिक आइडेंटिफायर (GUID) निर्दिष्ट करता है जो Office Open XML दस्तावेज़ में एकल कस्टम XML भाग को विशिष्ट रूप से पहचानता है। |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | एक ग्लोबली यूनिक आइडेंटिफायर (GUID) निर्दिष्ट करता है जो Office Open XML दस्तावेज़ में एकल कस्टम XML भाग को विशिष्ट रूप से पहचानता है। |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | कस्टम XML भाग से जुड़ी संग्रह XML स्कीमा को वापस करता है। |
| [remove()](#remove--) | प्रेजेंटेशन से कस्टम XML भाग को हटाता है। |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

XML डेटा को UTF-8 स्ट्रिंग के रूप में वापस करता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

XML डेटा को UTF-8 स्ट्रिंग के रूप में वापस करता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

XML डेटा को वापस करता है या सेट करता है। पढ़ें/लिखें byte[].

**रिटर्न:**  
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

XML डेटा को वापस करता है या सेट करता है। पढ़ें/लिखें byte[].

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

एक ग्लोबली यूनिक आइडेंटिफायर (GUID) निर्दिष्ट करता है जो Office Open XML दस्तावेज़ में एकल कस्टम XML भाग को विशिष्ट रूप से पहचानता है। केवल पढ़ने योग्य java.util.UUID.

**रिटर्न:**  
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

एक ग्लोबली यूनिक आइडेंटिफायर (GUID) निर्दिष्ट करता है जो Office Open XML दस्तावेज़ में एकल कस्टम XML भाग को विशिष्ट रूप से पहचानता है। केवल पढ़ने योग्य java.util.UUID.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

कस्टम XML भाग से जुड़ी संग्रह XML स्कीमा को वापस करता है। केवल पढ़ने योग्य String[].

**रिटर्न:**  
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

प्रेजेंटेशन से कस्टम XML भाग को हटाता है।