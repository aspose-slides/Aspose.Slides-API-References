---
title: idx_get()
second_title: Aspose.Slides برای C++ مرجع API
description: صفتی با اندیس مشخص شده را برمی‌گرداند.
type: docs
weight: 1
url: /fa/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) متد

صفتی با اندیس مشخص شده را برمی‌گرداند.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | **int32_t** | اندیس صفت. |

### مقدار بازگشت

صفت در اندیس مشخص شده.

## XmlAttributeCollection::idx_get(const String\&) متد

صفتی با نام مشخص شده را برمی‌گرداند.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام کامل صفت. |

### مقدار بازگشت

صفت با نام مشخص شده. اگر صفت وجود نداشته باشد، این متد **nullptr** برمی‌گرداند.

## XmlAttributeCollection::idx_get(const String\&, const String\&) متد

صفتی با نام محلی و URI فضای‌نام مشخص شده را برمی‌گرداند.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | نام محلی صفت. |
| namespaceURI | const [String](../../../system/string/)\& | URI فضای‌نام صفت. |

### مقدار بازگشت

صفت با نام محلی و URI فضای‌نام مشخص شده. اگر صفت وجود نداشته باشد، این متد **nullptr** برمی‌گرداند.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlAttribute](../../xmlattribute/)
* کلاس [XmlAttributeCollection](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)