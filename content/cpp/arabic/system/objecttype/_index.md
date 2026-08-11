---
title: ObjectType
second_title: مرجع API لـ Aspose.Slides للغة C++
description: توفر طرقًا ثابتة تنفّذ الحصول على نوع الكائن. هذه فئة ثابتة لا تحتوي على خدمات كائنات. لا يجب عليك أبدًا إنشاء أمثلة منها بأي وسيلة.
type: docs
weight: 1158
url: /ar/system/objecttype/
---
## ObjectType فئة

توفر طرقًا ثابتة تنفّذ ترجمة typeof(). هذه فئة ثابتة لا تحتوي على خدمات كائنات. لا يجب عليك إنشاء مثيلات منها بأي وسيلة.

```cpp
class ObjectType
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ينفّذ ترجمة typeof(). تحميل زائد للمؤشرات الذكية. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ينفّذ ترجمة typeof(). تحميل زائد للهياكل. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ينفّذ ترجمة typeof(). تحميل زائد للاستثناءات. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | ينفّذ ترجمة typeof(). تحميل زائد للأنواع الأولية. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | ينفّذ ترجمة typeof(). تحميل زائد لأنواع [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد للأنواع الأولية. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لأنواع التعداد. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد للهياكل والمؤشرات. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لـ [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لـ MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد للهياكل والمؤشرات. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | ينفّذ ترجمة typeof(). تحميل زائد لنوع string. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لـ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لـ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لـ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لـ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لـ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ينفّذ ترجمة typeof(). تحميل زائد لـ **uint8_t**. |

## انظر أيضًا

* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)