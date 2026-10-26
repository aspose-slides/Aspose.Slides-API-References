---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides برای C++ مرجع API
description: عنصر را می‌خواند و محتوای Base64 را رمزگشایی می‌کند.
type: docs
weight: 651
url: /fa/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

عنصر را می‌خواند و محتوای Base64 را رمزگشایی می‌کند.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافرئی که متن حاصل در آن کپی می‌شود. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | جایگاهی در بافر که کپی نتیجه از آن شروع می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که به بافر کپی می‌شوند. تعداد واقعی بایت‌های کپی شده توسط این متد برگردانده می‌شود. |

### مقدار بازگشتی

تعداد بایت‌های نوشته شده در بافر.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlTextReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)