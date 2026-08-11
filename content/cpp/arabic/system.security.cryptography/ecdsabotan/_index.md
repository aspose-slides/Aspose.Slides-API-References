---
title: ECDsaBotan
second_title: Aspose.Slides لـ C++ مرجع API
description: "خوارزمية ECDsa بصيغة Botan. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيتسبب في أخطاء تشغيل و/أو أعطال تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 196
url: /ar/system.security.cryptography/ecdsabotan/
---
## فئة ECDsaBotan

[ECDsa](../ecdsa/) خوارزمية بصيغة Botan. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المُشغل new، لأن ذلك سيسبب أخطاء تشغيل أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## الطرق

| طريقة | وصف |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | يطلق جميع الموارد. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)() | ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECCurve](../eccurve/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA مع مفتاح تم إنشاؤه حديثًا على المنحنى المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECParameters](../ecparameters/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA باستخدام المعلمات المحددة. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [String](../../system/string/)\&) | ينشئ تنفيذًا محددًا لخوارزمية ECDSA. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | يطلق الموارد التي يملكها الكائن الحالي. |
| [ECDsaBotan](./ecdsabotan/)() | منشئ. يستخدم المعلمات الافتراضية. |
| [ECDsaBotan](./ecdsabotan/)(const [ECParameters](../ecparameters/)\&) | منشئ. |
| [ECDsaBotan](./ecdsabotan/)(const [ECCurve](../eccurve/)\&) | منشئ. |
| [ECDsaBotan](./ecdsabotan/)(**int32_t**) | منشئ. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | منشئ. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | منشئ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لمعيار IEC 60559:1989 لا تكون قيمة NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لمعيار IEC 60559:1989 لا تكون قيمة NaN مساوية لأي قيمة، بما في ذلك NaN. |
| [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) override | يصدر المعلمات الصريحة. |
| [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) override | يصدر المعلمات المسماة أو الصريحة. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | يُهيئ الكائن باستخدام معلمات مشفرة XML. غير مطبق. |
| void [FromXmlString](./fromxmlstring/)(const [String](../../system/string/)\&, [ECKeyXmlFormat](../eckeyxmlformat/)) | يُهيئ الكائن باستخدام معلمات مشفرة XML. غير مطبق. |
| void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) override | ينشئ زوجًا جديدًا من المفاتيح العامة/الخاصة للمنحنى المحدد. |
| [HashAlgorithmName](../hashalgorithmname/) [get_HashAlgorithm](./get_hashalgorithm/)() const | يعيد خوارزمية التجزئة. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](../ecdsa/get_keyexchangealgorithm/)() override | يعيد خوارزمية تبادل المفاتيح المستخدمة. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | يعيد حجم المفتاح. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | يعيد مصفوفة أحجام المفاتيح المسموح بها. |
| [String](../../system/string/) [get_SignatureAlgorithm](../ecdsa/get_signaturealgorithm/)() override | يعيد خوارزمية التوقيع المستخدمة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يعيد بنية عدّاد المراجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يعيد النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([ByteArrayPtr](../../system/bytearrayptr/), **int32_t**, **int32_t**, [HashAlgorithmName](../hashalgorithmname/)) override | يحسب قيمة التجزئة للمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([StreamPtr](../../system/streamptr/), [HashAlgorithmName](../hashalgorithmname/)) override | يحسب قيمة التجزئة لتدفق البيانات الثنائي المحدد باستخدام خوارزمية التجزئة المحددة. |
| void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) override | يستورد جميع المعلمات من بنية البيانات. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم الكائن [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_HashAlgorithm](./set_hashalgorithm/)(const [HashAlgorithmName](../hashalgorithmname/)\&) | يضبط خوارزمية التجزئة. |
| void [set_KeySize](./set_keysize/)(**int32_t**) override | يضبط حجم المفتاح. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كمؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يعيد القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يحسب قيمة التجزئة للمصفوفة البيانات المحددة، ويوقع النتيجة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | يحسب قيمة التجزئة للمصفوفة البيانات المحددة، ويوقع النتيجة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&) | يحسب قيمة التجزئة لتدفق البيانات الثنائي المحدد، ويوقع النتيجة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحسب قيمة التجزئة للمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحسب قيمة التجزئة للمصفوة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحسب قيمة التجزئة لتدفق البيانات الثنائي المحدد باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | يحسب توقيع القيمة المدخلة المحددة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | يصدر جميع المعلمات بصيغة XML. غير مطبق. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)([ECKeyXmlFormat](../eckeyxmlformat/)) | يصدر جميع المعلمات بصيغة XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم الكائن [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يتحقق من صحة توقيع البيانات المحددة. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يتحقق من صحة توقيع البيانات المحددة. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يتحقق من صحة توقيع تدفق البيانات الثنائي المحدد. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صحة توقيع البيانات المحددة. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صحة توقيع البيانات المحددة. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صحة توقيع تدفق البيانات الثنائي المحدد. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | يتحقق من توقيع البيانات. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## أنظر أيضًا

* فئة [ECDsa](../ecdsa/)
* نطاق [System::Security::Cryptography](../)
* مكتبة [Aspose.Slides](../../)