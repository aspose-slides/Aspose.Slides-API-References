---
title: Box()
second_title: Aspose.Slides برای C++ مرجع API
description: انواع مقدار را برای تبدیل به Object جعبه می‌کند. پیاده‌سازی برای انواع شمارشی.
type: docs
weight: 40
url: /fa/system/objectext/box/
---
## ObjectExt::Box(const T\&) متد


مقدارهای نوع را برای تبدیل به [Object](../../object/) جعبه می‌کند. پیاده‌سازی برای انواع شمارشی.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع [Enum](../../enum/). |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | مقدار [Enum](../../enum/) برای جعبه شدن. |

### مقدار بازگشت

اشاره‌گر هوشمند به شیء حاوی مقدار جعبه‌شده.

## ObjectExt::Box(const T\&) متد


مقدارهای نوع را برای تبدیل به [Object](../../object/) جعبه می‌کند. پیاده‌سازی برای انواع غیر شمارشی.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع مقدار. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | مقدار برای جعبه شدن. |

### مقدار بازگشت

اشاره‌گر هوشمند به شیء حاوی مقدار جعبه‌شده.

## ObjectExt::Box(const T\&) متد


مقدارهای [Nullable](../../nullable/) را برای تبدیل به [Object](../../object/) جعبه می‌کند.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع مقدار. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | مقدار برای جعبه شدن. |

### مقدار بازگشت

اشاره‌گر هوشمند به شیء حاوی مقدار جعبه‌شده.

## ObjectExt::Box(const String\&) متد


مقدارهای رشته‌ای را جعبه می‌کند.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | مقدار برای جعبه شدن. |

### مقدار بازگشت

مقدار جعبه‌شده یا null، اگر رشته منبع null باشد.

## موارد مرتبط

* کلاس [SmartPtr](../../smartptr/)
* کلاس [Object](../../object/)
* کلاس [ObjectExt](../)
* کلاس [String](../../string/)
* Struct [IsNullable](../../isnullable/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)