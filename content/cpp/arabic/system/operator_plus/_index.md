---
title: operator+()
second_title: دليل API لـ Aspose.Slides للغة C++
description: يعيد مثيلاً جديداً من الصنف Decimal الذي يمثل قيمة هي مجموع القيمة المحددة والقيمة التي يمثلها الكائن Decimal المحدد.
type: docs
weight: 2185
url: /ar/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) دالة


يعيد مثيلاً جديداً من الصنف [Decimal](../decimal/) الذي يمثل قيمة هي مجموع القيمة المحددة والقيمة التي يمثلها الكائن [Decimal](../decimal/) المحدد.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


### الوسيطات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const T\& | المجمع الأول |
| d | const [Decimal](../decimal/)\& | المرجع الثابت إلى كائن [Decimal](../decimal/) الذي يمثل المجمع الثاني |

### قيمة الإرجاع

مثيل جديد من الصنف [Decimal](../decimal/) الذي يمثل قيمة هي مجموع **x** والقيمة التي يمثلها **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) دالة


يربط جميع ردود النداء من المفوض اليميني إلى نهاية قائمة ردود النداء للمفوض اليساري.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### الوسيطات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | المفوض الذي تُضاف إليه ردود النداء. |
| rhv | MulticastDelegate\<T\> | المفوض الذي تُضاف منه ردود النداء. |

### قيمة الإرجاع

يعيد مفوضاً يحتوي على ردود النداء للقيمة اليسارية ثم ردود النداء للقيمة اليمنية.

## System::operator+(const T1\&, const Nullable\<T2\>\&) دالة


يجمع القيم غير القابلة للإلغاء والقابلة للإلغاء.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع العامل الأيسر. |
| T2 | نوع العامل الأيمن. |

### الوسيطات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| some | const T1\& | العامل الأيسر. |
| other | const [Nullable](../nullable/)\<T2\>\& | العامل الأيمن. |

### قيمة الإرجاع

نتيجة الجمع.

## System::operator+(T\&, const String\&) دالة


[String](../string/) دمج.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الحرفية [String](../string/). |

### الوسيطات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| left | T\& | الحرفية المراد دمجها مع السلسلة. |
| right | const [String](../string/)\& | [String](../string/) المراد دمجه. |

### قيمة الإرجاع

السلسلة المدمجة.

## System::operator+(T\&, const String\&) دالة


[String](../string/) دمج.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المؤشر [String](../string/). |

### الوسيطات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| left | T\& | مؤشر [String](../string/) المراد دمجه مع السلسلة. |
| right | const [String](../string/)\& | [String](../string/) المراد دمجه. |

### قيمة الإرجاع

السلسلة المدمجة.

## System::operator+(const char_t, const String\&) دالة


[String](../string/) دمج.

```cpp
String System::operator+(const char_t left, const String &right)
```


### الوسيطات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| left | const char_t | الحرف المراد دمجه مع السلسلة. |
| right | const [String](../string/)\& | [String](../string/) المراد دمجه. |

### قيمة الإرجاع

السلسلة المدمجة.

## انظر أيضًا

* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Class [String](../string/)
* Struct [IsStringLiteral](../isstringliteral/)
* Struct [IsStringPointer](../isstringpointer/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)