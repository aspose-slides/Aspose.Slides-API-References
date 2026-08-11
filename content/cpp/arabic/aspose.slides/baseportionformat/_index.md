---
title: BasePortionFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: خصائص تنسيق جزء النص الشائعة.
type: docs
weight: 144
url: /ar/aspose.slides/baseportionformat/
---
## BasePortionFormat فئة

خصائص تنسيق جزء النص الشائعة.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُconsider قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُconsider قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | إرجاع معرف لغة بديلة. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | إرجاع معلومات خط النص المعقد. يعني Null أن الخط غير معرف ويجب وراثته من الرئيسي. اقرأ [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | إرجاع معلومات خط شرق آسيا. يعني Null أن الخط غير معرف ويجب وراثته من الرئيسي. اقرأ [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | إرجاع خصائص النص [EffectFormat](../effectformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | إرجاع النص الفوقي أو التحتي. القيمة من -100% (تحتي) إلى 100% (فوقي). **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من الرئيسي. قراءة **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | إرجاع خصائص النص [FillFormat](../fillformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | إرجاع ارتفاع الخط لجزء. **std::numeric_limits<float>::quiet_NaN()** يعني أن الارتفاع غير معرف ويجب وراثته من الرئيسي. قراءة **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | إرجاع نوع خط النص المسطر. لا يتم تطبيق الوراثة. اقرأ [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | إرجاع اللون المستخدم لتظليل النص. لا يتم تطبيق الوراثة. للقراءة فقط [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | يحدد ما إذا كان نمط الخط المسطر يمتلك خصائص [FillFormat](../fillformat/) الخاصة به أو يرثها من خصائص [FillFormat](../fillformat/) للنص. اقرأ [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | يحدد ما إذا كان نمط الخط المسطر يمتلك خصائص [LineFormat](../lineformat/) الخاصة به أو يرثها من خصائص [LineFormat](../lineformat/) للنص. اقرأ [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | إرجاع الحد الأدنى لحجم الخط الذي يجب تفعيل التباعد بين الحروف عنده. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من الرئيسي. قراءة **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | يحدد ما إذا كانت الأرقام يجب أن تتجاهل تنسيق النص الرأسي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | إرجاع معرف لغة التدقيق. يُستخدم لتدقيق الإملاء والقواعد. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | إرجاع معلومات الخط اللاتيني. يعني Null أن الخط غير معرف ويجب وراثته من الرئيسي. اقرأ [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | إرجاع خصائص [LineFormat](../lineformat/) لتحديد حدود النص. لا يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | يحدد ما إذا كان ارتفاع النص يجب أن يكون طبيعيًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | إرجاع كائن Parent_Immediate. للقراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | إرجاع [IPresentationComponent](../ipresentationcomponent/) الأب. للقراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | يحدد ما إذا كان النص لا يجب تدقيقه. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | إرجاع زيادة التباعد بين الأحرف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من الرئيسي. قراءة **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | يحصل على قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلاً لجزء النص. عندما تُضبط هذه الخاصية على false، تُقمع عمليات التدقيق الإملائي لعناصر النص. عندما تُضبط على true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | إرجاع نوع الخط المشطوب للنص. لا يتم تطبيق الوراثة. اقرأ [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | إرجاع معلومات الخط الرمزي. يعني Null أن الخط غير معرف ويجب وراثته من الرئيسي. اقرأ [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | إرجاع نوع تحويل النص إلى أحرف كبيرة. لا يتم تطبيق الوراثة. اقرأ [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | إرجاع خصائص خط السطر المسطر [FillFormat](../fillformat/). لا يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | إرجاع خصائص [LineFormat](../lineformat/) المستخدمة لتحديد حدود خط السطر المسطر. لا يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المراجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | إرجاع قيمة التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفيذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | يضبط معرف لغة بديلة. اكتب [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط معلومات خط النص المعقد. يعني Null أن الخط غير معرف ويجب وراثته من الرئيسي. اكتب [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط معلومات خط شرق آسيا. يعني Null أن الخط غير معرف ويجب وراثته من الرئيسي. اكتب [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | يضبط النص الفوقي أو التحتي. القيمة من -100% (تحتي) إلى 100% (فوقي). **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من الرئيسي. اكتب **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | يضبط ارتفاع الخط لجزء. **std::numeric_limits<float>::quiet_NaN()** يعني أن الارتفاع غير معرف ويجب وراثته من الرئيسي. اكتب **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | يضبط نوع الخط المسطر للنص. لا يتم تطبيق الوراثة. اكتب [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان نمط الخط المسطر يمتلك خصائص [FillFormat](../fillformat/) الخاصة به أو يرثها من خصائص [FillFormat](../fillformat/) للنص. اكتب [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان نمط الخط المسطر يمتلك خصائص [LineFormat](../lineformat/) الخاصة به أو يرثها من خصائص [LineFormat](../lineformat/) للنص. اكتب [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | يضبط الحد الأدنى لحجم الخط الذي يجب تفعيل التباعد عنده. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من الرئيسي. اكتب **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كانت الأرقام يجب أن تتجاهل تنسيق النص الرأسي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | يضبط معرف لغة التدقيق. يُستخدم لتدقيق الإملاء والقواعد. اكتب [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط معلومات الخط اللاتيني. يعني Null أن الخط غير معرف ويجب وراثته من الرئيسي. اكتب [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان ارتفاع النص يجب أن يكون طبيعيًا. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان النص لا يجب تدقيقه. لا يتم تطبيق الوراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | يضبط زيادة التباعد بين الأحرف. **std::numeric_limits<float>::quiet_NaN()** يعني أن القيمة غير معرفة ويجب وراثتها من الرئيسي. اكتب **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | يضبط قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلاً لجزء النص. عندما تُضبط هذه الخاصية على false، تُقمع عمليات التدقيق الإملائي لعناصر النص. عندما تُضبط على true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | يضبط نوع الخط المشطوب للنص. لا يتم تطبيق الوراثة. اكتب [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط معلومات الخط الرمزي. يعني Null أن الخط غير معرف ويجب وراثته من الرئيسي. اكتب [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | يضبط نوع تحويل النص إلى أحرف كبيرة. لا يتم تطبيق الوراثة. اكتب [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تعيين الوسيط القالبي رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## راجع أيضًا

* فئة [PVIObject](../pviobject/)
* فئة [IBasePortionFormat](../ibaseportionformat/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)