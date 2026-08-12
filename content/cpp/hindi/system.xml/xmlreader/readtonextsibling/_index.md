---
title: ReadToNextSibling()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट योग्य नाम वाले अगले सहोदर तत्व तक XmlReader को आगे बढ़ाता है।
type: docs
weight: 924
url: /hi/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) विधि


[XmlReader](../) को निर्दिष्ट योग्य नाम वाले अगले सहोदर तत्व तक ले जाता है।

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | सहोदर तत्व का योग्य नाम जिसे आप स्थानांतरित होना चाहते हैं। |

### वापसी मान

**true** यदि मिलते-जुलते सहोदर तत्व पाया जाता है; अन्यथा **false**। यदि मिलते-जुलते सहोदर तत्व नहीं मिला, तो [XmlReader](../) पैरेंट तत्व के अंत टैग ([XmlReader::get_NodeType](../get_nodetype/) मान [XmlNodeType::EndElement](../../xmlnodetype/)) पर स्थित हो जाता है।

## XmlReader::ReadToNextSibling(String, String) विधि


[XmlReader](../) को निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले सहोदर तत्व तक ले जाता है।

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | सहोदर तत्व का स्थानीय नाम जिसे आप स्थानांतरित होना चाहते हैं। |
| namespaceURI | [String](../../../system/string/) | सहोदर तत्व का नेमस्पेस URI जिसे आप स्थानांतरित होना चाहते हैं। |

### वापसी मान

**true** यदि मिलते-जुलते सहोदर तत्व पाया जाता है; अन्यथा **false**। यदि मिलते-जुलते सहोदर तत्व नहीं मिला, तो [XmlReader](../) पैरेंट तत्व के अंत टैग ([XmlReader::get_NodeType](../get_nodetype/) मान [XmlNodeType::EndElement](../../xmlnodetype/)) पर स्थित हो जाता है।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)