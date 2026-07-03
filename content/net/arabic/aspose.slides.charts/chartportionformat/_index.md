---
title: ChartPortionFormat
second_title: Aspose.Sildes لـ .NET مرجع API
description: تحتوي هذه الفئة على خصائص تنسيق جزء المخطط المستخدمة في المخططات. على عكس IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 1430
url: /ar/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat فئة

هذه الفئة تحتوي على خصائص تنسيق جزء المخطط المستخدمة في المخططات. على عكس [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | إرجاع أو تعيين معرف لغة بديلة. قراءة/كتابة String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | السماح بالحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | إرجاع أو تعيين معلومات خط النص المركب. القيمة null تعني أن الخط غير محدد ويجب توريثه من القالب الرئيسي. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | إرجاع أو تعيين معلومات خط شرق أوروبي. القيمة null تعني أن الخط غير محدد ويجب توريثه من القالب الرئيسي. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | إرجاع خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | إرجاع أو تعيين نص مرتفع أو منخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **float.NaN** يعني أن القيمة غير محددة ويجب توريثها من القالب الرئيسي. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | إرجاع خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | تحديد ما إذا كان الخط غامقاً. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | إرجاع أو تعيين ارتفاع الخط لجزء. **float.NaN** يعني أن الارتفاع غير محدد ويجب توريثه من القالب الرئيسي. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | تحديد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | إرجاع أو تعيين نوع تسطير النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | إرجاع اللون المستخدم لتسليط الضوء على النص. لا يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | تحديد ما إذا كان نمط التسطير يمتلك خصائص FillFormat خاصة به أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | تحديد ما إذا كان نمط التسطير يمتلك خصائص LineFormat خاصة به أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | إرجاع أو تعيين الحد الأدنى لحجم الخط الذي يجب تشغيل التتباعد (kerning) له. **float.NaN** يعني أن القيمة غير محددة ويجب توريثها من القالب الرئيسي. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | تحديد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغة الشرقية. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | إرجاع أو تعيين معرف لغة التدقيق. يُستخدم للتحقق من الإملاء والقواعد. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | إرجاع أو تعيين معلومات خط اللاتينية. القيمة null تعني أن الخط غير محدد ويجب توريثه من القالب الرئيسي. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | إرجاع خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | تحديد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | تحديد ما إذا كان ينبغي عدم تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | إرجاع أو تعيين مقدار الزيادة في تباعد الحروف. **float.NaN** يعني أن القيمة غير محددة ويجب توريثها من القالب الرئيسي. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | إرجاع أو تعيين قيمة تشير إلى ما إذا كان تدقيق الإملائي مفعلاً لجزء النص. عندما يتم ضبط هذه الخاصية على false، يتم إلغاء فحص الإملاء لعناصر النص. عندما يتم ضبطها على true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | إرجاع أو تعيين نوع الخط المشطوب للنص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | إرجاع أو تعيين معلومات الخط الرمزي. القيمة null تعني أن الخط غير محدد ويجب توريثه من القالب الرئيسي. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | إرجاع أو تعيين نوع كتابة النص (حروف كبيرة/صغيرة). لا يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | إرجاع خصائص FillFormat لخط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن مع الكائن المحدد. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | إرجاع قيمة التجزئة. |

### ملاحظات

تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق جزء النص المحددة لهذا الجزء. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم معاملات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [`GetEffective`](../../aspose.slides/portionformat/geteffective) التي تُرجع كائن [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### انظر أيضًا

* فئة [BasePortionFormat](../../aspose.slides/baseportionformat)
* واجهة [IChartPortionFormat](../ichartportionformat)
* مساحة اسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->