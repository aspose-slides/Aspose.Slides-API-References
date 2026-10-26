---
title: get_Name()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يرّجع الاسم المؤهل للعقدة الحالية.
type: docs
weight: 14
url: /ar/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() طريقة

يرجع الاسم المؤهل للعقدة الحالية.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### قيمة الإرجاع

الاسم المؤهل للعقدة الحالية. على سبيل المثال، **Name** هو **bk:book** للعنصر **<bk:book>**.

## ملاحظات

يعتمد الاسم المرتجع على XmlValidatingReader::NodeType للعقدة. الأنواع التالية من العقد تُرجع القيم المذكورة. جميع أنواع العقد الأخرى تُرجع سلسلة فارغة. 

| نوع العقدة | الاسم |
| --- | --- |
| [Attribute](../../../system/attribute/)| اسم السمة. |
| DocumentType| اسم نوع المستند. |
| Element| اسم الوسم. |
| EntityReference| اسم الكيان المشار إليه. |
| ProcessingInstruction| الهدف من تعليمات المعالجة. |
| [XmlDeclaration](../../xmldeclaration/)| السلسلة الحرفية `xml`. |

## أنظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlValidatingReader](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)