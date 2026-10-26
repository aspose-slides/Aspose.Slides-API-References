---
title: get_Value()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند إعادة تعريفه في فئة مشتقة، يحصل على القيمة النصية للعقدة الحالية.
type: docs
weight: 92
url: /ar/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() طريقة

When overridden in a derived class, gets the text value of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### قيمة الإرجاع

The value returned depends on the [XmlReader::get_NodeType](../get_nodetype/) value of the node.

## ملاحظات

The following table lists node types that have a value to return. All other node types return [String::Empty](../../../system/string/empty/). 

| نوع العقدة | القيمة |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| قيمة السمة. |
| `CDATA`| محتوى قسم CDATA. |
| `Comment`| محتوى التعليق. |
| `DocumentType`| المجموعة الداخلية. |
| `ProcessingInstruction`| المحتوى الكامل، باستثناء الهدف. |
| `SignificantWhitespace`| مسافة بيضاء بين العلامات في نموذج محتوى مختلط. |
| `[Text](../../../system.text/)`| محتوى عقدة النص. |
| `Whitespace`| مسافة بيضاء بين العلامات. |
| [XmlDeclaration](../../xmldeclaration/)| محتوى الإعلان. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* نطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)