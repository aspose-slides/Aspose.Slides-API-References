---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Represents custom xml part.
type: docs
url: /hi/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

कस्टम XML भाग का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | UTF-8 स्ट्रिंग के रूप में xml डेटा को लौटाता या सेट करता है। |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | UTF-8 स्ट्रिंग के रूप में xml डेटा को लौटाता या सेट करता है। |
| [getXmlData()](#getXmlData--) | xml डेटा को लौटाता या सेट करता है। |
| [setXmlData(byte[] value)](#setXmlData-byte---) | xml डेटा को लौटाता या सेट करता है। |
| [getItemId()](#getItemId--) | एक Office Open XML दस्तावेज़ के भीतर एकल कस्टम XML भाग की विशिष्ट पहचान करने वाला ग्रोबली यूनिक आइडेंटिफायर (GUID) निर्दिष्ट करता है। |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | एक Office Open XML दस्तावेज़ के भीतर एकल कस्टम XML भाग की विशिष्ट पहचान करने वाला ग्रोबली यूनिक आइडेंटिफायर (GUID) निर्दिष्ट करता है। |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | कस्टम XML भाग से जुड़े संग्रह XML स्कीमा को लौटाता है। |
| [remove()](#remove--) | प्रस्तुति से कस्टम xml भाग को हटाता है। |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

UTF-8 स्ट्रिंग के रूप में xml डेटा को लौटाता या सेट करता है। पढ़ने/लिखने योग्य String.

**रिटर्न:**  
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

UTF-8 स्ट्रिंग के रूप में xml डेटा को लौटाता या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

xml डेटा को लौटाता या सेट करता है। पढ़ने/लिखने योग्य byte[].

**रिटर्न:**  
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

xml डेटा को लौटाता या सेट करता है। पढ़ने/लिखने योग्य byte[].

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

एक Office Open XML दस्तावेज़ के भीतर एकल कस्टम XML भाग की विशिष्ट पहचान करने वाला ग्रोबली यूनिक आइडेंटिफायर (GUID) निर्दिष्ट करता है। केवल पढ़ने योग्य java.util.UUID.

**रिटर्न:**  
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

एक Office Open XML दस्तावेज़ के भीतर एकल कस्टम XML भाग की विशिष्ट पहचान करने वाला ग्रोबली यूनिक आइडेंटिफायर (GUID) निर्दिष्ट करता है। केवल पढ़ने योग्य java.util.UUID.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

कस्टम XML भाग से जुड़े संग्रह XML स्कीमा को लौटाता है। केवल पढ़ने योग्य String[].

**रिटर्न:**  
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

प्रस्तुति से कस्टम xml भाग को हटाता है।