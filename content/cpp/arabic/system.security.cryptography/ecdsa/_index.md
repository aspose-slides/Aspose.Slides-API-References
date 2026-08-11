---
title: ECDsa
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "الفئة الأساسية لتطبيقات خوارزمية ECDsa. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء تشغيلية و/أو أعطال تأكيدية. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 183
url: /ar/system.security.cryptography/ecdsa/
---
## فئة ECDsa

فئة أساسية لتطبيقات خوارزمية [ECDsa](./). يجب تخصيص كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على مكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء تشغيلية و/أو أعطال تأكيدية. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ECDsa : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Methods

| الطريقة | الوصف |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | يطلق جميع الموارد. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)() | ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [ECCurve](../eccurve/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA مع مفتاح تم إنشاؤه حديثًا على المنحنى المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [ECParameters](../ecparameters/)\&) | ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA باستخدام المعلمات المحددة. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [String](../../system/string/)\&) | ينشئ تنفيذًا محددًا لخوارزمية ECDSA. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | يطلق الموارد التي يمتلكها الكائن الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة نقاط عائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة نقاط عائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) | يصدر المعلمات الصريحة. |
| virtual [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) | يصدر المعلمات المسماة أو الصريحة. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual void [FromXmlString](../asymmetricalgorithm/fromxmlstring/)([String](../../system/string/)) | يقرأ معلمات الخوارزمية من سلسلة XML. |
| virtual void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) | ينشئ زوجًا جديدًا من المفاتيح العامة/الخاصة للمنحنى المحدد. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | يحصل على خوارزمية تبادل المفاتيح المستخدمة. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | يحصل على حجم المفتاح. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | يحصل على مصفوفة أحجام المفاتيح المسموح بها. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | يحصل على خوارزمية التوقيع المستخدمة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مقابل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مقابل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) | يستورد جميع المعلمات من بنية البيانات. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مقابل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يقوم بتنفيذ قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مقابل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي مع nullptr حسب المرجع. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | يضبط حجم المفتاح. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحساب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحساب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يحساب قيمة التجزئة لتدفق البيانات الثنائي المحدد باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | يحساب التوقيع للقيمة المدخلة المحددة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مقابل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| virtual [String](../../system/string/) [ToXmlString](../asymmetricalgorithm/toxmlstring/)(**bool**) | يكتب معلمات الخوارزمية إلى سلسلة XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يقوم بتنفيذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يقوم بتنفيذ فك قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صلاحية توقيع البيانات المحددة. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صلاحية توقيع البيانات المحددة. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | يتحقق من صلاحية توقيع تدفق البيانات الثنائي المحدد. |
| virtual **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) | يفحص توقيع البيانات. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## See Also

* الفئة [AsymmetricAlgorithm](../asymmetricalgorithm/)
* النطاق [System::Security::Cryptography](../)
* المكتبة [Aspose.Slides](../../)