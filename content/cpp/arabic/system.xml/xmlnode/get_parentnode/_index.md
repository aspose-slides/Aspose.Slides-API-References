---
title: get_ParentNode()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: يعيد أصل هذه العقدة (للعقد التي يمكن أن يكون لها أصل).
type: docs
weight: 53
url: /ar/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() طريقة

يعيد أصل هذه العقدة (للعقد التي يمكن أن تكون لها أصل).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### قيمة الإرجاع

الـ[XmlNode](../) التي هي أصل العقدة الحالية.

## ملاحظات

إذا تم إنشاء عقدة للتو ولم يتم إضافتها بعد إلى الشجرة، أو إذا تم إزالتها من الشجرة، فإن الأصل يكون **nullptr**. لجميع العقد الأخرى، تعتمد القيمة المرجعة على [XmlNode::get_NodeType](../get_nodetype/) للعقدة. الجدول التالي يصف قيم الإرجاع الممكنة لطريقة **get_NodeType**.

| NodeType | قيمة الإرجاع لـ ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Returns `nullptr`; these nodes do not have parents. |
| CDATA | Returns the element or entity reference containing the CDATA section. |
| Comment | Returns the element, entity reference, document type, or document containing the comment. |
| DocumentType | Returns the document node. |
| Element | Returns the parent node of the element. If the element is the root node in the tree, the parent is the document node. |
| EntityReference | Returns the element, attribute, or entity reference containing the entity reference. |
| ProcessingInstruction | Returns the document, element, document type, or entity reference containing the processing instruction. |
| [Text](../../../system.text/)| Returns the parent element, attribute, or entity reference containing the text node. |

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../)
* مساحة الأسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)