---
title: get_NameTable()
second_title: مرجع API Aspose.Slides للغة C++
description: يرجع XmlNameTable المستخدمة لمقارنات السلاسل المذكرة.
type: docs
weight: 1
url: /ar/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() طريقة


إرجاع [XmlNameTable](../../xmlnametable/) المستخدمة لمقارنات السلاسل المذكرة.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### قيمة الإرجاع

ال[XmlNameTable](../../xmlnametable/) التي تخزن جميع السلاسل المذكرة المستخدمة من قبل جميع مثيلات [XmlReader](../../xmlreader/) التي تم إنشاؤها باستخدام كائن [XmlReaderSettings](../) هذا. القيمة الافتراضية هي **nullptr**. مثيل [XmlReader](../../xmlreader/) الذي تم إنشاؤه سيستخدم [NameTable](../../nametable/) فارغًا جديدًا إذا كانت هذه القيمة **nullptr**.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNameTable](../../xmlnametable/)
* فئة [XmlReaderSettings](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)