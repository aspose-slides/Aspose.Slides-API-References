---
title: get_Value()
second_title: مرجع API Aspose.Slides للغة C++
description: يرجع قيمة النص للعقدة الحالية.
type: docs
weight: 79
url: /ar/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() طريقة

يرجع قيمة النص للعقدة الحالية.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### قيمة الإرجاع

القيمة المعادة تعتمد على قيمة [XmlTextReader::get_NodeType](../get_nodetype/) للعقدة.

## ملاحظات

الجدول التالي يسرد أنواع العقد التي لها قيمة للإرجاع. جميع أنواع العقد الأخرى تُرجع [String::Empty](../../../system/string/empty/).

| نوع العقدة | القيمة |
| --- | --- |
| [Attribute](../../../system/attribute/)| قيمة السمة. |
| CDATA| محتوى قسم CDATA. |
| Comment| محتوى التعليق. |
| DocumentType| المجموعة الداخلية. |
| ProcessingInstruction| المحتوى بالكامل، باستثناء الهدف. |
| SignificantWhitespace| المسافة البيضاء داخل نطاق `xml:space='preserve'`. |
| [Text](../../../system.text/)| محتوى عقدة النص. |
| Whitespace| المسافة البيضاء بين العلامات. |
| [XmlDeclaration](../../xmldeclaration/)| محتوى الإعلان. |

## انظر أيضاً

* الفئة [String](../../../system/string/)
* الفئة [XmlTextReader](../)
* مساحة الأسماء [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)