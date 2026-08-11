---
title: NameValueHeaderValue
second_title: "Aspose.Slides للـ C++ مرجع واجهة برمجة التطبيقات"
description: "يمثل زوجًا من المفتاح/القيمة للاستخدام في رؤوس الطلبات. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأنه سيؤدي إلى أخطاء وقت تشغيل و/أو أعطال تأكيدية. غلف هذه الفئة دائمًا إلى مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 170
url: /ar/system.net.http.headers/namevalueheadervalue/
---
## NameValueHeaderValue فئة


يمثل زوج مفتاح/قيمة للاستخدام في رؤوس الطلبات. يجب إنشاء كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أعطال تأكيدية. اح-wrap دائمًا هذه الفئة إلى مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class NameValueHeaderValue : public virtual System::ICloneable
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaN-انان متساويتين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaN-انان متساويتين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\> [Find](./find/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>, [String](../../system/string/)) | يجد نسخة من فئة NameValueHeaderValue في مجموعة حسب الاسم المحدد. |
| [String](../../system/string/) [get_Name](./get_name/)() | يرجع اسم النسخة الحالية. |
| [String](../../system/string/) [get_Value](./get_value/)() | يحصل على قيمة النسخة الحالية. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن من تجزئة الكائنات المخصصة. |
| static **int32_t** [GetHashCode](./gethashcode/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>) | يرجع رمز تجزئة لجميع عناصر المجموعة. |
| static **int32_t** [GetNameValueLength](./getnamevaluelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\&) | يحول سلسلة مُدخلة من الفهرس المحدد إلى نسخة من الفئة [NameValueHeaderValue](./). |
| static **int32_t** [GetNameValueLength](./getnamevaluelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\&) | يحول سلسلة مُدخلة من الفهرس المحدد إلى نسخة من الفئة [NameValueHeaderValue](./). |
| static **int32_t** [GetNameValueListLength](./getnamevaluelistlength/)([String](../../system/string/), **int32_t**, char16_t, [System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>) | يحول سلسلة مُدخلة من الفهرس المحدد إلى مجموعة من نسخ فئة NameValueHeaderValue ويعيد طول المقطع المُحلل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int32_t** [GetValueLength](./getvaluelength/)([String](../../system/string/), **int32_t**) | يرجع طول قيمة من الفهرس المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن من استنساخ الأنواع المخصصة. |
|  [NameValueHeaderValue](./namevalueheadervalue/)() | يبني نسخة جديدة. |
|  [NameValueHeaderValue](./namevalueheadervalue/)([String](../../system/string/)) | يبني نسخة جديدة. |
|  [NameValueHeaderValue](./namevalueheadervalue/)([String](../../system/string/), [String](../../system/string/)) | يبني نسخة جديدة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويمكّن بناء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويمكّن بناء نسخ فرعية. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | يحول سلسلة مُدخلة إلى نسخة من الفئة [NameValueHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن من نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Value](./set_value/)([String](../../system/string/)) | يضبط قيمة النسخة الحالية. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n'th كإشارة ضعيفة (بدلاً من مشاركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن من تحويل الكائنات المخصصة إلى سلسلة. |
| static void [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>, char16_t, **bool**, [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>) | يرجع تمثيلًا نصيًا لمجموعة نسخ فئة NameValueHeaderValue. |
| static [String](../../system/string/) [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>, char16_t, **bool**) | يرجع تمثيلًا نصيًا لمجموعة نسخ فئة NameValueHeaderValue. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\&) | يحاول تحويل سلسلة مُدخلة إلى نسخة من الفئة [NameValueHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [ICloneable](../../system/icloneable/)
* مساحة الأسماء [System::Net::Http::Headers](../)
* مكتبة [Aspose.Slides](../../)