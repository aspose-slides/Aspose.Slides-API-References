---
title: X509Certificate
second_title: مرجع API Aspose.Slides للغة C++
description: "شهادة X.509 v.3. لا يتم دعم الشهادات المشفرة. يتم دعم علم X509KeyStorageFlags::DefaultKeySet فقط. يجب إنشاء كائنات هذه الفئة باستخدام دالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيلة."
type: docs
weight: 27
url: /ar/system.security.cryptography.x509certificates/x509certificate/
---
## فئة X509Certificate

X.509 v.3 شهادة. لا يتم دعم الشهادات المشفرة. فقط علامة [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) مدعومة. يجب إنشاء كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كوسيطة.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## طرق

| طريقة | وصف |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | ينشئ شهادة من ملف PKCS7 المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | ينشئ شهادة من الملف الموقع المحدد. |
| void [Dispose](./dispose/)() override | لا يفعل شيئًا. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن شهادتين. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين بالرغم من أن IEC 60559:1989 تنص على أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين بالرغم من أن IEC 60559:1989 تنص على أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | يصدر الكائن الحالي إلى مصفوفة بايت باستخدام الصيغة المحددة. غير مُنفَّذ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | يصدر الكائن الحالي إلى مصفوفة بايت باستخدام الصيغة المحددة. غير مُنفَّذ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | يصدر الكائن الحالي إلى مصفوفة بايت باستخدام الصيغة المحددة. غير مُنفَّذ. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| IntPtr [get_Handle](./get_handle/)() const | يحصل على مقبض لسياق شهادة Microsoft Cryptographic API. |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | يحصل على اسم سلطة الشهادة التي أصدرت شهادة X.509v3. |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | يحصل على الاسم المميز للموضوع من الشهادة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | يحصل على التجزئة للكائن الحالي كمصفوفة بايت. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | يحصل على التجزئة للكائن الحالي كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | يحصل على التجزئة [SHA1](../../system.security.cryptography/sha1/) للكائن الحالي كسلسلة سداسي عشرية. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | يحصل على التجزئة [SHA1](../../system.security.cryptography/sha1/) للكائن الحالي كسلسلة سداسي عشرية. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | يحصل على تاريخ السريان للشهادة الحالية. |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | يحصل على تاريخ الانتهاء للشهادة الحالية. |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | يحصل على اسم صيغة الشهادة. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | يحصل على رمز تجزئة الشهادة. |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | يحصل على اسم سلطة الشهادة التي أصدرت الشهادة الحالية. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | يحصل على معلومات المفتاح للشهادة الحالية كسلسلة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | يحصل على معلومات المفتاح للشهادة الحالية كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | يحصل على معلومات المفتاح للشهادة الحالية كسلسلة سداسي عشرية. |
| virtual [String](../../system/string/) [GetName](./getname/)() const | يحصل على اسم الطرف principal الذي أُصدرت له الشهادة الحالية. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | يحصل على المفتاح العام من الشهادة كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | يحصل على المفتاح العام من الشهادة كسلسلة سداسي عشرية. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | يحصل على البيانات الخام من الشهادة كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | يحصل على البيانات الخام من الشهادة كسلسلة سداسي عشرية. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | يحصل على الرقم التسلسلي من الشهادة كمصفوفة بايت. |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | يحصل على الرقم التسلسلي من الشهادة كسلسلة سداسي عشرية. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. ما يعادل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | يستورد المعلومات من ملف الشهادة المحدد. غير مُنفَّذ. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | يستورد المعلومات من ملف الشهادة المحدد. غير مُنفَّذ. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | يستورد المعلومات من بيانات الشهادة المحددة. غير مُنفَّذ. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | يستورد المعلومات من بيانات الشهادة المحددة. غير مُنفَّذ. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | يستورد المعلومات من ملف الشهادة المحدد. غير مُنفَّذ. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يستورد المعلومات من بيانات الشهادة المحددة. غير مُنفَّذ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. ما يعادل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ما يعادل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح ببناء نسخ من الفئات الفرعية. |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح ببناء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [Reset](./reset/)() | يعيد تعيين حالة الشهادة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | يعيد معلومات الشهادة بصيغة نصية. |
| [String](../../system/string/) [ToString](./tostring/)() const override | يعيد معلومات الشهادة بصيغة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | منشئ. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | منشئ. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## تعريفات الأنواع

| تعريف | وصف |
| --- | --- |
| [Ptr](./ptr/) | نوع المؤشر. |

## راجع أيضًا

* الفئة [Object](../../system/object/)
* الفئة [IDisposable](../../system/idisposable/)
* النطاق [System::Security::Cryptography::X509Certificates](../)
* المكتبة [Aspose.Slides](../../)