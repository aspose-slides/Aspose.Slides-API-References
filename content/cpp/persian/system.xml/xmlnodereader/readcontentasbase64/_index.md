---
title: ReadContentAsBase64()
second_title: مرجع API Aspose.Slides برای C++
description: محتوا را می‌خواند و بایت‌های دودویی رمزگشایی شده به Base64 را برمی‌گرداند.
type: docs
weight: 443
url: /fa/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) متد

محتوا را می‌خواند و بایت‌های دودویی رمزگشایی شده به‌صورت Base64 را بازمی‌گرداند.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافری که متن حاصل در آن کپی می‌شود. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | جابه‌جایی در بافر که از آن برای شروع کپی نتیجه استفاده می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که در بافر کپی می‌شوند. تعداد واقعی بایت‌های کپی‌شده توسط این متد بازگردانده می‌شود. |

### مقدار برگشتی

تعداد بایت‌های نوشته‌شده در بافر.

## مراجع

* نوع تعریف [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlNodeReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)