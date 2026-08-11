---
title: RSACryptoServiceProvider
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: "خوارزمية RSA في شكل CSP. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة System::MakeObject(). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 469
url: /ar/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider فئة

[RSA](../rsa/) خوارزمية في شكل CSP. الكائنات من هذه الفئة يجب أن تُخصص فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | يحرر جميع الموارد. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)() | ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../rsa/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [String](../../system/string/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../rsa/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(**int32_t**) | ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../rsa/) بحجم مفتاح محدد. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [RSAParameters](../rsaparameters/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../rsa/) بمعلمات محددة. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [CreateFromXmlString](../rsa/createfromxmlstring/)(const [String](../../system/string/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../rsa/) بمعلمات مشفرّة بـ XML. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | يفك تشفير الرسالة. غير مطبق. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | يفك تشفير البيانات المدخلة باستخدام وضع الحشو المحدد. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](../rsa/decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | يفك تشفير القيمة باستخدام المفتاح الخاص. |
| void [Dispose](./dispose/)() override | يفرغ البيانات المرتبطة بالكائن. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | يشفر الرسالة. غير مطبق. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | يشفر البيانات المدخلة باستخدام وضع الحشو المحدد. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](../rsa/encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | يشفر القيمة باستخدام المفتاح الخاص. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على طريقة C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على طريقة C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلد مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaNانين متساويتين رغم أن وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلد مقارنة النقطة العائمة ذات الدقة المزدوجة على نمط C# حيث تُعتبر NaNانين متساويتين رغم أن وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | يصدر كتلة بيانات تحتوي على معلومات المفتاح. غير مطبق. |
| [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | يصدر معلمات CSP. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [FromXmlString](../rsa/fromxmlstring/)([String](../../system/string/)) override | يفعل الكائن باستخدام معلمات مشفرة بـ XML. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | يحصل على كائن [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | يتحقق من خوارزمية تبادل المفاتيح المرتبطة بالكائن. |
| **int32_t** [get_KeySize](./get_keysize/)() override | يحصل على حجم المفتاح المُستخدم بواسطة الخوارزمية. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | يحصل على مصفوفة من أحجام المفاتيح المسموح بها. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | يتحقق مما إذا كان المفتاح محفوظًا في كائن CSP. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | يتحقق ما إذا كان المفتاح العام فقط موجودًا في كائن CSP. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | يحصل على خوارزمية التوقيع المرتبطة بكائن CSP. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | يتحقق مما إذا كان المفتاح محفوظًا في مخزن الجهاز بدلًا من مخزن المستخدم. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على نوع الكائن الفعلي. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | يستورد كتلة بيانات تحتوي على معلومات المفتاح. غير مطبق. |
| void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) override | يستورد معلمات CSP. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير المشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يُنشئ الكائن. يُهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | منشئ. يستخدم المعلمات الافتراضية. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | منشئ. غير مطبق. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [RSAParameters](../rsaparameters/)\&) | منشئ. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**) | منشئ. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | منشئ. غير مطبق. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | يضبط حجم المفتاح. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | يحدد ما إذا كان المفتاح محفوظًا في كائن CSP. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | يحدد ما إذا كان المفتاح محفوظًا في مخزن الجهاز بدلًا من مخزن المستخدم. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يحسّب توقيع القيمة المدخلة المحددة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يحسّب توقيع القيمة المدخلة المحددة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يحسّب توقيع القيمة المدخلة المحددة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | يحسّب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة والحشو، ثم يوقع النتيجة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | يحسّب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة والحشو، ثم يوقع النتيجة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | يحسّب قيمة التجزئة لتدفق البيانات الثنائي المحدد باستخدام خوارزمية التجزئة المحددة والحشو، ثم يوقع النتيجة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | يحسّب التوقيع للقيمة التجزيئية المحددة. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | يحسّب توقيع القيمة المدخلة المحددة. غير مطبق. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| [String](../../system/string/) [ToXmlString](../rsa/toxmlstring/)(**bool**) override | يصدر جميع المعلمات بصيغة XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يتحقق من توقيع البيانات. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | يتحقق من صحة توقيع البيانات المحددة. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | يتحقق من صحة توقيع البيانات المحددة. |
| **bool** [VerifyData](../rsa/verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | يتحقق من صحة توقيع تدفق البيانات الثنائي المحدد. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يتحقق من توقيع البيانات. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | يتحقق من صحة توقيع التجزئة المحددة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يفنّي الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [RSA](../rsa/)
* فئة [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* نطاق الاسم [System::Security::Cryptography](../)
* مكتبة [Aspose.Slides](../../)