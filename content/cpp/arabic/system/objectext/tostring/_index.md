---
title: ToString()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: بديل لطريقة C# ToString للعمل على أي نوع C++.
type: docs
weight: 27
url: /ar/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) قيمة حرفية للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | [Nullable](../../nullable/) نوع. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) كائن للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(const T&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | [Enum](../../enum/) نوع. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) قيمة للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(const T&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع المؤشر الذكي. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) قيمة للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(T&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع المؤشر الذكي أو [ExceptionWrapper](../../exceptionwrapper/). |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | T\& | مؤشر ذكي أو [ExceptionWrapper](../../exceptionwrapper/) للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(T&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع قياسي. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | T\& | قيمة قياسية للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(T&&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع قياسي. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | T\&& | قيمة قياسية للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(T&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع بنية. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | T\& | قيمة بنية للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(const T&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع بنية. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | قيمة بنية للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## ObjectExt::ToString(T&&) طريقة

بديل لطريقة C# ToString للعمل على أي نوع C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع قياسي. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | T\&& | قيمة قياسية للتحويل إلى سلسلة. |

### قيمة الإرجاع

[String](../../string/) تمثيل **obj**.

## انظر أيضًا

* الفئة [String](../../string/)
* الفئة [ObjectExt](../)
* الفئة [Nullable](../../nullable/)
* بنية [IsSmartPtr](../../issmartptr/)
* بنية [IsExceptionWrapper](../../isexceptionwrapper/)
* بنية [IsNullable](../../isnullable/)
* مساحة الاسم [System](../../)
* المكتبة [Aspose.Slides](../../../)