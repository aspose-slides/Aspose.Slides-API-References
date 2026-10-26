---
title: CopyTo()
second_title: مرجع API Aspose.Slides برای C++
description: عناصر لیست را به عناصر موجود آرایه کپی می‌کند.
type: docs
weight: 209
url: /fa/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) متد

عناصر لیست را به عناصر موجود آرایه کپی می‌کند.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | آرایه مقصد. |
| arrayIndex | int | شاخص شروع آرایه مقصد. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) متد

تمام عناصر را به عناصر موجود آرایه کپی می‌کند.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) برای کپی کردن عناصر به. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) متد

عناصر را که از شاخص مشخص شده شروع می‌شوند به عناصر موجود آرایه کپی می‌کند.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | یک شاخص صفر پایه از عنصر در لیست که توسط شیء فعلی نمایانگر است برای شروع کپی. |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) برای کپی کردن عناصر به. |
| arrayIndex | int | موقعیت شروع در آرایه مقصد. |
| count | int | تعداد عناصری که باید کپی شوند. |

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [List](../)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)