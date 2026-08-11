---
title: ExplicitCast()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم عندما يكون نوع المصدر ونوع النتيجة متطابقين.
type: docs
weight: 2627
url: /ar/system/explicitcast/
---
## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم عندما يكون نوع المصدر ونوع النتيجة متطابقين.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم عندما يكون تحويل بسيط يشبه المُنشئ مطلوبًا.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لأغلفة الاستثناء.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لتحويل الكائن إلى استثناء.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم عندما يكون المصدر والنتيجة كلاهما مؤشرات ذكية (دون SmartPtr<...> صريح في نوع النتيجة).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(Source) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم عند تحويل المؤشر الخام إلى مؤشر ذكي.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | Source | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم عندما يكون المصدر والنتيجة كلاهما مؤشرات ذكية (مع SmartPtr<...> صريح في نوع النتيجة).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لإلغاء تغليف الكائن إلى نوع قابل للإلغاء.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لتغليف قيمة قابلة للإلغاء.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لإلغاء تغليف كائن قابل للإلغاء.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لتغليف تعداد.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لنسخ الأنواع القيمة إلى الكُومة عندما يجب الإشارة إلى نوع القيمة كمؤشر ذكي (في الأنماط العامة المقيدة بنوع الواجهة ولكن المتخصصة بهيكل يطبق هذه الواجهة).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم للحصول على الواجهات من الأنواع القيمة.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لتغليف شائع.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لتغليف [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لإلغاء تغليف الواجهات.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لإلغاء تغليف شائع.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لتحويل nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## System::ExplicitCast(const Source\&) function

يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يُستخدم لتحويل بين المصفوفات.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template parameters

| معلم | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### Arguments

| معلم | النوع | الوصف |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) للتحويل. |

### Return Value

نتيجة التحويل.

## See Also

* تعريف نوع [Exception](../exception/)
* فئة [SmartPtr](../smartptr/)
* فئة [BoxedValueBase](../boxedvaluebase/)
* هيكل [CastResult](../castresult/)
* مساحة اسم [System](../)
* مكتبة [Aspose.Slides](../../)