---
title: ReadChars()
second_title: Aspose.Slides برای C++ مرجع API
description: متن محتوای یک عنصر را در یک بافر کاراکتری می‌خواند. این متد برای خواندن جریان‌های بزرگ متن جاسازی شده با فراخوانی متوالی طراحی شده است.
type: docs
weight: 755
url: /fa/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) متد

متن محتوای یک عنصر را در یک بافر کاراکتری می‌خواند. این متد برای خواندن جریان‌های بزرگ متن جاسازی شده با فراخوانی متوالی طراحی شده است.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | آرایه‌ای از کاراکترها که به عنوان بافر مورد استفاده قرار می‌گیرد که محتوای متن در آن نوشته می‌شود. |
| index | **int32_t** | موقعیتی درون **buffer** که متد می‌تواند نوشتن محتوای متن را از آنجا آغاز کند. |
| count | **int32_t** | تعداد کاراکترهایی که باید در **buffer** نوشته شوند. |

### مقدار بازگشت

تعداد کاراکترهای خوانده شده. این مقدار می‌تواند 0 باشد اگر خواننده بر روی یک عنصر قرار نگرفته باشد یا اگر محتوای متنی بیشتری برای بازگرداندن در زمینه فعلی موجود نباشد.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlTextReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)