---
title: get_Name()
second_title: Aspose.Slides لـ C++ - مرجع API
description: يعيد الاسم المؤهل للعقدة عندما يتم تجاوزها في فئة مشتقة.
type: docs
weight: 1
url: /ar/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() طريقة

Returns the qualified name of the node, when overridden in a derived class.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### قيمة الإرجاع

The qualified name of the node.

## ملاحظات

The name returned is dependent on the [XmlNode::get_NodeType](../get_nodetype/) of the node:

| نوع | اسم |
| --- | --- |
| [Attribute](../../../system/attribute/)| الاسم المؤهل للخاصية. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | اسم نوع المستند. |
| Element | الاسم المؤهل للعنصر. |
| Entity | اسم الكيان. |
| EntityReference | اسم الكيان المشار إليه. |
| Notation | اسم التدوين. |
| ProcessingInstruction | هدف تعليمات المعالجة. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNode](../)
* مساحة الأسماء [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)