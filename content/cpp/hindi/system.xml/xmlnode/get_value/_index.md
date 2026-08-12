---
title: get_Value()
second_title: Aspose.Slides for C++ API संदर्भ
description: नोड का मान लौटाता है।
type: docs
weight: 14
url: /hi/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() मेथड

नोड का मान लौटाता है।

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### रिटर्न मान

वापसी मान नोड के [XmlNode::get_NodeType](../get_nodetype/) पर निर्भर करता है:

| प्रकार | मान |
| --- | --- |
| [Attribute](../../../system/attribute/)| विशेषता का मान। |
| CDATASection | CDATA सेक्शन की सामग्री। |
| Comment | टिप्पणी की सामग्री। |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. आप XmlElement::InnerText या [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) मानों का उपयोग करके तत्व नोड का मान प्राप्त कर सकते हैं। |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | लक्ष्य को छोड़कर पूरी सामग्री। |
| [Text](../../../system.text/)| टेक्स्ट नोड की सामग्री। |
| SignificantWhitespace | व्हाइटस्पेस अक्षर। व्हाइटस्पेस में एक या अधिक स्पेस अक्षर, कैरिज रिटर्न, लाइन फ़ीड या टैब हो सकते हैं। |
| Whitespace | व्हाइटस्पेस अक्षर। व्हाइटस्पेस में एक या अधिक स्पेस अक्षर, कैरिज रिटर्न, लाइन फ़ीड या टैब हो सकते हैं। |
| [XmlDeclaration](../../xmldeclaration/)| घोषणा की सामग्री (अर्थात `<?xml` और `?>` के बीच सब कुछ)। |

## संबंधित

* क्लास [String](../../../system/string/)
* क्लास [XmlNode](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)