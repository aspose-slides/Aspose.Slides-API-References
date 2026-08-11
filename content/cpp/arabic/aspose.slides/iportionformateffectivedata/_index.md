---
title: IPortionFormatEffectiveData
second_title: مرجع API لـ Aspose.Slides للغة C++
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق الجزء النصي الفعَّال.
type: docs
weight: 3342
url: /ar/aspose.slides/iportionformateffectivedata/
---
## IPortionFormatEffectiveData فئة

كائن غير قابل للتغيير يحتوي على خصائص تنسيق الجزء النصي الفعّال.

```cpp
class IPortionFormatEffectiveData : public virtual Aspose::Slides::IBasePortionFormatEffectiveData
```

## الطرق

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطة عائمة على نمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساوياً لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطة عائمة على نمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساوياً لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformateffectivedata/get_alternativelanguageid/)() | يرجع معرف لغة بديلة. قراءة فقط [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | يرجع معرف الإشارة المرجعية. قراءة فقط [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformateffectivedata/get_complexscriptfont/)() | يرجع معلومات خط النص المركب. قراءة فقط [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformateffectivedata/get_eastasianfont/)() | يرجع معلومات خط شرق آسيا. قراءة فقط [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](../ibaseportionformateffectivedata/get_effectformat/)() | يرجع خصائص النص [EffectFormat](../effectformat/). قراءة فقط [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](../ibaseportionformateffectivedata/get_escapement/)() | يرجع النص مرتفع أو منخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). قراءة فقط **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](../ibaseportionformateffectivedata/get_fillformat/)() | يرجع خصائص النص [FillFormat](../fillformat/). قراءة فقط [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](../ibaseportionformateffectivedata/get_fontbold/)() | يحدد ما إذا كان الخط عريضاً. قراءة فقط **bool**. |
| virtual **float** [get_FontHeight](../ibaseportionformateffectivedata/get_fontheight/)() | يرجع ارتفاع الخط للجزء النصي، بالنقاط. قراءة فقط **float**. |
| virtual **bool** [get_FontItalic](../ibaseportionformateffectivedata/get_fontitalic/)() | يحدد ما إذا كان الخط مائلاً. قراءة فقط **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformateffectivedata/get_fontunderline/)() | يرجع نوع تسطير النص. قراءة فقط [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](../ibaseportionformateffectivedata/get_highlightcolor/)() | يرجع اللون المستخدم لتظليل النص. قراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() | يرجع الرابط التشعبي المحدد للنقر بالفأرة. قراءة فقط [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() | يرجع الرابط التشعبي المحدد عند مرور الفأرة. قراءة فقط [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsHardUnderlineFill](../ibaseportionformateffectivedata/get_ishardunderlinefill/)() | يحدد ما إذا كان نمط التسطير يمتلك خصائص [FillFormat](../fillformat/) الخاصة به أو يرثها من خصائص [FillFormat](../fillformat/) للنص. قراءة فقط **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](../ibaseportionformateffectivedata/get_ishardunderlineline/)() | يحدد ما إذا كان نمط التسطير يمتلك خصائص [LineFormat](../lineformat/) الخاصة به أو يرثها من خصائص [LineFormat](../lineformat/) للنص. قراءة فقط **bool**. |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformateffectivedata/get_kerningminimalsize/)() | يرجع الحد الأدنى لحجم الخط الذي يُفعل عنده التشخيص (Kerning). قراءة فقط **float**. |
| virtual **bool** [get_Kumimoji](../ibaseportionformateffectivedata/get_kumimoji/)() | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. قراءة فقط **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformateffectivedata/get_languageid/)() | يرجع معرف لغة. قراءة فقط [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformateffectivedata/get_latinfont/)() | يرجع معلومات خط اللاتينية. قراءة فقط [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](../ibaseportionformateffectivedata/get_lineformat/)() | يرجع خصائص [LineFormat](../lineformat/) لتحديد النص. قراءة فقط [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](../ibaseportionformateffectivedata/get_normaliseheight/)() | يحدد ما إذا كان يجب تطبيع ارتفاع النص. قراءة فقط **bool**. |
| virtual **bool** [get_ProofDisabled](../ibaseportionformateffectivedata/get_proofdisabled/)() | يحدد ما إذا كان لا ينبغي تدقيق النص. قراءة فقط **bool**. |
| virtual **bool** [get_SmartTagClean](../ibaseportionformateffectivedata/get_smarttagclean/)() | يحدد ما إذا كان يجب مسح العلامة الذكية. قراءة فقط **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformateffectivedata/get_spacing/)() | يرجع زيادة التباعد بين الأحرف، بالنقاط. قراءة فقط **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformateffectivedata/get_strikethroughtype/)() | يرجع نوع الشطب للنص. قراءة فقط [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformateffectivedata/get_symbolfont/)() | يرجع معلومات الخط الرمزي. قراءة فقط [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformateffectivedata/get_textcaptype/)() | يرجع نوع تحويل الأحرف في النص. قراءة فقط [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](../ibaseportionformateffectivedata/get_underlinefillformat/)() | يرجع خصائص خط التسطير [FillFormat](../fillformat/). قراءة فقط [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](../ibaseportionformateffectivedata/get_underlinelineformat/)() | يرجع خصائص [LineFormat](../lineformat/) المستخدمة لتحديد خط التسطير. قراءة فقط [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المراجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مشابهة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن التجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مشابهة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نسخة مشابهة لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مشابهة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مشابهة لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء القفل في بيان C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## ملاحظات

يُستخدم هذا الواجهة مع الواجهة [IPortionFormat](../iportionformat/) لإرجاع قيم التنسيق الفعّال مع تطبيق الوراثة.

## انظر أيضاً

* فئة [IBasePortionFormatEffectiveData](../ibaseportionformateffectivedata/)
* مساحة الأسماء [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)