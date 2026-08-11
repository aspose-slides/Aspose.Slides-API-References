---
title: Equals< float, float >()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تخصيص لقيم النقطة العائمة ذات الدقة الواحدة. على الرغم من أن قيمتين عائمة NaN معرفة وفقًا لـ IEC 60559:1989 لتكون دائمًا غير متساوية عند المقارنة، يتطلب العقد لـ System.Object.Equals أن تتوافق المتجاوزات مع متطلبات عامل التكافؤ. لذلك، System.Double.Equals و System.Single.Equals تُعيد True عند مقارنة قيمتين NaN، بينما يُعيد عامل المساواة False في تلك الحالة، كما هو مطلوب في المعيار."
type: docs
weight: 2705
url: /ar/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) دالة

تخصيص لقيم النقطة العائمة ذات الدقة الواحدة. على الرغم من أن قيمتين عائمة NaN معرفة وفقًا لـ IEC 60559:1989 لتكون دائمًا غير متساوية عند المقارنة، يتطلب العقدة لـ [System.Object.Equals](../object/equals/) أن تتوافق المتجاوزات مع متطلبات عامل التكافؤ. لذلك، System.Double.Equals و System.Single.Equals تُعيد True عند مقارنة قيمتين NaN، بينما يُعيد عامل المساواة False في تلك الحالة، كما هو مطلوب في المعيار.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | const **float**\& | المقارنة الأولى |
| b | const **float**\& | المقارنة الثانية |

### قيمة الإرجاع

True إذا كانت القيمتان NaN أو متساويتان، وإلا - false

## انظر أيضًا

* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)