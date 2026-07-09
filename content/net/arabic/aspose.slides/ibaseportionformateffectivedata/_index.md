---
title: IBasePortionFormatEffectiveData
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: واجهة أساسية للكائنات غير القابلة للتغيير التي تحتوي على خصائص تنسيق جزء النص الفعلي.
type: docs
weight: 5320
url: /ar/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData واجهة

الواجهة الأساسية للكائنات غير القابلة للتغيير التي تحتوي على خصائص تنسيق جزء النص الفعلي.

```csharp
public interface IBasePortionFormatEffectiveData
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | يرجع معرّف لغة بديلة. قراءة فقط String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | يرجع معلومات خط النص المعقّد. قراءة فقط [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | يرجع معلومات خط شرق آسيا. قراءة فقط [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | يرجع خصائص EffectFormat للنص. قراءة فقط [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | يرجع النص أعلى السطر أو أسفل السطر. القيمة من -100٪ (أسفل السطر) إلى 100٪ (أعلى السطر). قراءة فقط Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | يرجع خصائص FillFormat للنص. قراءة فقط [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | يحدد ما إذا كان الخط عريضًا. قراءة فقط Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | يرجع ارتفاع الخط لجزء النص، بالنقاط. قراءة فقط Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | يحدد ما إذا كان الخط مائلًا. قراءة فقط Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | يرجع نوع توضيح النص. قراءة فقط [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | يرجع اللون المستخدم لتظليل النص. قراءة فقط Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. قراءة فقط Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. قراءة فقط Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | يرجع الحد الأدنى لحجم الخط الذي يجب تشغيل تعديل المسافات (kerning) من أجله. قراءة فقط Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص بلغات الشرق. قراءة فقط Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | يرجع معرّف لغة. قراءة فقط String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | يرجع معلومات خط اللاتينية. قراءة فقط [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | يرجع خصائص LineFormat لتحديد حدود النص. قراءة فقط [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | يحدد ما إذا كان يجب تطبيع ارتفاع النص. قراءة فقط Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | يحدد ما إذا لا ينبغي تدقيق النص. قراءة فقط Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | يحدد ما إذا كان يجب مسح العلامة الذكية. قراءة فقط Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | يرجع الزيادة في مسافة الحروف، بالنقاط. قراءة فقط Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | يرجع نوع الشطب للنص. قراءة فقط [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | يرجع معلومات الخط الرمزي. قراءة فقط [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | يرجع نوع كتابة النص بالحروف الكبيرة. قراءة فقط [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | يرجع خصائص FillFormat لخط التسطير. قراءة فقط [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | يرجع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. قراءة فقط [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### انظر أيضًا

* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->