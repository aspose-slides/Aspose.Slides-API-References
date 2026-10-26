---
title: GetType()
second_title: Aspose.Slides برای C++ مرجع API
description: پیاده‌سازی ترجمه typeof(). بارگذاری برای اشاره‌گرهای هوشمند.
type: docs
weight: 1
url: /fa/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای اشاره‌گرهای هوشمند.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌گر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) برای دریافت [TypeInfo](../../typeinfo/). |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که کلاس نهایی شیء عبور داده شده را توصیف می‌کند.

## ObjectType::GetType(const T\&) متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای ساختارها.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ساختار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) برای دریافت [TypeInfo](../../typeinfo/). |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که کلاس نهایی شیء عبور داده شده را توصیف می‌کند.

## ObjectType::GetType(const T\&) متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای استثناها.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع استثنا. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) برای دریافت [TypeInfo](../../typeinfo/). |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که کلاس نهایی شیء عبور داده شده را توصیف می‌کند.

## ObjectType::GetType(const T) متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای انواع اولیه.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اولیه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T | نادیده گرفته شده |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که نوع شیء عبور داده شده را توصیف می‌کند.

## ObjectType::GetType(const T) متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای انواع [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Nullable](../../nullable/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T | نادیده گرفته شده |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که نوع شیء عبور داده شده را توصیف می‌کند.

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای انواع اولیه.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اولیه. |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که نوع مشخص‌شده را توصیف می‌کند.

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای انواع شمارشی.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اولیه. |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که نوع مشخص‌شده را توصیف می‌کند.

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای ساختارها و اشاره‌گرها.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اولیه. |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که ساختار مشخص‌شده را توصیف می‌کند.

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Nullable](../../nullable/). |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که ساختار مشخص‌شده را توصیف می‌کند.

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع MutlicastDelegate. |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که ساختار مشخص‌شده را توصیف می‌کند.

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای ساختارها و اشاره‌گرها.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اولیه. |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که ساختار مشخص‌شده یا نوع اشاره‌گر هدف را در صورت درخواست [SmartPtr](../../smartptr/) توصیف می‌کند.

## ObjectType::GetType(const String\&) متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای نوع رشته.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اولیه. |

### مقدار بازگشت

مرجع ثابت به ساختار [TypeInfo](../../typeinfo/) که نوع [String](../../string/) را توصیف می‌کند.

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() متد


پیاده‌سازی ترجمه typeof(). بارگذاری برای [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## موارد مرتبط

* کلاس [ObjectType](../)
* کلاس [TypeInfo](../../typeinfo/)
* کلاس [String](../../string/)
* ساختار [IsSmartPtr](../../issmartptr/)
* ساختار [IsExceptionWrapper](../../isexceptionwrapper/)
* ساختار [IsNullable](../../isnullable/)
* ساختار [IsBoxable](../../isboxable/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)