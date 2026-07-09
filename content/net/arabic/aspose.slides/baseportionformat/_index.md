---
title: BasePortionFormat
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: خصائص تنسيق جزء النص العامة.
type: docs
weight: 970
url: /ar/aspose.slides/baseportionformat/
---
## BasePortionFormat فئة

خصائص تنسيق جزء النص العامة.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | يرجع أو يعيّن معرف لغة بديلة. قراءة/كتابة String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يتيح الحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | يرجع أو يعيّن معلومات خط النص المعقد. يعني Null أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | يرجع أو يعيّن معلومات خط اللغة الشرقية الآسيوية. يعني Null أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | يرجع خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | يرجع أو يعيّن النص المرتفع أو المنخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | يرجع خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | يرجع أو يعيّن ارتفاع خط الجزء. **float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من الـ Master. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | يرجع أو يعيّن نوع تحت خط النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | يرجع اللون المستخدم لتظليل النص. لا يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | يحدد ما إذا كان نمط الخط السفلي يحتوي على خصائص FillFormat خاصة به أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | يحدد ما إذا كان نمط الخط السفلي يحتوي على خصائص LineFormat خاصة به أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | يرجع أو يعيّن الحد الأدنى لحجم الخط، الذي يجب تشغيل التعديل الحرفي (kerning) عنده. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | يحدد ما إذا كانت الأرقام يجب أن تتجاهل تنسيق النص العمودي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | يرجع أو يعيّن معرف لغة التدقيق. يستخدم لتدقيق الإملاء والنحو. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | يرجع أو يعيّن معلومات خط اللاتينية. يعني Null أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | يرجع خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | يحدد ما إذا كان ارتفاع النص يجب أن يُصبح طبيعيًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | يرجع أو يعيّن زيادة الفاصل بين الأحرف. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعّلاً لجزء النص. عندما تكون هذه الخاصية `false`، يتم إلغاء تدقيق الإملاء لعناصر النص. عندما تكون `true`، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | يرجع أو يعيّن نوع الشطب للنص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | يرجع أو يعيّن معلومات الخط الرمزي. يعني Null أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | يرجع أو يعيّن نوع كتابة النص (الأحرف الكبيرة/الصغيرة). لا يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | يرجع خصائص FillFormat لخط تحت الخط. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | يرجع خصائص LineFormat المستخدمة لتحديد حدود خط تحت الخط. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن مع الكائن المحدد. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | يرجع قيمة التجزئة. |

### انظر أيضًا

* فئة [PVIObject](../pviobject)
* واجهة [IBasePortionFormat](../ibaseportionformat)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->