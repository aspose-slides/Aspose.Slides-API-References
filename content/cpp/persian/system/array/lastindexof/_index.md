---
title: LastIndexOf()
second_title: Aspose.Slides برای مرجع API C++
description: شاخص آخرین رخداد آیتم مشخص‌شده را در بازه‌ای از آیتم‌های آرایه که توسط شاخص شروع و تعداد عناصر در بازه تعیین می‌شود، تعیین می‌کند.
type: docs
weight: 703
url: /fa/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method

شاخص آخرین رخداد آیتم مشخص‌شده را در بازه‌ای از آیتم‌های آرایه که توسط شاخص شروع و تعداد عناصر در بازه مشخص می‌شود، تعیین می‌کند.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ArrayType | نوع عناصر در آرایه هدف |
| ValueType | نوع آیتمی که در آرایه جستجو می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) برای جستجوی آیتم مشخص‌شده در |
| value | const [ValueType](../valuetype/)\& | شاخص آیتمی که باید تعیین شود |
| startIndex | int | [Index](../../index/) که جستجو در آن آغاز می‌شود |
| count | int | تعداد عناصر بازه‌ای که جستجو در آن انجام می‌شود |

### مقدار بازگشتی

[Index](../../index/) از آخرین رخداد آیتم مشخص‌شده اگر آیتم یافت شود، در غیر این صورت -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method

شاخص آخرین رخداد آیتم مشخص‌شده در آرایه را که از شاخص مشخص‌شده شروع می‌شود، تعیین می‌کند.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ArrayType | نوع عناصر در آرایه هدف |
| ValueType | نوع آیتمی که در آرایه جستجو می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) برای جستجوی آیتم مشخص‌شده در |
| value | const [ValueType](../valuetype/)\& | شاخص آیتمی که باید تعیین شود |
| startIndex | int | [Index](../../index/) که جستجو در آن آغاز می‌شود |

### مقدار بازگشتی

[Index](../../index/) از آخرین رخداد آیتم مشخص‌شده اگر آیتم یافت شود، در غیر این صورت -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method

شاخص آخرین رخداد آیتم مشخص‌شده در آرایه را تعیین می‌کند.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ArrayType | نوع عناصر در آرایه هدف |
| ValueType | نوع آیتمی که در آرایه جستجو می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) برای جستجوی آیتم مشخص‌شده در |
| value | const [ValueType](../valuetype/)\& | شاخص آیتمی که باید تعیین شود |

### مقدار بازگشتی

[Index](../../index/) از آخرین رخداد آیتم مشخص‌شده اگر آیتم یافت شود، در غیر این صورت -1

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)