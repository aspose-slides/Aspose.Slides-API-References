---
title: Array()
second_title: مرجع API Aspose.Slides برای C++
description: یک آرایهٔ خالی می‌سازد.
type: docs
weight: 1
url: /fa/system/array/array/
---
## Array::Array() سازنده

یک آرایهٔ خالی می‌سازد.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) سازنده

سازنده پر کردن.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| count | int | اندازهٔ اولیهٔ آرایه |
| init | const T\& | مقدار اولیه‌ای که برای پر کردن آرایه استفاده می‌شود |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) سازنده

سازنده پر کردن.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ValueType | نوع مقدار اولیه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | اندازهٔ اولیهٔ آرایه |
| init | [ValueType](../valuetype/) | مقدار اولیه‌ای که برای پر کردن آرایه استفاده می‌شود |

## Array::Array(int, const T) سازنده

سازنده پر کردن.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| count | int | اندازهٔ اولیهٔ آرایه |
| inits | const T | مقدارهایی که برای پر کردن آرایه استفاده می‌شوند |

## Array::Array(vector_t\&&) سازنده

سازندهٔ جابجایی.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector که عناصری که توسط آرایه به دست می‌آید |

## Array::Array(const vector_t\&) سازنده

سازندهٔ کپی.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector برای کپی مقادیر از آن |

## Array::Array(const std::vector\<Q\>\&) سازنده

یک شیء [Array](../) می‌سازد و آن را با مقادیر کپی شده از یک شیء std::vector که نوع مقادیر آن همان **T** است اما متفاوت از **UnderlyingType** پر می‌کند.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع عناصری که برای کپی کردن از شیء std::vector استفاده می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector برای کپی مقادیر از آن |

## Array::Array(std::vector\<Q\>\&&) سازنده

یک شیء [Array](../) می‌سازد و آن را با مقادیر جابجا شده از یک شیء std::vector که نوع مقادیر آن همان **T** است اما متفاوت از **UnderlyingType** پر می‌کند.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع عناصری که برای جابجایی از شیء std::vector استفاده می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector برای جابجایی مقادیر از آن |

## Array::Array(std::initializer_list\<UnderlyingType\>) سازنده

یک شیء [Array](../) می‌سازد و آن را با مقادیر از لیست اولیهٔ مشخص شده که شامل عناصری از نوع **UnderlyingType** است پر می‌کند.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | لیست اولیهٔ شامل عناصری که برای پر کردن آرایه استفاده می‌شود |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) سازنده

یک شیء [Array](../) می‌سازد و آن را با مقادیر از آرایهٔ مشخص شده که شامل عناصری از نوع **UnderlyingType** است پر می‌کند.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| InitArraySize | تعداد عناصر آرایه **init** |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) برای کپی به آرایه‌ای که در حال ساخت است. |

## Array::Array(std::initializer_list\<bool\>, int) سازنده

یک شیء [Array](../) می‌سازد و آن را با مقادیر از لیست اولیهٔ مشخص شده که شامل عناصری از نوع bool است پر می‌کند.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | لیست اولیهٔ شامل عناصری که برای پر کردن آرایه استفاده می‌شود |

## موارد مرتبط

* تعریف نوع [ValueType](../valuetype/)
* تعریف نوع [UnderlyingType](../underlyingtype/)
* کلاس [Array](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)