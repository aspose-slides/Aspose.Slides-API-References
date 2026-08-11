---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides برای مرجع API C++
description: عنصر را می‌خواند و محتوای BinHex را رمزگشایی می‌کند.
type: docs
weight: 612
url: /fa/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

عنصر را می‌خواند و محتوای BinHex را رمزگشایی می‌کند.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر که متن حاصل در آن کپی می‌شود. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | افست در بافر که از آنجا کپی نتایج آغاز می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که به بافر کپی می‌شوند. تعداد واقعی بایت‌های کپی شده توسط این متد برگردانده می‌شود. |

## مقدار برگردانده شده

تعداد بایت‌های نوشته شده در بافر.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlValidatingReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)