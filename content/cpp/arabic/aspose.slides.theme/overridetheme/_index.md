---
title: OverrideTheme
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل سمةً متجاوزةً.
type: docs
weight: 547
url: /ar/aspose.slides.theme/overridetheme/
---
## فئة OverrideTheme

يمثل سمةً متجاوزةً.

```cpp
class OverrideTheme : public Aspose::Slides::Theme::Theme,
                      public Aspose::Slides::Theme::IOverrideTheme
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Clear](./clear/)() override | قم بتعيين [ColorScheme](../colorscheme/) و [FontScheme](../fontscheme/) و [FormatScheme](../formatscheme/) إلى null لتعطيل أي تجاوز باستخدام كائن الثيم هذا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعتبر NaNانَين متساوين على الرغم من أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعتبر NaNانَين متساوين على الرغم من أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](./get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](./get_colorscheme/)() override | يرجع مخطط اللون. قراءة فقط [IColorScheme](../icolorscheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](./get_fontscheme/)() override | يرجع مخطط الخط. قراءة فقط [IFontScheme](../ifontscheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](./get_formatscheme/)() override | يرجع مخطط تنسيق الشكل. قراءة فقط [IFormatScheme](../iformatscheme/). |
| **bool** [get_IsEmpty](./get_isempty/)() override | القيمة true تعني أن [ColorScheme](../colorscheme/) و [FontScheme](../fontscheme/) و [FormatScheme](../formatscheme/) هي null وأن أي تجاوز باستخدام كائن الثيم هذا مُعطل. قراءة فقط **bool**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | يرجع العنصر الأب [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). قراءة فقط [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../theme/get_presentation/)() override | يرجع العرض التقديمي الأب. قراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../theme/geteffective/)() override | يحصل على بيانات الثيم الفعّالة مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [InitColorScheme](./initcolorscheme/)() override | أبدا [ColorScheme](../colorscheme/) بكائن جديد لتجاوز [ColorScheme](../colorscheme/) في InheritedTheme. |
| void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) override | أبدا [ColorScheme](../colorscheme/) بكائن جديد لتجاوز [ColorScheme](../colorscheme/) في InheritedTheme. |
| void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() override | أبدا [ColorScheme](../colorscheme/) بكائن جديد لتجاوز [ColorScheme](../colorscheme/) في InheritedTheme. ثم قم بتهيئة بيانات هذا الكائن الجديد ببيانات [ColorScheme](../colorscheme/) في InheritedTheme. |
| void [InitFontScheme](./initfontscheme/)() override | أبدا [FontScheme](../fontscheme/) بكائن جديد لتجاوز [FontScheme](../fontscheme/) في InheritedTheme. |
| void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) override | أبدا [FontScheme](../fontscheme/) بكائن جديد لتجاوز [FontScheme](../fontscheme/) في InheritedTheme. |
| void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() override | أبدا [FontScheme](../fontscheme/) بكائن جديد لتجاوز [FontScheme](../fontscheme/) في InheritedTheme. ثم قم بتهيئة بيانات هذا الكائن الجديد ببيانات [FontScheme](../fontscheme/) في InheritedTheme. |
| void [InitFormatScheme](./initformatscheme/)() override | أبدا [FormatScheme](../formatscheme/) بكائن جديد لتجاوز [FormatScheme](../formatscheme/) في InheritedTheme. |
| void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) override | أبدا [FormatScheme](../formatscheme/) بكائن جديد لتجاوز [FormatScheme](../formatscheme/) في InheritedTheme. |
| void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() override | أبدا [FormatScheme](../formatscheme/) بكائن جديد لتجاوز [FormatScheme](../formatscheme/) في InheritedTheme. ثم قم بتهيئة بيانات هذا الكائن الجديد ببيانات [FormatScheme](../formatscheme/) في InheritedTheme. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي مع nullptr بالمرجع. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المراجع المشتركة ويعيد قيمته. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Theme](../theme/)
* الفئة [IOverrideTheme](../ioverridetheme/)
* مساحة الأسماء [Aspose::Slides::Theme](../)
* المكتبة [Aspose.Slides](../../)