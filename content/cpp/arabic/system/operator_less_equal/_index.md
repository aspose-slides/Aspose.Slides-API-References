---
title: operator<=()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 2107
url: /ar/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) دالة




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) دالة




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) دالة


دائمًا ما تُرجع false.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) دالة


يحدد ما إذا كانت القيمة المحددة أصغر أو مساوية للقيمة التي يمثلها كائن [Nullable](../nullable/) المحدد عن طريق تطبيق [operator<=()](./) على هذه القيم.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة الأولى للمقارنة |
| T2 | النوع الأساسي لكائن [Nullable](../nullable/) الذي يمثل القيمة المقارنة الثانية |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| some | const T1\& | إشارة ثابتة إلى القيمة التي ستُستخدم كقيمة المقارنة الأولى |
| other | const [Nullable](../nullable/)\<T2\>\& | إشارة ثابتة إلى كائن [Nullable](../nullable/) الذي تم تمثيل قيمته لاستخدامها كقيمة المقارنة الثانية |

### قيمة الإرجاع

صحيح إذا كانت قيمة المقارنة الأولى أصغر أو مساوية لقيمة المقارنة الثانية، وإلا - false

## System::operator<=(std::nullptr_t, TimeSpan) دالة




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## انظر أيضًا

* الفئة [DateTime](../datetime/)
* الفئة [DateTimeOffset](../datetimeoffset/)
* الفئة [Nullable](../nullable/)
* الفئة [TimeSpan](../timespan/)
* البنية [IsNullable](../isnullable/)
* المجال [System](../)
* المكتبة [Aspose.Slides](../../)