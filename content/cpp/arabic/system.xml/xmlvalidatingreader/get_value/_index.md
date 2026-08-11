---
title: get_Value()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد القيمة النصية للعقدة الحالية.
type: docs
weight: 79
url: /ar/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() طريقة

يعيد القيمة النصية للعقدة الحالية.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```


### قيمة الإرجاع

القيمة المرجعة تعتمد على XmlValidatingReader::NodeType للعقدة.

## ملاحظات

القائمة التالية تسرد أنواع العقد التي لها قيمة تُرجع. جميع أنواع العقد الأخرى تُرجع [String::Empty](../../../system/string/empty/). 

| نوع العقدة | القيمة |
| --- | --- |
| [Attribute](../../../system/attribute/)| قيمة السمة. |
| CDATA| محتوى قسم CDATA. |
| Comment| محتوى التعليق. |
| DocumentType| المجموعة الداخلية. |
| ProcessingInstruction| المحتوى الكامل، باستثناء الهدف. |
| SignificantWhitespace| المسافة البيضاء بين العلامات في نموذج محتوى مختلط. |
| [Text](../../../system.text/)| محتوى عقدة النص. |
| Whitespace| المسافة البيضاء بين العلامات. |
| [XmlDeclaration](../../xmldeclaration/)| محتوى الإعلان. |


## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlValidatingReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)