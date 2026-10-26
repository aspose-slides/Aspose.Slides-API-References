---
title: GraphicsPath
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل مجموعة من الخطوط والمنحنيات المتصلة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو عطل في التأكيد. احرص دائمًا على تضمين هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 66
url: /ar/system.drawing.drawing2d/graphicspath/
---
## فئة GraphicsPath

يمثل مجموعة من الخطوط والمنحنيات المتصلة. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيسبّب ذلك أخطاءً في وقت التشغيل أو عَطلًا في التأكيد. احرص دائمًا على تضمين هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريرها إلى الدوال كوسيطة.

```cpp
class GraphicsPath : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | يضيف القوس الإهليلجي المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | يضيف القوس الإهليلجي المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | يضيف القوس الإهليلجي المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | يضيف القوس الإهليلجي المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | يضيف منحنى بيزيه مكعب المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | يضيف منحنى بيزيه مكعب المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | يضيف منحنى بيزيه مكعب المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | يضيف منحنى بيزيه مكعب المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | يضيف سلسلة من منحنيات بيزيه المكعبة المتصلة إلى الشكل الحالي. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | يضيف سلسلة من منحنيات بيزيه المكعبة المتصلة إلى الشكل الحالي. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | يضيف المنحنى المغلق المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | يضيف المنحنى المغلق المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | يضيف المنحنى المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | يضيف المنحنى المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | يضيف المنحنى المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | يضيف المنحنى المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | يضيف الإهليلج المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | يضيف الإهليلج المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | يضيف الإهليلج المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | يضيف الإهليلج المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | يضيف الخط المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | يضيف الخط المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddLine](./addline/)(int, int, int, int) | يضيف الخط المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | يضيف الخط المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | يضيف سلسلة من القطع الخطية المتصلة إلى المسار الذي تمثله الكائن الحالي. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | يضيف سلسلة من القطع الخطية المتصلة إلى المسار الذي تمثله الكائن الحالي. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | يضيف المسار المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | يضيف المخطط الخارجي لشكل الفطيرة المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | يضيف المخطط الخارجي لشكل الفطيرة المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | يضيف المخطط الخارجي لشكل الفطيرة المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | يضيف المضلع المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | يضيف المضلع المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | يضيف المستطيل المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | يضيف المستطيل المحدد إلى المسار الذي تمثله الكائن الحالي. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | يضيف سلسلة من المستطيلات إلى المسار الذي تمثله الكائن الحالي. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | يضيف سلسلة من المستطيلات إلى المسار الذي تمثله الكائن الحالي. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | يضيف سلسلة نصية إلى المسار الذي تمثله الكائن الحالي. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | يضيف سلسلة نصية إلى المسار الذي تمثله الكائن الحالي. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | يضيف سلسلة نصية إلى المسار الذي تمثله الكائن الحالي. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | يضيف سلسلة نصية إلى المسار الذي تمثله الكائن الحالي. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | ينشئ نسخة من الكائن الحالي. |
| void [CloseAllFigures](./closeallfigures/)() | يغلق جميع الأشكال المفتوحة ويبدأ واحدة جديدة. |
| void [CloseFigure](./closefigure/)() | يغلق الشكل الحالي ويبدأ واحدًا جديدًا. |
| void [Dispose](./dispose/)() | يطلق جميع موارد نظام التشغيل التي اكتسبها الكائن الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سمات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية بنمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 يوضح أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية بنمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 يوضح أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [Flatten](./flatten/)() | يسطح كل منحنى في المسار عن طريق تحويله إلى سلسلة من الخطوط المتصلة. يتم استخدام قيمة التسطيح 0.25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | يسطح كل منحنى في المسار عن طريق تحويله إلى سلسلة من الخطوط المتصلة. يتم استخدام قيمة التسطيح 0.25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | يسطح كل منحنى في المسار عن طريق تحويله إلى سلسلة من الخطوط المتصلة. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | إرجاع وضع التعبئة للكائن الحالي. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | إرجاع كائن [PathData](../pathdata/) يحتوي على النقاط التي تشكل مسارًا تمثله الكائن الحالي وأنواعها. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | إرجاع مصفوفة تحتوي على النقاط التي تشكل مسارًا تمثله الكائن الحالي. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | إرجاع مصفوفة تحتوي على القيم التي تشير إلى أنواع النقاط التي تشكل مسارًا تمثله الكائن الحالي. |
| int [get_PointCount](./get_pointcount/)() const | إرجاع عدد النقاط في المسار الذي تمثله الكائن الحالي. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | إرجاع كائن [RectangleF](../../system.drawing/rectanglef/) يمثل مستطيلًا يحد المسار الذي تمثله الكائن الحالي عندما يتم تحويله بالمصفوفة المحددة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المراجع المرتبطة بالكائن. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | إرجاع قيمة هي مجموعة تركيبة بتية من قيم Detail::FigureType التي تشير إلى أنواع الأشكال المحتواة داخل المسار الذي تمثله الكائن الحالي. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | إرجاع كائن [PointF](../../system.drawing/pointf/) يمثل آخر نقطة في المسار. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | ينشئ نسخة جديدة من الفئة [GraphicsPath](./) مع وضع التعبئة المحدد. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | ينشئ نسخة جديدة من الكائن [GraphicsPath](./) الذي يمثل المسار المحدد. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | ينشئ نسخة جديدة من الكائن [GraphicsPath](./) الذي يمثل المسار المحدد. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](./) عند رسمه بالـ [Pen](../../system.drawing/pen/) المحدد. غير مُنفَّذ. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | يحدد ما إذا كانت النقطة المحددة موجودة داخل المسار الذي تمثله الكائن الحالي. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | يحدد ما إذا كانت النقطة المحددة موجودة داخل المسار الذي تمثله الكائن الحالي. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل كما في C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع البنى الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع قيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [Reset](./reset/)() | يفرغ المسار بحذف جميع النقاط منه. |
| void [Reverse](./reverse/)() | يعكس ترتيب النقاط في مصفوفة PathPoints لهذا [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | يعيّن وضع التعبئة للكائن الحالي. |
| void [SetMarkers](./setmarkers/)() | غير مُنفَّذ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الحجة القالبية n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [StartFigure](./startfigure/)() | يبدأ شكلًا جديدًا. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة نصية. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | يحوّل المسار الذي تمثله الكائن الحالي بتطبيق مصفوفة التحويل المحددة عليه. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ عملية إلغاء القفل كما في C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | يستبدل هذا المسار بمخططٍ حول المسار الأصلي. |
|  [~GraphicsPath](./~graphicspath/)() | المُدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع البنى الداخلية. |

## انظر أيضًا

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)