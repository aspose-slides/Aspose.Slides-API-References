---
title: HasFeature()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يفحص ما إذا كان تنفيذ نموذج كائن المستند (DOM) يدعم ميزة محددة.
type: docs
weight: 14
url: /ar/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) طريقة


يختبر ما إذا كان تنفيذ Document [Object](../../../system/object/) نموذج (DOM) يدعم ميزة محددة.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | اسم الحزمة الخاصة بالميزة التي سيتم اختبارها. هذا الاسم غير حساس لحالة الأحرف. |
| strVersion | const [String](../../../system/string/)\& | رقم الإصدار لاسم الحزمة المراد اختباره. إذا لم يُحدد الإصدار (**nullptr**)، فإن دعم أي إصدار من الميزة يجعل الطريقة تُعيد **true**. |

### قيمة الإرجاع

**true** إذا كانت الميزة مُنفَّذة في الإصدار المحدد؛ وإلا، **false**.
## ملاحظات



الجدول التالي يُظهر التركيبات التي تجعل **HasFeature** تُعيد **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## انظر أيضاً

* فئة [String](../../../system/string/)
* فئة [XmlImplementation](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)