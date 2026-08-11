---
title: LinearGradientBrush
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "يمثل فرساة تدرج لوني خطي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو أعطال التأكيد. احرص دائماً على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 105
url: /ar/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush فئة


يمثل فرساة تدرج لوني خطي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التنفيذ و/أو أخطاء التأكيد. احرص دائماً على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينشئ نسخة من الكائن الحالي. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | لا يفعل شيئًا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNان متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNان متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | يعيد مزيجًا يحدد عوامل ومواقع الألوان الأساسية لهذه الفرشاة. |
| **bool** [get_GammaCorrection](./get_gammacorrection/)() const | يعيد قيمة تشير إلى أن تصحيح غاما مُمكن لهذه الفرشاة. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | يعيد كائن [ColorBlend](../colorblend/) يحدد تدرجًا خطيًا متعدد الألوان. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_LinearColors](./get_linearcolors/)() const | يعيد الألوان الابتدائية والنهائية لهذا التدرج. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | يعيد مستطيل الحد. |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | يعيد نسخة من كائن [Matrix](../matrix/) يحدد التحويلات الهندسية للفرشاة الممثّلة بالكائن الحالي. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | يعيد وضع الالتفاف. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل للنداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثل للمشغل C# 'is'. |
|  [LinearGradientBrush](./lineargradientbrush/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | يبني مثيلًا جديدًا من [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | يبني مثيلًا جديدًا من [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | يبني مثيلًا جديدًا من [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | يبني مثيلًا جديدًا من [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | يبني مثيلًا جديدًا من [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | يبني مثيلًا جديدًا من [LinearGradientBrush](./). |
| void [Lock](../../system/object/lock/)() | ينفّذ قفلًا على طريقة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصّصة. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | يضرب مصفوفة تحويل الكائن الحالي بالمصفوفة المحددة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشيء النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [ResetTransform](./resettransform/)() | يعيد تعيين مصفوفة التحويل للكائن الحالي. |
| void [RotateTransform](./rotatetransform/)(**float**, [MatrixOrder](../matrixorder/)) | يدور مصفوفة تحويل الكائن الحالي. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | يغير مقياس مصفوفة تحويل الكائن الحالي. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | يضبط مزيجًا يحدد عوامل ومواقع الألوان الأساسية لهذه الفرشاة. |
| void [set_GammaCorrection](./set_gammacorrection/)(**bool**) | يضبط حالة تصحيح غاما لهذه الفرشاة. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | يضبط كائن [ColorBlend](../colorblend/) يحدد تدرجًا خطيًا متعدد الألوان. |
| void [set_LinearColors](./set_linearcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | يضبط الألوان الابتدائية والنهائية لهذا التدرج. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | يضبط كائن [Matrix](../matrix/) يحدد التحويلات الهندسية للفرشاة الممثّلة بالكائن الحالي. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | يضبط وضع اللف. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | غير مُنفّذ. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | غير مُنفّذ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يحدد الوسيط القالبي n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدّاد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصّصة إلى سلسلة. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | يترجم مصفوفة تحويل الكائن الحالي. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Brush](../../system.drawing/brush/)
* نطاق [System::Drawing::Drawing2D](../)
* مكتبة [Aspose.Slides](../../)