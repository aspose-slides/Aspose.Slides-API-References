---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes لـ .NET مرجع API
description: واجهة أساسية للكائنات غير القابلة للتغيير التي تحتوي على خصائص تنسيق جزء النص الفعلي.
type: docs
weight: 5320
url: /ar/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData واجهة

واجهة أساسية للكائنات غير القابلة للتغيير التي تحتوي على خصائص تنسيق جزء النص الفعلي.

```csharp
public interface IBasePortionFormatEffectiveData
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | يرجع معرف لغة بديلة. للقراءة فقط String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | يرجع معلومات خط النص المعقد. للقراءة فقط [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | يرجع معلومات خط شرق آسيوي. للقراءة فقط [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | يرجع خصائص EffectFormat للنص. للقراءة فقط [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | يرجع نص القيد العلوي أو السفلي. القيمة من -100٪ (سفلي) إلى 100٪ (علوي). للقراءة فقط Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | يرجع خصائص FillFormat للنص. للقراءة فقط [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | يحدد ما إذا كان الخط عريضًا. للقراءة فقط Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | يرجع ارتفاع خط جزء النص، بالنقاط. للقراءة فقط Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | يحدد ما إذا كان الخط مائلًا. للقراءة فقط Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | يرجع نوع تحت خط النص. للقراءة فقط [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | يرجع اللون المستخدم لتسليط الضوء على النص. للقراءة فقط Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | يحدد ما إذا كان نمط تحت الخط يملك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. للقراءة فقط Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | يحدد ما إذا كان نمط تحت الخط يملك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. للقراءة فقط Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | يرجع الحد الأدنى لحجم الخط الذي يجب تشغيل التباعد الحرفي (kerning) عنده. للقراءة فقط Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. للقراءة فقط Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | يرجع معرف لغة. للقراءة فقط String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | يرجع معلومات خط اللاتينية. للقراءة فقط [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | يرجع خصائص LineFormat لتحديد حدود النص. للقراءة فقط [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | يحدد ما إذا كان يجب تطبيع ارتفاع النص. للقراءة فقط Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | يحدد ما إذا لا ينبغي تدقيق النص إملائيًا. للقراءة فقط Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | يحدد ما إذا يجب مسح العلامة الذكية. للقراءة فقط Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | يرجع زيادة التباعد بين الحروف، بالنقاط. للقراءة فقط Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | يرجع نوع الشطب للنص. للقراءة فقط [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | يرجع معلومات الخط الرمزي. للقراءة فقط [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | يرجع نوع تكبير الأحرف للنص. للقراءة فقط [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | يرجع خصائص FillFormat لخط تحت الخط. للقراءة فقط [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | يرجع خصائص LineFormat المستخدمة لتحديد حدود خط تحت الخط. للقراءة فقط [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### انظر أيضًا

* النطاق [Aspose.Slides](../../aspose.slides)
* التجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->