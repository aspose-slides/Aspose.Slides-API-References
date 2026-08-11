---
title: RegionInfo
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يوفر معلومات عن المنطقة. يجب تخصيص كائنات هذه الفئة باستخدام دالة System::MakeObject() فقط. لا تنشئ نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا غلف هذه الفئة بمؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 274
url: /ar/system.globalization/regioninfo/
---
## RegionInfo فئة

يوفر معلومات عن المنطقة. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. دائمًا غلف هذه الفئة بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class RegionInfo : public virtual System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يُقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يُقارن كائنات نوع المرجع بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaNّان متساويتين بالرغم من أن IEC 60559:1989 تُشير إلى أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaNّان متساويتين بالرغم من أن IEC 60559:1989 تُشير إلى أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [String](../../system/string/) [get_CurrencyEnglishName](./get_currencyenglishname/)() const | يحصل على اسم العملة باللغة الإنجليزية. |
| virtual [String](../../system/string/) [get_CurrencyNativeName](./get_currencynativename/)() const | يحصل على اسم العملة الأصلي. |
| virtual [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | يحصل على رمز العملة. |
| static [RegionInfoPtr](../regioninfoptr/) [get_CurrentRegion](./get_currentregion/)() | يحصل على المنطقة المحددة في النظام. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | يحصل على الاسم الكامل للمنطقة. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | يحصل على اسم المنطقة باللغة الإنجليزية. |
| virtual int [get_GeoId](./get_geoid/)() const | يحصل على معرف فريد للمنطقة. |
| virtual **bool** [get_IsMetric](./get_ismetric/)() const | يتحقق مما إذا كانت المنطقة تستخدم النظام المتري. |
| virtual [String](../../system/string/) [get_ISOCurrencySymbol](./get_isocurrencysymbol/)() const | يحصل على رمز العملة ISO. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | يحصل على اسم المنطقة. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | يحصل على اسم المنطقة الأصلي. |
| virtual [String](../../system/string/) [get_ThreeLetterISORegionName](./get_threeletterisoregionname/)() const | يحصل على رمز ISO للمنطقة المكوّن من 3 أحرف. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsRegionName](./get_threeletterwindowsregionname/)() const | يحصل على رمز المنطقة المكوّن من 3 أحرف [Windows](../../system.windows/). |
| virtual [String](../../system/string/) [get_TwoLetterISORegionName](./get_twoletterisoregionname/)() const | يحصل على رمز ISO للمنطقة المكوّن من حرفين. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| int [GetHashCode](./gethashcode/)() const override | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويتيح استنساخ الفئات المشتقة. |
| [RegionInfo](./)\& [operator=](./operator_equal/)(const [RegionInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويتيح استنساخ الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ[Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ[Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| [RegionInfo](./regioninfo/)(const [String](../../system/string/)\&) | معلومات RTTI. |
| [RegionInfo](./regioninfo/)(int) | منشئ. |
| [RegionInfo](./regioninfo/)(const [RegionInfo](./)\&) |  |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [String](../../system/string/) [ToString](./tostring/)() const override | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## أنظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [System::Globalization](../)
* مكتبة [Aspose.Slides](../../)