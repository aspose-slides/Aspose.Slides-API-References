---
title: IBasePortionFormat
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس IPortionFormatEffectiveData./iportionformateffectivedata جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 5310
url: /ar/aspose.slides/ibaseportionformat/
---
## واجهة IBasePortionFormat

تحتوي هذه الفئة على خصائص تنسيق جزء النص. على عكس [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

```csharp
public interface IBasePortionFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | إرجاع أو تعيين معرف لغة بديلة. قراءة/كتابة String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | إرجاع أو تعيين معلومات خط النص المعقد. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | إرجاع أو تعيين معلومات خط شرق آسيا. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | إرجاع خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | إرجاع أو تعيين نص فوقي أو تحتي. القيمة من -100% (تحتي) إلى 100% (فوقي). **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | إرجاع خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | تحديد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | إرجاع أو تعيين ارتفاع الخط لجزء. **float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من الـ Master. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | تحديد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | إرجاع أو تعيين نوع تسطير النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | إرجاع اللون المستخدم لتظليل النص. لا يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | تحديد ما إذا كان نمط التسطير له خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | تحديد ما إذا كان نمط التسطير له خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | إرجاع أو تعيين الحد الأدنى لحجم الخط الذي يُفعل له الضبط (kerning). **float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | تحديد ما إذا كان يجب على الأرقام تجاهل تنسيق النص العمودي الخاص بلغات الشرق. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | إرجاع أو تعيين معرف لغة التدقيق. يستخدم لتصحيح الإملاء والنحو. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | إرجاع أو تعيين معلومات خط اللاتينية. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | إرجاع خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | تحديد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | تحديد ما إذا كان لا ينبغي تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | إرجاع أو تعيين زيادة التباعد بين الأحرف. **float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | إرجاع أو تعيين قيمة تشير إلى ما إذا كان تدقيق الإملاء ممكّنًا لجزء النص. عند تعيين هذه الخاصية إلى false، يتم إيقاف تدقيق الإملاء لعناصر النص. عند تعيينها إلى true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | إرجاع أو تعيين نوع الشطب للنص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | إرجاع أو تعيين معلومات الخط الرمزي. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | إرجاع أو تعيين نوع كتابة النص (capitalization). لا يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | إرجاع خصائص FillFormat لخط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |

### ملاحظات

يتم استخدام هذه الفئة لإرجاع وتعديل خصائص تنسيق جزء النص المحدد للجزء المعين. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرفة".

للحصول على قيم معلمات التنسيق الفعلية بما في ذلك الموروثة، يجب عليك استخدام طريقة [`GetEffective`](../iportionformat/geteffective) التي تُعيد مثالًا من نوع [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### انظر أيضًا

* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->