---
title: ReadElementContentAsBase64()
second_title: مرجع API Aspose.Slides برای C++
description: عنصر را می‌خواند و محتوای Base64 را رمزگشایی می‌کند.
type: docs
weight: 586
url: /fa/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) متد

عنصر را می‌خواند و محتوای Base64 را رمزگشایی می‌کند.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافری که متن حاصل در آن کپی می‌شود. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | جابه‌جایی داخل بافر که کپی نتیجه از آن شروع می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که باید در بافر کپی شوند. تعداد واقعی بایت‌های کپی‌شده توسط این متد بازگردانده می‌شود. |

### مقدار بازگشتی

تعداد بایت‌های نوشته‌شده در بافر.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlValidatingReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)