---
title: operator-()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحسب عدد الأيام بين يومين من أيام الأسبوع.
type: docs
weight: 2172
url: /ar/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) function

يحسب عدد الأيام بين يومين من أيام الأسبوع.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | The minuend |
| b | [DayOfWeek](../dayofweek/) | The subtrahend |

### قيمة الإرجاع

عدد الأيام بين يومي الأسبوع **a** و **b**؛ تكون قيمة الإرجاع عددًا سالبًا إذا *يأتي* بعد ****

## System::operator-(const T\&, const Decimal\&) function

يرجع نسخة جديدة من الفئة [Decimal](../decimal/) التي تمثّل قيمة هي نتيجة عملية الطرح للقيمة التي يمثلها كائن [Decimal](../decimal/) المحدد من القيمة المحددة.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const T\& | القيمة التي تُطرح منها |
| d | const [Decimal](../decimal/)\& | كائن [Decimal](../decimal/) الذي يمثل القيمة المخصومة |

### قيمة الإرجاع

نسخة جديدة من الفئة [Decimal](../decimal/) التي تمثّل قيمة هي نتيجة عملية الطرح للقيمة التي يمثلها **d** من **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) function

يفصل جميع ردود النداء في التفويض الأيمن من نهاية قائمة ردود النداء في التفويض الأيسر.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | التفويض الذي ستُزيل منه ردود النداء. |
| rhv | MulticastDelegate\<T\> | التفويض الذي ستُزيل منه ردود النداء. |

### قيمة الإرجاع

يرجع تفويضًا يحتوي على ردود النداء للقيمة اليسرى، دون ردود النداء الخاصة بالقيمة اليمنى.

## System::operator-(const T1\&, const Nullable\<T2\>\&) function

يطرح القيم غير القابلة للمتغير والقيم القابلة للمتغير.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع المعامل الأيسر. |
| T2 | نوع المعامل الأيمن. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| some | const T1\& | المعامل الأيسر. |
| other | const [Nullable](../nullable/)\<T2\>\& | المعامل الأيمن. |

### قيمة الإرجاع

نتيجة الطرح.

## انظر أيضًا

* Enum [DayOfWeek](../dayofweek/)
* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)