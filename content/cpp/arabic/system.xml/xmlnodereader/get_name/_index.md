---
title: get_Name()
second_title: Aspose.Slides للـ C++ مرجع API
description: يُعيد الاسم المؤهل للعقدة الحالية.
type: docs
weight: 14
url: /ar/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() طريقة

تُعيد الاسم المؤهل للعقدة الحالية.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### قيمة الإرجاع

الاسم المؤهل للعقدة الحالية. على سبيل المثال، **Name** هو **bk:book** للعنصر **<bk:book>**.

## ملاحظات

الاسم المعاد يعتمد على قيمة [XmlNodeReader::get_NodeType](../get_nodetype/) للعقدة. الأنواع التالية من العقد تُعيد القيم المذكورة. جميع أنواع العقد الأخرى تُعيد سلسلة فارغة. 

| نوع العقدة | الاسم |
| --- | --- |
| [Attribute](../../../system/attribute/)| اسم السمة. |
| DocumentType| اسم نوع المستند. |
| Element| اسم الوسم. |
| EntityReference| اسم الكيان المشار إليه. |
| ProcessingInstruction| هدف تعليمات المعالجة. |
| [XmlDeclaration](../../xmldeclaration/)| السلسلة الحرفية `xml`. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNodeReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)