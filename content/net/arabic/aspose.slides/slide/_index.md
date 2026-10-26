---
title: Slide
second_title: مرجع API Aspose.Sildes لـ .NET
description: يمثل شريحة في عرض تقديمي.
type: docs
weight: 9960
url: /ar/aspose.slides/slide/
---
## فئة Slide

يمثل شريحة في عرض تقديمي.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | يعيد خلفية الشريحة. قراءة فقط [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | يعيد مجموعة عناصر التحكم ActiveX في الشريحة. قراءة فقط [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | يعيد البيانات المخصصة للشريحة. قراءة فقط [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | يعيد مدير HeaderFooter للشريحة. قراءة فقط [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قراءة/كتابة Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | يوفر وصولاً سهلاً إلى الروابط التشعبية المحتواة. قراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | يعيد أو يضع شريحة التخطيط للشريحة الحالية. قراءة/كتابة [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | يعيد أو يضع اسم الشريحة. قراءة/كتابة String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | السماح بالوصول إلى شريحة الملاحظات، وإضافة وإزالتها. قراءة فقط [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | يعيد الواجهة IPresentation. قراءة فقط [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | يعيد أشكال الشريحة. قراءة فقط [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. قراءة/كتابة Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | يعيد معرف الشريحة. قراءة فقط UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | يعيد رقم الشريحة. فهرس الشريحة في مجموعة [`Slides`](../presentation/slides) يكون دائمًا مساويًا لـ SlideNumber - Presentation.FirstSlideNumber. قراءة/كتابة Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | يعيد كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. قراءة فقط [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | يعيد مدير السمة المتجاوز. قراءة فقط [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | يعيد كائن خط الزمن للرسوم المتحركة. قراءة فقط [`IAnimationTimeLine`](../ianimationtimeline). |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | يعيد سمة فعالة لهذه الشريحة. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | يحدد ما إذا كانت مثيلتا IBaseSlide الاثنين متساويتين. يتم حساب القيمة المرجعية بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى… متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | يبحث عن أول حدوث لشكل بالنص البديل المحدد. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | يعيد كائن صورة مصغرة (20% من الحجم الحقيقي). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | يعيد كائن صورة مصغرة. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | يعيد كائن صورة tiff مصغرة مع المعلمات المحددة. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | يعيد كائن صورة مصغرة بالحجم المحدد. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | يعيد كائن صورة مصغرة مع مقياس مخصص. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | يعيد كائن صورة مصغرة بالحجم المحدد. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | يعيد كائن صورة مصغرة مع مقياس مخصص. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | يعيد جميع تعليقات الشريحة المضافة من قبل مؤلف محدد. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | يجمع النصوص المتتالية ذات التنسيق ذاته في جميع الفقرات في جميع الأشكال المقبولة. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | يجمع النصوص المتتالية ذات التنسيق ذاته في جميع الفقرات في جميع الأشكال المقبولة. |
| [Remove](../../aspose.slides/slide/remove)() | يزيل الشريحة من العرض التقديمي. |
| [Reset](../../aspose.slides/slide/reset)() | يعيد تعيين الموضع والحجم والتنسيق لكل شكل لديه قالب على LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | يحفظ محتوى الشريحة كملف EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | يحفظ محتوى الشريحة كملف SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | يحفظ محتوى الشريحة كملف SVG. |

### انظر أيضًا

* فئة [BaseSlide](../baseslide)
* واجهة [ISlide](../islide)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->