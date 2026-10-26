---
title: get_Value()
second_title: Aspose.Slides لـ C++ مرجع API
description: يرجع قيمة النص للعقدة الحالية.
type: docs
weight: 79
url: /ar/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() طريقة

يرجع قيمة النص للعقدة الحالية.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### قيمة الإرجاع

القيمة المرجعة تعتمد على [XmlNodeReader::get_NodeType](../get_nodetype/) العقدة.

## ملاحظات

القائمة التالية تسرد أنواع العقد التي لها قيمة لإرجاعها. جميع أنواع العقد الأخرى تُعيد [String::Empty](../../../system/string/empty/). 

| نوع العقدة | القيمة |
| --- | --- |
| [Attribute](../../../system/attribute/)| قيمة السمة. |
| CDATA| محتوى قسم CDATA. |
| Comment| محتوى التعليق. |
| DocumentType| المجموعة الداخلية. |
| ProcessingInstruction| المحتوى بالكامل، باستثناء الهدف. |
| SignificantWhitespace| المسافات البيضاء بين العلامات في نموذج محتوى مختلط. |
| [Text](../../../system.text/)| محتوى عقدة النص. |
| Whitespace| المسافات البيضاء بين العلامات. |
| [XmlDeclaration](../../xmldeclaration/)| محتوى الإعلان. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNodeReader](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)