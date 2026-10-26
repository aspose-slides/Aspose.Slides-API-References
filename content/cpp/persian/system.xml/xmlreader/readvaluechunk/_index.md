---
title: ReadValueChunk()
second_title: مرجع API Aspose.Slides برای C++
description: متن‌های بزرگ جاسازی‌شده در یک سند XML را می‌خواند.
type: docs
weight: 807
url: /fa/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) متد

متن‌های بزرگ جاسازی‌شده در یک سند XML را می‌خواند.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | آرایه‌ای از کاراکترها که به عنوان بافر برای نوشتن محتوای متن استفاده می‌شود. این مقدار نمی‌تواند **nullptr** باشد. |
| index | **int32_t** | محل‌جای‌گیری داخل بافر که [XmlReader](../) می‌تواند شروع به کپی کردن نتایج کند. |
| count | **int32_t** | حداکثر تعداد کاراکترهایی که باید به بافر کپی شوند. تعداد واقعی کاراکترهای کپی‌شده توسط این متد بازگردانده می‌شود. |

### مقدار بازگشتی

تعداد کاراکترهای خوانده‌شده به بافر. وقتی محتوای متنی دیگری باقی نمی‌ماند مقدار صفر بازگردانده می‌شود.

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)