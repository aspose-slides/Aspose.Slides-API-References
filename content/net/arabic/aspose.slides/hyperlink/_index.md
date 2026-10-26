---
title: Hyperlink
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل ارتباطًا تشعبيًا.
type: docs
weight: 5120
url: /ar/aspose.slides/hyperlink/
---
## الفئة Hyperlink

يمثل ارتباطًا تشعبيًا.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## المنشئون

| الاسم | الوصف |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | إنشاء مثال من ارتباط تشعبي يشير إلى شريحة معينة. ملاحظة: يجب تعيين الارتباط التشعبي الذي تم إنشاؤه إلى كائن ما من نفس العرض التقديمي، وإلا سيتم حفظ الرابط كـ NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | إنشاء مثال من ارتباط تشعبي. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | إنشاء مثال من ارتباط تشعبي باستخدام ارتباط تشعبي آخر كمصدر، مع تجاوز الخصائص الثانوية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | إرجاع ارتباط تشعبي ينهي العرض. للقراءة فقط [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | إرجاع ارتباط تشعبي إلى الشريحة الأولى من العرض التقديمي. للقراءة فقط [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | إرجاع ارتباط تشعبي إلى الشريحة الأخيرة من العرض التقديمي. للقراءة فقط [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | إرجاع ارتباط تشعبي إلى آخر شريحة عُرضت. للقراءة فقط [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | إرجاع ارتباط تشعبي خاص "play mediafile". يستخدم في AudioFrame و VideoFrame. للقراءة فقط [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | إرجاع ارتباط تشعبي إلى الشريحة التالية. للقراءة فقط [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | إرجاع ارتباط تشعبي خاص "do nothing". للقراءة فقط [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | إرجاع ارتباط تشعبي إلى الشريحة السابقة. للقراءة فقط [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | إرجاع نوع فعل الارتباط التشعبي. للقراءة فقط [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | السماح بالحصول على واجهة IPresentationComponent الأساسية. للقراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة/كتابة [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | يحدد عنوان URL الخارجي. للقراءة فقط String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء دون اعتبار لمحتوى الجزء الفعلي. يتعامل PowerPoint بشكل خاص مع الروابط والنص المقابل لها في الجزء. يسمح بإنشاء نص للارتباط التشعبي على شكل عنوان URL صالح، مختلف عن العنوان الحقيقي للربط. في هذه الحالة، عند عرض الرابط في نافذة التحرير، سيتغير ليتطابق مع نص الجزء. تمثل هذه الخاصية القيمة الأصلية للارتباط التشعبي. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. قراءة/كتابة Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | يحدد ما إذا كان هدف الارتباط التشعبي الأصلي يجب إضافته إلى قائمة الروابط المشاهدة عند تنفيذه. قراءة/كتابة Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | يمثل الصوت المشغَل للارتباط التشعبي. قراءة/كتابة [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة/كتابة Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | إرجاع الإطار داخل مجموعة إطارات HTML الأصلية لهدف الارتباط التشعبي الأصلي عندما يكون موجودًا. قراءة/كتابة String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | إذا كان الارتباط التشعبي يستهدف شريحة معينة، يرجع هذه الشريحة. للقراءة فقط [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | إرجاع السلسلة التي قد تُعرض في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. قراءة/كتابة String. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | يحدد ما إذا كانت مثيلتي الارتباط التشعبي متساويتين. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | يحدد ما إذا كانت مثيلتي الارتباط التشعبي متساويتين. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة والهياكل البيانية مثل جدول التجزئة. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | يفحص تساوي ارتباطين تشعبيين. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | يفحص عدم تساوي ارتباطين تشعبيين. |

### انظر أيضا

* الفئة [PVIObject](../pviobject)
* الواجهة [IHyperlink](../ihyperlink)
* نطاق الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->