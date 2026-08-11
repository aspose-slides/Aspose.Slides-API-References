---
title: Region
second_title: Aspose.Slides لـ C++ مرجع API
description: "يمثل الجزء الداخلي من شكل رسومي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new ، لأن ذلك سيتسبب في أخطاؤ وقت التشغيل و/أو أخطاء التأكيد. احرص دائماً على تغليف هذه الفئة بمؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 261
url: /ar/system.drawing/region/
---
## Region فئة

يمثل الجزء الداخلي من شكل رسومي. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيتسبب في أخطاؤ وقت التشغيل و/أو أخطاء التأكيد. احرص دائماً على تغليف هذه الفئة بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class Region : public System::Object
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | يعيد نسخة من الكائن الحالي. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بالجزء من المنطقة المحددة بالمستطيل المحدد والذي لا يتقاطع مع هذه المنطقة. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بالجزء من المنطقة المحددة بالمستطيل المحدد والذي لا يتقاطع مع هذه المنطقة. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بالجزء من المنطقة المحددة بالمسار المحدد والذي لا يتقاطع مع هذه المنطقة. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بالجزء من المنطقة المحددة والذي لا يتقاطع مع هذه المنطقة. |
| void [Dispose](./dispose/)() | يطلق جميع موارد نظام التشغيل التي حصل عليها الكائن الحالي. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | يحدد ما إذا كانت المنطقة المحددة مطابقة للمنطقة التي يمثلها الكائن الحالي على سطح الرسم المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة المحددة بالمستطيل منه. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة المحددة بالمستطيل منه. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة المحددة بالمسار منه. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة المحددة منه. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | يحصل على بنية [RectangleF](../rectanglef/) التي تمثل مستطيلًا يحد هذا [Region](./) على سطح رسم كائن [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | يعيد كائن RegionData يحتوي على البيانات التي تعرف المنطقة التي يمثلها الكائن الحالي. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | يعيد مصفوفة من بنى [RectangleF](../rectanglef/) التي تقارب هذا [Region](./) بعد تطبيق تحويل المصفوفة المحدد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة تقاطع هذه المنطقة ومنطقة محددة بالمستطيل. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة تقاطع هذه المنطقة ومنطقة محددة بالمستطيل. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة تقاطع هذه المنطقة ومنطقة محددة بالمسار. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة تقاطع هذه المنطقة والمنطقة المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثالاً للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | يحدد ما إذا كانت المنطقة التي يمثلها الكائن الحالي ذات داخلية فارغة على سطح الرسم المحدد. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | يحدد ما إذا كانت المنطقة التي يمثلها الكائن الحالي ذات داخلية لا نهائية على سطح الرسم المحدد. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | يحدد ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل المنطقة التي يمثلها الكائن الحالي. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | يحدد ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل المنطقة التي يمثلها الكائن الحالي. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | يحدد ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | يحدد ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل لتعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | يُهيّء الكائن الحالي إلى داخلية فارغة. |
| void [MakeInfinite](./makeinfinite/)() | يُهيّء كائن المنطقة هذا إلى داخلية لا نهائية. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يُهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يُهيّء كائنًا جديدًا ويسمح ببناء نسخة فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يُهيّء كائنًا جديدًا ويسمح ببناء نسخة فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجعية كائنًا من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
|  [Region](./region/)() | ينشئ مثالًا جديدًا من فئة [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | ينشئ مثالًا جديدًا من فئة [Region](./) التي تمثل منطقة محددة بالمستطيل المحدد. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | ينشئ مثالًا جديدًا من فئة [Region](./) التي تمثل منطقة محددة بالمستطيل المحدد. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | ينشئ مثالًا جديدًا من فئة [Region](./) التي تمثل منطقة محددة بالمسار المحدد. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | ينشئ مثالًا جديدًا من فئة [Region](./) التي تمثل منطقة محددة بكائن RegionData المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلّل عداد الإشارة المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n ليكون مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | يحوّل هذه المنطقة بالمصفوفة المحددة. |
| void [Transform](./transform/)(const SkMatrix\&) | يحوّل هذه المنطقة بالمصفوفة المحددة. |
| void [Translate](./translate/)(int, int) | ينقل إحداثيات المنطقة بالمقدار المحدد. |
| void [Translate](./translate/)(**float**, **float**) | ينقل إحداثيات المنطقة بالمقدار المحدد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة عملية الاتحاد بين هذه المنطقة ومنطقة محددة بالمستطيل. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة اتحاد هذه المنطقة ومنطقة محددة بالمستطيل. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة اتحاد هذه المنطقة ومنطقة محددة بالمسار. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة اتحاد هذه المنطقة والمنطقة المحددة. |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بأجزاء هذه المنطقة والمنطقة المحددة بالمستطيل التي لا تتقاطع. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بأجزاء هذه المنطقة والمنطقة المحددة بالمستطيل التي لا تتقاطع. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بأجزاء هذه المنطقة والمنطقة المحددة بالمسار التي لا تتقاطع. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | يستبدل المنطقة التي يمثلها الكائن الحالي بأجزاء هذه المنطقة والمنطقة المحددة التي لا تتقاطع. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
| virtual  [~Region](./~region/)() | المدمر. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [System::Drawing](../)
* مكتبة [Aspose.Slides](../../)