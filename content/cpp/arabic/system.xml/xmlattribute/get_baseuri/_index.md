---
title: get_BaseURI()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يُرجع معرف الموارد الموحد (URI) الأساسي للعقدة.
type: docs
weight: 183
url: /ar/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() طريقة

يعيد معرف الموارد الموحد (URI) الأساسي للعقدة.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```

### قيمة الإرجاع

الموقع الذي تم تحميل العقدة منه أو [String::Empty](../../../system/string/empty/) إذا لم يكن للعقدة معرف URI أساسي. عقد [Attribute](../../../system/attribute/) لها نفس URI الأساسي كعنصر المالك. إذا لم يكن لعقدة صفة عنصر مالك، فإن get_BaseURI يعيد [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlAttribute](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)