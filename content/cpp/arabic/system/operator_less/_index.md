---
title: operator<()
second_title: مرجع API Aspose.Slides للغة C++
description: 
type: docs
weight: 2094
url: /ar/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) دالة




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) دالة




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) دالة


دائماً تُعيد false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) دالة


يحدد ما إذا كانت القيمة المحددة أصغر من القيمة التي يمثلها كائن [Nullable](../nullable/) المحدد عن طريق تطبيق [operator<()](./) على هذه القيم.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة المقارنة الأولى |
| T2 | نوع الكائن الأساسي [Nullable](../nullable/) الذي يمثل القيمة المقارنة الثانية |

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| some | const T1\& | مرجع ثابت إلى القيمة التي ستُستخدم كمقارنة أولى |
| other | const [Nullable](../nullable/)\<T2\>\& | مرجع ثابت إلى كائن [Nullable](../nullable/) الذي تمثّل قيمته المقارنة الثانية |

### قيمة الإرجاع

صحيح إذا كان المقارن الأول أصغر من المقارن الثاني، وإلا - false

## System::operator<(std::nullptr_t, TimeSpan) دالة




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## انظر أيضاً

* الصنف [DateTime](../datetime/)
* الصنف [DateTimeOffset](../datetimeoffset/)
* الصنف [Nullable](../nullable/)
* الصنف [TimeSpan](../timespan/)
* البنية [IsNullable](../isnullable/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)