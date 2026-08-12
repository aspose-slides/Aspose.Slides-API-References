---
title: ReadToFollowing()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट योग्य नाम वाले तत्व को मिलने तक पढ़ता है।
type: docs
weight: 898
url: /hi/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) विधि

निर्दिष्ट योग्य नाम वाले तत्व को मिलने तक पढ़ता है।

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | तत्व का योग्य नाम। |

### रिटर्न वैल्यू

**true** यदि मिलते-जुलते तत्व को पाया जाता है; अन्यथा **false** और [XmlReader](../) फ़ाइल के अंत की स्थिति में है।

## XmlReader::ReadToFollowing(String, String) विधि

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले तत्व को मिलने तक पढ़ता है।

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | तत्व का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | तत्व का नेमस्पेस URI। |

### रिटर्न वैल्यू

**true** यदि मिलते-जुलते तत्व को पाया जाता है; अन्यथा **false** और [XmlReader](../) फ़ाइल के अंत की स्थिति में है।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)