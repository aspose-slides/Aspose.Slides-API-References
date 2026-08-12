---
title: Read()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: इनपुट स्ट्रीम से एकल अक्षर पढ़ता है।
type: docs
weight: 66
url: /hi/system.io/binaryreader/read/
---
## BinaryReader::Read() विधि

इनपुट स्ट्रीम से एकल अक्षर पढ़ता है।

```cpp
virtual int System::IO::BinaryReader::Read()
```

### वापसी मान

UTF-16 एन्कोडिंग के साथ एन्कोडेड पढ़ा गया अक्षर; यदि पढ़ा गया अक्षर UTF-16 एन्कोडिंग में दो कोडपॉइंट्स द्वारा दर्शाया गया है तो केवल उच्च सर्रेगेट लौटाया जाता है।

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) विधि

इनपुट स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे |
| index | int | **buffer** में 0-आधारित स्थिति जहाँ से लिखना शुरू करना है |
| count | int | पढ़ने के लिए बाइट्स की संख्या |

### वापसी मान

पढ़े गए बाइट्स की संख्या

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) विधि

इनपुट स्ट्रीम से निर्दिष्ट संख्या में अक्षर पढ़ता है, उन्हें UTF-16 एन्कोडिंग में बदलता है और प्राप्त UTF-16 अक्षरों को निर्दिष्ट कैरेक्टर एरे में निर्दिष्ट स्थिति से लिखता है।

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | इनपुट स्ट्रीम से पढ़े गए अक्षरों को लिखने के लिए UTF-16 कैरेक्टर एरे |
| index | int | **buffer** में 0-आधारित इंडेक्स जहाँ से लिखना शुरू करना है |
| count | int | स्ट्रीम से पढ़ने के लिए अक्षरों की संख्या |

### वापसी मान

इनपुट स्ट्रीम से पढ़े गए अक्षरों की संख्या

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [BinaryReader](../)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)