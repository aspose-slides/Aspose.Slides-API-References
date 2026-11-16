---
title: Hyperlink
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل ارتباطًا تشعبيًا.
type: docs
weight: 5140
url: /ar/aspose.slides/hyperlink/
---
## فئة Hyperlink

يمثل ارتباطًا تشعبيًا.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | يقوم بإنشاء مثيل من ارتباط تشعبي يشير إلى شريحة معينة. ملاحظة: يجب تعيين الارتباط التشعبي المنشأ إلى كائن ما من نفس العرض التقديمي، وإلا سيُحفظ الرابط كـ NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | يقوم بإنشاء مثيل من ارتباط تشعبي. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | يقوم بإنشاء مثيل من ارتباط تشعبي باستخدام ارتباط تشعبي آخر كمصدر، متجاوزًا الخصائص الثانوية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | يعيد ارتباطًا تشعبيًا ينهي العرض. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | يعيد ارتباطًا تشعبيًا إلى الشريحة الأولى في العرض التقديمي. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | يعيد ارتباطًا تشعبيًا إلى الشريحة الأخيرة في العرض التقديمي. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | يعيد ارتباطًا تشعبيًا إلى الشريحة التي عرضت آخرًا. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | يعيد ارتباطًا تشعبيًا خاصًا "play mediafile". يُستخدم في AudioFrame و VideoFrame. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | يعيد ارتباطًا تشعبيًا إلى الشريحة التالية. قراءة فقط [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | يعيد ارتباطًا تشعبيًا خاصًا "do nothing". قراءة فقط [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | يعيد ارتباطًا تشعبيًا إلى الشريحة السابقة. قراءة فقط [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | يعيد نوع إجراء الارتباط التشعبي. قراءة فقط [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يسمح بالحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة/كتابة [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | يحدد عنوان URL الخارجي. قراءة فقط String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء بغض النظر عن المحتوى الفعلي للجزء. يتصرف PowerPoint بطريقة خاصة للروابط والنص المقابل لها في الجزء. يسمح بإنشاء نص للارتباط التشعبي على شكل عنوان URL صالح، مختلف عن العنوان الحقيقي للرابط. في هذه الحالة، عند عرض الرابط في نافذة التحرير، سيتغير ليتطابق مع نص الجزء. هذه الخاصية تمثل القيمة الأصلية للارتباط التشعبي. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. قراءة/كتابة Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | يحدد ما إذا كان ينبغي إضافة هدف الارتباط التشعبي الأصل إلى قائمة الروابط التي تم عرضها عند تنفيذه. قراءة/كتابة Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | يمثل الصوت المشغل للارتباط التشعبي. قراءة/كتابة [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة/كتابة Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | يعيد الإطار داخل مجموعة إطارات HTML الأصلية لهدف الارتباط التشعبي الأصل عندما يكون موجودًا. قراءة/كتابة String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | إذا كان الارتباط التشعبي يستهدف شريحة معينة، يعيد هذه الشريحة. قراءة فقط [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصل. قراءة/كتابة String. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | يحدد ما إذا كانت مثيلات الارتباط التشعبي الاثنين متساوية. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | يحدد ما إذا كانت مثيلات الارتباط التشعبي الاثنين متساوية. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | يفحص ما إذا كان الارتباطان التشابيان متساويين. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | يفحص ما إذا كان الارتباطان التشابيان غير متساويين. |

### راجع أيضًا

* فئة [PVIObject](../pviobject)
* واجهة [IHyperlink](../ihyperlink)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->