---
title: BasePortionFormat
second_title: Aspose.Sildes لـ .NET مرجع API
description: خصائص تنسيق جزء النص الشائعة.
type: docs
weight: 970
url: /ar/aspose.slides/baseportionformat/
---
## BasePortionFormat فئة

خصائص تنسيق الجزء النصي المشتركة.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | إرجاع أو تعيين معرف لغة بديلة. قراءة/كتابة String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يسمح بالحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | إرجاع أو تعيين معلومات خط النص المعقد. Null يعني أن الخط غير معرف ويجب وراثته من القالب الرئيسي. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | إرجاع أو تعيين معلومات خط شرق آسيا. Null يعني أن الخط غير معرف ويجب وراثته من القالب الرئيسي. قراءة/كتابة [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | إرجاع خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | إرجاع أو تعيين نص فوق أو تحت النص. القيمة من -100% (تحت النص) إلى 100% (فوق النص). **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب الرئيسي. قراءة/كتابة Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | إرجاع خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | تحديد ما إذا كان الخط عريضاً. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | إرجاع أو تعيين ارتفاع خط الجزء. **float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من القالب الرئيسي. قراءة/كتابة Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | تحديد ما إذا كان الخط مائلاً. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | إرجاع أو تعيين نوع تسطير النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | إرجاع اللون المستخدم لتظليل النص. لا يتم تطبيق الوراثة. قراءة فقط [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | تحديد ما إذا كان نمط التسطير يحتوي على خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | تحديد ما إذا كان نمط التسطير يحتوي على خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | إرجاع أو تعيين الحد الأدنى لحجم الخط، الذي يجب تمكين تعديل التباعد له. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب الرئيسي. قراءة/كتابة Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | تحديد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص بلغات الشرق. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | إرجاع أو تعيين معرف لغة التدقيق. يُستخدم للتحقق من الإملاء والقواعد. قراءة/كتابة String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | إرجاع أو تعيين معلومات خط اللاتينية. Null يعني أن الخط غير معرف ويجب وراثته من القالب الرئيسي. قراءة/كتابة [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | إرجاع خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | تحديد ما إذا كان يجب توحيد ارتفاع النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | تحديد ما إذا كان يجب عدم تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | إرجاع أو تعيين زيادة المسافة بين الأحرف. **float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من القالب الرئيسي. قراءة/كتابة Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | الحصول أو تعيين قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلاً للجزء النصي. عندما تكون هذه الخاصية مضبوطة إلى false، يتم قمع فحص الإملاء لعناصر النص. عندما تكون مضبوطة إلى true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | إرجاع أو تعيين نوع الخط عبر للنص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | إرجاع أو تعيين معلومات الخط الرمزي. Null يعني أن الخط غير معرف ويجب وراثته من القالب الرئيسي. قراءة/كتابة [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | إرجاع أو تعيين نوع كتابة النص. لا يتم تطبيق الوراثة. قراءة/كتابة [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | إرجاع خصائص FillFormat لخط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [`ILineFormat`](../ilineformat). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن مع الكائن المحدد. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | إرجاع رمز التجزئة. |

### انظر أيضاً

* فئة [PVIObject](../pviobject)
* واجهة [IBasePortionFormat](../ibaseportionformat)
* نطاق [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->