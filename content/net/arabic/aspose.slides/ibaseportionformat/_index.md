---
title: IBasePortionFormat
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: تحتوي هذه الفئة على خصائص تنسيق جزء النص. على عكس IPortionFormatEffectiveData./iportionformateffectivedata جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 5330
url: /ar/aspose.slides/ibaseportionformat/
---
## واجهة IBasePortionFormat

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

```csharp
public interface IBasePortionFormat
```

## الخصائص

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | تعيد أو تعين معرف لغة بديلة. قراءة/كتابة String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | تعيد أو تعين معلومات خط النص المعقّد. Null يعني أن الخط غير محدد ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | تعيد أو تعين معلومات خط شرق آسيا. Null يعني أن الخط غير محدد ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | تعيد خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | تعيد أو تعين النص المترفع أو النص المنخفض. القيمة من -100% (منخفض) إلى 100% (مترفع). **float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | تعيد خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | تحدد ما إذا كان الخط عريضاً (bold). لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | تعيد أو تعين ارتفاع الخط للجزء. **float.NaN** يعني أن الارتفاع غير محدد ويجب وراثته من الـ Master. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | تحدد ما إذا كان الخط مائلًا (itallic). لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | تعيد أو تعين نوع تحته الخط للنص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | تعيد اللون المستخدم لتسليط الضوء على النص. لا يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | تحدد ما إذا كان نمط التحته الخط يمتلك خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | تحدد ما إذا كان نمط التحته الخط يمتلك خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | تعيد أو تعين الحد الأدنى لحجم الخط الذي يجب تشغيل التتبع له (kerning). **float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | تحدد ما إذا كان يجب تجاهل التخطيط الرأسي للنص للغات الشرقية الخاصة. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | تعيد أو تعين معرف لغة التدقيق. تُستخدم للتحقق من الإملاء والقواعد. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | تعيد أو تعين معلومات الخط اللاتيني. Null يعني أن الخط غير محدد ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | تعيد خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | تحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | تحدد ما إذا كان لا يجب تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | تعيد أو تعين زيادة الفاصل بين الأحرف. **float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من الـ Master. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | تحصل أو تعين قيمة تشير إلى ما إذا كان تمكين التدقيق الإملائي للجزء النصي. عندما تُضبط هذه الخاصية إلى false، يتم قمع فحص الإملاء لعناصر النص. عندما تُضبط إلى true، يُسمح بفحص الإملاء. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | تعيد أو تعين نوع الشطب (strikethrough) للنص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | تعيد أو تعين معلومات الخط الرمزي. Null يعني أن الخط غير محدد ويجب وراثته من الـ Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | تعيد أو تعين نوع تحويل النص إلى حروف كبيرة. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | تعيد خصائص FillFormat لخط التحته. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | تعيد خصائص LineFormat المستخدمة لتحديد حدود خط التحته. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |

### ملاحظات

تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق جزء النص المعرفة للجزء المحدد. هذا يعني أنه لا يتم تطبيق الوراثة عند جلب القيم لذا في معظم الحالات ستحصل على قيم تعني "غير معرفة".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [`GetEffective`](../iportionformat/geteffective) التي تُعيد مثيل [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### راجع أيضًا

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->