---
title: ReadToDescendant()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट योग्य नाम वाले अगले वंशज तत्व तक XmlReader को आगे बढ़ाता है।
type: docs
weight: 911
url: /hi/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) विधि

[XmlReader](../) को निर्दिष्ट योग्य नाम वाले अगले वंशज तत्व तक ले जाता है।

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### तर्क

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| name | [String](../../../system/string/) | वह योग्य नाम जो आप तत्व तक पहुँचने के लिए चाहते हैं। |

### वापसी मान

**true** यदि मिलते-जुलते वंशज तत्व पाया जाता है; अन्यथा **false**। यदि मिलते-जुलते बाल तत्व नहीं मिलता, तो [XmlReader](../) तत्व के अंत टैग ([XmlReader::get_NodeType](../get_nodetype/) मान [XmlNodeType::EndElement](../../xmlnodetype/)) पर स्थित हो जाता है। यदि [XmlReader](../) को [XmlReader::ReadToDescendant(String)](./) कॉल होने पर किसी तत्व पर स्थित नहीं किया गया है, तो यह विधि **false** लौटाती है और [XmlReader](../) की स्थिति नहीं बदलती।

## XmlReader::ReadToDescendant(String, String) विधि

[XmlReader](../) को निर्दिष्ट स्थानीय नाम और नामस्थान URI वाले अगले वंशज तत्व तक ले जाता है।

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### तर्क

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| localName | [String](../../../system/string/) | वह स्थानीय नाम जो आप तत्व तक पहुँचने के लिए चाहते हैं। |
| namespaceURI | [String](../../../system/string/) | वह नामस्थान URI जो आप तत्व तक पहुँचने के लिए चाहते हैं। |

### वापसी मान

**true** यदि मिलते-जुलते वंशज तत्व पाया जाता है; अन्यथा **false**। यदि मिलते-जुलते बाल तत्व नहीं मिलता, तो [XmlReader](../) तत्व के अंत टैग ([XmlReader::get_NodeType](../get_nodetype/) मान [XmlNodeType::EndElement](../../xmlnodetype/)) पर स्थित हो जाता है। यदि [XmlReader](../) को [XmlReader::ReadToDescendant(String,String)](./) कॉल होने पर किसी तत्व पर स्थित नहीं किया गया है, तो यह विधि **false** लौटाती है और [XmlReader](../) की स्थिति नहीं बदलती।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)