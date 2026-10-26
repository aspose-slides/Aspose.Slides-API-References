---
title: ConvertAll()
second_title: Aspose.Slides برای C++ مرجع API
description: فهرستی از عناصری که به نوع متفاوتی تبدیل شده‌اند ایجاد می‌کند.
type: docs
weight: 352
url: /fa/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) متد

فهرستی از عناصری که به نوع متفاوتی تبدیل شده‌اند ایجاد می‌کند.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| OutputType | نوع عنصر لیست خروجی. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Converter برای تبدیل آیتم‌ها استفاده می‌شود. |

### مقدار بازگشتی

یک فهرست جدید از عناصر تبدیل‌شده ایجاد می‌شود.

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [Converter](../../../system/converter/)
* کلاس [List](../)
* فضای نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)