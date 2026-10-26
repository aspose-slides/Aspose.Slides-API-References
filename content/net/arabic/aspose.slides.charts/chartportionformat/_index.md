---
title: ChartPortionFormat
second_title: مرجع API لـ Aspose.Sildes على .NET
description: هذه الفئة تحتوي على خصائص تنسيق جزء المخطط المستخدمة في المخططات. على عكس IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 1430
url: /ar/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat فئة

هذه الفئة تحتوي على خصائص تنسيق أجزاء المخطط المستخدمة في المخططات. على عكس [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | إرجاع أو تعيين معرف لغة بديلة. قراءة/كتابة String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يسمح بالحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | إرجاع أو تعيين معلومات خط النص المعقد. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | إرجاع أو تعيين معلومات خط اللغة الشرقية الآسيوية. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | إرجاع خصائص EffectFormat للنص. لم يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | إرجاع أو تعيين النص المرفوع أو النص السفلي. القيمة من -100% (نص سفلي) إلى 100% (نص مرفوع). **float.NaN** يعني أن القيمة غير معرف ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | إرجاع خصائص FillFormat للنص. لم يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | يحدد ما إذا كان الخط عريضًا. لم يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | إرجاع أو تعيين ارتفاع خط الجزء. **float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من الـ Master. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | يحدد ما إذا كان الخط مائلًا. لم يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | إرجاع أو تعيين نوع تسطير النص. لم يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | إرجاع اللون المستخدم لتظليل النص. لم يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat خاصة به أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat خاصة به أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | إرجاع أو تعيين الحد الأدنى لحجم الخط الذي يُفعل فيه التراكب الحرفي. **float.NaN** يعني أن القيمة غير معرف ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | يحدد ما إذا كانت الأرقام يجب أن تتجاهل تخطيط النص الرأسي الخاص باللغة الشرقية. لم يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | إرجاع أو تعيين معرف لغة التدقيق. يُستخدم لتدقيق الإملاء والنحو. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | إرجاع أو تعيين معلومات خط اللغة اللاتينية. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | إرجاع خصائص LineFormat لتحديد حدود النص. لم يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | يحدد ما إذا كان ارتفاع النص يجب أن يكون موحدًا. لم يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | يحدد ما إذا كان النص لا يجب تدقيقه. لم يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | إرجاع أو تعيين زيادة التباعد بين الأحرف. **float.NaN** يعني أن القيمة غير معرف ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | إرجاع أو تعيين قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلاً لجزء النص. عندما تكون هذه الخاصية مساوية لـ false، يتم كبح فحوصات الإملاء لعناصر النص. عندما تكون مساوية لـ true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | إرجاع أو تعيين نوع الضربة عبر النص. لم يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | إرجاع أو تعيين معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | إرجاع أو تعيين نوع التحويل إلى أحرف كبيرة أو صغيرة للنص. لم يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | إرجاع خصائص FillFormat لخط التسطير. لم يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لم يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن مع الكائن المحدد. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | إرجاع رمز التجزئة. |

### ملاحظات

هذه الفئة تُستخدم لإرجاع ومعالجة خصائص تنسيق جزء النص المعرفة للجزء المحدد. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم المعلمات الفعلية للتنسيق بما في ذلك القيم الموروثة، تحتاج إلى استخدام طريقة [`GetEffective`](../../aspose.slides/portionformat/geteffective) التي تُرجع كائن [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### انظر أيضًا

* فئة [BasePortionFormat](../../aspose.slides/baseportionformat)
* واجهة [IChartPortionFormat](../ichartportionformat)
* مساحة الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->