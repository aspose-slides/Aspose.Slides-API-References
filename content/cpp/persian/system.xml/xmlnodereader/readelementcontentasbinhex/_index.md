---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides برای C++ مرجع API
description: عنصر را می‌خواند و محتوای BinHex را رمزگشایی می‌کند.
type: docs
weight: 482
url: /fa/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) متد


خواندن عنصر و رمزگشایی محتوای BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافری که متن حاصل را در آن کپی می‌کنید. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | جایگاه در بافر که کپی نتیجه از آن شروع می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که به بافر کپی می‌شوند. تعداد واقعی بایت‌های کپی‌شده توسط این متد بازگردانده می‌شود. |

### مقدار برگشتی

تعداد بایت‌های نوشته‌شده به بافر.

## مشاهده کنید

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlNodeReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)