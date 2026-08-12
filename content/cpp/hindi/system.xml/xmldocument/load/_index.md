---
title: Load()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट URL से XML दस्तावेज़ लोड करता है।
type: docs
weight: 508
url: /hi/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) विधि

निर्दिष्ट URL से XML दस्तावेज़ लोड करता है।

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | [String](../../../system/string/) | लोड करने के लिए XML दस्तावेज़ वाली फ़ाइल का URL। URL स्थानीय फ़ाइल या HTTP URL (एक [Web](../../../system.web/) पता) हो सकता है। |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) विधि

निर्दिष्ट स्ट्रीम से XML दस्तावेज़ लोड करता है।

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | लोड करने के लिए XML दस्तावेज़ वाली स्ट्रीम। |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) विधि

निर्दिष्ट TextReader से XML दस्तावेज़ लोड करता है।

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | दस्तावेज़ में XML डेटा फ़ीड करने के लिए प्रयुक्त TextReader। |

## XmlDocument::Load(SharedPtr\<XmlReader\>) विधि

निर्दिष्ट [XmlReader](../../xmlreader/) से XML दस्तावेज़ लोड करता है।

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | दस्तावेज़ में XML डेटा फ़ीड करने के लिए प्रयुक्त [XmlReader](../../xmlreader/)। |

## संदर्भ

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [XmlDocument](../)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [TextReader](../../../system.io/textreader/)
* क्लास [XmlReader](../../xmlreader/)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)