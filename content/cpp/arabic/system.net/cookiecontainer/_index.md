---
title: CookieContainer
second_title: مرجع API Aspose.Slides للغة C++
description: "يوفر حاوية لنسخ فئة CookieCollection-class. يجب تخصيص كائنات هذه الفئة باستخدام دالة System::MakeObject() فقط. لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيؤدي إلى أخطاء تشغيلية و/أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 40
url: /ar/system.net/cookiecontainer/
---
## فئة CookieContainer

يوفر حاوية لنسخ فئة CookieCollection. يجب تخصيص كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيؤدي إلى أخطاء تنفيذ و/أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class CookieContainer : public System::Object
```

## الطرق

| Method | Description |
| --- | --- |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | يضيف ملف تعريف ارتباط إلى المجموعة. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>, **bool**) | يضيف ملف تعريف ارتباط إلى المجموعة. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | ينسخ ملفات تعريف الارتباط من المجموعة المحددة إلى الحالية. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | يضيف ملف تعريف ارتباط للـ URI المحدد. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | ينسخ ملفات تعريف الارتباط من المجموعة المحددة للـ URI المحدد إلى المجموعة الحالية. |
| [CookieContainer](./cookiecontainer/)() | يبني كائنًا جديدًا. |
| [CookieContainer](./cookiecontainer/)(**int32_t**) | يبني كائنًا جديدًا. |
| [CookieContainer](./cookiecontainer/)(**int32_t**, **int32_t**, **int32_t**) | يبني كائنًا جديدًا. |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [CookieCutter](./cookiecutter/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), [String](../../system/string/), **bool**) | ينسخ ملفات تعريف الارتباط من رأس HTTP المحدد للـ URI المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_Capacity](./get_capacity/)() | يحصل على سعة المجموعة. |
| **int32_t** [get_Count](./get_count/)() | يعيد عدد عناصر المجموعة. |
| **int32_t** [get_MaxCookieSize](./get_maxcookiesize/)() | يحصل على الحد الأقصى لحجم ملف تعريف الارتباط. |
| **int32_t** [get_PerDomainCapacity](./get_perdomaincapacity/)() | يحصل على سعة المجموعة لكل نطاق. |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يعيد رأس HTTP يحتوي على ملفات تعريف الارتباط المرتبطة بالـ URI المحدد. |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)\&) | يعيد رأس HTTP يحتوي على ملفات تعريف الارتباط المرتبطة بالـ URI المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [GetCookies](./getcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يعيد مجموعة من ملفات تعريف الارتباط المرتبطة بالـ URI المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [InternalGetCookies](./internalgetcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يعيد مجموعة من ملفات تعريف الارتباط المرتبطة بالـ URI المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا من النوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| **bool** [IsLocalDomain](./islocaldomain/)([String](../../system/string/)) | يفحص ما إذا كان النطاق المحدد هو localhost. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). يُستدعى مباشرة أو باستخدام كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعًا لكائن من النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Capacity](./set_capacity/)(**int32_t**) | يضبط سعة المجموعة. |
| void [set_MaxCookieSize](./set_maxcookiesize/)(**int32_t**) | يضبط الحد الأقصى لحجم ملف تعريف الارتباط. |
| void [set_PerDomainCapacity](./set_perdomaincapacity/)(**int32_t**) | يضبط سعة المجموعة لكل نطاق. |
| void [SetCookies](./setcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) | ينسخ ملفات تعريف الارتباط من الرأس المحدد إلى المجموعة ويربطها بالـ URI المحدد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). يُستدعى مباشرة أو باستخدام كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## الحقول

| Field | Description |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | الحد الأقصى لحجم ملف تعريف الارتباط. |
| static [DefaultCookieLimit](./defaultcookielimit/) | الحد الأقصى لعدد عناصر المجموعة. |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | الحد الأقصى لعدد عناصر المجموعة لكل نطاق. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [System::Net](../)
* مكتبة [Aspose.Slides](../../)