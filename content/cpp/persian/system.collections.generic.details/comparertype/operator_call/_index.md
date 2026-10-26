---
title: operator()()
second_title: مرجع API Aspose.Slides برای C++
description: انواع مقدار را که رابط IComparable را پیاده‌سازی می‌کنند مقایسه می‌کند.
type: docs
weight: 1
url: /fa/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const متد


انواع مقدار را که رابط [IComparable](../../../system/icomparable/) را پیاده‌سازی می‌کنند مقایسه می‌کند.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع برای مقایسه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const Q\& | مقدار سمت چپ. |
| b | const Q\& | مقدار سمت راست. |

### مقدار بازگشت

True اگر **a** کمتر از **b** در نظر گرفته شود، false در غیر این صورت.

## ComparerType::operator()(const Q\&, const Q\&) const متد


انواع مقدار اولیه و اشیایی که رابط [IComparable](../../../system/icomparable/) را پیاده‌سازی نمی‌کنند مقایسه می‌کند.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع برای مقایسه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const Q\& | مقدار سمت چپ. |
| b | const Q\& | مقدار سمت راست. |

### مقدار بازگشت

True اگر **a** کمتر از **b** در نظر گرفته شود، false در غیر این صورت.

## ComparerType::operator()(const Q\&, const Q\&) const متد


انواع عدد شناور را مقایسه می‌کند.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع برای مقایسه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const Q\& | مقدار سمت چپ. |
| b | const Q\& | مقدار سمت راست. |

### مقدار بازگشت

True اگر **a** کمتر از **b** در نظر گرفته شود، false در غیر این صورت.

## موارد مرتبط

* کلاس [IComparable](../../../system/icomparable/)
* ساختار [has_method_compareto](../../has_method_compareto/)
* ساختار [ComparerType](../)
* فضای نام [System::Collections::Generic::Details](../../)
* کتابخانه [Aspose.Slides](../../../)