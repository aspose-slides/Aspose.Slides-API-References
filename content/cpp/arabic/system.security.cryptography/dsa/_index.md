---
title: DSA
second_title: "مرجع API لـ Aspose.Slides للـ C++"
description: "الفئة الأساسية لتطبيقات خوارزمية DSA. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. دائمًا غلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 131
url: /ar/system.security.cryptography/dsa/
---
## فئة DSA

الفئة الأساسية لتطبيقات خوارزمية [DSA](./). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المُعامل new، حيث سيؤدي ذلك إلى أخطاء في وقت تشغيل و/أو أخطاء تأكيد. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class DSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | يطلق جميع الموارد. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)() | ينشئ تنفيذًا افتراضيًا لخوارزمية [DSA](./). |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(const [String](../../system/string/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية [DSA](./). |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(**int32_t**) | ينشئ تنفيذًا افتراضيًا لخوارزمية [DSA](./) بحجم مفتاح محدد. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(const [DSAParameters](../dsaparameters/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية [DSA](./) بمعلمات محددة. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [CreateFromXmlString](./createfromxmlstring/)(const [String](../../system/string/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية [DSA](./) بمعلمات مُشفرة بصيغة XML. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [CreateSignature](./createsignature/)([ByteArrayPtr](../../system/bytearrayptr/)) | إنشاء توقيع [DSA](./) للبيانات المحددة. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | يطلق الموارد التي يملكها الكائن الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| virtual [DSAParameters](../dsaparameters/) [ExportParameters](./exportparameters/)(**bool**) | يصدر جميع المعلمات. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | يُهيّئ الكائن باستخدام معلمات مُشفرة بصيغة XML. |
| virtual [String](../../system/string/) [get_KeyExchangeAlgorithm](../asymmetricalgorithm/get_keyexchangealgorithm/)() | يحصل على خوارزمية تبادل المفاتيح المستخدمة. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | يحصل على حجم المفتاح. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | يحصل على مصفوفة أحجام المفاتيح المسموح بها. |
| virtual [String](../../system/string/) [get_SignatureAlgorithm](../asymmetricalgorithm/get_signaturealgorithm/)() | يحصل على خوارزمية التوقيع المستخدمة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّ المُراجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [ImportParameters](./importparameters/)([DSAParameters](../dsaparameters/)) | يستورد جميع المعلمات من بنية البيانات. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مُعامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّ المرجع المشترك بالقيمة المحددة. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | يضبط حجم المفتاح. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالبي الـ n مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّ المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّ المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّ المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحسب قيمة التجزئة للمصفوفة البيانات المحددة باستخدام الخوارزمية المحددة، ويوقع النتيجة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحسب قيمة التجزئة للمصفوفة البيانات المحددة باستخدام الخوارزمية المحددة، ويوقع النتيجة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحسب قيمة التجزئة لتدفق البيانات الثنائي المحدد باستخدام الخوارزمية المحددة، ويوقع النتيجة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | يصدر جميع المعلمات بصيغة XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء القفل في بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صحة توقيع البيانات المحددة. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صحة توقيع البيانات المحددة. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صحة توقيع تدفق البيانات الثنائي المحدد. |
| virtual **bool** [VerifySignature](./verifysignature/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) | تحقق من توقيع [DSA](./) للبيانات المحددة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّ المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّ المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضاً

* الفئة [AsymmetricAlgorithm](../asymmetricalgorithm/)
* النطاق [System::Security::Cryptography](../)
* المكتبة [Aspose.Slides](../../)