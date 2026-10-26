---
title: get_Name()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يعيد الاسم المؤهل للعقدة الحالية.
type: docs
weight: 14
url: /ar/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() طريقة

تُعيد الاسم المؤهل للعقدة الحالية.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### قيمة الإرجاع

الاسم المؤهل للعقدة الحالية. على سبيل المثال، **Name** هو **bk:book** للعنصر **<bk:book>**.

## ملاحظات

يعتمد الاسم المُرجع على قيمة [XmlTextReader::get_NodeType](../get_nodetype/) للعقدة. تُعيد أنواع العقد التالية القيم المذكورة. جميع أنواع العقد الأخرى تُعيد سلسلة فارغة. 

| نوع العقدة | الاسم |
| --- | --- |
| [Attribute](../../../system/attribute/)| اسم السمة. |
| DocumentType| اسم نوع الوثيقة. |
| Element| اسم العلامة. |
| EntityReference| اسم الكيان المشار إليه. |
| ProcessingInstruction| هدف تعليمات المعالجة. |
| [XmlDeclaration](../../xmldeclaration/)| السلسلة الحرفية `xml`. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlTextReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)