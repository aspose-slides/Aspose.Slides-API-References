---
title: ChartPortionFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحتوي هذه الفئة على خصائص تنسيق جزء المخطط المستخدمة في المخططات. على عكس IPortionFormatEffectiveData، جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 261
url: /ar/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat فئة


تحتوي هذه الفئة على خصائص تنسيق جزء المخطط المستخدمة في المخططات. على عكس [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/)، جميع خصائص هذه الفئة قابلة للكتابة.

```cpp
class ChartPortionFormat : public Aspose::Slides::BasePortionFormat,
                           public Aspose::Slides::Charts::IChartPortionFormat
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة على نمط C# حيث يعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة على نمط C# حيث يعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/baseportionformat/get_alternativelanguageid/)() override | يعيد معرف لغة بديلة. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/baseportionformat/get_complexscriptfont/)() override | يعيد معلومات خط النص المعقَّد. يعني Null أن الخط غير معرف ويجب أن يُورث من القالب الرئيسي. اقرأ [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/baseportionformat/get_eastasianfont/)() override | يعيد معلومات خط شرق آسيا. يعني Null أن الخط غير معرف ويجب أن يُورث من القالب الرئيسي. اقرأ [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/baseportionformat/get_effectformat/)() override | يعيد خصائص النص [EffectFormat](../../aspose.slides/effectformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IEffectFormat](../../aspose.slides/ieffectformat/). |
| **float** [get_Escapement](../../aspose.slides/baseportionformat/get_escapement/)() override | يعيد النص الأعلى أو الأدنى. القيمة من -100% (نص أدنى) إلى 100% (نص أعلى). **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب أن تُورث من القالب الرئيسي. اقرأ **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/baseportionformat/get_fillformat/)() override | يعيد خصائص النص [FillFormat](../../aspose.slides/fillformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../../aspose.slides/ifillformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/baseportionformat/get_fontbold/)() override | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_FontHeight](../../aspose.slides/baseportionformat/get_fontheight/)() override | يعيد ارتفاع الخط لجزء. **std::numeric_limits<float>::quiet_NaN()** يعني أن الارتفاع غير معرف ويجب أن يُورث من القالب الرئيسي. اقرأ **float**. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/baseportionformat/get_fontitalic/)() override | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/baseportionformat/get_fontunderline/)() override | يعيد نوع تسطير النص. لا يتم تطبيق الوراثة. اقرأ [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/baseportionformat/get_highlightcolor/)() override | يعيد اللون المستخدم لتسليط الضوء على نص. لا يتم تطبيق الوراثة. للقراءة فقط [IColorFormat](../../aspose.slides/icolorformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/baseportionformat/get_ishardunderlinefill/)() override | يحدد ما إذا كان نمط التسطير لديه خصائص [FillFormat](../../aspose.slides/fillformat/) خاصة أو يورثها من خصائص [FillFormat](../../aspose.slides/fillformat/) للنص. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/baseportionformat/get_ishardunderlineline/)() override | يحدد ما إذا كان نمط التسطير لديه خصائص [LineFormat](../../aspose.slides/lineformat/) خاصة أو يورثها من خصائص [LineFormat](../../aspose.slides/lineformat/) للنص. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_KerningMinimalSize](../../aspose.slides/baseportionformat/get_kerningminimalsize/)() override | يعيد الحد الأدنى لحجم الخط الذي ينبغي تفعيل الضبط بين الحروف له. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب أن تُورث من القالب الرئيسي. اقرأ **float**. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/baseportionformat/get_kumimoji/)() override | يحدد ما إذا كان يجب على الأرقام تجاهل تنسيق النص العمودي الخاص بلغات الشرق. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/baseportionformat/get_languageid/)() override | يعيد معرف لغة التدقيق. تُستخدم لتصحيح الإملاء والقواعد. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/baseportionformat/get_latinfont/)() override | يعيد معلومات خط اللاتينية. يعني Null أن الخط غير معرف ويجب أن يُورث من القالب الرئيسي. اقرأ [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/baseportionformat/get_lineformat/)() override | يعيد خصائص [LineFormat](../../aspose.slides/lineformat/) لتحديد حدود النص. لا يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../../aspose.slides/ilineformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/baseportionformat/get_normaliseheight/)() override | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | يعيد كائن Parent_Immediate. للقراءة فقط [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | يعيد الأصل [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). للقراءة فقط [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/baseportionformat/get_proofdisabled/)() override | يحدد ما إذا يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_Spacing](../../aspose.slides/baseportionformat/get_spacing/)() override | يعيد زيادة التباعد بين الأحرف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب أن تُورث من القالب الرئيسي. اقرأ **float**. |
| **bool** [get_SpellCheck](../../aspose.slides/baseportionformat/get_spellcheck/)() override | يحصل على قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعَّلًا لجزء النص. عندما تُضبط هذه الخاصية إلى false، تُحجب فحوصات الإملاء لعناصر النص. عندما تُضبط إلى true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي **false**. |
| [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/baseportionformat/get_strikethroughtype/)() override | يعيد نوع الشط المرسوم على النص. لا يتم تطبيق الوراثة. اقرأ [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/baseportionformat/get_symbolfont/)() override | يعيد معلومات الخط الرمزي. يعني Null أن الخط غير معرف ويجب أن يُورث من القالب الرئيسي. اقرأ [IFontData](../../aspose.slides/ifontdata/). |
| [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/baseportionformat/get_textcaptype/)() override | يعيد نوع تحويل الأحرف للنص. لا يتم تطبيق الوراثة. اقرأ [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/baseportionformat/get_underlinefillformat/)() override | يعيد خصائص خط التسطير [FillFormat](../../aspose.slides/fillformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/baseportionformat/get_underlinelineformat/)() override | يعيد خصائص [LineFormat](../../aspose.slides/lineformat/) المستخدمة لتحديد خط التسطير. لا يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../../aspose.slides/ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعات المرتبط بالكائن. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | يعيد رمز التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويمكن من نسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن من نسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AlternativeLanguageId](../../aspose.slides/baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | يضبط معرف لغة بديلة. اكتب [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../../aspose.slides/baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | يضبط معلومات خط النص المعقَّد. يعني Null أن الخط غير معرف ويجب أن يُورث من القالب الرئيسي. اكتب [IFontData](../../aspose.slides/ifontdata/). |
| void [set_EastAsianFont](../../aspose.slides/baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | يضبط معلومات خط شرق آسيا. يعني Null أن الخط غير معرف ويجب أن يُورث من القالب الرئيسي. اكتب [IFontData](../../aspose.slides/ifontdata/). |
| void [set_Escapement](../../aspose.slides/baseportionformat/set_escapement/)(**float**) override | يضبط النص الأعلى أو الأدنى. القيمة من -100% (نص أدنى) إلى 100% (نص أعلى). **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب أن تُورث من القالب الرئيسي. اكتب **float**. |
| void [set_FontBold](../../aspose.slides/baseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) override | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_FontHeight](../../aspose.slides/baseportionformat/set_fontheight/)(**float**) override | يضبط ارتفاع الخط لجزء. **std::numeric_limits<float>::quiet_NaN()** يعني أن الارتفاع غير معرف ويجب أن يُورث من القالب الرئيسي. اكتب **float**. |
| void [set_FontItalic](../../aspose.slides/baseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) override | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_FontUnderline](../../aspose.slides/baseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) override | يضبط نوع تسطير النص. لا يتم تطبيق الوراثة. اكتب [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| void [set_IsHardUnderlineFill](../../aspose.slides/baseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) override | يحدد ما إذا كان نمط التسطير لديه خصائص [FillFormat](../../aspose.slides/fillformat/) خاصة أو يورثها من خصائص [FillFormat](../../aspose.slides/fillformat/) للنص. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_IsHardUnderlineLine](../../aspose.slides/baseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) override | يحدد ما إذا كان نمط التسطير لديه خصائص [LineFormat](../../aspose.slides/lineformat/) خاصة أو يورثها من خصائص [LineFormat](../../aspose.slides/lineformat/) للنص. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_KerningMinimalSize](../../aspose.slides/baseportionformat/set_kerningminimalsize/)(**float**) override | يضبط الحد الأدنى لحجم الخط الذي يُفعَّل له الضبط بين الحروف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب أن تُورث من القالب الرئيسي. اكتب **float**. |
| void [set_Kumimoji](../../aspose.slides/baseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) override | يحدد ما إذا كان يجب على الأرقام تجاهل تنسيق النص العمودي الخاص بلغات الشرق. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_LanguageId](../../aspose.slides/baseportionformat/set_languageid/)([System::String](../../system/string/)) override | يضبط معرف لغة التدقيق. تُستخدم لتصحيح الإملاء والقواعد. اكتب [System::String](../../system/string/). |
| void [set_LatinFont](../../aspose.slides/baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | يضبط معلومات خط اللاتينية. يعني Null أن الخط غير معرف ويجب أن يُورث من القالب الرئيسي. اكتب [IFontData](../../aspose.slides/ifontdata/). |
| void [set_NormaliseHeight](../../aspose.slides/baseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) override | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_ProofDisabled](../../aspose.slides/baseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) override | يحدد ما إذا يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Spacing](../../aspose.slides/baseportionformat/set_spacing/)(**float**) override | يضبط زيادة التباعد بين الأحرف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب أن تُورث من القالب الرئيسي. اكتب **float**. |
| void [set_SpellCheck](../../aspose.slides/baseportionformat/set_spellcheck/)(**bool**) override | يضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعَّلًا لجزء النص. عندما تُضبط هذه الخاصية إلى false، تُحجب فحوصات الإملاء لعناصر النص. عندما تُضبط إلى true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي **false**. |
| void [set_StrikethroughType](../../aspose.slides/baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) override | يضبط نوع الشط المرسوم على النص. لا يتم تطبيق الوراثة. اكتب [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| void [set_SymbolFont](../../aspose.slides/baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | يضبط معلومات الخط الرمزي. يعني Null أن الخط غير معرف ويجب أن يُورث من القالب الرئيسي. اكتب [IFontData](../../aspose.slides/ifontdata/). |
| void [set_TextCapType](../../aspose.slides/baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) override | يضبط نوع تحويل الأحرف للنص. لا يتم تطبيق الوراثة. اكتب [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبية رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | * يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## ملاحظات

تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق جزء النص المعرفة للجزء المحدد. يعني ذلك أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرّفة".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [PortionFormat::GetEffective](../../aspose.slides/portionformat/geteffective/) التي تُعيد مثيل [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/).

## انظر أيضًا

* الفئة [BasePortionFormat](../../aspose.slides/baseportionformat/)
* الفئة [IChartPortionFormat](../ichartportionformat/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)