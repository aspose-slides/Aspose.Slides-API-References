---
title: Read()
second_title: Aspose.Slides for C++ API संदर्भ
description: "प्रदान किए गए IO::TextReader से XML Schema पढ़ता है।"
type: docs
weight: 365
url: /hi/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) विधि

प्रदान किए गए [IO::TextReader](../../../system.io/textreader/) से XML [Schema](../../) पढ़ता है।

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | [IO::TextReader](../../../system.io/textreader/) जिसमें पढ़ने के लिये XML [Schema](../../) शामिल है। |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) सिंटैक्स त्रुटियों के बारे में जानकारी प्राप्त करने वाला सत्यापन इवेंट हैंडलर। |

### रिटर्न मान

[XmlSchema](../) ऑब्जेक्ट जो XML [Schema](../../) का प्रतिनिधित्व करता है।

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) विधि

प्रदान किए गए स्ट्रीम से XML [Schema](../../) पढ़ता है।

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | प्रदान किया गया डेटा स्ट्रीम। |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) सिंटैक्स त्रुटियों के बारे में जानकारी प्राप्त करने वाला सत्यापन इवेंट हैंडलर। |

### रिटर्न मान

[XmlSchema](../) ऑब्जेक्ट जो XML [Schema](../../) का प्रतिनिधित्व करता है।

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) विधि

प्रदान किए गए [XmlReader](../../../system.xml/xmlreader/) से XML [Schema](../../) पढ़ता है।

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) जिसमें पढ़ने के लिये XML [Schema](../../) शामिल है। |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) सिंटैक्स त्रुटियों के बारे में जानकारी प्राप्त करने वाला सत्यापन इवेंट हैंडलर। |

### रिटर्न मान

[XmlSchema](../) ऑब्जेक्ट जो XML [Schema](../../) का प्रतिनिधित्व करता है।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* क्लास [XmlSchema](../)
* क्लास [TextReader](../../../system.io/textreader/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* नेमस्पेस [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)