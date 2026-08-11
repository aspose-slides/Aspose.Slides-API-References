---
title: AreFPNaN()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تفاصيل مساحة الاسم
type: docs
weight: 1
url: /ar/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) دالة

namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | النوع العائم الأول. |
| T2 | النوع العائم الثاني. |

### وسيطات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs | T1 | القيمة العائمة الأولى. |
| rhs | T2 | القيمة العائمة الثانية. |

### قيمة الإرجاع

صحيح إذا كانت كل من **lhs** و **rhs** قيمًا عائمة، خطأ غير ذلك.
## ملاحظات

يتحقق من أن قيمتين عائمتين كلاهما NaN. يتعامل مع الحالة عندما يكون NaN غير إشارة مدعومًا. 
## System::TestPredicates::AreFPNaN(T1, T2) دالة

يتحقق من أن قيمتين عائمتين كلاهما NaN. يتعامل مع الحالة عندما يكون NaN غير إشارة غير مدعوم.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | النوع العائم الأول. |
| T2 | النوع العائم الثاني. |

### وسيطات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs | T1 | القيمة العائمة الأولى. |
| rhs | T2 | القيمة العائمة الثانية. |

### قيمة الإرجاع

دائمًا ما يُعيد خطأ لأن قيمة NaN غير مدعومة.

## انظر أيضاً

* النطاق [System::TestPredicates](../)
* المكتبة [Aspose.Slides](../../)