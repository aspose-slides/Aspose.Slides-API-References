---
title: operator()()
second_title: مرجع API Aspose.Slides برای C++
description: تابع مقایسه برای نوع‌هایی که عملگر < در دسترس است.
type: docs
weight: 27
url: /fa/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const متد

[Comparison](../../../system/comparison/) تابعی برای نوع‌هایی که عملگر < در دسترس است.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع مقایسه‌شده؛ قالب برای در دسترس بودن تبدیل نوع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const Q\& | اولین مقدار برای مقایسه. |
| y | const Q\& | دومین مقدار برای مقایسه. |

### مقدار بازگشت

در صورتی که **x** کمتر از **y** در نظر گرفته شود، True؛ در غیر این صورت false.

## ComparerAdapter::operator()(const Q\&, const Q\&) const متد

[Comparison](../../../system/comparison/) تابعی برای نوع‌هایی که عملگر < در دسترس نیست.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع مقایسه‌شده؛ قالب برای در دسترس بودن تبدیل نوع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const Q\& | اولین مقدار برای مقایسه. |
| y | const Q\& | دومین مقدار برای مقایسه. |

### مقدار بازگشت

در صورتی که مقایسه‌کننده تنظیم شده باشد و **x** کمتر از **y** در نظر گرفته شود، True؛ در غیر این صورت false.

## مراجعه به

* ساختار [ComparerAdapter](../)
* فضای نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)