---
title: PortionFormat
second_title: مرجع API لـ Aspose.Slides للـ C++
description: تحتوي هذه الفئة على خصائص تنسيق جزء النص. على عكس IPortionFormatEffectiveData، جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 4811
url: /ar/aspose.slides/portionformat/
---
## PortionFormat فئة


هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [IPortionFormatEffectiveData](../iportionformateffectivedata/)، جميع خصائص هذه الفئة قابلة للكتابة.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين بالرغم من أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين بالرغم من أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | يرجع معرف لغة بديلة. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | يرجع معرف الإشارة المرجعية. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | يرجع معلومات خط النص المعقد. يعني Null أن الخط غير معرف ويجب وراثته من القالب. اقرأ [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | يرجع معلومات خط شرق آسيا. يعني Null أن الخط غير معرف ويجب وراثته من القالب. اقرأ [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | يرجع خصائص النص [EffectFormat](../effectformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | يرجع النص كارتفاع فوق السطر أو تحته. القيمة من -100٪ (تحته) إلى 100٪ (فوق السطر). **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. للقراءة **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | يرجع خصائص النص [FillFormat](../fillformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | يرجع ارتفاع الخط لجزء. **std::numeric_limits<float>::quiet_NaN()** يعني أن الارتفاع غير معرف ويجب وراثته من القالب. للقراءة **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | يرجع نوع تحت خط النص. لا يتم تطبيق الوراثة. اقرأ [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | يرجع اللون المستخدم لتظليل النص. لا يتم تطبيق الوراثة. للقراءة فقط [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | يرجع الارتباط التشعبي المحدد للنقر بالماوس. اقرأ [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | مدير الروابط التشعبية. للقراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | يرجع الارتباط التشعبي المحدد عند مرور الفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | يحدد ما إذا كان نمط الخط السفلي يملك خصائص [FillFormat](../fillformat/) الخاصة أو يرثها من خصائص [FillFormat](../fillformat/) للنص. اقرأ [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | يحدد ما إذا كان نمط الخط السفلي يملك خصائص [LineFormat](../lineformat/) الخاصة أو يرثها من خصائص [LineFormat](../lineformat/) للنص. اقرأ [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | يرجع الحد الأدنى لحجم الخط الذي ينبغي تشغيل القرب بين الحروف عنده. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. للقراءة **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص بلغات الشرق. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | يرجع معرف لغة التدقيق. يستخدم للتحقق من الإملاء والقواعد. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | يرجع معلومات خط اللاتينية. يعني Null أن الخط غير معرف ويجب وراثته من القالب. اقرأ [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | يرجع خصائص [LineFormat](../lineformat/) لتحديد حدود النص. لا يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | يرجع كائن Parent_Immediate. للقراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يرجع الأصل [IPresentationComponent](../ipresentationcomponent/). للقراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | يحدد ما إذا كان ينبغي مسح العلامة الذكية. لا يتم تطبيق الوراثة. للقراءة **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | يرجع زيادة تباعد الأحرف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. للقراءة **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | يحصل على قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. عندما تُضبط هذه الخاصية إلى false، يتم قمع فحص الإملاء لعناصر النص. عندما تُضبط إلى true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | يرجع نوع الخط المشطوب للنص. لا يتم تطبيق الوراثة. اقرأ [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | يرجع معلومات الخط الرمزي. يعني Null أن الخط غير معرف ويجب وراثته من القالب. اقرأ [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | يرجع نوع تحويل النص إلى أحرف كبيرة. لا يتم تطبيق الوراثة. اقرأ [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | يرجع خصائص سطر الخط السفلي [FillFormat](../fillformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | يرجع خصائص [LineFormat](../lineformat/) المستخدمة لتحديد حدود سطر الخط السفلي. لا يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | يحصل على بيانات تنسيق الجزء الفعّال مع تطبيق الوراثة. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | يرجع رمز التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. التناظر لدالة C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا لنوع يصفه targetType. التناظر لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | إنشاء كائن. يتهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يتهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
|  [PortionFormat](./portionformat/)() | يمهّد مثيلًا جديدًا للفئة [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن عنصر قيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد مرات الإشارة المشتركة بقيمة محددة. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | يضبط معرف لغة بديلة. اكتب [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | يضبط معرف الإشارة المرجعية. اكتب [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط معلومات خط النص المعقد. يعني Null أن الخط غير معرف ويجب وراثته من القالب. اكتب [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط معلومات خط شرق آسيا. يعني Null أن الخط غير معرف ويجب وراثته من القالب. اكتب [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | يضبط النص كارتفاع فوق السطر أو تحته. القيمة من -100٪ (تحته) إلى 100٪ (فوق السطر). **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. اكتب **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | يضبط ارتفاع الخط لجزء. **std::numeric_limits<float>::quiet_NaN()** يعني أن الارتفاع غير معرف ويجب وراثته من القالب. اكتب **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | يضبط نوع تحت خط النص. لا يتم تطبيق الوراثة. اكتب [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي المحدد للنقر بالماوس. اكتب [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي المحدد عند مرور الفأرة. اكتب [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان نمط الخط السفلي يملك خصائص [FillFormat](../fillformat/) الخاصة أو يرثها من خصائص [FillFormat](../fillformat/) للنص. اكتب [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان نمط الخط السفلي يملك خصائص [LineFormat](../lineformat/) الخاصة أو يرثها من خصائص [LineFormat](../lineformat/) للنص. اكتب [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | يضبط الحد الأدنى لحجم الخط الذي ينبغي تشغيل القرب بين الحروف عنده. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. اكتب **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص بلغات الشرق. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | يضبط معرف لغة التدقيق. يستخدم للتحقق من الإملاء والقواعد. اكتب [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط معلومات خط اللاتينية. يعني Null أن الخط غير معرف ويجب وراثته من القالب. اكتب [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | يحدد ما إذا كان ينبغي مسح العلامة الذكية. لا يتم تطبيق الوراثة. اكتب **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | يضبط زيادة تباعد الأحرف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. اكتب **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | يضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. عندما تُضبط هذه الخاصية إلى false، يتم قمع فحص الإملاء لعناصر النص. عندما تُضبط إلى true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | يضبط نوع الخط المشطوب للنص. لا يتم تطبيق الوراثة. اكتب [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط معلومات الخط الرمزي. يعني Null أن الخط غير معرف ويجب وراثته من القالب. اكتب [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | يضبط نوع تحويل النص إلى أحرف كبيرة. لا يتم تطبيق الوراثة. اكتب [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيطة القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ قفل عبارة C# lock() لإلغاء القفل. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## ملاحظات


تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق جزء النص المحددة للجزء المعين. يعني ذلك أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في الغالب ستحصل على قيم تعني "غير معرّفة".

من أجل الحصول على قيم معلمات التنسيق الفعّالة بما يشمل الموروثة، تحتاج إلى استعمال طريقة [PortionFormat::GetEffective](./geteffective/) التي تُعيد مثالًا من نوع [IPortionFormatEffectiveData](../iportionformateffectivedata/).

الأمثلة التالية توضح لك كيفية تعيين الخط اللاتيني لجزء [Paragraph](../paragraph/) في PowerPoint [Presentation](../presentation/).

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides يستخدم هذه المعرفات الخاصة (مشابهة لتلك المستخدمة في PowerPoint):
// +mn-lt - خط جسم لاتيني (الخط اللاتيني الصغير)
// +mj-lt - خط عنوان لاتيني (الخط اللاتيني الرئيسي)
// +mn-ea - خط جسم شرق آسيوي (الخط الشرق آسيوي الصغير)
// +mj-ea - خط جسم شرق آسيوي (الخط الشرق آسيوي الصغير)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## انظر أيضًا

* الفئة [BasePortionFormat](../baseportionformat/)
* الفئة [IPortionFormat](../iportionformat/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)