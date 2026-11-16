---
title: PortionFormat
second_title: Aspose.Sildes لـ .NET مرجع API
description: هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس IPortionFormatEffectiveData./iportionformateffectivedata جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 9510
url: /ar/aspose.slides/portionformat/
---
## PortionFormat فئة

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## المنشئ

| الاسم | الوصف |
| --- | --- |
| [PortionFormat](portionformat)() | يُنشئ مثيلًا جديدًا من الفئة [`PortionFormat`](../portionformat). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | يعيد أو يضبط معرف لغة بديلة. قراءة/كتابة String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يسمح بالحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | يعيد أو يضبط معرف الإشارة المرجعية. قراءة/كتابة String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | يعيد أو يضبط معلومات خط النص المعقد. Null يعني أن الخط غير معرف ويجب وراثته من Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | يعيد أو يضبط معلومات خط شرق آسيوي. Null يعني أن الخط غير معرف ويجب وراثته من Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | يعيد خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | يعيد أو يضبط نصًا فوقيًّا أو تحتيًّا. القيمة من -100٪ (تحتي) إلى 100٪ (فوقي). **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من Master. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | يعيد خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | يحدد ما إذا كان الخط غامقًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | يعيد أو يضبط ارتفاع خط الجزء. **float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من Master. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | يعيد أو يضبط نوع تسطير النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | يعيد اللون المستخدم لتسليط الضوء على النص. لا يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | مدير الروابط التشعبية. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | يعيد أو يضبط الارتباط التشعبي المحدد للتمرير بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أم يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أم يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | يعيد أو يضبط الحد الأدنى لحجم الخط، الذي يتم تشغيل التجانس له. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من Master. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغة الشرقية. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | يعيد أو يضبط معرف لغة التدقيق. يُستخدم لتدقيق الإملاء والقواعد. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | يعيد أو يضبط معلومات الخط اللاتيني. Null يعني أن الخط غير معرف ويجب وراثته من Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | يعيد خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | يحدد ما إذا يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | يحدد ما إذا يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | يحدد ما إذا يجب مسح العلامة الذكية. لا يتم تطبيق الوراثة. قراءة/كتابة Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | يعيد أو يضبط زيادة التباعد بين الأحرف. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من Master. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً للجزء النصي. عندما تكون الخاصية false، يتم كبح فحوصات الإملاء لعناصر النص. عندما تكون true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | يعيد أو يضبط نوع شطب النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | يعيد أو يضبط معلومات الخط الرمزي. Null يعني أن الخط غير معرف ويجب وراثته من Master. قراءة/كتابة [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | يعيد أو يضبط نوع تحويل النص إلى أحرف كبيرة. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | يعيد خصائص FillFormat لخط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | يعيد خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن مع الكائن المحدد. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | يحصل على بيانات تنسيق الجزء الفعّال مع تطبيق الوراثة. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | يعيد رمز التجزئة. |

### ملاحظات

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المعرفة للجزء المحدد. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم معايير التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [`GetEffective`](./geteffective) التي تُعيد مثيلًا من [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### أمثلة

توضح الأمثلة التالية كيفية تعيين الخط اللاتيني لجزء من الفقرة في عرض تقديمي PowerPoint.

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
// تستخدم Aspose.Slides هذه المعرفات الخاصة (مشابهة لتلك المستخدمة في PowerPoint):
// +mn-lt - خط جسم لاتيني (خط لاتيني ثانوي)
// +mj-lt - خط عنوان لاتيني (خط لاتيني رئيسي)
// +mn-ea - خط جسم آسيوي شرقي (خط آسيوي شرقي ثانوي)
// +mj-ea - خط عنوان آسيوي شرقي (خط آسيوي شرقي رئيسي)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### انظر أيضًا

* فئة [BasePortionFormat](../baseportionformat)
* واجهة [IPortionFormat](../iportionformat)
* فضاء الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->