---
title: Equals()
second_title: مرجع API Aspose.Slides برای C++
description: برابری مقدار مشخص‌شده را با استفاده از عملگر==() تعیین می‌کند.
type: docs
weight: 66
url: /fa/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) تابع

برابری مقدار مشخص‌شده را با استفاده از [operator==()](../../system/operator_equal_equal/) تعیین می‌کند.

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| این | نوع مقادیر مقایسه‌شده |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value1 | T | اولین مقایسه‌شونده |
| value2 | T | دومین مقایسه‌شونده |

### مقدار بازگشت

در صورتی که مقدار مشخص‌شده برابر باشد همان‌طور که توسط [operator==()](../../system/operator_equal_equal/) تعیین شده است، True؛ در غیر این صورت - false

## System::BoxedValueDetail::Equals(T, T) تابع

برابری مقدار مشخص‌شده را با استفاده از متد [System::Object::Equals()](../../system/object/equals/) تعیین می‌کند.

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| این | نوع مقادیر مقایسه‌شده |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value1 | T | اولین مقایسه‌شونده |
| value2 | T | دومین مقایسه‌شونده |

### مقدار بازگشت

در صورتی که مقدار مشخص‌شده برابر باشد همان‌طور که توسط متد [Equals()](./) تعیین شده است، True؛ در غیر این صورت - false

## موارد مرتبط

* فضای‌نام [System::BoxedValueDetail](../)
* کتابخانه [Aspose.Slides](../../)