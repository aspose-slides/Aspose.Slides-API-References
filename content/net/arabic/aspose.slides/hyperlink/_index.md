---
title: Hyperlink
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل رابطًا تشعبيًا.
type: docs
weight: 5120
url: /ar/aspose.slides/hyperlink/
---
## فئة Hyperlink

يمثل رابطًا تشعبيًا.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | ينشئ كائنًا من رابط تشعبي يشير إلى شريحة معينة. ملاحظة: يجب ربط الرابط التشعبي المنشأ بكائن من نفس العرض، وإلا سيُحفظ الرابط كـ NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | ينشئ كائنًا من رابط تشعبي. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | ينشئ كائنًا من رابط تشعبي باستخدام رابط تشعبي آخر كمصدر، مع تجاوز الخصائص الثانوية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | يرجع رابطًا تشعبيًا ينهي العرض. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | يرجع رابطًا تشعبيًا إلى الشريحة الأولى من العرض. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | يرجع رابطًا تشعبيًا إلى الشريحة الأخيرة من العرض. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | يرجع رابطًا تشعبيًا إلى آخر شريحة عُرضت. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | يرجع رابطًا تشعبيًا خاصًا "تشغيل ملف وسائط". يستخدم في AudioFrame و VideoFrame. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | يرجع رابطًا تشعيبيًا إلى الشريحة التالية. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | يرجع رابطًا تشعبيًا خاصًا "عدم القيام بشيء". قراءة فقط [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | يرجع رابطًا تشعبيًا إلى الشريحة السابقة. قراءة فقط [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | يرجع نوع إجراء الرابط التشعبي. قراءة فقط [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يتيح الحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | يمثل مصدر لون الرابط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة/كتابة [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | يحدد عنوان URL الخارجي. قراءة فقط String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | يمثل رابطًا تشعبيًا يتم تعيينه لهذا الجزء دون مراعاة المحتوى الفعلي للجزء. يتعامل PowerPoint خصيصًا مع الروابط والنص المقابل لها في الجزء. يسمح بإنشاء نص للرابط التشعبي على شكل عنوان URL صالح، مختلف عن العنوان الفعلي للارتباط. في هذه الحالة، عند عرض الرابط في نافذة التحرير، سيتغير ليتطابق مع جزء النص. تمثل هذه الخاصية القيمة الأصلية للرابط التشعبي. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | يحدد ما إذا كان يجب تمييز الرابط التشعبي عند النقر. قراءة/كتابة Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | يحدد ما إذا كان ينبغي إضافة هدف الرابط التشعبي الأصل إلى قائمة الروابط المشاهدة عند استدعائه. قراءة/كتابة Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | يمثل الصوت المشغل للرابط التشعبي. قراءة/كتابة [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الرابط التشعبي. قراءة/كتابة Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | يرجع الإطار داخل مجموعة إطارات HTML الأصلية لهدف الرابط التشعبي الأصلي عندما يكون موجودًا. قراءة/كتابة String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | إذا كان الرابط التشعبي يستهدف شريحة محددة، يرجع هذه الشريحة. قراءة فقط [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | يرجع السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالرابط التشعبي الأصلي. قراءة/كتابة String. |

## الدوال

| الاسم | الوصف |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | يحدد ما إذا كان كائني الرابط التشعبي متساويين. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | يحدد ما إذا كان كائني الرابط التشعبي متساويين. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة والهياكل مثل جدول التجزئة. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | يختبر رابطين تشعبيين للتساوي. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | يختبر رابطين تشعبيين لعدم التساوي. |

### انظر أيضًا

* فئة [PVIObject](../pviobject)
* واجهة [IHyperlink](../ihyperlink)
* نطاق الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->