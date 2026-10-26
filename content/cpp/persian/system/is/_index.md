---
title: Is()
second_title: مرجع API Aspose.Slides برای C++
description: پیاده‌سازی ترجمه الگوی اعلان 'is'.
type: docs
weight: 2302
url: /fa/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) تابع


پیاده‌سازی ترجمه الگوی اعلان 'is'.


```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| PatternT | نوعی که باید بررسی شود. |
| ExpressionT | نوع عبارت سمت چپ. |
| ResultT | نوع عبارت نتیجه. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | عبارتی که بررسی خواهد شد. |
| result | ResultT\& | متغیری که نوع بررسی‌شده به آن اختصاص می‌یابد. |

### Return Value

true اگر بررسی نوع موفق باشد، false در غیر این صورت.

## System::Is(const ExpressionT\&, const ConstantT\&) تابع


پیاده‌سازی ترجمه الگوی ثابت 'is'.


```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ExpressionT | نوع عبارت سمت چپ. |
| ConstantT | نوع عبارت ثابت. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | عبارتی که بررسی خواهد شد. |
| constant | const ConstantT\& | عبارتی که با عبارت سمت چپ مقایسه خواهد شد. |

### Return Value

true اگر بررسی نوع موفق باشد، false در غیر این صورت.

## System::Is(const E\&, const A\&) تابع


تابع مقایسه سطح بالا. یک الگو را روی مقدار اعمال می‌کند.


```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| A | نوع الگو (باید از Details::Pattern ارث‌بری کند). |
| E | نوع مقدار برای مقایسه. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| e | const E\& | مقداری که برای مقایسه استفاده می‌شود. |
| a | const A\& | الگو برای اعمال. |

### Return Value

true اگر الگو با مقدار مطابقت داشته باشد، false در غیر این صورت.

## See Also

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)