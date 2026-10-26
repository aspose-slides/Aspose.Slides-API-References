---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: OLE ऑब्जेक्ट के लिए एम्बेडेड डेटा जानकारी का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/oleembeddeddatainfo/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

OLE ऑब्जेक्ट के लिए एम्बेडेड डेटा जानकारी का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | OLE ऑब्जेक्ट के लिए नई एम्बेडेड डेटा जानकारी बनाता है। |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | OLE ऑब्जेक्ट के लिए एम्बेडेड डेटा जानकारी का एक नया इंस्टेंस बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | एक एम्बेडेड OLE ऑब्जेक्ट का फ़ाइल डेटा लौटाता है केवल पढ़ने योग्य byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | वर्तमान एम्बेडेड OLE ऑब्जेक्ट के लिए फ़ाइल एक्सटेंशन लौटाता है केवल पढ़ने योग्य String। |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

OLE ऑब्जेक्ट के लिए नई एम्बेडेड डेटा जानकारी बनाता है।

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

OLE ऑब्जेक्ट के लिए एम्बेडेड डेटा जानकारी का एक नया इंस्टेंस बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| embeddedFileData | byte[] | एक एम्बेडेड OLE ऑब्जेक्ट का फ़ाइल डेटा byte[]. |
| embeddedFileExtension | java.lang.String | वर्तमान एम्बेडेड OLE ऑब्जेक्ट के लिए फ़ाइल एक्सटेंशन String। |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

एक एम्बेडेड OLE ऑब्जेक्ट का फ़ाइल डेटा लौटाता है केवल पढ़ने योग्य byte[]।

**रिटर्न:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

वर्तमान एम्बेडेड OLE ऑब्जेक्ट के लिए फ़ाइल एक्सटेंशन लौटाता है केवल पढ़ने योग्य String।

**रिटर्न:**
java.lang.String