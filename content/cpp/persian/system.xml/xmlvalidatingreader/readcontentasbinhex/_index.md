---
title: ReadContentAsBinHex()
second_title: Aspose.Slides برای C++ مرجع API
description: محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شده BinHex را بر می‌گرداند.
type: docs
weight: 599
url: /fa/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) متد

محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شده BinHex را بر می‌گرداند.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر‌ای که متن حاصل در آن کپی می‌شود. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | جابجایی در بافر که از آنجا کپی نتیجه آغاز می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که در بافر کپی می‌شود. تعداد واقعی بایت‌های کپی‌شده توسط این متد بازگردانده می‌شود. |

### مقدار بازگشتی

تعداد بایت‌های نوشته‌شده در بافر.

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlValidatingReader](../)
* فضا نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)