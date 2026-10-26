---
title: get_Name()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: जब किसी व्युत्पन्न वर्ग में पुनःपरिभाषित किया जाता है, तो यह वर्तमान नोड का योग्य नाम प्राप्त करता है।
type: docs
weight: 27
url: /hi/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() विधि

When overridden in a derived class, gets the qualified name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### रिटर्न मान

वर्तमान नोड का योग्य नाम। उदाहरण के लिए, **Name** तत्व **<bk:book>** के लिए **bk:book** है।

## टिप्पणी

वापस किया गया नाम नोड के [XmlReader::get_NodeType](../get_nodetype/) मान पर निर्भर करता है। निम्नलिखित नोड प्रकार सूचीबद्ध मान लौटाते हैं। सभी अन्य नोड प्रकार खाली स्ट्रिंग लौटाते हैं। 

| नोड प्रकार | नाम |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| गुणधर्म का नाम। |
| `DocumentType`| दस्तावेज़ प्रकार का नाम। |
| `Element`| टैग का नाम। |
| `EntityReference`| संदर्भित इकाई का नाम। |
| `ProcessingInstruction`| प्रोसेसिंग निर्देश का लक्ष्य। |
| [XmlDeclaration](../../xmldeclaration/)| लिटरल स्ट्रिंग `xml`। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)