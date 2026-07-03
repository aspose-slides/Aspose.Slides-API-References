---
title: PortionFormat
second_title: مرجع API Aspose.Sildes لـ .NET
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
| [PortionFormat](portionformat)() | يهيئ مثيلاً جديداً من فئة [`PortionFormat`](../portionformat). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | إرجاع أو ضبط معرف لغة بديلة. قابل للقراءة/الكتابة String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يسمح بالحصول على واجهة IPresentationComponent الأساسية. للقراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | إرجاع أو ضبط معرف الإشارة المرجعية. قابل للقراءة/الكتابة String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | إرجاع أو ضبط معلومات خط النص المعقد. القيمة Null تعني أن الخط غير معرف ويجب وراثته من القالب الرئيسي. قابل للقراءة/الكتابة [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | إرجاع أو ضبط معلومات خط شرق آسيا. القيمة Null تعني أن الخط غير معرف ويجب وراثته من القالب الرئيسي. قابل للقراءة/الكتابة [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | إرجاع خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. للقراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | إرجاع أو ضبط النص كحرف مرتفع أو منخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب الرئيسي. قابل للقراءة/الكتابة Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | إرجاع خصائص FillFormat للنص. لا يتم تطبيق الوراثة. للقراءة فقط [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | يحدد ما إذا كان الخط عريضاً. لا يتم تطبيق الوراثة. قابل للقراءة/الكتابة [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | إرجاع أو ضبط ارتفاع خط الجزء. **float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من القالب الرئيسي. قابل للقراءة/الكتابة Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قابل للقراءة/الكتابة [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | إرجاع أو ضبط نوع التسطير النصي. لا يتم تطبيق الوراثة. قابل للقراءة/الكتابة [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | إرجاع اللون المستخدم لتسليط الضوء على النص. لا يتم تطبيق الوراثة. للقراءة فقط [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | إرجاع أو ضبط الارتباط التشعبي المحدد للنقر بالفأرة. قابل للقراءة/الكتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | مدير الارتباطات التشعبية. للقراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | إرجاع أو ضبط الارتباط التشعبي المحدد عند مرور الفأرة. قابل للقراءة/الكتابة [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | يحدد ما إذا كان نمط التسطير يملك خصائص FillFormat خاصة به أو يرثها من خصائص FillFormat للنص. قابل للقراءة/الكتابة [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | يحدد ما إذا كان نمط التسطير يملك خصائص LineFormat خاصة به أو يرثها من خصائص LineFormat للنص. قابل للقراءة/الكتابة [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | إرجاع أو ضبط الحد الأدنى لحجم الخط الذي يتم فيه تفعيل Kerning. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب الرئيسي. قابل للقراءة/الكتابة Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | يحدد ما إذا كان يجب تجاهل الأرقام لتخطيط النص العمودي الخاص باللغة الشرقية. لا يتم تطبيق الوراثة. قابل للقراءة/الكتابة [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | إرجاع أو ضبط معرف لغة التدقيق. يستخدم لفحص الإملاء والقواعد. قابل للقراءة/الكتابة String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | إرجاع أو ضبط معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير معرف ويجب وراثته من القالب الرئيسي. قابل للقراءة/الكتابة [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | إرجاع خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. للقراءة فقط [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قابل للقراءة/الكتابة [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | يحدد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. قابل للقراءة/الكتابة [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | يحدد ما إذا يجب تنظيف العلامة الذكية. لا يتم تطبيق الوراثة. Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | إرجاع أو ضبط الزيادة في تباعد الأحرف. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب الرئيسي. قابل للقراءة/الكتابة Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | الحصول أو ضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. عندما تُضبط هذه الخاصية إلى false، يُقمع فحص الإملاء لعناصر النص. عندما تُضبط إلى true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | إرجاع أو ضبط نوع الشطب للنص. لا يتم تطبيق الوراثة. قابل للقراءة/الكتابة [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | إرجاع أو ضبط معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب وراثته من القالب الرئيسي. قابل للقراءة/الكتابة [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | إرجاع أو ضبط نوع تحويل الحروف للنص. لا يتم تطبيق الوراثة. قابل للقراءة/الكتابة [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | إرجاع خصائص FillFormat لخط التسطير. لا يتم تطبيق الوراثة. للقراءة فقط [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لا يتم تطبيق الوراثة. للقراءة فقط [`ILineFormat`](../ilineformat). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن بالعنصر المحدد. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | يحصل على بيانات تنسيق الجزء الفعلي مع تطبيق الوراثة. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | إرجاع رمز التجزئة. |

### الملاحظات

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المحددة للجزء المعين. وهذا يعني أنه لا يتم تطبيق الوراثة عند جلب القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرفة".

للحصول على قيم معلمات التنسيق الفعلي بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [`GetEffective`](./geteffective) التي تُعيد مثيلاً من [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### الأمثلة

تُظهر الأمثلة التالية كيفية تعيين الخط اللاتيني لجزء الفقرة في عرض تقديمي PowerPoint.

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
// +mn-lt - خط جسم لاتيني (خط لاتيني أصغر)
// +mj-lt - خط عنوان لاتيني (خط لاتيني رئيسي)
// +mn-ea - خط جسم شرق آسيوي (خط شرق آسيوي أصغر)
// +mj-ea - خط جسم شرق آسيوي (خط شرق آسيوي أصغر)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### انظر أيضاً

* class [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->