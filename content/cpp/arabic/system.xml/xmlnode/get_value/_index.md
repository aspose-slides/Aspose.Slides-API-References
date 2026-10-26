---
title: get_Value()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يرجع قيمة العقدة.
type: docs
weight: 14
url: /ar/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() طريقة

ترجع قيمة العقدة.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### قيمة الإرجاع

القيمة المرتجعة تعتمد على [XmlNode::get_NodeType](../get_nodetype/) العقدة:

| النوع | القيمة |
| --- | --- |
| [Attribute](../../../system/attribute/)| قيمة السمة. |
| CDATASection | محتوى قسم CDATA. |
| Comment | محتوى التعليق. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. يمكنك استخدام XmlElement::InnerText أو قيم [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) للوصول إلى قيمة عقدة العنصر. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | المحتوى الكامل باستثناء الهدف. |
| [Text](../../../system.text/)| محتوى عقدة النص. |
| SignificantWhitespace | حروف المسافة. يمكن أن يتكون الفراغ من حرف مساحة واحد أو أكثر، أو عودة سطر، أو تغذية سطر، أو علامات تبويب. |
| Whitespace | حروف المسافة. يمكن أن يتكون الفراغ من حرف مساحة واحد أو أكثر، أو عودة سطر، أو تغذية سطر، أو علامات تبويب. |
| [XmlDeclaration](../../xmldeclaration/)| محتوى الإعلان (أي كل شيء بين `<?xml و ?>`). |

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [XmlNode](../)
* النطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)