---
title: Slide
second_title: Aspose.Sildes لواجهة برمجة التطبيقات .NET
description: يمثل شريحة في عرض تقديمي.
type: docs
weight: 9960
url: /ar/aspose.slides/slide/
---
## Slide فئة

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | تُرجع خلفية الشريحة. قراءة فقط [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | تُرجع مجموعة عناصر تحكم ActiveX على الشريحة. قراءة فقط [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | تُرجع البيانات المخصصة للشريحة. قراءة فقط [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | تُرجع مدير الترويسة والتذييل للشريحة. قراءة فقط [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قراءة/كتابة منطقية. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | يُوفر وصولًا سهلًا إلى الروابط التشعبية المحتواة. قراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | تُرجع أو تعين شريحة layout slide للشريحة الحالية. قراءة/كتابة [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | تُرجع أو تعين اسم الشريحة. قراءة/كتابة String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | يسمح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها. قراءة فقط [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | تُرجع الواجهة IPresentation. قراءة فقط [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | تُرجع أشكال الشريحة. قراءة فقط [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | يحدد ما إذا كانت الأشكال على الشريحة الرئيسة يجب أن تُظهر على الشرائح أم لا. قراءة/كتابة منطقية. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | تُرجع معرف الشريحة. قراءة فقط UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | تُرجع رقم الشريحة. فهرس الشريحة في مجموعة [`Slides`](../presentation/slides) يساوي دائمًا SlideNumber - Presentation.FirstSlideNumber. قراءة/كتابة Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | تُرجع كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. قراءة فقط [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | تُرجع مدير السمة المتجاوزة. قراءة فقط [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | تُرجع كائن خط زمني للرسوم المتحركة. قراءة فقط [`IAnimationTimeLine`](../ianimationtimeline). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | تُرجع سمة فعّالة لهذه الشريحة. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | يحدد ما إذا كان مثالي IBaseSlide الاثنين متساويين. تُحسب القيمة المرتجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى... متساوية. لا يأخذ المقارنة في الاعتبار قيم المعرف الفريدة، مثل SlideId والمحتوى الديناميكي، مثل القيمة الحالية لتاريخ العنصر النائبي Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | يبحث عن أول ظهور لشكل بالنص البديل المحدد. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | تُرجع كائن Thumbnail Image (20% من الحجم الحقيقي). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | تُرجع كائن Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | تُرجع كائن صورة TIFF مصغرة مع المعلمات المحددة. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | تُرجع كائن Thumbnail Image بالحجم المحدد. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | تُرجع كائن Thumbnail Image بمقاس مخصص. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | تُرجع كائن Thumbnail Image بالحجم المحدد. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | تُرجع كائن Thumbnail Image بمقاس مخصص. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | تُرجع جميع تعليقات الشريحة التي أضافها مؤلف محدد. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | يجمع السلاسل ذات التنسيق نفسه في جميع الفقرات بجميع الأشكال القابلة للقبول. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | يجمع السلاسل ذات التنسيق نفسه في جميع الفقرات بجميع الأشكال القابلة للقبول. |
| [Remove](../../aspose.slides/slide/remove)() | يزيل الشريحة من العرض التقديمي. |
| [Reset](../../aspose.slides/slide/reset)() | يعيد تعيين موضع وحجم وتنسيق كل شكل له نموذج أولي على LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | يحفظ محتوى الشريحة كملف EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | يحفظ محتوى الشريحة كملف SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | يحفظ محتوى الشريحة كملف SVG. |

### انظر أيضًا

* فئة [BaseSlide](../baseslide)
* واجهة [ISlide](../islide)
* مساحة اسم [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->