---
title: MathF
second_title: Aspose.Slides لـ C++ مرجع API
description: يحتوي على دوال رياضية للقيم العائمة بدقة مفردة. هذا نوع ثابت لا يقدم خدمات مثيلات. لا يجب عليك إنشاء مثيلات منه بأي وسيلة.
type: docs
weight: 1795
url: /ar/system/mathf/
---
## MathF struct

يحتوي على دوال رياضية للقيم العائمة بدقة مفردة. هذا نوع ثابت لا يقدم خدمات مثيلات. لا يجب عليك إنشاء مثيلات منه بأي وسيلة.

```cpp
class MathF
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static T [Abs](./abs/)(T) | ترجع القيمة المطلقة للقيمة المحددة. |
| static **float** [Acos](./acos/)(**float**) | تحسب قوس جيب التمام للقيمة المحددة. |
| static **float** [Asin](./asin/)(**float**) | تحسب قوس جيب الزاوية للقيمة المحددة. |
| static **float** [Atan](./atan/)(**float**) | تحسب قوس الظل للقيمة المحددة. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | تحسب قوس الظل لنسبة القيم المحددة. |
| static **float** [Ceiling](./ceiling/)(**float**) | ترجع أصغر قيمة صحيحة تكون أكبر من أو تساوي القيمة المحددة. |
| static **float** [Cos](./cos/)(**float**) | تحسب جيب التمام للقيمة المحددة. |
| static **float** [Cosh](./cosh/)(**float**) | تحسب جيب التمام الزائدي للقيمة المحددة. |
| static **float** [Exp](./exp/)(**float**) | ترجع ثابت e مرفوعًا إلى القوة المحددة. |
| static **float** [Floor](./floor/)(**float**) | ترجع أكبر قيمة صحيحة تكون أصغر من أو تساوي القيمة المحددة. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | ترجع الباقي الناتج عن قسمة عدد محدد على عدد محدد آخر. |
| static **float** [Log](./log/)(**float**) | ترجع اللوغاريتم الطبيعي للقيمة المحددة. |
| static **float** [Log](./log/)(**float**, **float**) | ترجع لوغاريتم القيمة المحددة بالأساس المحدد. |
| static **float** [Log10](./log10/)(**float**) | ترجع لوغاريتم القاعدة 10 للقيمة المحددة. |
| static **float** [Pow](./pow/)(**float**, **float**) | ترجع القيمة المحددة مرفوعة إلى القوة المحددة. |
| static **float** [Round](./round/)(**float**) | تقرب القيمة المحددة إلى أقرب قيمة صحيحة. |
| static **float** [Round](./round/)(**float**, int) | تقرب القيمة المحددة إلى أقرب قيمة بعدد الأرقام العشرية المحدد. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | تقرب القيمة المحددة إلى أقرب عدد صحيح. معلمة تحدد سلوك الدالة إذا كانت القيمة المحددة متساوية القرب إلى أقرب عددين. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | تقرب القيمة المحددة إلى أقرب قيمة بعدد الأرقام العشرية المحدد. معلمة تحدد سلوك الدالة إذا كانت القيمة المحددة متساوية القرب إلى أقرب عددين. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | تقرب القيمة المحددة إلى أقرب قيمة بعدد الأرقام العشرية المحدد. معلمة تحدد سلوك الدالة إذا كانت القيمة المحددة متساوية القرب إلى أقرب عددين. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | تحدد إشارة القيمة الصحيحة الموقعة المحددة. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | تحدد إشارة القيمة العائمة المحددة. |
| static **float** [Sin](./sin/)(**float**) | تحسب جيب الزاوية للقيمة المحددة. |
| static **float** [Sinh](./sinh/)(**float**) | تحسب الجيب الزائدي للقيمة المحددة. |
| static **float** [Sqrt](./sqrt/)(**float**) | ترجع الجذر التربيعي للقيمة المحددة. |
| static **float** [Tan](./tan/)(**float**) | تحسب الظل للقيمة المحددة. |
| static **float** [Tanh](./tanh/)(**float**) | تحسب الظل الزائدي للقيمة المحددة. |
| static **float** [Truncate](./truncate/)(**float**) | ترجع قيمة عائمة ذات دقة فلووت لها الجزء الصحيح مساوي للجزء الصحيح للقيمة المحددة مع حذف جميع الأجزاء العشرية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [E](./e/) | قاعدة اللوغاريتم الطبيعي. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | ثابت عدد باي. |
| static [Tau](./tau/) | قيمة تاو. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)