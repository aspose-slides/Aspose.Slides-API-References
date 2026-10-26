---
title: Cookie
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل ملف تعريف ارتباط HTTP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احرص دائماً على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 1
url: /ar/system.net/cookie/
---
## فئة Cookie

يمثل ملف تعريف الارتباط HTTP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. اح Wrap هذه الفئة دائمًا إلى مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class Cookie : public System::Object
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | ينشئ نسخة من المثيل الحالي. |
| [Cookie](./cookie/)() | ينشئ مثيلًا جديدًا. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | ينشئ مثيلًا جديدًا. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | ينشئ مثيلًا جديدًا. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | ينشئ مثيلًا جديدًا. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقاط عائمة بأسلوب C# حيث يُعتبر NaNانين متساويين رغم أن IEC 60559:1989 يعرّف أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقاط عائمة بأسلوب C# حيث يُعتبر NaNانين متساويين رغم أن IEC 60559:1989 يعرّف أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | يحصل على قيمة السمة 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | يحصل على قيمة السمة 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | يحصل على قيمة السمة 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | يحصل على قيمة السمة 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | يحصل على قيمة تشير إلى ما إذا كان النطاق ضمنيًا. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | يرجع مفتاح النطاق. |
| **bool** [get_Expired](./get_expired/)() | يحصل على قيمة تشير إلى ما إذا انتهت صلاحية الملف التعريفي. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | يحصل على قيمة السمة 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | يحصل على قيمة السمة 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | يحصل على اسم الملف التعريفي. |
| [String](../../system/string/) [get_Path](./get_path/)() const | يحصل على قيمة السمة 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | يرجع قيمة تشير إلى ما إذا كانت مواصفات الملف التعريفي 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | يحصل على قيمة السمة 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | يرجع مجموعة قيم السمة 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | يحصل على قيمة السمة 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | يرجع الوقت الذي تم إنشاء الملف التعريفي فيه. |
| [String](../../system/string/) [get_Value](./get_value/)() const | يحصل على قيمة الملف التعريفي. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | يحصل على مواصفات الملف التعريفي. |
| **int32_t** [get_Version](./get_version/)() const | يحصل على قيمة السمة '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | تُستدعى هذه الطريقة من قبل طرق أخرى لتعيين اسم طريقة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. تمثيل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعليمة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية للطبقات. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية للطبقات. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | يضبط قيمة السمة 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يضبط قيمة السمة 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | يضبط قيمة السمة 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | يضبط قيمة السمة 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان النطاق ضمنيًا. |
| void [set_Expired](./set_expired/)(**bool**) | يضبط قيمة تشير إلى ما إذا انتهت صلاحية الملف التعريفي. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | يضبط قيمة السمة 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | يضبط قيمة السمة 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | يضبط اسم الملف التعريفي. |
| void [set_Path](./set_path/)([String](../../system/string/)) | يضبط قيمة السمة 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | يضبط قيمة السمة 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | يضبط قيمة السمة 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | يضبط قيمة الملف التعريفي. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | يضبط مواصفات الملف التعريفي. |
| void [set_Version](./set_version/)(**int32_t**) | يضبط قيمة السمة '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي n إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | ي сериализует المثيل الحالي إلى تمثيل نصي. |
| [String](../../system/string/) [ToString](./tostring/)() const override | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعليمة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | يتحقق ويضبط القيم الافتراضية للسمات. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | اسم السمة 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | اسم السمة 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | اسم السمة 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | اسم السمة 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | الفاصل المستخدم لفصل الاسم والقيمة للسمات. |
| static [ExpiresAttributeName](./expiresattributename/) | اسم السمة 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | اسم السمة 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | اسم السمة 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | أعلى نسخة مدعومة. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | تمثيل النص للنسخة القصوى المدعومة. |
| static [PathAttributeName](./pathattributename/) | اسم السمة 'Path'. |
| static [PortAttributeName](./portattributename/) | اسم السمة 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | المصفوفة التي تحتوي على الفواصل لقيم السمة 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | الرمز المستخدم لتغليف أجزاء السمة. |
| static [ReservedToName](./reservedtoname/) | قيمة محجوزة لاسم الملف التعريفي. |
| static [ReservedToValue](./reservedtovalue/) | قيمة محجوزة لقيمة الملف التعريفي. |
| static [SecureAttributeName](./secureattributename/) | اسم السمة 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | فاصل السمات. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | بادئة أسماء السمات الخاصة. |
| static [VersionAttributeName](./versionattributename/) | اسم السمة '[Version](../../system/version/)'. |

## انظر أيضًا

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.Slides](../../)