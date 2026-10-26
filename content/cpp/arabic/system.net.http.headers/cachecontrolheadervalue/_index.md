---
title: CacheControlHeaderValue
second_title: مرجع API Aspose.Slides للغة C++
description: "يمثل قيمة رأس 'Cache-Control'. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تُنشئ أبدًا مثيلًا لهذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة بمؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 14
url: /ar/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue فئة


يمثل قيمة رأس 'Cache-Control'. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، إذ سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## طرق

| الطريقة | الوصف |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | ينشئ مثيلًا جديدًا. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتَبر NaNانين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتَبر NaNانين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | يعيد مجموعة رموز امتداد الذاكرة المؤقتة. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | يحصل على قيمة العمر الأقصى بالثواني التي تحدد الفترة التي سيقبل فيها العميل الاستجابة. |
| **bool** [get_MaxStale](./get_maxstale/)() | يحصل على القيمة التي تحدد ما إذا كان العميل سيقبل الاستجابات المنتهية الصلاحية. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | يحصل على القيمة بالثواني التي تحدد الفترة التي سيقبل فيها العميل الاستجابات المنتهية الصلاحية. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | يحصل على القيمة التي تحدد عمر الحداثة. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | يحصل على القيمة التي تحدد ما إذا كان الخادم يتطلب إعادة التحقق من صحة الإدخال عندما يصبح قديمًا. |
| **bool** [get_NoCache](./get_nocache/)() | يحصل على القيمة التي تحدد ما إذا كان العميل سيقبل استجابة مخزنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | يحصل على مجموعة أسماء الحقول في توجيه 'no-cache' في رأس 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | يحصل على القيمة التي تحدد ما إذا كان على الذاكرة المؤقتة عدم تخزين أي جزء من طلب HTTP أو استجابة. |
| **bool** [get_NoTransform](./get_notransform/)() | يحصل على القيمة التي تحدد ما إذا كان على الذاكرة المؤقتة أو الوكيل عدم تعديل أي جزء من جسم الكيان. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | يحصل على القيمة التي تحدد ما إذا كان على العميل استخدام الإدخالات المخزنة فقط. |
| **bool** [get_Private](./get_private/)() | يحصل على القيمة التي تحدد ما إذا كانت رسالة الاستجابة HTTP أو جزء منها موجهة لمستخدم واحد ولا يجب تخزينها في ذاكرة مؤقتة مشتركة. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | يحصل على مجموعة أسماء الحقول في توجيه 'private' في رأس 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | يحصل على القيمة التي تحدد ما إذا كان الخادم يتطلب إعادة التحقق من صحة الإدخال عندما يصبح قديمًا للذاكرات المشتركة لوكيل المستخدم. |
| **bool** [get_Public](./get_public/)() | يحصل على القيمة التي تحدد ما إذا كان يمكن تخزين استجابة HTTP في أي ذاكرة مؤقتة. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | يحصل على قيمة العمر الأقصى المشتركة بالثواني التي تتجاوز توجيه 'max-age' في رأس 'Cache-Control' أو رأس 'Expires' للذاكرة المؤقتة المشتركة. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | يقوم بتحويل سلسلة مُعطاة من الفهرس المحدد إلى مثيل من الفئة [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الم beschrieben بـ targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ تأمين جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا يقوم بنسخ أي شيء، بل فقط يهيئ كائنًا جديدًا ويسمح ببناء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا يقوم بنسخ أي شيء، بل فقط يهيئ كائنًا جديدًا ويسمح ببناء نسخ فرعية. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | يقوم بتحويل سلسلة مُعطاة إلى مثيل من الفئة [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يصغّر عداد المرجع المشترك بالقيمة المحددة. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | يضبط قيمة العمر الأقصى بالثواني التي تحدد الفترة التي سيقبل فيها العميل الاستجابة. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان العميل سيقبل الاستجابات المنتهية الصلاحية. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | يضبط القيمة بالثواني التي تحدد الفترة التي سيقبل فيها العميل الاستجابات المنتهية الصلاحية. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | يضبط القيمة التي تحدد عمر الحداثة. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان الخادم يتطلب إعادة التحقق من صحة الإدخال عندما يصبح قديمًا. |
| void [set_NoCache](./set_nocache/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان العميل سيقبل استجابة مخزنة. |
| void [set_NoStore](./set_nostore/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان على الذاكرة المؤقتة عدم تخزين أي جزء من طلب HTTP أو استجابة. |
| void [set_NoTransform](./set_notransform/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان على الذاكرة المؤقتة أو الوكيل عدم تعديل أي جزء من جسم الكيان. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان على العميل استخدام الإدخالات المخزنة فقط. |
| void [set_Private](./set_private/)(**bool**) | يضبط القيمة التي تحدد ما إذا كانت رسالة استجابة HTTP أو جزء منها موجهة لمستخدم واحد ولا يجب تخزينها في ذاكرة مؤقتة مشتركة. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان الخادم يتطلب إعادة التحقق من صحة الإدخال عندما يصبح قديمًا للذاكرات المشتركة لوكيل المستخدم. |
| void [set_Public](./set_public/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان يمكن تخزين استجابة HTTP في أي ذاكرة مؤقتة. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | يضبط قيمة العمر الأقصى المشتركة بالثواني التي تتجاوز توجيه 'max-age' في رأس 'Cache-Control' أو رأس 'Expires' للذاكرة المؤقتة المشتركة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يصغّر ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [String](../../system/string/) [ToString](./tostring/)() const override | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | يحاول تحويل سلسلة مُعطاة إلى مثيل من الفئة [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء تأمين جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يصغّر عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [ICloneable](../../system/icloneable/)
* مساحة الاسم [System::Net::Http::Headers](../)
* المكتبة [Aspose.Slides](../../)