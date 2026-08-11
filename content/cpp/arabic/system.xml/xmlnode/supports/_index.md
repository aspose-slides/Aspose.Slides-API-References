---
title: Supports()
second_title: Aspose.Slides لـ C++ مرجع API
description: يختبر ما إذا كان تنفيذ DOM ينفّذ ميزة محددة.
type: docs
weight: 482
url: /ar/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) طريقة

يختبر ما إذا كان تنفيذ DOM يدعم ميزة معينة.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| feature | [String](../../../system/string/) | اسم الحزمة للميزة التي سيتم اختبارها. لا يهم حالة الأحرف في هذا الاسم. |
| version | [String](../../../system/string/) | رقم إصدار اسم الحزمة التي سيتم اختبارها. إذا لم يتم تحديد الإصدار (null)، فإن دعم أي إصدار من الميزة يجعل الطريقة تُرجع **true**. |

### قيمة الإرجاع

**true** إذا كانت الميزة مُنفذة في النسخة المحددة؛ وإلا، **false**.

## ملاحظات

الجدول التالي يصف التركيبات التي تُعيد **true**.

| الميزة | [Version](../../../system/version/) |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [XmlNode](../)
* مساحة الأسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)