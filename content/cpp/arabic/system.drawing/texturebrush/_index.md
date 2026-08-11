---
title: TextureBrush
second_title: Aspose.Slides للغة C++ مرجع API
description: "يمثل فرشاة تستخدم صورة لملء داخل الشكل. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أعطال التحقق. احرص دائماً على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 352
url: /ar/system.drawing/texturebrush/
---
## TextureBrush فئة

يمثل فرشاة تستخدم صورة لملء داخل الشكل. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أعطال التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class TextureBrush : public System::Drawing::Brush
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | إنشاء نسخة من الكائن الحالي. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | لا يفعل شيئًا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد الفاصلة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد الفاصلة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [get_Image](./get_image/)() | إرجاع صورة يستخدمها الكائن [TextureBrush](./) الحالي. |
| [System::SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | إرجاع نسخة من كائن Matrix يحدد التحولات الهندسية للفرشاة التي يمثلها الكائن الحالي. |
| [Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/) [get_WrapMode](./get_wrapmode/)() | إرجاع قيمة تحدد كيف يتم تجانس الفرشاة التي يمثلها الكائن الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | الحصول على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | الحصول على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | التحقق مما إذا كان الكائن يمثل نسخة من النوع الموضّح بواسطة targetType. تمثيل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفيذ تأمين بيان C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | يضرب مصفوفة التحويل الخاصة بالكائن الحالي بالمصفوفة المحددة. |
|  [Object](../../system/object/object/)() | إنشاء كائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [ResetTransform](./resettransform/)() | إعادة تعيين مصفوفة التحويل للكائن الحالي لتصبح مصفوفة هوية. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | يضبط التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد. |
| void [set_Transform](./set_transform/)(const [System::SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | يضبط كائن Matrix يحدد التحولات الهندسية للفرشاة التي يمثلها الكائن الحالي. |
| void [set_WrapMode](./set_wrapmode/)([Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/)) | يضبط قيمة تحدد كيف يتم تجانس الفرشاة التي يمثلها الكائن الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تعيين الوسيط القالبي n'th إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | الحصول على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | زيادة عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | تقليل وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/)) | إنشاء نسخة جديدة من فئة [TextureBrush](./) التي تستخدم الصورة المحددة. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [RectangleF](../rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | إنشاء نسخة جديدة من فئة [TextureBrush](./) التي تستخدم الصورة المحددة. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | إنشاء نسخة جديدة من فئة [TextureBrush](./) التي تستخدم الصورة المحددة. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [RectangleF](../rectanglef/)) | إنشاء نسخة جديدة من فئة [TextureBrush](./) التي تستخدم الصورة المحددة. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [Rectangle](../rectangle/)) | إنشاء نسخة جديدة من فئة [TextureBrush](./) التي تستخدم الصورة المحددة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ إلغاء قفل بيان C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | زيادة عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تقليل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | تدمير الكائن. تحرير جميع هياكل البيانات الداخلية. |
| virtual  [~TextureBrush](./~texturebrush/)() | المدمر. |

## انظر أيضًا

* فئة [Brush](../brush/)
* نطاق [System::Drawing](../)
* مكتبة [Aspose.Slides](../../)