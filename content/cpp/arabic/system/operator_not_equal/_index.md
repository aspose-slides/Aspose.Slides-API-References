---
title: operator!=()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: 
type: docs
weight: 2055
url: /ar/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) دالة




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) دالة




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) دالة 




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) دالة


يحدد ما إذا كان الكائن [Nullable](../nullable/) المحدد يمثل قيمة لا تساوي null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | std::nullptr_t | إشارة ثابتة إلى كائن [Nullable](../nullable/) لاختبار |

### قيمة الإرجاع

صحيح إذا كان الكائن المحدد يمثل قيمة غير فارغة، خطأ خلاف ذلك

## System::operator!=(const T1\&, const Nullable\<T2\>\&) دالة


يحدد ما إذا كانت القيمة المحددة لا تساوي القيمة التي يمثلها الكائن [Nullable](../nullable/) المحدد من خلال تطبيق [operator!=()](./) على هذه القيم.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة الأولى للمقارنة |
| T2 | النوع الأساسي للكائن [Nullable](../nullable/) الذي يمثل القيمة الثانية للمقارنة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| some | const T1\& | إشارة ثابتة إلى القيمة التي ستُستخدم كأول قيمة للمقارنة |
| other | const [Nullable](../nullable/)\<T2\>\& | إشارة ثابتة إلى الكائن [Nullable](../nullable/) التي تمثّل قيمته المستخدمة كقيمة ثانية للمقارنة |

### قيمة الإرجاع

صحيح إذا كانت القيم غير متساوية، وإلا - خطأ

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) دالة


تقارن عدم المساواة مؤشرين ذكيين.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| X | نوع العنصر المؤشر إليه للمؤشر الأول. |
| Y | نوع العنصر المؤشر إليه للمؤشر الثاني. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | المؤشر الأول للمقارنة. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | المؤشر الثاني للمقارنة. |

### قيمة الإرجاع

خطأ إذا كان المؤشرات متطابقة، صحيح خلاف ذلك.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) دالة


يتحقق مما إذا كان المؤشر الذكي غير فارغ.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| X | نوع العنصر المؤشر إليه للمؤشر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | المؤشر للتحقق منه. |

### قيمة الإرجاع

خطأ إذا كان المؤشر فارغًا، صحيح خلاف ذلك.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) دالة


يتحقق مما إذا كان المؤشر الذكي غير فارغ.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| X | نوع العنصر المؤشر إليه للمؤشر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | std::nullptr_t | المؤشر للتحقق منه. |

### قيمة الإرجاع

خطأ إذا كان المؤشر فارغًا، صحيح خلاف ذلك.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) دالة


مقارنة عدم المساواة بين مؤشر ذكي ومؤشر بسيط (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| X | نوع المؤشر الذكي. |
| Y | نوع المؤشر البسيط. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | المؤشر الذكي للمقارنة (يسار). |
| y | const Y * | المؤشر للمقارنة (يمين). |

### قيمة الإرجاع

خطأ إذا كان المؤشرات متطابقة، صحيح خلاف ذلك.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) دالة


مقارنة المساواة بين مؤشر ذكي ومؤشر بسيط (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| X | نوع المؤشر البسيط. |
| Y | نوع المؤشر الذكي. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const X * | المؤشر للمقارنة (يمين). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | المؤشر الذكي للمقارنة (يسار). |

### قيمة الإرجاع

خطأ إذا كان المؤشرات متطابقة، صحيح خلاف ذلك.

## System::operator!=(Chars\&, const String\&) دالة


[String](../string/) مقارنة.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| Chars | [String](../string/) نوع الحرف الحرفي. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| left | Chars\& | الحرف [String](../string/) للمقارنة. |
| right | const [String](../string/)\& | [String](../string/) للمقارنة. |

### قيمة الإرجاع

خطأ إذا كانت السلاسل متطابقة، صحيح خلاف ذلك.

## System::operator!=(T\&, const String\&) دالة


[String](../string/) مقارنة.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المؤشر [String](../string/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| left | T\& | المؤشر [String](../string/) للمقارنة. |
| right | const [String](../string/)\& | [String](../string/) للمقارنة. |

### قيمة الإرجاع

خطأ إذا كانت السلاسل متطابقة، صحيح خلاف ذلك.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) دالة


[Object](../object/) ومقارنة السلسلة.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) للتحويل إلى سلسلة ومقارنتها. |
| right | const [String](../string/)\& | [String](../string/) للمقارنة. |

### قيمة الإرجاع

خطأ إذا كانت تمثيل الكائن كسلسلة يساوي السلسلة، صحيح خلاف ذلك.

## System::operator!=(std::nullptr_t, const String\&) دالة


يتحقق مما إذا كانت السلسلة فارغة.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) للتحقق. |

### قيمة الإرجاع

خطأ إذا كانت السلسلة فارغة، صحيح خلاف ذلك.

## System::operator!=(std::nullptr_t, TimeSpan) دالة




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) دالة


يحدد ما إذا كانت عناوين URI التي يمثلها الكائن الحالي والكائن المحدد غير متساوية.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | الكائن [Uri](../uri/) الأول للمقارنة |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | الكائن [Uri](../uri/) الثاني للمقارنة |

### قيمة الإرجاع

صحيح إذا كانت عناوين URI غير متساوية، وإلا - خطأ

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)