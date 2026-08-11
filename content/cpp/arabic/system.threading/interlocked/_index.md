---
title: Interlocked
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يوفر API للعمليات الآمنة عبر الخيوط. هذا نوع ثابت لا يحتوي على خدمات كائنات. لا ينبغي لك أبدًا إنشاء كائنات منه بأي طريقة.
type: docs
weight: 131
url: /ar/system.threading/interlocked/
---
## Interlocked فئة

توفر API للعمليات الآمنة عبر الخيوط. هذا نوع ثابت لا يحتوي على خدمات كائنات. يجب ألا تقوم بإنشاء كائنات منه بأي طريقة.

```cpp
class Interlocked
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | يزيد القيمة بصورة ذرية. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | يزيد القيمة بصورة ذرية. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | يقارن ويستبدل القيمة على المتغيّر: يتحقق مما إذا كان المتغيّر مساويًا لقيمة محددة ويسجل القيمة الجديدة فقط إذا تطابقت القيمة المخزنة مع المتوقعة. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | يقارن ويستبدل القيمة على المتغيّر: يتحقق مما إذا كان المتغيّر مساويًا لقيمة محددة ويسجل القيمة الجديدة فقط إذا تطابقت القيمة المخزنة مع المتوقعة. لم يتم التنفيذ. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | يقارن ويستبدل القيمة على المتغيّر: يتحقق مما إذا كان المتغيّر مساويًا لقيمة محددة ويسجل القيمة الجديدة فقط إذا تطابقت القيمة المخزنة مع المتوقعة. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | يقلل القيمة بصورة ذرية. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | يقلل القيمة بصورة ذرية. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | يبدّل القيمة على المتغيّر: يخزن القيمة الجديدة ويعيد القيمة التي كان المتغيّر يحتويها مباشرةً قبل التخزين. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | يبدّل القيمة على المتغيّر: يخزن القيمة الجديدة ويعيد القيمة التي كان المتغيّر يحتويها مباشرةً قبل التخزين. لم يتم التنفيذ. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | يزيد القيمة بصورة ذرية عبر إجراء exchange-add. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | يزيد القيمة بصورة ذرية عبر إجراء exchange-add. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | يزيد القيمة بصورة ذرية. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | يزيد القيمة بصورة ذرية. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | يعيد قيمة 64-بت، يتم تحميلها كعملية ذرية. |

## انظر أيضًا

* نطاق الاسم [System::Threading](../)
* المكتبة [Aspose.Slides](../../)