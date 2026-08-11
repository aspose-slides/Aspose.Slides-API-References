---
title: GetType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينفذ ترجمة typeof(). تحميل زائد للمؤشرات الذكية.
type: docs
weight: 1
url: /ar/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) طريقة

يطبق ترجمة typeof(). تحميل زائد للمؤشرات الذكية.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Pointer object type. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) للحصول على [TypeInfo](../../typeinfo/) لـ. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف الفئة النهائية للكائن الممرَّر.

## ObjectType::GetType(const T\&) طريقة

يطبق ترجمة typeof(). تحميل زائد للهيكليات.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Structure type. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) للحصول على [TypeInfo](../../typeinfo/) لـ. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف الفئة النهائية للكائن الممرَّر.

## ObjectType::GetType(const T\&) طريقة

يطبق ترجمة typeof(). تحميل زائد للاستثناءات.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Exception type. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) للحصول على [TypeInfo](../../typeinfo/) لـ. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف الفئة النهائية للكائن الممرَّر.

## ObjectType::GetType(const T) طريقة

يطبق ترجمة typeof(). تحميل زائد للأنواع البدائية.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Primitive type. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T | IGNORED |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف نوع الكائن الممرَّر.

## ObjectType::GetType(const T) طريقة

يطبق ترجمة typeof(). تحميل زائد لأنواع [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T | IGNORED |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف نوع الكائن الممرَّر.

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للأنواع البدائية.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Primitive type. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف النوع المحدد.

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد لأنواع التعداد.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Primitive type. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف النوع المحدد.

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للهيكليات والمؤشرات.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Primitive type. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف الهيكل المحدد.

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد لـ[Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف الهيكل المحدد.

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للـMutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | MutlicastDelegate type. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف الهيكل المحدد.

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للهيكليات والمؤشرات.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Primitive type. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف الهيكل المحدد أو نوع المؤشر إذا تم استدعاؤه لـ [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) طريقة

يطبق ترجمة typeof(). تحميل زائد لنوع السلسلة.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | Primitive type. |

### قيمة الإرجاع

إشارة ثابتة إلى بنية [TypeInfo](../../typeinfo/) التي تصف نوع [String](../../string/).

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للـ **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للـ char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للـ **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للـ **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد للـ bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() طريقة

يطبق ترجمة typeof(). تحميل زائد لـ [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## أنظر أيضًا

* الفئة [ObjectType](../)
* الفئة [TypeInfo](../../typeinfo/)
* الفئة [String](../../string/)
* البنية [IsSmartPtr](../../issmartptr/)
* البنية [IsExceptionWrapper](../../isexceptionwrapper/)
* البنية [IsNullable](../../isnullable/)
* البنية [IsBoxable](../../isboxable/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)