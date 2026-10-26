---
title: ToString()
second_title: Aspose.Slides لـ C++ مرجع API
description: يرجع القيمة النصية لـ XmlQualifiedName.
type: docs
weight: 79
url: /ar/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const طريقة

يرجع قيمة السلسلة للـ [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### قيمة الإرجاع

قيمة السلسلة للـ [XmlQualifiedName](../) بالتنسيق **namespace:localname**. إذا لم يكن للكائن نطاق معرف، تُعيد هذه الطريقة اسم العنصر المحلي فقط.

## XmlQualifiedName::ToString(const String\&, const String\&) طريقة

يرجع قيمة السلسلة للـ [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم الكائن. |
| ns | const [String](../../../system/string/)\& | نطاق الكائن. |

### قيمة الإرجاع

قيمة السلسلة للـ [XmlQualifiedName](../) بالتنسيق **namespace:localname**. إذا لم يكن للكائن نطاق معرف، تُعيد هذه الطريقة اسم العنصر المحلي فقط.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlQualifiedName](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)