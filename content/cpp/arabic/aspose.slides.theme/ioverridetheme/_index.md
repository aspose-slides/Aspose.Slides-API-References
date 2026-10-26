---
title: IOverrideTheme
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل سمةً متجاوزةً.
type: docs
weight: 391
url: /ar/aspose.slides.theme/ioverridetheme/
---
## IOverrideTheme فئة

يمثل سمةً متجاوزةً.

```cpp
class IOverrideTheme : public virtual Aspose::Slides::Theme::ITheme
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Clear](./clear/)() | عيّن [ColorScheme](../colorscheme/)، [FontScheme](../fontscheme/)، [FormatScheme](../formatscheme/) إلى null لتعطيل أي تجاوز باستخدام كائن السمة هذا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يماثل مقارنة الأعداد العائمة بنمط C# حيث تُعتبر NaNين متساويتين رغم أن وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يماثل مقارنة الأعداد العائمة بنمط C# حيث تُعتبر NaNين متساويتين رغم أن وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](../itheme/get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](../itheme/get_colorscheme/)() | يعيد مخطط الألوان. للقراءة فقط [IColorScheme](../icolorscheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](../itheme/get_fontscheme/)() | يعيد مخطط الخط. للقراءة فقط [IFontScheme](../ifontscheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](../itheme/get_formatscheme/)() | يعيد مخطط تنسيق الشكل. للقراءة فقط [IFormatScheme](../iformatscheme/). |
| virtual **bool** [get_IsEmpty](./get_isempty/)() | القيمة true تعني أن [ColorScheme](../colorscheme/)، [FontScheme](../fontscheme/)، [FormatScheme](../formatscheme/) هي null وأن أي تجاوز باستخدام كائن السمة هذا مُعطل. للقراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. للقراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجع المرتبط بالكائن. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../itheme/geteffective/)() | يحصل على بيانات السمة الفعلية مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر لدالة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [InitColorScheme](./initcolorscheme/)() | تهيئة [ColorScheme](../colorscheme/) باستخدام كائن جديد لتجاوز [ColorScheme](../colorscheme/) من InheritedTheme. |
| virtual void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) | تهيئة [ColorScheme](../colorscheme/) باستخدام كائن جديد لتجاوز [ColorScheme](../colorscheme/) من InheritedTheme. |
| virtual void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() | تهيئة [ColorScheme](../colorscheme/) باستخدام كائن جديد لتجاوز [ColorScheme](../colorscheme/) من InheritedTheme. وتفعيل بيانات هذا الكائن الجديد ببيانات [ColorScheme](../colorscheme/) من InheritedTheme. |
| virtual void [InitFontScheme](./initfontscheme/)() | تهيئة [FontScheme](../fontscheme/) باستخدام كائن جديد لتجاوز [FontScheme](../fontscheme/) من InheritedTheme. |
| virtual void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) | تهيئة [FontScheme](../fontscheme/) باستخدام كائن جديد لتجاوز [FontScheme](../fontscheme/) من InheritedTheme. |
| virtual void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() | تهيئة [FontScheme](../fontscheme/) باستخدام كائن جديد لتجاوز [FontScheme](../fontscheme/) من InheritedTheme. وتفعيل بيانات هذا الكائن الجديد ببيانات [FontScheme](../fontscheme/) من InheritedTheme. |
| virtual void [InitFormatScheme](./initformatscheme/)() | تهيئة [FormatScheme](../formatscheme/) باستخدام كائن جديد لتجاوز [FormatScheme](../formatscheme/) من InheritedTheme. |
| virtual void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) | تهيئة [FormatScheme](../formatscheme/) باستخدام كائن جديد لتجاوز [FormatScheme](../formatscheme/) من InheritedTheme. |
| virtual void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() | تهيئة [FormatScheme](../formatscheme/) باستخدام كائن جديد لتجاوز [FormatScheme](../formatscheme/) من InheritedTheme. وتفعيل بيانات هذا الكائن الجديد ببيانات [FormatScheme](../formatscheme/) من InheritedTheme. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. تناظر لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر لدالة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | عيّن الوسيط القالب الـ n't إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر لدالة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحذف جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [ITheme](../itheme/)
* مساحة الاسم [Aspose::Slides::Theme](../)
* مكتبة [Aspose.Slides](../../)