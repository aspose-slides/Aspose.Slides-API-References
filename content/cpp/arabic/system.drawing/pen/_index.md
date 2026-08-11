---
title: Pen
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل خصائص مثل اللون والعرض وغيرها للخطوط والمنحنيات التي يتم رسمها. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤ مؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 183
url: /ar/system.drawing/pen/
---
## Pen فئة


يمثل خصائص مثل اللون والعرض وما إلى ذلك للخطوط والمنحنيات التي يتم رسمها. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class Pen : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | يرجع نسخة من الكائن الحالي. |
| void [Dispose](./dispose/)() | يطلق جميع الموارد التشغيلية التي حصل عليها الكائن الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام بنية C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaN مزدوجة متساوية بالرغم من أن IEC 60559:1989 ينص على أن NaN لا تساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaN مزدوجة متساوية بالرغم من أن IEC 60559:1989 ينص على أن NaN لا تساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | يرجع قيمة تشير إلى محاذاة كائن [Pen](./) الحالي. |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | يرجع كائن [Brush](../brush/) لهذه القلم. |
| [Color](../color/) [get_Color](./get_color/)() const | يرجع لون هذا القلم. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | يرجع مصفوفة من القيم التي تحدد قلمًا مركبًا. |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | يرجع قيمة تشير إلى الغطاء المستخدم في طرفي الخط المتقطع. |
| **float** [get_DashOffset](./get_dashoffset/)() const | يرجع المسافة من بداية الخط إلى بداية نمط الشرط. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | يرجع مصفوفة تشير إلى نمط الشرط المخصّص في خط متقطع. |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | يرجع قيمة تشير إلى نمط الشرط لكائن [Pen](./) الحالي. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | يرجع قيمة تشير إلى غطاء نهاية الخط لكائن [Pen](./) الحالي. |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | يرجع قيمة تشير إلى طريقة ربط الخطوط التي يرسمها كائن [Pen](./) هذا. |
| **float** [get_MiterLimit](./get_miterlimit/)() const | يرجع الحد الأقصى لسماكة الوصلة عند زاوية مائلة. |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | غير مُطبق. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | يرجع قيمة تشير إلى غطاء بداية الخط لكائن [Pen](./) الحالي. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | يرجع نسخة من كائن Matrix الذي يحدد التحويلات الهندسية للقلم الممثل بواسطة الكائن الحالي. |
| **float** [get_Width](./get_width/)() const | يرجع عرض كائن [Pen](./) الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصّصة. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | يضرب مصفوفة التحويل الخاصة بالكائن الحالي بالمصفوفة المحددة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Pen](./pen/)(const [Color](../color/)\&) | يبني كائن [Pen](./) جديد يمثل اللون المحدد. |
| [Pen](./pen/)(const [Color](../color/)\&, **float**) | يبني كائن [Pen](./) جديد يمثل اللون والعرض المحددين. |
| [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | يبني كائن [Pen](./) جديد ويهيئه بالكائن [Brush](../brush/) المحدد. |
| [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | يبني كائن [Pen](./) جديد ويهيئه بالكائن [Brush](../brush/) المحدد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| void [ResetTransform](./resettransform/)() | يعيد ضبط مصفوفة التحويل الخاصة بالكائن الحالي لتصبح مصفوفة هوية. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | يقيس التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد. |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | يضبط محاذاة كائن [Pen](./) الحالي. |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | يضبط كائن [Brush](../brush/) لهذا القلم. |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | يضبط لون هذا القلم. |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | يضبط مصفوفة من القيم التي تحدد قلمًا مركبًا. |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | يضبط غطاء نهاية الخط المخصص. |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | يضبط غطاء بداية الخط المخصّص. |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | يضبط قيمة تحدد الغطاء المستخدم في طرفي الخط المتقطع. |
| void [set_DashOffset](./set_dashoffset/)(**float**) | يضبط المسافة من بداية الخط إلى بداية نمط الشرط. |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | يضبط مصفوفة تحدد نمط الشرط المخصّص في خط متقطع. تتكون المصفوفة من أرقام تحدد أطوال الشرطات والمسافات المتناوبة. |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | يضبط قيمة تحدد نمط الشرط لكائن [Pen](./) الحالي. |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | يضبط غطاء نهاية الخط لكائن [Pen](./) الحالي. |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | يضبط قيمة تحدد طريقة ربط الخطوط التي يرسمها كائن [Pen](./) هذا. |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | يضبط الحد الأقصى لسماكة الوصلة عند زاوية مائلة. |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | يضبط غطاء بداية الخط لكائن [Pen](./) الحالي. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | يضبط كائن Matrix الذي يحدد التحويلات الهندسية للقلم الممثل بالكائن الحالي. |
| void [set_Width](./set_width/)(**float**) | يضبط عرض كائن [Pen](./) الحالي. |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | غير مُطبق. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المراجع المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصّصة إلى نص. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [System::Drawing](../)
* مكتبة [Aspose.Slides](../../)