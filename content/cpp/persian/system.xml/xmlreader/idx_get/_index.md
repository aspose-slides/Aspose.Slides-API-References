---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: زمانی که در یک کلاس مشتق بازنویسی می‌شود، مقدار ویژگی با ایندکس مشخص‌شده را برمی‌گرداند.
type: docs
weight: 612
url: /fa/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) متد

زمانی که در یک کلاس مشتق بازنویسی می‌شود، مقدار ویژگی با ایندکس مشخص شده را بر می‌گرداند.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | **int32_t** | ایندکس ویژگی. |

### مقدار بازگشتی

مقدار ویژگی مشخص شده.

## XmlReader::idx_get(String) متد

زمانی که در یک کلاس مشتق بازنویسی می‌شود، مقدار ویژگی با مقدار [XmlReader::get_Name](../get_name/) مشخص شده را بر می‌گرداند.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام معتبر ویژگی. |

### مقدار بازگشتی

مقدار ویژگی مشخص شده. اگر ویژگی یافت نشود، **nullptr** برگردانده می‌شود.

## XmlReader::idx_get(String, String) متد

زمانی که در یک کلاس مشتق بازنویسی می‌شود، مقدار ویژگی با مقادیر [XmlReader::get_LocalName](../get_localname/) و [XmlReader::get_NamespaceURI](../get_namespaceuri/) مشخص شده را بر می‌گرداند.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای‌نام ویژگی. |

### مقدار بازگشتی

مقدار ویژگی مشخص شده. اگر ویژگی یافت نشود، **nullptr** برگردانده می‌شود.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)