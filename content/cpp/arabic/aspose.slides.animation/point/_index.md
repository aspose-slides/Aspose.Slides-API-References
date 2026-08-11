---
title: Point
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يمثل نقطة الرسوم المتحركة.
type: docs
weight: 495
url: /ar/aspose.slides.animation/point/
---
## فئة Point

يمثل نقطة الرسوم المتحركة.

```cpp
class Point : public Aspose::Slides::Animation::IPoint
```

## الطرق

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة أعداد الفاصلة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا للمعيار IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة أعداد الفاصلة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا للمعيار IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_Formula](./get_formula/)() override | يمكن تكوين الصيغ داخل القيم، والخصائص from و to و by من هذه العناصر: عوامل حسابية معيارية: \\u2018+\\u2019، \\u2018-\\u2018، \\u2018*\\u2019، \\u2018/\\u2019، \\u2018^\\u2019، \\u2018\\u2019 (mod) ثوابت: \\u2018pi\\u2019 \\u2018e\\u2019 عوامل شرطية: \\u2018abs\\u2019، \\u2018min\\u2019، \\u2018max\\u2019، \\u2018?\\u2019 (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: \\u2018sin()\\u2019، \\u2018cos()\\u2019، \\u2018tan()\\u2019، \\u2018asin()\\u2019، \\u2018acos()\\u2019، \\u2018atan()\\u2019 اللوغاريتم الطبيعي \\u2018ln()\\u2019 مراجع الخصائص (الخصائص المدعومة من المضيف) |
| **float** [get_Time](./get_time/)() override | يمثل قيمة الوقت. قراءة **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() override | يمثل قيمة النقطة. القيم المسموح بها: bool، [ColorFormat](../../aspose.slides/colorformat/)، float، int، string. قراءة [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثل للمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
|  [Point](./point/)() | منشئ افتراضي. |
|  [Point](./point/)(**float**, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::String](../../system/string/)) | إنشاء نقطة رسوم متحركة بالوقت والقيمة والصيغة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعًا كائن النوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Formula](./set_formula/)([System::String](../../system/string/)) override | يمكن تكوين الصيغ داخل القيم، والخصائص from و to و by من هذه العناصر: عوامل حسابية معيارية: \\u2018+\\u2019، \\u2018-\\u2018، \\u2018*\\u2019، \\u2018/\\u2019، \\u2018^\\u2019، \\u2018\\u2019 (mod) ثوابت: \\u2018pi\\u2019 \\u2018e\\u2019 عوامل شرطية: \\u2018abs\\u2019، \\u2018min\\u2019، \\u2018max\\u2019، \\u2018?\\u2019 (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: \\u2018sin()\\u2019، \\u2018cos()\\u2019، \\u2018tan()\\u2019، \\u2018asin()\\u2019، \\u2018acos()\\u2019، \\u2018atan()\\u2019 اللوغاريتم الطبيعي \\u2018ln()\\u2019 مراجع الخصائص (الخصائص المدعومة من المضيف) |
| void [set_Time](./set_time/)(**float**) override | يمثل قيمة الوقت. كتابة **float**. |
| void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يمثل قيمة النقطة. القيم المسموح بها: bool، [ColorFormat](../../aspose.slides/colorformat/)، float، int، string. كتابة [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كمرجع ضعيف (**uint32_t**) (بدلاً من مشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضا

* الفئة [IPoint](../ipoint/)
* نطاق الاسم [Aspose::Slides::Animation](../)
* المكتبة [Aspose.Slides](../../)