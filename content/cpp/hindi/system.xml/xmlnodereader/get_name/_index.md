---
title: get_Name()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान नोड का योग्य नाम लौटाता है।
type: docs
weight: 14
url: /hi/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() विधि

Current node का qualified name लौटाता है।

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### रिटर्न मान

Current node का qualified name। उदाहरण के लिए, **Name** **bk:book** है element **<bk:book>** के लिये।

## टिप्पणी

वापस किया गया नाम नोड के [XmlNodeReader::get_NodeType](../get_nodetype/) मान पर निर्भर करता है। नीचे दिए गए नोड प्रकार सूचीबद्ध मान लौटाते हैं। सभी अन्य नोड प्रकार एक खाली स्ट्रिंग लौटाते हैं।

| नोड प्रकार | नाम |
| --- | --- |
| [Attribute](../../../system/attribute/)| एट्रिब्यूट का नाम। |
| DocumentType| दस्तावेज़ प्रकार का नाम। |
| Element| टैग का नाम। |
| EntityReference| संदर्भित इकाई का नाम। |
| ProcessingInstruction| प्रोसेसिंग निर्देश का लक्ष्य। |
| [XmlDeclaration](../../xmldeclaration/)| लिटरल स्ट्रिंग `xml`। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)