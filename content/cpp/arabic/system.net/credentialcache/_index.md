---
title: CredentialCache
second_title: مرجع API Aspose.Slides للغة C++
description: "يوفر تخزين بيانات الاعتماد. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. قم دائماً بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 66
url: /ar/system.net/credentialcache/
---
## CredentialCache فئة

يوفر تخزين بيانات الاعتماد. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. قم دائماً بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class CredentialCache : public System::Net::ICredentials,
                        public System::Net::ICredentialsByHost
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NetworkCredential](../networkcredential/)\>) | يضيف بيانات الاعتماد الشبكية المحددة إلى الذاكرة المؤقتة. |
| void [Add](./add/)([String](../../system/string/), **int32_t**, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NetworkCredential](../networkcredential/)\>) | يضيف بيانات الاعتماد الشبكية المحددة إلى الذاكرة المؤقتة. |
| [CredentialCache](./credentialcache/)() | ينشئ مثيلاً جديداً. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلّد مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaNانين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلّد مقارنة النقطة العائمة (Double) بأسلوب C# حيث تُ considered NaNانين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_DefaultCredentials](./get_defaultcredentials/)() | يعيد بيانات الاعتماد النظامية للتطبيق. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NetworkCredential](../networkcredential/)\> [get_DefaultNetworkCredentials](./get_defaultnetworkcredentials/)() | يعيد بيانات الاعتماد الشبكية للمستخدم الحالي أو التطبيق. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkCredential](../networkcredential/)\> [GetCredential](./getcredential/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) override | يعيد بيانات الاعتماد للمسار URI المحدد ونوع المصادقة. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkCredential](../networkcredential/)\> [GetCredential](./getcredential/)([String](../../system/string/), **int32_t**, [String](../../system/string/)) override | يعيد بيانات الاعتماد لاسم المضيف، المنفذ، ونوع المصادقة المحددين. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً لنوع يوصف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائناً. يهيّء جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئاً فعلياً، فقط يهيّء كائناً جديداً ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئاً فعلياً، فقط يهيّء كائناً جديداً ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) | يُزيل بيانات الاعتماد الشبكية للمسار URI المحدد ونوع المصادقة. |
| void [Remove](./remove/)([String](../../system/string/), **int32_t**, [String](../../system/string/)) | يُزيل بيانات الاعتماد الشبكية لاسم المضيف، المنفذ، ونوع المصادقة المحددين. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتغيير المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يُدمّر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [ICredentials](../icredentials/)
* فئة [ICredentialsByHost](../icredentialsbyhost/)
* مساحة الاسم [System::Net](../)
* مكتبة [Aspose.Slides](../../)