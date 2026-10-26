---
title: get_Name()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تحصل على الاسم المؤهل للعقدة الحالية.
type: docs
weight: 27
url: /ar/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() طريقة

عند تجاوزها في فئة مشتقة، تحصل على الاسم المؤهل للعقدة الحالية.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### قيمة الإرجاع

الاسم المؤهل للعقدة الحالية. على سبيل المثال، **Name** هو **bk:book** للعنصر **<bk:book>**.

## ملاحظات

الاسم المعاد يعتمد على قيمة [XmlReader::get_NodeType](../get_nodetype/) للعقدة. أنواع العقد التالية تُعيد القيم المدونة. جميع أنواع العقد الأخرى تُعيد سلسلة فارغة. 

| نوع العقدة | الاسم |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| اسم السمة. |
| `DocumentType`| اسم نوع المستند. |
| `Element`| اسم العلامة. |
| `EntityReference`| اسم الكيان المشار إليه. |
| `ProcessingInstruction`| هدف تعليمات المعالجة. |
| [XmlDeclaration](../../xmldeclaration/)| السلسلة الحرفية `xml`. |

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [XmlReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)