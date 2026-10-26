---
title: IPortionFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحتوي هذه الفئة على خصائص تنسيق جزء النص. على عكس IPortionFormatEffectiveData، جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 3329
url: /ar/aspose.slides/iportionformat/
---
## IPortionFormat فئة

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [IPortionFormatEffectiveData](../iportionformateffectivedata/)، جميع خصائص هذه الفئة قابلة للكتابة.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | يعيد معرف اللغة البديلة. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | يعيد معرف الإشارة المرجعية. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | يعيد معلومات خط النص المعقد. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب الرئيسي. اقرأ [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | يعيد معلومات خط شرق آسيا. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب الرئيسي. اقرأ [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | يعيد خصائص النص [EffectFormat](../effectformat/). لا يتم تطبيق الوراثة. قراءة فقط [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | يعيد النص المرتفع أو المنخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير محددة ويجب وراثتها من القالب الرئيسي. اقرأ **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | يعيد خصائص النص [FillFormat](../fillformat/). لا يتم تطبيق الوراثة. قراءة فقط [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | يعيد ارتفاع الخط لجزء من النص. **std::numeric_limits<float>::quiet_NaN()** يعني أن الارتفاع غير محدد ويجب وراثته من القالب الرئيسي. اقرأ **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | يعيد نوع تسطير النص. لا يتم تطبيق الوراثة. اقرأ [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | يعيد اللون المستخدم لتظليل النص. لا يتم تطبيق الوراثة. قراءة فقط [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | يعيد الارتباط التشعبي المحدد للنقر بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الروابط التشعبية قراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | يعيد الارتباط التشعبي المحدد للتحويم بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | يحدد ما إذا كان نمط التسطير يمتلك خصائص [FillFormat](../fillformat/) الخاصة أو يرثها من خصائص [FillFormat](../fillformat/) للنص. اقرأ [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | يحدد ما إذا كان نمط التسطير يمتلك خصائص [LineFormat](../lineformat/) الخاصة أو يرثها من خصائص [LineFormat](../lineformat/) للنص. اقرأ [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | يعيد الحد الأدنى لحجم الخط الذي يجب تشغيل الترصيع له. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير محددة ويجب وراثتها من القالب الرئيسي. اقرأ **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | يعيد معرف لغة التدقيق. يُستخدَم للتحقق من الإملاء والقواعد. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | يعيد معلومات خط اللاتينية. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب الرئيسي. اقرأ [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | يعيد خصائص [LineFormat](../lineformat/) لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | يحدد ما إذا كان يجب توحيد ارتفاع النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | يحدد ما إذا كان لا ينبغي تدقيق النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | يحدد ما إذا كان يجب تنظيف العلامة الذكية. لا يتم تطبيق الوراثة. اقرأ **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | يعيد الزيادة في تباعد الأحرف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير محددة ويجب وراثتها من القالب الرئيسي. اقرأ **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | يحصل على قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعّلاً لجزء النص. عندما تُضبط هذه الخاصية على false يتم إلغاء فحص الإملاء للعناصر النصية. عندما تُضبط على true يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | يعيد نوع الخط المشطوب للنص. لا يتم تطبيق الوراثة. اقرأ [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | يعيد معلومات الخط الرمزي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب الرئيسي. اقرأ [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | يعيد نوع كتابة النص بالحروف الكبيرة. لا يتم تطبيق الوراثة. اقرأ [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | يعيد خصائص خط التسطير [FillFormat](../fillformat/). لا يتم تطبيق الوراثة. قراءة فقط [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | يعيد خصائص [LineFormat](../lineformat/) المستخدمة لتحديد حدود خط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد الإشارة المرتبط بالكائن. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | يحصل على بيانات تنسيق الجزء الفعّالة مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ البُنى الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ البُنى الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بواسطة الإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بواسطة الإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالإشارة إلى nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشترك بالقيمة المحددة. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | يضبط معرف اللغة البديلة. اكتب [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | يضبط معرف الإشارة المرجعية. اكتب [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يضبط معلومات خط النص المعقد. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب الرئيسي. اكتب [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يضبط معلومات خط شرق آسيا. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب الرئيسي. اكتب [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | يضبط النص المرتفع أو المنخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير محددة ويجب وراثتها من القالب الرئيسي. اكتب **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | يضبط ارتفاع الخط لجزء من النص. **std::numeric_limits<float>::quiet_NaN()** يعني أن الارتفاع غير محدد ويجب وراثته من القالب الرئيسي. اكتب **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | يضبط نوع تسطير النص. لا يتم تطبيق الوراثة. اكتب [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد للنقر بالفأرة. اكتب [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد للتحويم بالفأرة. اكتب [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان نمط التسطير يمتلك خصائص [FillFormat](../fillformat/) الخاصة أو يرثها من خصائص [FillFormat](../fillformat/) للنص. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان نمط التسطير يمتلك خصائص [LineFormat](../lineformat/) الخاصة أو يرثها من خصائص [LineFormat](../lineformat/) للنص. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | يضبط الحد الأدنى لحجم الخط لتفعيل الترصيع. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير محددة ويجب وراثتها من القالب الرئيسي. اكتب **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | يضبط معرف لغة التدقيق. يُستَخدَم للتحقق من الإملاء والقواعد. اكتب [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يضبط معلومات خط اللاتينية. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب الرئيسي. اكتب [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان يجب توحيد ارتفاع النص. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان لا ينبغي تدقيق النص. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | يحدد ما إذا كان يجب تنظيف العلامة الذكية. لا يتم تطبيق الوراثة. اكتب **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | يضبط الزيادة في تباعد الأحرف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير محددة ويجب وراثتها من القالب الرئيسي. اكتب **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعّلاً لجزء النص. عندما تُضبط هذه الخاصية على false يتم إلغاء فحص الإملاء للعناصر النصية. عندما تُضبط على true يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | يضبط نوع الخط المشطوب للنص. لا يتم تطبيق الوراثة. اكتب [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يضبط معلومات الخط الرمزي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب الرئيسي. اكتب [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | يضبط نوع كتابة النص بالحروف الكبيرة. لا يتم تطبيق الوراثة. اكتب [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد الإشارة المشترك. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء القفل في جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## ملاحظات

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المعروفة للجزء المحدد. يعني ذلك أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير مُحددة".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [IPortionFormat::GetEffective](./geteffective/) التي تُعيد كائن [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## انظر أيضاً

* الفئة [IBasePortionFormat](../ibaseportionformat/)
* الفئة [IHyperlinkContainer](../ihyperlinkcontainer/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)