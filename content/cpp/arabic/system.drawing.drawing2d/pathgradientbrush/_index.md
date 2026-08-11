---
title: PathGradientBrush
second_title: Aspose.Slides للغة C++ - مرجع API
description: "يمثل فرشاة تملأ داخل كائن GraphicsPath بتدرج لوني. يجب تخصيص الكائنات من هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء زمن التنفيذ أو أخطاء التأكيد. غلف دائمًا هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 144
url: /ar/system.drawing.drawing2d/pathgradientbrush/
---
## فئة PathGradientBrush

يمثل فرشاة تملأ داخل كائن [GraphicsPath](../graphicspath/) بتدرج لوني. يجب تخصيص الكائنات من هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء زمن التنفيذ أو أخطاء التأكيد. غلف دائمًا هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينشئ نسخة من الكائن الحالي. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | لا يفعل شيئًا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaN مزدوجة متساوية بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية مزدوجة بأسلوب C# حيث تُعتبر NaN مزدوجة متساوية بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | غير مُنفَّذ. |
| [Color](../../system.drawing/color/) [get_CenterColor](./get_centercolor/)() const | يعيد لونًا يقع في مركز المسار المملوء بواسطة الكائن الحالي. |
| [PointF](../../system.drawing/pointf/) [get_CenterPoint](./get_centerpoint/)() const | يحصل على نقطة المركز للتدرج اللوني. |
| [PointF](../../system.drawing/pointf/) [get_FocusScales](./get_focusscales/)() const | يحصل على نقطة التركيز لانخفاض التدرج اللوني. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | يعيد قيمة تُعرّف تدرجًا خطيًا متعدد الألوان. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | غير مُنفَّذ. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_SurroundColors](./get_surroundcolors/)() const | يعيد الألوان التي تتطابق مع نقاط المسار الذي يملؤه [PathGradientBrush](./). |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | يعيد نسخة من كائن [Matrix](../matrix/) يحدد التحولات الهندسية للفرشاة التي يمثلها الكائن الحالي. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | يعيد وضع الالتفاف. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المراجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصَّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفّذ قفل عبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | يضرب مصفوفة التحويل للكائن الحالي بالمصفوفة المحددة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء حقًا، فقط يتهيئ كائنًا جديدًا ويتيح نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء حقًا، فقط يتهيئ كائنًا جديدًا ويتيح نسخ الفئات الفرعية. |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, [WrapMode](../wrapmode/)) | ينشئ نسخة جديدة من فئة [PathGradientBrush](./). |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, [WrapMode](../wrapmode/)) | ينشئ نسخة جديدة من فئة [PathGradientBrush](./). |
|  [PathGradientBrush](./pathgradientbrush/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&) | ينشئ نسخة جديدة من فئة [PathGradientBrush](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [ResetTransform](./resettransform/)() | يعيد تعيين مصفوفة التحويل للكائن الحالي لتصبح مصفوفة هوية. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../matrixorder/)) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | يغير مقياس التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | يضبط مزيجًا يحدد عوامل ومواقع الألوان الأساسية لهذه الفرشاة. |
| void [set_CenterColor](./set_centercolor/)([Color](../../system.drawing/color/)) | يضبط لونًا يقع في مركز المسار المملوء بواسطة الكائن الحالي. |
| void [set_CenterPoint](./set_centerpoint/)(const [PointF](../../system.drawing/pointf/)\&) | يضبط نقطة مركز التدرج اللوني. |
| void [set_FocusScales](./set_focusscales/)(const [PointF](../../system.drawing/pointf/)\&) | يضبط نقطة التركيز لانخفاض التدرج اللوني. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | يضبط قيمة تُعرّف تدرجًا خطيًا متعدد الألوان. |
| void [set_SurroundColors](./set_surroundcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | يضبط الألوان التي تتطابق مع نقاط المسار الذي يملؤه [PathGradientBrush](./). |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | يضبط كائن [Matrix](../matrix/) يحدد التحولات الهندسية للفرشاة التي يمثلها الكائن الحالي. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | يضبط وضع الالتفاف. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | غير مُنفَّذ. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | غير مُنفَّذ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يُدمّر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضاً

* الفئة [Brush](../../system.drawing/brush/)
* النطاق [System::Drawing::Drawing2D](../)
* المكتبة [Aspose.Slides](../../)