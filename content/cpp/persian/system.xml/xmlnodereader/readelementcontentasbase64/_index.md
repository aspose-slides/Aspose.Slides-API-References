---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides برای مرجع API C++
description: عنصر را می‌خواند و محتوای Base64 را رمزگشایی می‌کند.
type: docs
weight: 469
url: /fa/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

عنصر را می‌خواند و محتوای Base64 را رمزگشایی می‌کند.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافرئی که متن حاصل را در آن کپی می‌کنیم. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | جابجایی داخل بافر که از آنجا کپی نتیجه شروع می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که به بافر کپی می‌شوند. تعداد واقعی بایت‌های کپی‌شده توسط این متد برگردانده می‌شود. |

### مقدار بازگشتی

تعداد بایت‌های نوشته‌شده در بافر.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)