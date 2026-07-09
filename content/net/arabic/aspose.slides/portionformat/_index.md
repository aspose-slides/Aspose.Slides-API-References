---
title: PortionFormat
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس IPortionFormatEffectiveData./iportionformateffectivedata جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 9490
url: /ar/aspose.slides/portionformat/
---
## فئة PortionFormat

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PortionFormat](portionformat)() | يهيئ نسخة جديدة من الفئة [`PortionFormat`](../portionformat). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | يرجع أو يعيّن معرف لغة بديلة. قراءة/كتابة String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يسمح بالحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | يرجع أو يعيّن معرف العلامة المرجعية. قراءة/كتابة String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | يرجع أو يعيّن معلومات خط النص المعقد. القيمة Null تعني أن الخط غير معرف ويجب وراثته من القالب. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | يرجع أو يعيّن معلومات خط اللغة الشرقية الآسيوية. القيمة Null تعني أن الخط غير معرف ويجب وراثته من القالب. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | يرجع خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | يرجع أو يعيّن نص أعلى أو أسفل السطر. القيمة من -100% (أسفل السطر) إلى 100% (أعلى السطر). **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | يرجع خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | يرجع أو يعيّن ارتفاع الخط للجزء. **float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من القالب. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | يرجع أو يعيّن نوع خط تحت النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | يرجع اللون المستخدم لتسليط الضوء على النص. لا يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | يرجع أو يعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | مدير الارتباطات التشعبية. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | يرجع أو يعيّن الارتباط التشعبي المحدد للتمرير فوق الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | يحدد ما إذا كان نمط الخط تحت النص يمتلك خصائص FillFormat خاصة به أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | يحدد ما إذا كان نمط الخط تحت النص يمتلك خصائص LineFormat خاصة به أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | يرجع أو يعيّن الحد الأدنى لحجم الخط الذي يجب تشغيل التتبع الإنسي للخط عنده. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | يحدد ما إذا كانت الأرقام تتجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | يرجع أو يعيّن معرف لغة التدقيق. يستخدم لفحص الإملاء والقواعد. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | يرجع أو يعيّن معلومات خط اللاتينية. القيمة Null تعني أن الخط غير معرف ويجب وراثته من القالب. قراءة/كتابة [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | يرجع خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | يحدد ما إذا كان ارتفاع النص يجب أن يكون طبيعيًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | يحدد ما إذا كان النص لا يجب تدقيقه. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | يحدد ما إذا كان يجب مسح العلامة الذكية. لا يتم تطبيق الوراثة. قراءة/كتابة Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | يرجع أو يعيّن الزيادة في التباعد بين الأحرف. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعّلاً للجزء النصي. عندما تكون الخاصية false، يتم قمع فحوص الإملاء لعناصر النص. عندما تكون true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | يرجع أو يعيّن نوع الخط المشطوب. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | يرجع أو يعيّن معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من القالب. قراءة/كتابة [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | يرجع أو يعيّن نوع تحويل الحروف. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | يرجع خصائص FillFormat لخط السطر تحت النص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | يرجع خصائص LineFormat المستخدمة لتحديد حدود سطر الخط تحت النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن مع الكائن المحدد. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | يحصل على بيانات تنسيق الجزء الفعّال مع تطبيق الوراثة. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | يرجع رمز التجزئة. |

### ملاحظات

تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق جزء النص المحدد. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرفة".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، يجب استخدام طريقة [`GetEffective`](./geteffective) التي تُعيد كائن [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### أمثلة

المثال التالي يوضح كيفية تعيين الخط اللاتيني لجزء فقرة في عرض تقديمي PowerPoint.

```csharp
[C#]
//إنشاء كائن عرض تقديمي يمثل ملف عرض تقديمي
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides يستخدم هذه المعرفات الخاصة (مشابهة لتلك المستخدمة في PowerPoint):
// +mn-lt - خط الجسم اللاتيني (الخط اللاتيني الصغير)
// +mj-lt - خط العنوان اللاتيني (الخط اللاتيني الرئيسي)
// +mn-ea - خط الجسم الشرقي الآسيوي (الخط الشرقي الآسيوي الصغير)
// +mj-ea - خط الجسم الشرقي الآسيوي (الخط الشرقي الآسيوي الصغير)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### انظر أيضًا

* class [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->