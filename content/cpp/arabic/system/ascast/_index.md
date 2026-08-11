---
title: AsCast()
second_title: مرجع API Aspose.Slides للـ C++
description: يحول نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يُستخدم عندما يكون هناك حاجة إلى تحويل بسيط يشبه المُنشئ.
type: docs
weight: 2640
url: /ar/system/ascast/
---
## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم عندما يكون هناك حاجة إلى تحويل بسيط يشبه المُنشئ.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم عندما يكون نوع المصدر والنوع النتيجة نفسهما.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم لتغليف الاستثناءات.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم لتحويل كائن إلى استثناء.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم عندما يكون المصدر والنتيجة كلاهما مؤشرات ذكية.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل. يُرجع nullptr إذا لم يتوفر تحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم عندما يكون المصدر والنتيجة كلاهما مؤشرات ذكية (مع SmartPtr<...> صريح في نوع النتيجة).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل. يُرجع nullptr إذا لم يتوفر تحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم لإلغاء تغليف كائن إلى nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل. يُرجع nullable فارغ إذا لم يتوفر تحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. إلغاء تغليف غير صالح إلى نوع غير كائن.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

دائمًا يُرجع null.

## System::AsCast(const Source\&) دالة

إلغاء تغليف غير صالح إلى نوع غير كائن.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

دائمًا يُرجع null.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم لتغليف كائن nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم لتغليف كائن عادي.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم لتغليف كائن عادي.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم لإلغاء تغليف سلسلة.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم لتعامل مع nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل.

## System::AsCast(const Source\&) دالة

يقوم بتحويل نوع المصدر إلى نوع النتيجة باستخدام تحويل المشغل 'as'. يستخدم للتحويل بين المصفوفات.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### قيمة الإرجاع

نتيجة التحويل. يُرجع nullptr إذا لم يتوفر تحويل لأي عنصر في المصفوفة.

## See Also

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)