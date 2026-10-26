---
title: CultureInfo
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "مجموعة من القيم والخوارزميات الخاصة بثقافة معينة. عمليات الضبط مفعّلة فقط على الكائنات غير القابلة للقراءة فقط. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء وقت تشغيل و/أو أخطاء تأكيد. دائمًا غلف هذه الفئة بمؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 53
url: /ar/system.globalization/cultureinfo/
---
## فئة CultureInfo

مجموعة من القيم والخوارزميات الخاصة بالثقافة. يتم تمكين عمليات الضبط فقط على الكائنات غير القابلة للقراءة فقط. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيتسبب في أخطاء وقت التشغيل و/أو أخطاء التحقق. احفظ دائمًا هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## الطرق

| Method | الوصف |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | يقوم بتحديث معلومات الثقافة المخزنة مؤقتًا. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينسخ معلومات الثقافة. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | ينشئ ثقافة بالاسم. |
| explicit  [CultureInfo](./cultureinfo/)(int) | معلومات RTTI. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | منشئ. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | منشئ. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | منشئ. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | دائمًا يرمى استثناء ArgumentNullException. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن الكائنات. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة أعداد نقطية بأسلوب C# حيث يُعتبر NaNانين متساويين بالرغم من أنه وفقًا لـ IEC 60559:1989 لا يُعد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة أعداد نقطية بأسلوب C# حيث يُعتبر NaNانين متساويين بالرغم من أنه وفقًا لـ IEC 60559:1989 لا يُعد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | يحصل على التقويم المستخدم من قبل الثقافة. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | يحصل على مُقارن السلاسل الذي يلتزم بقواعد الثقافة. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | يحصل على الجمع البتّي لأنواع الثقافة التي تصف الثقافة الحالية. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | يحصل على الثقافة المعينة للخيط الحالي. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | يحصل على ثقافة واجهة المستخدم للخيط الحالي. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | يحصل على معلومات صيغة التاريخ. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | يحصل على الثقافة الافتراضية في نطاق التطبيق الحالي. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | يحصل على ثقافة واجهة المستخدم الافتراضية في نطاق التطبيق الحالي. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | يحصل على اسم العرض للثقافة. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | يحصل على الاسم الإنجليزي للثقافة. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | يحصل على اسم RFC 4646 لللغة. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | يحصل على الثقافة المثبتة مع نظام التشغيل. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | يحصل على الثقافة غير المتغيرة. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | يتحقق مما إذا كانت الثقافة محايدة. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | يتحقق مما إذا كان كائن الثقافة للقراءة فقط. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | يحصل على معرف اللغة النشط للمدخل. |
| virtual int [get_LCID](./get_lcid/)() const | يحصل على معرف الثقافة. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | يحصل على اسم الثقافة. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | يحصل على الاسم الأصلي للثقافة. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | يحصل على معلومات تنسيق الأعداد. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | قائمة بالتقويمات التي يمكن استخدامها مع الثقافة. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | يحصل على الثقافة الأصلية. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | يحصل على معلمات النص المستخدمة في الثقافة. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | يحصل على رمز اللغة ثلاثي الأحرف وفق ISO 639-2. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | يحصل على رمز اللغة ثلاثي الأحرف كما هو معرف في واجهة برمجة التطبيقات [Windows](../../system.windows/). |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | يحصل على اسم اللغة المكوّن من حرفين وفق ISO المرتبط بالثقافة. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | يحصل على علامة تشير إلى ما إذا كان [CultureInfo](./) يستخدم إعدادات الثقافة التي يحددها المستخدم. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | يحصل على ثقافة بديلة مناسبة لتطبيقات وحدة التحكم. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | يحصل على الثقافة بناءً على اسمها. نفس CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يحصل على الثقافة بناءً على اسمها. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | يحصل على الثقافة بناءً على المعرف. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | مهمل. يحصل على كائن [CultureInfo](./) للقراءة فقط بواسطة علامة اللغة RFC 4646 المحددة. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | يحصل على الثقافات التي تنتمي إلى الأنواع المحددة. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | يحصل على كائن التنسيق للنوع المحدد. |
| int [GetHashCode](./gethashcode/)() const override | يعيد رمز التجزئة للكائن. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثلاً للنوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| **bool** [IsInherited](./isinherited/)() const | يحصل على علامة الوراثة. للاستخدام الداخلي فقط. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | يقارن معلمات الثقافة. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | يحصل على نسخة قراءة فقط من الثقافة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | يضبط الثقافة للخيط الحالي. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | يضبط ثقافة واجهة المستخدم للخيط الحالي. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | يضبط معلومات صيغة التاريخ. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | يضبط الثقافة الافتراضية في نطاق التطبيق الحالي. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | يضبط ثقافة واجهة المستخدم الافتراضية في نطاق التطبيق الحالي. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | يحصل على معلومات تنسيق الأعداد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب الـ n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | يحويل الثقافة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* الفئة [IFormatProvider](../../system/iformatprovider/)
* الفئة [ICloneable](../../system/icloneable/)
* النطاق [System::Globalization](../)
* المكتبة [Aspose.Slides](../../)