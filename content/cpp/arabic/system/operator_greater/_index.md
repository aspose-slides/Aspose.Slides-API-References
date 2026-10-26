---
title: operator>()
second_title: Aspose.Slides لـ C++ مرجع API
description: 
type: docs
weight: 2120
url: /ar/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) دالة




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) دالة




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) دالة


دائمًا يُرجع false.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) دالة


يحدد ما إذا كانت القيمة المحددة أكبر من القيمة التي يمثلها كائن [Nullable](../nullable/) المحدد عن طريق تطبيق [operator>()](./) على هاتين القيمتين.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة المقارنة الأولى |
| T2 | النوع الأساسي لكائن [Nullable](../nullable/) الذي يمثل القيمة المقارنة الثانية |

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| some | const T1\& | إشارة ثابتة إلى القيمة التي ستُستَخدم كمقارنة أولى |
| other | const [Nullable](../nullable/)\<T2\>\& | إشارة ثابتة إلى كائن [Nullable](../nullable/) الذي تمثّل قيمته المقارنة الثانية |

### قيمة الإرجاع

True إذا كانت المقارنة الأولى أكبر من المقارنة الثانية، وإلا - false

## System::operator>(std::nullptr_t, TimeSpan) دالة




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## انظر أيضًا

* فئة [DateTime](../datetime/)
* فئة [DateTimeOffset](../datetimeoffset/)
* فئة [Nullable](../nullable/)
* فئة [TimeSpan](../timespan/)
* بنية [IsNullable](../isnullable/)
* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)