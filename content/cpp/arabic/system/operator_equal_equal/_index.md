---
title: operator==()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 2042
url: /ar/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) الدالة




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) الدالة




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) الدالة




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) الدالة


يحدد ما إذا كان الكائن [Nullable](../nullable/) المحدد يمثل قيمة تساوي null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| other | std::nullptr_t | إشارة ثابتة إلى كائن [Nullable](../nullable/) للاختبار |

### قيمة الإرجاع

صحيح إذا كان الكائن المحدد يمثل قيمة null، وإلا خاطئ

## System::operator==(const T1\&, const Nullable\<T2\>\&) الدالة


يحدد ما إذا كانت القيمة المحددة مساوية للقيمة التي يمثلها الكائن [Nullable](../nullable/) المحدد عن طريق تطبيق [operator==()](./) على هاتين القيمتين.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T1 | نوع القيمة الأولى للمقارنة |
| T2 | النوع الأساسي للكائن [Nullable](../nullable/) الذي يمثل القيمة الثانية للمقارنة |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| some | const T1\& | إشارة ثابتة إلى القيمة التي ستُستخدم كالمقارنة الأولى |
| other | const [Nullable](../nullable/)\<T2\>\& | إشارة ثابتة إلى الكائن [Nullable](../nullable/) الذي تمثّل قيمته المقارنة الثانية |

### قيمة الإرجاع

صحيح إذا كانت القيم المتقارَنة متساوية، وإلا خاطئ

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) الدالة


يقارن المتساوية مؤشرين ذكيين.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| X | نوع العنصر المشار إليه للمؤشر الأول. |
| Y | نوع العنصر المشار إليه للمؤشر الثاني. |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | المؤشر الأول للمقارنة. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | المؤشر الثاني للمقارنة. |

### قيمة الإرجاع

صحيح إذا كان المؤشرات متطابقة، وإلا خاطئ.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) الدالة


يفحص ما إذا كان المؤشر الذكي يساوي null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| X | نوع العنصر المشار إليه للمؤشر. |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | std::nullptr_t | المؤشر المراد فحصه. |

### قيمة الإرجاع

صحيح إذا كان المؤشر يساوي null، وإلا خاطئ.

## System::operator==(const SmartPtr\<X\>\&, const Y *) الدالة


مقارنة المساواة بين المؤشر الذكي والمؤشر البسيط (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| X | نوع المؤشر الذكي. |
| Y | نوع المؤشر البسيط. |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | المؤشر الذكي للمقارنة (يسار). |
| y | const Y * | المؤشر للمقارنة (يمين). |

### قيمة الإرجاع

صحيح إذا كان المؤشرات متطابقة، وإلا خاطئ.

## System::operator==(const X *, const SmartPtr\<Y\>\&) الدالة


مقارنة المساواة بين المؤشر البسيط والمؤشر الذكي.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| X | نوع المؤشر البسيط. |
| Y | نوع المؤشر الذكي. |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | const X * | المؤشر للمقارنة (يمين). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | المؤشر الذكي للمقارنة (يسار). |

### قيمة الإرجاع

صحيح إذا كان المؤشرات متطابقة، وإلا خاطئ.

## System::operator==(T const\&, std::nullptr_t) الدالة


يفحص ما إذا كان كائن نوع القيمة (هيكل C# مترجم، إلخ) يساوي null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع القيمة. |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | T const\& | [Object](../object/) للفحص. |

### قيمة الإرجاع

صحيح إذا كان الكائن يساوي null، وإلا خاطئ.

## System::operator==(std::nullptr_t, T const\&) الدالة


يفحص ما إذا كان كائن نوع القيمة (هيكل C# مترجم، إلخ) يساوي null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع القيمة. |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) للفحص. |

### قيمة الإرجاع

صحيح إذا كان الكائن يساوي null، وإلا خاطئ.

## System::operator==(Chars\&, const String\&) الدالة


[String](../string/) مقارنة.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| Chars | نوع النص الحرفي [String](../string/). |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| left | Chars\& | النص الحرفي [String](../string/) للمقارنة. |
| right | const [String](../string/)\& | [String](../string/) للمقارنة. |

### قيمة الإرجاع

true إذا كانت السلاسل متطابقة، false وإلا.

## System::operator==(T\&, const String\&) الدالة


[String](../string/) مقارنة.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع المؤشر [String](../string/). |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| left | T\& | مؤشر [String](../string/) للمقارنة. |
| right | const [String](../string/)\& | [String](../string/) للمقارنة. |

### قيمة الإرجاع

true إذا كانت السلاسل متطابقة، false وإلا.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) الدالة


[Object](../object/) ومقارنة السلسلة.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) للتحويل إلى سلسلة ومقارنتها. |
| right | const [String](../string/)\& | [String](../string/) للمقارنة. |

### قيمة الإرجاع

true إذا كانت تمثيلات الكائن كسلسلة تساوي السلسلة، false وإلا.

## System::operator==(std::nullptr_t, const String\&) الدالة


يفحص ما إذا كانت السلسلة تساوي null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) للفحص. |

### قيمة الإرجاع

true إذا كانت السلسلة تساوي null، false وإلا.

## System::operator==(std::nullptr_t, TimeSpan) الدالة




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) الدالة


يحدد ما إذا كانت عناوين URI التي تمثلها الكائنات الحالية والمحددة متساوية.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | أول كائن [Uri](../uri/) للمقارنة |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | ثاني كائن [Uri](../uri/) للمقارنة |

### قيمة الإرجاع

صحيح إذا كانت عناوين URI متساوية، وإلا خاطئ

## انظر أيضًا

* تعريف نوع [SharedPtr](../sharedptr/)
* فئة [ArraySegment](../arraysegment/)
* فئة [DateTime](../datetime/)
* فئة [DateTimeOffset](../datetimeoffset/)
* فئة [Nullable](../nullable/)
* فئة [SmartPtr](../smartptr/)
* فئة [Object](../object/)
* فئة [String](../string/)
* فئة [TimeSpan](../timespan/)
* فئة [Uri](../uri/)
* بنية [IsNullable](../isnullable/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)