---
title: Matrix
second_title: Aspose.Slides للـ C++ مرجع API
description: "يمثل مصفوفة 3×3 تحدد عمليات التحويل. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() function. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل و/أو أعطال تحقق. احرص دائمًا على تغليف هذه الفئة بمؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 118
url: /ar/system.drawing.drawing2d/matrix/
---
## Matrix فئة

Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Matrix : public System::Object
```

## الطرق

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | ينشئ نسخة من الكائن الحالي. |
| void [Dispose](./dispose/)() | يطلق جميع موارد نظام التشغيل التي حصل عليها الكائن الحالي. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | يفحص ما إذا كان الكائن المحدد هو [Matrix](./) ومطابق لهذا الكائن. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتَبَر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتَبَر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | يرجع مصفوفة تحتوي على عناصر المصفوفة بالترتيب التالي: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | يحدّد ما إذا كانت المصفوفة التي يمثلها الكائن الحالي مصفوفة هوية. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | يحدّد ما إذا كانت المصفوفة التي يمثلها الكائن الحالي قابلة للعكس. |
| **float** [get_OffsetX](./get_offsetx/)() const | يرجع قيمة الإزاحة X للمصفوفة التي يمثلها الكائن الحالي. |
| **float** [get_OffsetY](./get_offsety/)() const | يرجع قيمة الإزاحة Y للمصفوفة التي يمثلها الكائن الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | يعكس المصفوفة التي يمثلها الكائن الحالي. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفيذ عملية القفل في بيان C# lock(). استدعِ مباشرةً أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
|  [Matrix](./matrix/)() | ينشئ مثالًا جديدًا من الفئة [Matrix](./) التي تمثل مصفوفة هوية. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | ينشئ مثالًا جديدًا من الفئة [Matrix](./) ويُهيئه بالقيم المحددة. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | ينشئ مثالًا جديدًا من الفئة [Matrix](./) للتحويل الهندسي المحدد بالمستطيل ومجموعة النقاط المحددة. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | ينشئ مثالًا جديدًا من الفئة [Matrix](./) للتحويل الهندسي المحدد بالمستطيل ومجموعة النقاط المحددة. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | يضرب المصفوفة التي يمثلها الكائن الحالي بالمصفوفة المحددة. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | يضرب المصفوفة التي يمثلها الكائن الحالي بالمصفوفة المحددة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائنًا من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [Reset](./reset/)() | يعيد ضبط المصفوفة التي يمثلها الكائن الحالي لتصبح مصفوفة هوية. |
| void [Rotate](./rotate/)(**float**) | يدير المصفوفة التي يمثلها الكائن الحالي باتجاه عقارب الساعة بالزاوية المحددة. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | يدير المصفوفة التي يمثلها الكائن الحالي باتجاه عقارب الساعة حول الأصل بالزاوية المحددة. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | يدير المصفوفة التي يمثلها الكائن الحالي باتجاه عقارب الساعة حول النقطة المحددة بالزاوية المحددة. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | يدير المصفوفة التي يمثلها الكائن الحالي باتجاه عقارب الساعة حول النقطة المحددة بالزاوية المحددة. |
| void [Scale](./scale/)(**float**, **float**) | يطبق متجه المقياس المحدد على المصفوفة التي يمثلها الكائن الحالي. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | يطبق متجه المقياس المحدد على المصفوفة التي يمثلها الكائن الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي رقم n'th إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتغيير المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [Shear](./shear/)(**float**, **float**) | يطبق متجه القص المحدد على المصفوفة التي يمثلها الكائن الحالي. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | يطبق متجه القص المحدد على المصفوفة التي يمثلها الكائن الحالي. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | يطبق التحويل الهندسي المحدد بالمصفوفة التي يمثلها الكائن الحالي على النقاط المحددة. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | يطبق التحويل الهندسي المحدد بالمصفوفة التي يمثلها الكائن الحالي على النقاط المحددة. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | يطبق التحويل الهندسي المحدد بالمصفوفة التي يمثلها الكائن الحالي على النقاط المحددة. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | يطبق التحويل الهندسي المحدد بالمصفوفة التي يمثلها الكائن الحالي على النقاط المحددة. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | يطبق فقط مكوّنات المقياس والدوران للمصفوفة التي يمثلها الكائن الحالي على النقاط المحددة. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | يطبق فقط مكوّنات المقياس والدوران للمصفوفة التي يمثلها الكائن الحالي على النقاط المحددة. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | يطبق فقط مكوّنات المقياس والدوران للمصفوفة التي يمثلها الكائن الحالي على النقاط المحددة. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | يطبق فقط مكوّنات المقياس والدوران للمصفوفة التي يمثلها الكائن الحالي على النقاط المحددة. |
| void [Translate](./translate/)(**float**, **float**) | يطبق متجه الإزاحة المحدد على المصفوفة التي يمثلها الكائن الحالي. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | يطبق متجه الإزاحة المحدد على المصفوفة التي يمثلها الكائن الحالي. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ فك القفل في بيان C# lock(). استدعِ مباشرةً أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | يضرب كل متجه في المصفوفة بالمصفوفة التي يمثلها الكائن الحالي. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | يضرب كل متجه في المصفوفة بالمصفوفة التي يمثلها الكائن الحالي. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Matrix](./~matrix/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## أنظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الأسماء [System::Drawing::Drawing2D](../)
* مكتبة [Aspose.Slides](../../)