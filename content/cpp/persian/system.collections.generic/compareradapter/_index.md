---
title: ComparerAdapter
second_title: مرجع API Aspose.Slides برای C++
description: آداپتری برای استفاده از IComparer در محیط STL. اگر IComparer تنظیم شده باشد از آن استفاده می‌کند؛ در غیر این صورت از عملگر < (در صورت موجود بودن) استفاده می‌کند یا مقدار false برمی‌گرداند (در صورت عدم موجودی).
type: docs
weight: 638
url: /fa/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

آداپتری برای استفاده از [IComparer](../icomparer/) در محیط STL. اگر [IComparer](../icomparer/) تنظیم شده باشد از آن استفاده می‌کند؛ در غیر این صورت از عملگر < (در صورت موجود بودن) استفاده می‌کند یا مقدار false برمی‌گرداند (در صورت عدم موجودی).

```cpp
template<class T>class ComparerAdapter
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقایسه‌شده. |

## متدها

| متد | توضیح |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | آداپتری را بدون هیچ مقایسه‌گری موجود می‌سازد. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | آداپتری را می‌سازد. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) تابع برای نوع‌هایی که عملگر < موجود است. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) تابع برای نوع‌هایی که عملگر < موجود نیست. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | شیء مقایسه‌گر را تنظیم می‌کند. |

## همچنین ببینید

* فضای نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)