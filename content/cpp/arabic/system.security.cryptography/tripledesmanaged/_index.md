---
title: TripleDESManaged
second_title: "مرجع API لـ Aspose.Slides للغة C++"
description: "تنفيذ TripleDES المدار. يدعم فقط أوضاع ECB و CFB مع حشو None ووضع CBC مع حشو None و Zeros و PKCS7. يجب تخصيص كائنات هذا الصف فقط باستخدام الدالة System::MakeObject(). لا تُنشئ أبداً نسخة من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. دائماً غلف هذا الصف في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 690
url: /ar/system.security.cryptography/tripledesmanaged/
---
## TripleDESManaged صف

تنفيذ [TripleDES](../tripledes/) المدار. يدعم فقط أوضاع ECB و CFB مع حشوة None ووضع CBC مع الحشوات None و Zeros و PKCS7. يجب تخصيص كائنات هذه الصف فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائماً غلف هذه الصف في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class TripleDESManaged : public System::Security::Cryptography::TripleDES
```

## الطرق

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | ينشئ مثالًا للخوارزمية. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | ينشئ كائن فك التشفير مع معلمات صريحة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | ينشئ كائن فك التشفير مع معلمات محددة بواسطة كائن الخوارزمية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ينشئ كائن فك التشفير مع معلمات محددة بواسطة كائن الخوارزمية. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | ينشئ كائن تشفير مع معلمات صريحة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | ينشئ كائن تشفير مع معلمات محددة بواسطة كائن الخوارزمية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ينشئ كائن تشفير مع معلمات محددة بواسطة كائن الخوارزمية. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلد مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلد مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [GenerateIV](./generateiv/)() override | ينشئ قيمة أولية عشوائية ويخزنها داخل الخوارزمية. |
| void [GenerateKey](./generatekey/)() override | ينشئ مفتاحًا عشوائيًا ويخزنها داخل الخوارزمية. |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | يحصل على حجم الكتلة لعملية التشفير. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | يحصل على حجم التغذية الراجعة لعملية التشفير. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | يحصل على القيمة الأولية لعملية التشفير. ينشئ قيمة جديدة إذا لم تُنشأ بعد. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | يحصل على المفتاح لعملية التشفير. ينشئ مفتاحًا جديدًا إذا لم يُنشأ بعد. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | يحصل على حجم المفتاح لعملية التشفير. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | يحصل على وضعية عملية التشفير. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | يحصل على الحشو لعملية التشفير. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق القفل في عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع البنى الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح ببناء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح ببناء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشترك بالقيمة المحددة. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | يضبط حجم الكتلة لعملية التشفير. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | يضبط حجم التغذية الراجعة لعملية التشفير. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يضبط القيمة الأولية لعملية التشفير. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يضبط المفتاح لعملية التشفير. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | يضبط حجم المفتاح لعملية التشفير. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | يضبط وضعية عملية التشفير. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | يضبط الحشو لعملية التشفير. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُرجع عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء القفل في عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | يفحص ما إذا كان حجم المفتاح صالحًا. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع البنى الداخلية. |

## أنظر أيضًا

* صف [TripleDES](../tripledes/)
* مساحة اسم [System::Security::Cryptography](../)
* مكتبة [Aspose.Slides](../../)