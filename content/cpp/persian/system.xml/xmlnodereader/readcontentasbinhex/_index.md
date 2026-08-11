---
title: ReadContentAsBinHex()
second_title: Aspose.Slides برای C++ مرجع API
description: محتوا را می‌خواند و بایت‌های دودویی رمزگشایی‌شده از BinHex را برمی‌گرداند.
type: docs
weight: 456
url: /fa/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) متد

محتوا را می‌خواند و بایت‌های دودویی رمزگشایی شده از BinHex را برمی‌گرداند.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافرئی که متن نتیجه را به آن کپی می‌کند. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | افست در بافر که کپی نتیجه از آنجا شروع می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت برای کپی به بافر. تعداد واقعی بایت‌های کپی‌شده توسط این متد برگردانده می‌شود. |

### مقدار بازگشتی

تعداد بایت‌های نوشته‌شده در بافر.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlNodeReader](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)