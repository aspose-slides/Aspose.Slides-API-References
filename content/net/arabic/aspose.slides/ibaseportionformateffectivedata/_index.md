---
title: IBasePortionFormatEffectiveData
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: واجهة أساسية للكائنات غير القابلة للتغيير التي تحتوي على خصائص تنسيق الجزء النصي الفعّال.
type: docs
weight: 5340
url: /ar/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData واجهة

Base interface for immutable objects which contain effective text portion formatting properties.

```csharp
public interface IBasePortionFormatEffectiveData
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | يعيد معرف اللغة البديلة. للقراءة فقط String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | يعيد معلومات خط النص المعقد. للقراءة فقط [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | يعيد معلومات خط شرق آسيا. للقراءة فقط [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | يعيد خصائص EffectFormat للنص. للقراءة فقط [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | يعيد النص العلوي أو السفلي. القيمة من -100% (سفلي) إلى 100% (علوي). للقراءة فقط Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | يعيد خصائص FillFormat للنص. للقراءة فقط [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | يحدد ما إذا كان الخط عريضًا. للقراءة فقط Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | يعيد ارتفاع الخط لجزء النص، بالنقاط. للقراءة فقط Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | يحدد ما إذا كان الخط مائلًا. للقراءة فقط Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | يعيد نوع الخط السفلي للنص. للقراءة فقط [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | يعيد اللون المستخدم لتظليل النص. للقراءة فقط Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | يحدد ما إذا كان نمط الخط السفلي يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. للقراءة فقط Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | يحدد ما إذا كان نمط الخط السفلي يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. للقراءة فقط Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | يعيد الحد الأدنى لحجم الخط الذي يجب تشغيل التراصف له. للقراءة فقط Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. للقراءة فقط Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | يعيد معرف اللغة. للقراءة فقط String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | يعيد معلومات خط اللاتينية. للقراءة فقط [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | يعيد خصائص LineFormat لتحديد حدود النص. للقراءة فقط [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | يحدد ما إذا كان يجب تطبيع ارتفاع النص. للقراءة فقط Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | يحدد ما إذا كان لا يجب تدقيق النص. للقراءة فقط Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | يحدد ما إذا كان يجب تنظيف العلامة الذكية. للقراءة فقط Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | يعيد مقدار زيادة التباعد بين الأحرف، بالنقاط. للقراءة فقط Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | يعيد نوع الخط المشطوب للنص. للقراءة فقط [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | يعيد معلومات الخط الرمزي. للقراءة فقط [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | يعيد نوع كتابة النص بالحروف الكبيرة. للقراءة فقط [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | يعيد خصائص FillFormat لخط الخط السفلي. للقراءة فقط [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | يعيد خصائص LineFormat المستخدمة لتحديد حدود خط الخط السفلي. للقراءة فقط [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### انظر أيضا

* النطاق [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->