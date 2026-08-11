---
title: ColorMatrix
second_title: مرجع API Aspose.Slides للغة C++
description: "يمثل مصفوفة 5×5 تحتوي على إحداثيات مساحة اللون RGBAW. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. احفظ هذه الفئة دائمًا داخل مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 27
url: /ar/system.drawing.imaging/colormatrix/
---
## فئة ColorMatrix

يمثل مصفوفة 5×5 تحتوي على إحداثيات مساحة اللون RGBAW. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. احفظ هذه الفئة دائمًا داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class ColorMatrix : public System::Object
```

## الطرق

| طريقة | وصف |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | ينشئ نسخة جديدة من فئة [ColorMatrix](./) ويُهيئها بقيم مصفوفة الهوية. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | ينشئ نسخة جديدة من فئة [ColorMatrix](./) ويُهيئها بالقيم المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقاط العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقاط العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| **float** [get_Matrix00](./get_matrix00/)() const | يعيد قيمة في الصف 0 والعمود 0. |
| **float** [get_Matrix01](./get_matrix01/)() const | يعيد قيمة في الصف 0 والعمود 1. |
| **float** [get_Matrix02](./get_matrix02/)() const | يعيد قيمة في الصف 0 والعمود 2. |
| **float** [get_Matrix03](./get_matrix03/)() const | يعيد قيمة في الصف 0 والعمود 3. |
| **float** [get_Matrix04](./get_matrix04/)() const | يعيد قيمة في الصف 0 والعمود 4. |
| **float** [get_Matrix10](./get_matrix10/)() const | يعيد قيمة في الصف 1 والعمود 0. |
| **float** [get_Matrix11](./get_matrix11/)() const | يعيد قيمة في الصف 1 والعمود 1. |
| **float** [get_Matrix12](./get_matrix12/)() const | يعيد قيمة في الصف 1 والعمود 2. |
| **float** [get_Matrix13](./get_matrix13/)() const | يعيد قيمة في الصف 1 والعمود 3. |
| **float** [get_Matrix14](./get_matrix14/)() const | يعيد قيمة في الصف 1 والعمود 4. |
| **float** [get_Matrix20](./get_matrix20/)() const | يعيد قيمة في الصف 2 والعمود 0. |
| **float** [get_Matrix21](./get_matrix21/)() const | يعيد قيمة في الصف 2 والعمود 1. |
| **float** [get_Matrix22](./get_matrix22/)() const | يعيد قيمة في الصف 2 والعمود 2. |
| **float** [get_Matrix23](./get_matrix23/)() const | يعيد قيمة في الصف 2 والعمود 3. |
| **float** [get_Matrix24](./get_matrix24/)() const | يعيد قيمة في الصف 2 والعمود 4. |
| **float** [get_Matrix30](./get_matrix30/)() const | يعيد قيمة في الصف 3 والعمود 0. |
| **float** [get_Matrix31](./get_matrix31/)() const | يعيد قيمة في الصف 3 والعمود 1. |
| **float** [get_Matrix32](./get_matrix32/)() const | يعيد قيمة في الصف 3 والعمود 2. |
| **float** [get_Matrix33](./get_matrix33/)() const | يعيد قيمة في الصف 3 والعمود 3. |
| **float** [get_Matrix34](./get_matrix34/)() const | يعيد قيمة في الصف 3 والعمود 4. |
| **float** [get_Matrix40](./get_matrix40/)() const | يعيد قيمة في الصف 4 والعمود 0. |
| **float** [get_Matrix41](./get_matrix41/)() const | يعيد قيمة في الصف 4 والعمود 1. |
| **float** [get_Matrix42](./get_matrix42/)() const | يعيد قيمة في الصف 4 والعمود 2. |
| **float** [get_Matrix43](./get_matrix43/)() const | يعيد قيمة في الصف 4 والعمود 3. |
| **float** [get_Matrix44](./get_matrix44/)() const | يعيد قيمة في الصف 4 والعمود 4. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة (hash) الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | يعيد قيمة في الصف والعمود المحددين. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | يحدد القيمة المحددة في الموقع المحدد في المصفوفة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموضح بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل العبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بنية الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بنية الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة مع nullptr بالمرجع. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Matrix00](./set_matrix00/)(**float**) | يحدد قيمة في الصف 0 والعمود 0. |
| void [set_Matrix01](./set_matrix01/)(**float**) | يحدد قيمة في الصف 0 والعمود 1. |
| void [set_Matrix02](./set_matrix02/)(**float**) | يحدد قيمة في الصف 0 والعمود 2. |
| void [set_Matrix03](./set_matrix03/)(**float**) | يحدد قيمة في الصف 0 والعمود 3. |
| void [set_Matrix04](./set_matrix04/)(**float**) | يحدد قيمة في الصف 0 والعمود 4. |
| void [set_Matrix10](./set_matrix10/)(**float**) | يحدد قيمة في الصف 1 والعمود 0. |
| void [set_Matrix11](./set_matrix11/)(**float**) | يحدد قيمة في الصف 1 والعمود 1. |
| void [set_Matrix12](./set_matrix12/)(**float**) | يحدد قيمة في الصف 1 والعمود 2. |
| void [set_Matrix13](./set_matrix13/)(**float**) | يحدد قيمة في الصف 1 والعمود 3. |
| void [set_Matrix14](./set_matrix14/)(**float**) | يحدد قيمة في الصف 1 والعمود 4. |
| void [set_Matrix20](./set_matrix20/)(**float**) | يحدد قيمة في الصف 2 والعمود 0. |
| void [set_Matrix21](./set_matrix21/)(**float**) | يحدد قيمة في الصف 2 والعمود 1. |
| void [set_Matrix22](./set_matrix22/)(**float**) | يحدد قيمة في الصف 2 والعمود 2. |
| void [set_Matrix23](./set_matrix23/)(**float**) | يحدد قيمة في الصف 2 والعمود 3. |
| void [set_Matrix24](./set_matrix24/)(**float**) | يحدد قيمة في الصف 2 والعمود 4. |
| void [set_Matrix30](./set_matrix30/)(**float**) | يحدد قيمة في الصف 3 والعمود 0. |
| void [set_Matrix31](./set_matrix31/)(**float**) | يحدد قيمة في الصف 3 والعمود 1. |
| void [set_Matrix32](./set_matrix32/)(**float**) | يحدد قيمة في الصف 3 والعمود 2. |
| void [set_Matrix33](./set_matrix33/)(**float**) | يحدد قيمة في الصف 3 والعمود 3. |
| void [set_Matrix34](./set_matrix34/)(**float**) | يحدد قيمة في الصف 3 والعمود 4. |
| void [set_Matrix40](./set_matrix40/)(**float**) | يحدد قيمة في الصف 4 والعمود 0. |
| void [set_Matrix41](./set_matrix41/)(**float**) | يحدد قيمة في الصف 4 والعمود 1. |
| void [set_Matrix42](./set_matrix42/)(**float**) | يحدد قيمة في الصف 4 والعمود 2. |
| void [set_Matrix43](./set_matrix43/)(**float**) | يحدد قيمة في الصف 4 والعمود 3. |
| void [set_Matrix44](./set_matrix44/)(**float**) | يحدد قيمة في الصف 4 والعمود 4. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالب الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل العبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [System::Drawing::Imaging](../)
* مكتبة [Aspose.Slides](../../)