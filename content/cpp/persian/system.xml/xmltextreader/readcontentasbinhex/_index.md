---
title: ReadContentAsBinHex()
second_title: Aspose.Slides برای C++ مرجع API
description: محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شده با BinHex را برمی‌گرداند.
type: docs
weight: 664
url: /fa/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) متد

محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شده با **BinHex** را برمی‌گرداند.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافرئی که متن حاصل به آن کپی می‌شود. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | جایگاه در بافر که کپی نتیجه از آن شروع می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که به بافر کپی می‌شوند. تعداد واقعی بایت‌های کپی‌شده توسط این متد بازگردانده می‌شود. |

### مقدار برگردانده شده

تعداد بایت‌های نوشته‌شده در بافر.

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlTextReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)