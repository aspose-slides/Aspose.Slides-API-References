---
title: IndexOf()
second_title: Aspose.Slides برای C++ مرجع API
description: اندیس اولین رخداد مورد مشخص در آرایه را تعیین می‌کند.
type: docs
weight: 131
url: /fa/system/array/indexof/
---
## Array::IndexOf(const T\&) const method

اندیس اولین رخداد مورد مشخص در آرایه را تعیین می‌کند.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | const T\& | اندیس موردی که باید تعیین شود |

### مقدار بازگشت

[Index](../../index/) اولین رخداد مورد مشخص در صورتی که مورد یافت شود، در غیر این صورت -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method

اندیس اولین رخداد مورد مشخص در آرایه را تعیین می‌کند.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ArrayType | نوع عناصری که در آرایه هدف وجود دارند |
| ValueType | نوع موردی که در آرایه جستجو می‌شود |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) برای جستجوی مورد مشخص در |
| value | const [ValueType](../valuetype/)\& | اندیس موردی که باید تعیین شود |

### مقدار بازگشت

[Index](../../index/) اولین رخداد مورد مشخص اگر مورد پیدا شود، در غیر این صورت -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method

اندیس اولین رخداد مورد مشخص در آرایه را از اندیس مشخص شده شروع می‌کند.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ArrayType | نوع عناصری که در آرایه هدف وجود دارند |
| ValueType | نوع موردی که در آرایه جستجو می‌شود |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) برای جستجوی مورد مشخص در |
| value | const [ValueType](../valuetype/)\& | اندیس موردی که باید تعیین شود |
| startIndex | int | [Index](../../index/) که جستجو در آن شروع می‌شود |

### مقدار بازگشت

[Index](../../index/) اولین رخداد مورد مشخص در صورتی که مورد یافت شود، در غیر این صورت -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method

اندیس اولین رخداد مورد مشخص را در بازه‌ای از موارد آرایه که توسط اندیس شروع و تعداد عناصر در بازه مشخص شده‌اند تعیین می‌کند.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ArrayType | نوع عناصری که در آرایه هدف وجود دارند |
| ValueType | نوع موردی که در آرایه جستجو می‌شود |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) برای جستجوی مورد مشخص در |
| value | const [ValueType](../valuetype/)\& | اندیس موردی که باید تعیین شود |
| startIndex | int | [Index](../../index/) که جستجو در آن شروع می‌شود |
| count | int | تعداد عناصر بازه برای جستجو |

### مقدار بازگشت

[Index](../../index/) اولین رخداد مورد مشخص در صورتی که مورد یافت شود، در غیر این صورت -1

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* کلاس [Array](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)