---
title: IRotation3D
second_title: مرجع API لـ Aspose.Slides للـ C++
description: تمثل دوران ثلاثي الأبعاد لمخطط.
type: docs
weight: 1171
url: /ar/aspose.slides.charts/irotation3d/
---
## فئة IRotation3D

تمثل دوران ثلاثي الأبعاد لمخطط.

```cpp
class IRotation3D : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يعتبر NaN مساويًا رغم أنه وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يعتبر NaN مساويًا رغم أنه وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | إرجاع عمق مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و2000 بالمائة). قراءة **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | تحديد ارتفاع مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و500 بالمائة). قراءة **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | إرجاع قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و100). يتم تجاهلها إذا كانت قيمة الخاصية RightAngleAxes صحيحة. قراءة **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | تحديد ما إذا كانت محاور المخطط مستقيمة بزاوية قائمة، بدلاً من أن تُرسم بمنظور. بعبارة أخرى، يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. قراءة **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | إرجاع درجة الدوران حول المحور X، أي في الاتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و90 درجة). تتطابق الخاصية مع العنصر 21.2.2.157 rotX (دوران X) في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. قراءة **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | إرجاع درجة الدوران حول المحور Y، أي في الاتجاه X للمخططات ثلاثية الأبعاد (بين 0 و360 درجة). تتطابق الخاصية مع العنصر 21.2.2.158 rotY (دوران Y) في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. قراءة **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | الحصول على بنية البيانات لعداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | الحصول على النوع الفعلي للكائن. نسخة مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نسخة مماثلة للمشغل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | تنفيذ عملية القفل في عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | إنشاء كائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | تعيين عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و2000 بالمائة). كتابة **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | تحديد ارتفاع مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و500 بالمائة). كتابة **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | تعيين قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و100). يتم تجاهلها إذا كانت قيمة الخاصية RightAngleAxes صحيحة. كتابة **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | تحديد ما إذا كانت محاور المخطط مستقيمة بزاوية قائمة، بدلاً من أن تُرسم بمنظور. بعبارة أخرى، يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. كتابة **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | تعيين درجة الدوران حول المحور X، أي في الاتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و90 درجة). تتطابق الخاصية مع العنصر 21.2.2.157 rotX (دوران X) في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. كتابة **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | تعيين درجة الدوران حول المحور Y، أي في الاتجاه X للمخططات ثلاثية الأبعاد (بين 0 و360 درجة). تتطابق الخاصية مع العنصر 21.2.2.158 rotY (دوران Y) في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. كتابة **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تحديد الوسيط القالب الـ n كمؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | الحصول على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | زيادة عدّاد المرجع المشترك. يجب عدم استدعائه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | تقليل وإرجاع عدّاد المرجع المشترك. يجب عدم استدعائه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ فك القفل في عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | زيادة عدّاد المرجع الضعيف. يجب عدم استدعائه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تقليل عدّاد المرجع الضعيف. يجب عدم استدعيره مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | تدمير الكائن. تحرير جميع بنى البيانات الداخلية. |
## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)