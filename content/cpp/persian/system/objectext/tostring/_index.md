---
title: ToString()
second_title: مرجع API Aspose.Slides برای C++
description: جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.
type: docs
weight: 27
url: /fa/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) شیء برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(const T\&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [Enum](../../enum/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) مقدار برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(const T\&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اشاره‌گر هوشمند. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) مقدار برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(T\&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اشاره‌گر هوشمند یا [ExceptionWrapper](../../exceptionwrapper/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | T\& | اشاره‌گر هوشمند یا [ExceptionWrapper](../../exceptionwrapper/) برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(T\&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اسکالر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | T\& | مقدار اسکالر برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(T\&&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اسکالر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | T\&& | مقدار اسکالر برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(T\&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ساختار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | T\& | مقدار ساختار برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(const T\&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ساختار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | مقدار ساختار برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## ObjectExt::ToString(T\&&) متد

جایگزینی برای متد C# ToString به‌منظور کار بر روی هر نوع C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اسکالر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | T\&& | مقدار اسکالر برای تبدیل به رشته. |

### مقدار بازگشت

[String](../../string/) نمایش **obj**.

## موارد مرتبط

* کلاس [String](../../string/)
* کلاس [ObjectExt](../)
* کلاس [Nullable](../../nullable/)
* ساختار [IsSmartPtr](../../issmartptr/)
* ساختار [IsExceptionWrapper](../../isexceptionwrapper/)
* ساختار [IsNullable](../../isnullable/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)