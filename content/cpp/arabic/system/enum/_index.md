---
title: Enum
second_title: Aspose.Slides لمرجع API C++
description: يوفر طرقًا تقوم ببعض العمليات على قيم نوع التعداد. هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب ألا تقوم بإنشاء أي مثيلات له بأي طريقة.
type: docs
weight: 1587
url: /ar/system/enum/
---
## هيكل تعداد


توفر طرقاً تُجري بعض العمليات على قيم نوع تعداد. هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب ألا تنشئ أي مثيلات له بأي وسيلة.

```cpp
template<class E,class Guard>class Enum
```


### معلمات القالب

| معامل | الوصف |
| --- | --- |
| E | نوع التعداد الذي تتعامل الفئة مع قيمه |
| Guard | معامل نوع الخدمة الذي هدفه ضمان أن **E** هو نوع قابل للتعداد |
## طرق

| طريقة | الوصف |
| --- | --- |
| static int [Compare](./compare/)(E, T) | يجري المقارنة الحسابية لقيم الثوابت التعدادية المحددة. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | يعيد اسم الثابت التعدادي الذي له القيمة المحددة. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | يعيد اسم الثابت التعدادي الذي له القيمة المحددة. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | يعيد مصفوفة تحتوي على أسماء جميع أعضاء التعدد **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | يعيد النوع الأساسي للتعداد. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | يعيد مصفوفة تحتوي على جميع أعضاء التعدد **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | يحدد ما إذا كانت البتات المحددة مضبوطة في تمثيل ثنائي للقيمة التعدادية المحددة. |
| static **bool** [IsDefined](./isdefined/)(E) | يحدد ما إذا كانت القيمة المحددة عضوًا في نوع التعدد **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | يحدد ما إذا كانت القيمة المحددة عضوًا في نوع التعدد **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | يحدد ما إذا كانت القيمة بالاسم المحدد موجودة بين أعضاء التعدد **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | يقوم بتحويل السلسلة المحددة إلى ثابت تعدادي مكافئ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | يحاول تحويل السلسلة المحددة إلى ثابت تعدادي مكافئ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | يحاول تحويل السلسلة المحددة إلى ثابت تعدادي مكافئ. |
## تعريفات الأنواع

| تعريف نوع | الوصف |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | اسم مستعار لنوع التعدد الأساسي. |
## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)