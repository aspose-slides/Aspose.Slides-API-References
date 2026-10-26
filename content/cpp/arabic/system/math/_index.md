---
title: Math
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحتوي على دوال رياضية. هذا نوع ثابت بدون خدمات مثيل. يجب ألا تقوم بإنشاء نماذج منه بأي وسيلة.
type: docs
weight: 1782
url: /ar/system/math/
---
## Math بنية

يحتوي على دوال رياضية. هذا نوع ثابت بدون خدمات مثيل. يجب ألا تقوم بإنشاء نماذج منه بأي وسيلة.

```cpp
class Math
```

## الأساليب

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | يرجع القيمة المطلقة للقيمة المحددة. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | يرجع القيمة المطلقة لقيمة ممثلة بواسطة كائن [Decimal](../decimal/) المحدد. |
| static **double** [Acos](./acos/)(**double**) | يحسب القوس العكسي للقيمة المحددة. |
| static **double** [Asin](./asin/)(**double**) | يحسب القوس الجيبي للقيمة المحددة. |
| static **double** [Atan](./atan/)(**double**) | يحسب الظل المعكوس للقيمة المحددة. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | يحسب الظل العكسي لنسبة القيم المحددة. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | يرجع حاصل الضرب الكامل لعددين صحيحين 32-بت. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | يرجع أصغر قيمة صحيحة أكبر من أو تساوي القيمة المحددة. |
| static **double** [Ceiling](./ceiling/)(**double**) | يرجع أصغر قيمة صحيحة أكبر من أو تساوي القيمة المحددة. |
| static **double** [Cos](./cos/)(**double**) | يحسب جيب التمام للقيمة المحددة. |
| static **double** [Cosh](./cosh/)(**double**) | يحسب جيب التمام الزائدي للقيمة المحددة. |
| static int [DivRem](./divrem/)(int, int, int\&) | يحسب حاصل القسمة لعددين صحيحين 32-بت والباقي. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | يحسب حاصل القسمة لعددين صحيحين 64-بت والباقي. |
| static **double** [Exp](./exp/)(**double**) | يرجع ثابت e مرفوعًا للقوة المحددة. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | يرجع أكبر قيمة صحيحة أصغر من أو تساوي القيمة المحددة. |
| static **double** [Floor](./floor/)(**double**) | يرجع أكبر قيمة صحيحة أصغر من أو تساوي القيمة المحددة. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | يرجع الباقي الناتج عن قسمة عدد محدد على عدد محدد آخر. |
| static **double** [Log](./log/)(**double**) | يرجع اللوغاريتم الطبيعي للقيمة المحددة. |
| static **double** [Log](./log/)(**double**, **double**) | يرجع اللوغاريتم للقيمة المحددة بالأساس المحدد. |
| static **double** [Log10](./log10/)(**double**) | يرجع اللوغاريتم العشري للقيمة المحددة. |
| static auto [Max](./max/)(T0, T1) | يرجع أكبر قيمة من قيمتين عدديتين محددتين. |
| static T0 [Max](./max/)(T0, T1) | يرجع أكبر قيمة من قيمتين عدديتين محددتين. |
| **float** [Max_](./max_/)(**float**, **float**) | يرجع أكبر قيمة ذات دقة مفردة من القيمتين المحددتين. |
| **double** [Max_](./max_/)(**double**, **double**) | يرجع أكبر قيمة ذات دقة مزدوجة من القيمتين المحددتين. |
| static auto [Min](./min/)(T0, T1) | يرجع أصغر قيمة من قيمتين عدديتين محددتين. |
| static T0 [Min](./min/)(T0, T1) | يرجع أصغر قيمة من قيمتين عدديتين محددتين. |
| **float** [Min_](./min_/)(**float**, **float**) | يرجع أصغر قيمة ذات دقة مفردة من القيمتين المحددتين. |
| **double** [Min_](./min_/)(**double**, **double**) | يرجع أصغر قيمة ذات دقة مزدوجة من القيمتين المحددتين. |
| static T [Modulus](./modulus/)(T, T) | يحسب الباقي الناتج عن قسمة قيمة محددة على قيمة أخرى محددة. |
| static **double** [Pow](./pow/)(**double**, **double**) | يرجع القيمة المحددة مرفوعة للقوة المحددة. |
| static **double** [Round](./round/)(**double**) | يقرب القيمة المحددة إلى أقرب قيمة صحيحة. |
| static **double** [Round](./round/)(**double**, int) | يقرب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | يقرب القيمة المحددة إلى أقرب عدد صحيح. معلمة تحدد سلوك الدالة إذا كانت القيمة المحددة متساوية المسافة بين عددين أقرب. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | يقرب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية. معلمة تحدد سلوك الدالة إذا كانت القيمة المحددة متساوية المسافة بين عددين أقرب. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | يقرب القيمة المحددة إلى أقرب قيمة صحيحة. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | يقرب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | يقرب القيمة المحددة إلى أقرب عدد صحيح. معلمة تحدد سلوك الدالة إذا كانت القيمة المحددة متساوية المسافة بين عددين أقرب. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | يقرب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية. معلمة تحدد سلوك الدالة إذا كانت القيمة المحددة متساوية المسافة بين عددين أقرب. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | يحدد إشارة القيمة الصحيحة الموقعة المحددة. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | يحدد إشارة القيمة الفاصلة العائمة المحددة. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | يحدد إشارة القيمة العشرية المحددة. |
| static **double** [Sin](./sin/)(**double**) | يحسب جيب الزاوية للقيمة المحددة. |
| static **double** [Sinh](./sinh/)(**double**) | يحسب جيب الزاوية الزائد للقيمة المحددة. |
| static **double** [Sqrt](./sqrt/)(**double**) | يرجع الجذر التربيعي للقيمة المحددة. |
| static **double** [Tan](./tan/)(**double**) | يحسب الظل للقيمة المحددة. |
| static **double** [Tanh](./tanh/)(**double**) | يحسب الظل الزائد للقيمة المحددة. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | يرجع كائن [Decimal](../decimal/) الذي يمثل قيمة لها الجزء الصحيح مساوي لجزء القيمة الممثلة بواسطة كائن [Decimal](../decimal/) المحدد مع حذف جميع الأرقام العشرية. |
| static **double** [Truncate](./truncate/)(**double**) | يرجع قيمة ذات دقة مزدوجة لها الجزء الصحيح مساوي لجزء القيمة المحددة مع حذف جميع الأرقام العشرية. |

## الحقول

| Field | Description |
| --- | --- |
| static [E](./e/) | قاعدة اللوغاريتم الطبيعي. |
| static [NaN](./nan/) | يمثل قيمة غير عددية (NaN). |
| static [NegativeInfinity](./negativeinfinity/) | يمثل ما لا نهائي سالب. |
| static [PI](./pi/) | ثابت عدد باي. |
| static [PositiveInfinity](./positiveinfinity/) | يمثل ما لا نهائي موجب. |

## ملاحظات

```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // اطبع القيم المطلقة.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // اطبع جيب الزاوية PI/2 وجيب التمام للزاوية PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## انظر أيضًا

* مساحة اسمية [System](../)
* مكتبة [Aspose.Slides](../../)