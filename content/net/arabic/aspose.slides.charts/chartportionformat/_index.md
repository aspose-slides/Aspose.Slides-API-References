---
title: ChartPortionFormat
second_title: Aspose.Sildes لـ .NET مرجع API
description: هذه الفئة تحتوي على خصائص تنسيق جزء الرسم البياني المستخدمة في المخططات. على عكس IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 1440
url: /ar/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat فئة

هذه الفئة تحتوي على خصائص تنسيق جزء الرسم البياني المستخدمة في المخططات. على عكس [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | إرجاع أو تعيين معرف لغة بديلة. قراءة/كتابة String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يسمح بالحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | إرجاع أو تعيين معلومات خط النص المعقد. يعني Null أن الخط غير معرف ويجب وراثته من القالب الأساسي. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | إرجاع أو تعيين معلومات خط شرق آسيا. يعني Null أن الخط غير معرف ويجب وراثته من القالب الأساسي. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | إرجاع خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | إرجاع أو تعيين النص المرتفع أو النص السفلي. القيمة من -100% (سفلي) إلى 100% (علوي). **float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب الأساسي. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | إرجاع خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | يحدد ما إذا كان الخط غامقًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | إرجاع أو تعيين ارتفاع الخط لجزء. **float.NaN** يعني أن الارتفاع غير محدد ويجب وراثته من القالب الأساسي. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | إرجاع أو تعيين نوع تحت خط النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | إرجاع اللون المستخدم لتظليل النص. لا يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | يحدد ما إذا كان نمط الخط السفلي لديه خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | يحدد ما إذا كان نمط الخط السفلي لديه خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | إرجاع أو تعيين الحد الأدنى لحجم الخط الذي يتم تشغيل التعديل الحرفي (kerning) من أجله. **float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب الأساسي. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص بلغات الشرق. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | إرجاع أو تعيين معرف لغة التدقيق. يُستخدم لتدقيق الإملاء والقواعد. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | إرجاع أو تعيين معلومات خط اللاتينية. يعني Null أن الخط غير معرف ويجب وراثته من القالب الأساسي. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | إرجاع خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | إرجاع أو تعيين زيادة تباعد الأحرف. **float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب الأساسي. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | الحصول أو تعيين قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعَّلًا لجزء النص. عندما تُعيّن هذه الخاصية إلى false، تُقمع فحوصات الإملاء لعناصر النص. عندما تُعيّن إلى true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | إرجاع أو تعيين نوع الشطب للنص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | إرجاع أو تعيين معلومات الخط الرمزي. يعني Null أن الخط غير معرف ويجب وراثته من القالب الأساسي. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | إرجاع أو تعيين نوع تحويل النص إلى أحرف كبيرة/صغيرة. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | إرجاع خصائص FillFormat لخط الخط السفلي. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | إرجاع خصائص LineFormat المستخدمة لتحديد إطار خط الخط السفلي. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن مع الكائن المحدد. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | إرجاع قيمة التجزئة. |

### ملاحظات

يتم استخدام هذه الفئة لإرجاع وتعديل خصائص تنسيق جزء النص المحدد. وهذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذلك في معظم الحالات ستحصل على قيم تعني "غير محدد".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [`GetEffective`](../../aspose.slides/portionformat/geteffective) التي تُرجع مثيلًا من [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### انظر أيضاً

* فئة [BasePortionFormat](../../aspose.slides/baseportionformat)
* واجهة [IChartPortionFormat](../ichartportionformat)
* نطاق [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->