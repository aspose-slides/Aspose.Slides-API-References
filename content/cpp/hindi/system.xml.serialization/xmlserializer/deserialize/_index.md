---
title: Deserialize()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है।
type: docs
weight: 14
url: /hi/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) विधि

XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है।

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | दस्तावेज़ को पढ़ने के लिए स्ट्रीम। |

### रिटर्न वैल्यू

[Object](../../../system/object/) जो पहले दी गई दस्तावेज़ में सीरियलाइज़ किया गया था।

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) विधि

XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है।

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | दस्तावेज़ को पढ़ने के लिए रीडर। |

### रिटर्न वैल्यू

[Object](../../../system/object/) जो पहले दी गई दस्तावेज़ में सीरियलाइज़ किया गया था।

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) विधि

XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है।

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | दस्तावेज़ को पढ़ने के लिए रीडर। |

### रिटर्न वैल्यू

[Object](../../../system/object/) जो पहले दी गई दस्तावेज़ में सीरियलाइज़ किया गया था।

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) विधि

XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है।

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | दस्तावेज़ को पढ़ने के लिए रीडर। |
| encodingStyle | [String](../../../system/string/) | ऑब्जेक्ट को सीरियलाइज़ करने के लिए उपयोग किया गया शैली। |

### रिटर्न वैल्यू

[Object](../../../system/object/) जो पहले दी गई दस्तावेज़ में सीरियलाइज़ किया गया था।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [XmlSerializer](../)
* क्लास [TextReader](../../../system.io/textreader/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml::Serialization](../../)
* लाइब्रेरी [Aspose.Slides](../../../)