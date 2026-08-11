---
title: get_LocalName()
second_title: مرجع API Aspose.Slides للغة C++
description: يرجع الاسم المحلي للعقدة عندما يتم تجاوزها في فئة مشتقة.
type: docs
weight: 209
url: /ar/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() طريقة

يرجع الاسم المحلي للعقدة عندما يتم تجاوزها في فئة مشتقة.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```

### قيمة الإرجاع

اسم العقدة بعد إزالة البادئة. على سبيل المثال، **LocalName** هو **book** للعنصر **<bk:book>**.

## ملاحظات

الاسم المرجع يعتمد على [XmlNode::get_NodeType](../get_nodetype/) للعقدة:

| النوع | الاسم |
| --- | --- |
| [Attribute](../../../system/attribute/)| الاسم المحلي للخاصية. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | اسم نوع المستند. |
| Element | الاسم المحلي للعنصر. |
| Entity | اسم الكيان. |
| EntityReference | اسم الكيان المرجعي. |
| Notation | اسم التدوين. |
| ProcessingInstruction | الهدف من تعليمات المعالجة. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## انظر أيضاً

* فئة [String](../../../system/string/)
* فئة [XmlNode](../)
* نطاق الأسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)