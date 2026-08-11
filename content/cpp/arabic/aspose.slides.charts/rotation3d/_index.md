---
title: Rotation3D
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يمثل دورانًا ثلاثيًا للمخطط.
type: docs
weight: 1327
url: /ar/aspose.slides.charts/rotation3d/
---
## Rotation3D فئة

يمثِّل دورانًا ثلاثي الأبعاد للمخطط.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام semantics [Object.Equals](../../system/object/equals/) الخاصة بلغة C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن IEC 60559:1989 تُعرّف أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن IEC 60559:1989 تُعرّف أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | إرجاع عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و2000 بالمائة). قراءة **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | تحديد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و500 بالمائة). قراءة **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | إرجاع قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و240). يتم تجاهلها إذا كانت قيمة الخاصية RightAngleAxes صحيحة. قراءة **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | تحديد ما إذا كانت محاور المخطط بزاوية قائمة بدلاً من الرسم بوجه منظور. بعبارة أخرى، يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. قراءة **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | إرجاع درجة الدوران حول محور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و90 درجة). الخاصية توافق العنصر rotX (X Rotation) رقم 21.2.2.157 في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. قراءة **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | إرجاع درجة الدوران حول محور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و360 درجة). الخاصية توافق العنصر rotY (Y Rotation) رقم 21.2.2.158 في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. قراءة **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | الحصول على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يُمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | الحصول على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | فحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمعامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | تنفيذ جملة القفل C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يُمكّن نسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | إنشاء كائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنفِّذ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويُمكّن بناء النسخ للصفوف المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويُمكّن بناء النسخ للصفوف المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة النصية وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل النصية. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | تعيين عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و2000 بالمائة). كتابة **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | تحديد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و500 بالمائة). كتابة **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | تعيين قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و240). يتم تجاهلها إذا كانت قيمة الخاصية RightAngleAxes صحيحة. كتابة **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | تحديد ما إذا كانت محاور المخطط بزاوية قائمة بدلاً من الرسم بوجه منظور. بعبارة أخرى، يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. كتابة **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | تعيين درجة الدوران حول محور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و90 درجة). الخاصية توافق العنصر rotX (X Rotation) رقم 21.2.2.157 في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. كتابة **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | تعيين درجة الدوران حول محور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و360 درجة). الخاصية توافق العنصر rotY (Y Rotation) رقم 21.2.2.158 في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. كتابة **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تعيين الوسيط القالب رقم n إلى إشارة ضعيفة (بدلاً من مشاركة). يُتيح تحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | الحصول على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | زيادة عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | تقليل عداد المرجع المشترك وإرجاع قيمته. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يُمكّن تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ جملة إلغاء القفل C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | زيادة عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تقليل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | تدمير الكائن. تحرير جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IRotation3D](../irotation3d/)
* فئة [IDOMObject](../../aspose.slides/idomobject/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)