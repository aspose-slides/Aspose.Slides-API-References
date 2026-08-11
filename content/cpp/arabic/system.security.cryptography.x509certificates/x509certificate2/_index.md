---
title: X509Certificate2
second_title: مرجع Aspose.Slides للغة C++
description: "يمثل شهادة X509. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تُنشئ أبدا مثيلاً لهذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أعطال التأكيد. دائمًا لفّ هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 40
url: /ar/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 فئة

يمثل شهادة X509. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبب أخطاء وقت التشغيل أو أعطال التأكيد. قم دائمًا بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | ينشئ شهادة من الملف PKCS7 المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | ينشئ شهادة من الملف الموقّع المحدد. |
| void [Dispose](../x509certificate/dispose/)() override | لا يفعل شيئًا. |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن شهادتين. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تعتبر NaNانّين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تعتبر NaNانّين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | يصدر الكائن الحالي إلى مصفوفة بايت باستخدام الصيغة المحددة. غير منفذ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | يصدر الكائن الحالي إلى مصفوفة بايت باستخدام الصيغة المحددة. غير منفذ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | يصدر الكائن الحالي إلى مصفوفة بايت باستخدام الصيغة المحددة. غير منفذ. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_Archived](./get_archived/)() const | يحصل على قيمة تشير إلى أن الشهادة مؤرشفة. |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | يحصل على مجموعة من كائنات الامتداد المرتبطة بالشهادة. |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | يحصل على الاسم الودي للشهادة. |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | يحصل على مقبض لسياق شهادة Microsoft Cryptographic API. |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | يتحقق مما إذا كانت الشهادة لديها مفتاح خاص. |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | يحصل على اسم سلطة الشهادة التي أصدرت شهادة X.509v3. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | يحصل على اسم الجهة التي أصدرت الشهادة. |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | يحصل على التاريخ والوقت المحلي بعدهما تصبح الشهادة غير صالحة. |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | يحصل على التاريخ والوقت المحلي الذي تصبح فيه الشهادة صالحة. |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | يحصل على المفتاح الخاص المرتبط بالشهادة. |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | يحصل على كائن شهادة [PublicKey](../publickey/). |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | يحصل على البيانات الخام للشهادة. |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | يحصل على الرقم التسلسلي للشهادة. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | يحصل على الخوارزمية المستخدمة لإنشاء توقيع الشهادة. |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | يحصل على الاسم المميز للموضوع من الشهادة. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | يحصل على اسم الموضوع من شهادة. |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | يحصل على بصمة الشهادة. |
| **int32_t** [get_Version](./get_version/)() const | يحصل على إصدار صيغة الشهادة. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يحصل على نوع الشهادة الموجود في مصفوفة البايت المحددة. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | يحصل على نوع الشهادة الموجود في الملف المحدد. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | يحصل على التجزئة للكائن الحالي كمصفوفة بايت. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | يحصل على التجزئة للكائن الحالي كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | يحصل على تجزئة [SHA1](../../system.security.cryptography/sha1/) للكائن الحالي كسلسلة ست عشرية. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | يحصل على تجزئة [SHA1](../../system.security.cryptography/sha1/) للكائن الحالي كسلسلة ست عشرية. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المراجع المرتبطة بالكائن. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | يحصل على المفتاح الخاص [RSA](../../system.security.cryptography/rsa/)؛ |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | يحصل على المفتاح العام [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | يحصل على المفتاح الخاص [RSA](../../system.security.cryptography/rsa/)؛ |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | يحصل على المفتاح العام [RSA](../../system.security.cryptography/rsa/). |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | يحصل على التاريخ الفعلي للشهادة الحالية. |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | يحصل على تاريخ الانتهاء للشهادة الحالية. |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | يحصل على اسم صيغة الشهادة. |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | يحصل على رمز تجزئة الشهادة. |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | يحصل على اسم سلطة التصديق التي أصدرت الشهادة الحالية. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | يحصل على معلومات المفتاح للشهادة الحالية كسلسلة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | يحصل على معلومات المفتاح للشهادة الحالية كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | يحصل على معلومات المفتاح للشهادة الحالية كسلسلة ست عشرية. |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | يحصل على اسم الكيان الذي أُصدرت له الشهادة الحالية. |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | يحصل على اسم الموضوع أو المُصدِر من الشهادة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | يحصل على المفتاح العام من الشهادة كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | يحصل على المفتاح العام من الشهادة كسلسلة ست عشرية. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | يحصل على البيانات الخام من الشهادة كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | يحصل على البيانات الخام من الشهادة كسلسلة ست عشرية. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | يحصل على المفتاح الخاص [RSA](../../system.security.cryptography/rsa/)؛ |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | يحصل على المفتاح العام [RSA](../../system.security.cryptography/rsa/). |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | يحصل على الرقم التسلسلي من الشهادة كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | يحصل على الرقم التسلسلي من الشهادة كسلسلة ست عشرية. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | يستورد المعلومات من ملف الشهادة المحدد. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | يستورد المعلومات من ملف الشهادة المحدد. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | يستورد المعلومات من بيانات الشهادة المحددة. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | يستورد المعلومات من بيانات الشهادة المحددة. |
| void [Import](./import/)(const [String](../../system/string/)\&) override | يستورد المعلومات من ملف الشهادة المحدد. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | يستورد المعلومات من بيانات الشهادة المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا لنوع يوصف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | منشئ النسخ. لا ينسخ شيء فعليًا، فقط يهيّء كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | مشغل الإسناد. لا ينسخ شيء فعليًا، فقط يهيّء كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقّلل عداد المرجع المشترك بالقيمة المحددة. |
| void [Reset](./reset/)() override | يعيد تعيين حالة الشهادة. |
| void [set_Archived](./set_archived/)(**bool**) const | يضبط قيمة تشير إلى أن الشهادة مؤرشفة. |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | يضبط الاسم الودي للشهادة. |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | يضبط أو يمسح المفتاح الخاص المرتبط بالشهادة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كمرجع ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | يرجع معلومات الشهادة بصيغة نصية. |
| [String](../../system/string/) [ToString](./tostring/)() const override | يرجع معلومات الشهادة بصيغة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| **bool** [Verify](./verify/)() const | يتحقق من سلسلة الشهادة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [X509Certificate](../x509certificate/)\&) |  |
|  [X509Certificate](../x509certificate/x509certificate/)() | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate2](./x509certificate2/)() | يبني [X509Certificate2](./) فارغًا. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [X509Certificate](../x509certificate/)
* مساحة الأسماء [System::Security::Cryptography::X509Certificates](../)
* مكتبة [Aspose.Slides](../../)