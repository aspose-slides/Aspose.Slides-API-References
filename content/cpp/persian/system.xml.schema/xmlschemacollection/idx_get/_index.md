---
title: idx_get()
second_title: Aspose.Slides برای C++ مرجع API
description: طرح XmlSchema مرتبط با URI فضای نام داده شده را باز می‌گرداند.
type: docs
weight: 53
url: /fa/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) متد

مقدار [XmlSchema](../../xmlschema/) مرتبط با URI فضای‌نامی ارائه‌شده را باز می‌گرداند.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI فضای‌نامی مرتبط با طرح‌schema که می‌خواهید برگردانید. این معمولاً **targetNamespace** طرح خواهد بود. |

### مقدار بازگشتی

[XmlSchema](../../xmlschema/) مرتبط با URI فضای‌نامی؛ **nullptr** اگر طرح بارگذاری‌شده‌ای مرتبط با فضای‌نامی داده‌شده وجود نداشته باشد یا اگر فضای‌نامی با یک طرح XDR مرتبط باشد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlSchema](../../xmlschema/)
* کلاس [String](../../../system/string/)
* کلاس [XmlSchemaCollection](../)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)