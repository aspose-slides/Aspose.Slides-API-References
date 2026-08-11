---
title: operator>=()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 2133
url: /ar/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) دالة




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) دالة




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) دالة


دائمًا تُعيد false.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) دالة


يحدد ما إذا كانت القيمة المحددة أكبر أو مساوية للقيمة التي يمثلها الكائن [Nullable](../nullable/) المحدد عن طريق تطبيق [operator>=()](./) على هذه القيم.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة المقارنة الأولى |
| T2 | النوع الأساسي لكائن [Nullable](../nullable/) الذي يمثل القيمة المقارنة الثانية |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| some | const T1\& | إشارة ثابتة إلى القيمة التي ستُستخدم كالقيمة المقارنة الأولى |
| other | const [Nullable](../nullable/)\<T2\>\& | إشارة ثابتة إلى كائن [Nullable](../nullable/) الذي تمثل قيمته تُستخدم كالقيمة المقارنة الثانية |

### قيمة الإرجاع

True إذا كانت القيمة المقارنة الأولى أكبر أو مساوية للقيمة المقارنة الثانية، وإلا - false

## System::operator>=(std::nullptr_t, TimeSpan) دالة




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## انظر أيضًا

* فئة [DateTime](../datetime/)
* فئة [DateTimeOffset](../datetimeoffset/)
* فئة [Nullable](../nullable/)
* فئة [TimeSpan](../timespan/)
* بنية [IsNullable](../isnullable/)
* نطاق الاسم [System](../)
* مكتبة [Aspose.Slides](../../)