---
title: IChartPortionFormat
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل خصائص تنسيق جزء الرسم البياني المستخدمة في الرسوم البيانية.
type: docs
weight: 807
url: /ar/aspose.slides.charts/ichartportionformat/
---
## IChartPortionFormat فئة


يمثل خصائص تنسيق جزء الرسم البياني المستخدمة في الرسوم البيانية.

```cpp
class IChartPortionFormat : public virtual Aspose::Slides::IBasePortionFormat
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يعتبر NaNين متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يعتبر NaNين متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/get_alternativelanguageid/)() | يرجع معرف لغة بديلة. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/ibaseportionformat/get_complexscriptfont/)() | يرجع معلومات خط النص المعقد. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الأصل. اقرأ [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/ibaseportionformat/get_eastasianfont/)() | يرجع معلومات خط شرق آسيوي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الأصل. اقرأ [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ibaseportionformat/get_effectformat/)() | يرجع خصائص النص [EffectFormat](../../aspose.slides/effectformat/). لا يتم تطبيق الوراثة. قراءة فقط [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual **float** [get_Escapement](../../aspose.slides/ibaseportionformat/get_escapement/)() | يرجع النص العلوي أو السفلي. القيمة من -100% (سفلي) إلى 100% (علوي). **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الأصل. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ibaseportionformat/get_fillformat/)() | يرجع خصائص النص [FillFormat](../../aspose.slides/fillformat/). لا يتم تطبيق الوراثة. قراءة فقط [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/ibaseportionformat/get_fontbold/)() | يحدّد ما إذا كان الخط عريضاً. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_FontHeight](../../aspose.slides/ibaseportionformat/get_fontheight/)() | يرجع ارتفاع الخط للجزء. **std::numeric_limits<float>::quiet_NaN()** تعني أن الارتفاع غير معرف ويجب وراثته من الأصل. قراءة **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/ibaseportionformat/get_fontitalic/)() | يحدد ما إذا كان الخط مائلاً. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/ibaseportionformat/get_fontunderline/)() | يرجع نوع تسطير النص. لا يتم تطبيق الوراثة. اقرأ [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/ibaseportionformat/get_highlightcolor/)() | يرجع اللون المستخدم لتسليط الضوء على النص. لا يتم تطبيق الوراثة. قراءة فقط [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/get_ishardunderlinefill/)() | يحدّد ما إذا كان نمط التسطير له خصائص [FillFormat](../../aspose.slides/fillformat/) خاصة أو يرثها من خصائص [FillFormat](../../aspose.slides/fillformat/) للنص. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/get_ishardunderlineline/)() | يحدّد ما إذا كان نمط التسطير له خصائص [LineFormat](../../aspose.slides/lineformat/) خاصة أو يرثها من خصائص [LineFormat](../../aspose.slides/lineformat/) للنص. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../../aspose.slides/ibaseportionformat/get_kerningminimalsize/)() | يرجع الحد الأدنى لحجم الخط الذي يجب تشغيل التتبع الحرفي له. **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الأصل. قراءة **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/ibaseportionformat/get_kumimoji/)() | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/ibaseportionformat/get_languageid/)() | يرجع معرف لغة التدقيق. يستخدم للتحقق من الإملاء والقواعد. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/ibaseportionformat/get_latinfont/)() | يرجع معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الأصل. اقرأ [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ibaseportionformat/get_lineformat/)() | يرجع خصائص [LineFormat](../../aspose.slides/lineformat/) لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/ibaseportionformat/get_normaliseheight/)() | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/ibaseportionformat/get_proofdisabled/)() | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_Spacing](../../aspose.slides/ibaseportionformat/get_spacing/)() | يرجع زيادة التباعد بين الحروف. **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الأصل. قراءة **float**. |
| virtual **bool** [get_SpellCheck](../../aspose.slides/ibaseportionformat/get_spellcheck/)() | يحصل على قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلاً لجزء النص. عندما تكون الخاصية false يتم إيقاف فحص الإملاء لعناصر النص. عندما تكون true يُسمح بالتدقيق. القيمة الافتراضية هي **false**. |
| virtual [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/ibaseportionformat/get_strikethroughtype/)() | يرجع نوع الخط عبر النص. لا يتم تطبيق الوراثة. اقرأ [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/ibaseportionformat/get_symbolfont/)() | يرجع معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الأصل. اقرأ [IFontData](../../aspose.slides/ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/ibaseportionformat/get_textcaptype/)() | يرجع نوع تحويل الحروف للنص. لا يتم تطبيق الوراثة. اقرأ [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/ibaseportionformat/get_underlinefillformat/)() | يرجع خصائص خط التسطير [FillFormat](../../aspose.slides/fillformat/). لا يتم تطبيق الوراثة. قراءة فقط [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/ibaseportionformat/get_underlinelineformat/)() | يرجع خصائص [LineFormat](../../aspose.slides/lineformat/) المستخدمة لتحديد حدود خط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [ILineFormat](../../aspose.slides/ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلاً للنوع الموضح بـ targetType. تناظر معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالإشارة كائن نوع قيم بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشترك بقيمة محددة. |
| virtual void [set_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | يضبط معرف لغة بديلة. اكتب [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../../aspose.slides/ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | يضبط معلومات خط النص المعقد. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الأصل. اكتب [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_EastAsianFont](../../aspose.slides/ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | يضبط معلومات خط شرق آسيوي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الأصل. اكتب [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_Escapement](../../aspose.slides/ibaseportionformat/set_escapement/)(**float**) | يضبط النص العلوي أو السفلي. القيمة من -100% (سفلي) إلى 100% (علوي). **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الأصل. اكتب **float**. |
| virtual void [set_FontBold](../../aspose.slides/ibaseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontHeight](../../aspose.slides/ibaseportionformat/set_fontheight/)(**float**) | يضبط ارتفاع الخط للجزء. **std::numeric_limits<float>::quiet_NaN()** تعني أن الارتفاع غير معرف ويجب وراثته من الأصل. اكتب **float**. |
| virtual void [set_FontItalic](../../aspose.slides/ibaseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان الخط مائلاً. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontUnderline](../../aspose.slides/ibaseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) | يضبط نوع تسطير النص. لا يتم تطبيق الوراثة. اكتب [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان نمط التسطير له خصائص [FillFormat](../../aspose.slides/fillformat/) خاصة أو يرثها من خصائص [FillFormat](../../aspose.slides/fillformat/) للنص. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان نمط التسطير له خصائص [LineFormat](../../aspose.slides/lineformat/) خاصة أو يرثها من خصائص [LineFormat](../../aspose.slides/lineformat/) للنص. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_KerningMinimalSize](../../aspose.slides/ibaseportionformat/set_kerningminimalsize/)(**float**) | يضبط الحد الأدنى لحجم الخط الذي يجب تشغيل التتبع الحرفي له. **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الأصل. اكتب **float**. |
| virtual void [set_Kumimoji](../../aspose.slides/ibaseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_LanguageId](../../aspose.slides/ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | يضبط معرف لغة التدقيق. يستخدم للتحقق من الإملاء والقواعد. اكتب [System::String](../../system/string/). |
| virtual void [set_LatinFont](../../aspose.slides/ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | يضبط معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الأصل. اكتب [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_NormaliseHeight](../../aspose.slides/ibaseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_ProofDisabled](../../aspose.slides/ibaseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Spacing](../../aspose.slides/ibaseportionformat/set_spacing/)(**float**) | يضبط زيادة التباعد بين الحروف. **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الأصل. اكتب **float**. |
| virtual void [set_SpellCheck](../../aspose.slides/ibaseportionformat/set_spellcheck/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلاً لجزء النص. عندما تكون الخاصية false يتم إيقاف فحص الإملاء لعناصر النص. عندما تكون true يُسمح بالتدقيق. القيمة الافتراضية هي **false**. |
| virtual void [set_StrikethroughType](../../aspose.slides/ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) | يضبط نوع الخط عبر النص. لا يتم تطبيق الوراثة. اكتب [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| virtual void [set_SymbolFont](../../aspose.slides/ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | يضبط معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الأصل. اكتب [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_TextCapType](../../aspose.slides/ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) | يضبط نوع تحويل الحروف للنص. لا يتم تطبيق الوراثة. اكتب [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n على مؤشر ضعيف (بدلاً من مشترك). يسمح بتغيير المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد الإشارة المشترك ويعيد قيمته. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [IBasePortionFormat](../../aspose.slides/ibaseportionformat/)
* مساحة الاسم [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)