---
title: IsDefined()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا مقدار مشخص‌شده عضو نوع enumeration **E** است یا خیر.
type: docs
weight: 27
url: /fa/system/enum/isdefined/
---
## Enum::IsDefined(E) متد


مشخص می‌کند که آیا مقدار مشخص‌شده عضو نوع enumeration **E** است یا خیر.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | E | مقداری که باید بررسی شود |

### مقدار بازگشتی

True اگر **value** عضو enumeration **E** باشد، در غیر این صورت - false

## Enum::IsDefined(T) متد


مشخص می‌کند که آیا مقدار مشخص‌شده عضو نوع enumeration **T** است یا خیر.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T | مقداری که باید بررسی شود |

### مقدار بازگشتی

True اگر **value** عضو enumeration **T** باشد، در غیر این صورت - false

## Enum::IsDefined(const String\&) متد


مشخص می‌کند که آیا مقداری با نام مشخص‌شده در میان اعضای enum **E** وجود دارد یا نه.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../string/)\& | نامی که باید بررسی شود |

### مقدار بازگشتی

True اگر عضوی از enum **E** با نام مشخص‌شده وجود داشته باشد.

## موارد مرتبط

* Typedef [UnderlyingType](../underlyingtype/)
* کلاس [String](../../string/)
* ساختار [Enum](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)