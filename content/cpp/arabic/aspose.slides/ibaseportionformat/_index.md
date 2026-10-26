---
title: IBasePortionFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحتوي هذه الفئة على خصائص تنسيق الجزء النصي. على عكس IPortionFormatEffectiveData، جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 1457
url: /ar/aspose.slides/ibaseportionformat/
---
## فئة IBasePortionFormat

هذه الفئة تحتوي على خصائص تنسيق الجزء النصي. على عكس [IPortionFormatEffectiveData](../iportionformateffectivedata/)، جميع خصائص هذه الفئة قابلة للكتابة.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد [Object.Equals](../../system/object/equals/) الخاصة بـ C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن IEC 60559:1989 تنص على أن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن IEC 60559:1989 تنص على أن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | يُعيد معرف لغة بديلة. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | يُعيد معلومات خط النص المعقد. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. اقرأ [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | يُعيد معلومات خط شرق آسيا. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. اقرأ [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | يُعيد خصائص [EffectFormat](../effectformat/) النص. لا يتم تطبيق الوراثة. قراءة فقط [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | يُعيد النص المرتفع أو المنخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | يُعيد خصائص [FillFormat](../fillformat/) النص. لا يتم تطبيق الوراثة. قراءة فقط [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | يحدد ما إذا كان الخط غامقًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | يُعيد ارتفاع الخط للجزء. **std::numeric_limits<float>::quiet_NaN()** تعني أن الارتفاع غير معرفة ويجب وراثته من الـ Master. قراءة **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | يُعيد نوع تسطير النص. لا يتم تطبيق الوراثة. اقرأ [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | يُعيد اللون المستخدم لتظليل النص. لا يتم تطبيق الوراثة. قراءة فقط [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | يحدد ما إذا كان نمط التسطير له خصائص [FillFormat](../fillformat/) خاصة أو يرثها من خصائص [FillFormat](../fillformat/) النص. اقرأ [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | يحدد ما إذا كان نمط التسطير له خصائص [LineFormat](../lineformat/) خاصة أو يرثها من خصائص [LineFormat](../lineformat/) النص. اقرأ [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | يُعيد الحد الأدنى لحجم الخط الذي يجب تمكين التشكيل فيه. **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص بلغة الشرق. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | يُعيد معرف لغة التدقيق. يُستخدم لتدقيق الإملاء والقواعد. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | يُعيد معلومات خط اللاتينية. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. اقرأ [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | يُعيد خصائص [LineFormat](../lineformat/) لتحديد حد النص. لا يتم تطبيق الوراثة. قراءة فقط [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. اقرأ [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | يُعيد الزيادة في تباعد الأحرف. **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | يحصل على قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً للجزء النصي. عندما تُضبط هذه الخاصية على false، تُقمع عمليات تدقيق الإملاء لعناصر النص. عندما تُضبط على true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | يُعيد نوع الخط المشطوب. لا يتم تطبيق الوراثة. اقرأ [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | يُعيد معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. اقرأ [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | يُعيد نوع تحويل الحروف في النص. لا يتم تطبيق الوراثة. اقرأ [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | يُعيد خصائص خط التسطير [FillFormat](../fillformat/). لا يتم تطبيق الوراثة. قراءة فقط [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | يُعيد خصائص [LineFormat](../lineformat/) المستخدمة لتحديد خط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المراجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | يُنفّذ تعليمة C# lock() للقفل. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية من الفئات. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية من الفئات. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | يضع معرف لغة بديلة. كتابة [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يضع معلومات خط النص المعقد. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. كتابة [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يضع معلومات خط شرق آسيا. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. كتابة [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | يضع النص المرتفع أو المنخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. كتابة **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان الخط غامقًا. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | يضع ارتفاع الخط للجزء. **std::numeric_limits<float>::quiet_NaN()** تعني أن الارتفاع غير معرفة ويجب وراثته من الـ Master. كتابة **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | يضع نوع تسطير النص. لا يتم تطبيق الوراثة. كتابة [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان نمط التسطير له خصائص [FillFormat](../fillformat/) خاصة أو يرثها من خصائص [FillFormat](../fillformat/) النص. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان نمط التسطير له خصائص [LineFormat](../lineformat/) خاصة أو يرثها من خصائص [LineFormat](../lineformat/) النص. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | يضع الحد الأدنى لحجم الخط الذي يجب تمكين التشكيل فيه. **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. كتابة **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص بلغة الشرق. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | يضع معرف لغة التدقيق. يُستخدم لتدقيق الإملاء والقواعد. كتابة [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يضع معلومات خط اللاتينية. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. كتابة [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | يضع الزيادة في تباعد الأحرف. **std::numeric_limits<float>::quiet_NaN()** تعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. كتابة **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً للجزء النصي. عندما تُضبط هذه الخاصية على false، تُقمع عمليات تدقيق الإملاء لعناصر النص. عندما تُضبط على true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | يضع نوع الخط المشطوب. لا يتم تطبيق الوراثة. كتابة [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يضع معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. كتابة [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | يضع نوع تحويل الحروف في النص. لا يتم تطبيق الوراثة. كتابة [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ تعليمة C# lock() لإلغاء القفل. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## ملاحظات

تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق الجزء النصي المحددة للجزء المعين. وهذا يعني أن لا وراثة تُطبّق عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم المعلمات التنسيقية الفعّالة بما في ذلك المتوارثة، تحتاج إلى استخدام طريقة [IPortionFormat::GetEffective](../iportionformat/geteffective/) التي تُعيد نسخة [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## انظر أيضاً

* الفئة [Object](../../system/object/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)