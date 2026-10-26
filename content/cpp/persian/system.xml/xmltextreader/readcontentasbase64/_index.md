---
title: ReadContentAsBase64()
second_title: Aspose.Slides برای مرجع API C++
description: محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شده Base64 را برمی‌گرداند.
type: docs
weight: 638
url: /fa/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) متد

محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شده **Base64** را برمی‌گرداند.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافری که متن حاصل در آن کپی می‌شود. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | انحراف در بافر که از آن شروع به کپی نتیجه می‌شود. |
| count | **int32_t** | حداکثر تعداد بایت‌هایی که به بافر کپی می‌شوند. تعداد واقعی بایت‌های کپی‌شده توسط این متد برگردانده می‌شود. |

### مقدار بازگشتی

تعداد بایت‌های نوشته‌شده در بافر.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlTextReader](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)