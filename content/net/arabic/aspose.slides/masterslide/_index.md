---
title: MasterSlide
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل ماستر سلايد في عرض تقديمي.
type: docs
weight: 8030
url: /ar/aspose.slides/masterslide/
---
## فئة MasterSlide

يمثل ماستر سلايد في عرض تقديمي.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | يررج خلفية الشريحة. للقراءة فقط [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | يررج نمط نص الجسم. للقراءة فقط [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | يررج مجموعة عناصر تحكم ActiveX على الشريحة. للقراءة فقط [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | يررج البيانات المخصصة للشريحة. للقراءة فقط [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | يررج مجموعة من أدلة الرسم للماستر سلايد. للقراءة فقط [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | يررج true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذا الماستر سلايد. للقراءة فقط Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | يررج مدير HeaderFooter للماستر سلايد. للقراءة فقط [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | يوفر وصولًا سهلاً إلى الروابط التشعبية المضمنة. للقراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | يررج مجموعة شرائح تخطيط الطفل لهذا الماستر سلايد. للقراءة فقط [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | يررج أو يضبط اسم الماستر سلايد. قراءة/كتابة String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | يررج نمط نص آخر. للقراءة فقط [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | يررج واجهة IPresentation. للقراءة فقط [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | يحدد ما إذا كان الماستر المقابل يُحذف عندما تُحذف جميع الشرائح التي تلاحقه. ملاحظة: Aspose.Slides لن يزيل أي ماستر غير مستخدم بنفسه؛ لإزالة الماسترات غير المستخدمة فعليًا، استدعِ [`RemoveUnused`](../masterslidecollection/removeunused) قراءة/كتابة Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | يررج أشكال الشريحة. للقراءة فقط [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | يحدد ما إذا كان يجب إظهار الأشكال على الماستر سلايد في الشرائح أم لا. بالنسبة للماستر سلايد نفسه، تُرجع هذه الخاصية دائمًا `false`. قراءة/كتابة Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | يررج معرف الشريحة. للقراءة فقط UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | يررج كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة خلال عرض الشرائح. للقراءة فقط [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | يررج مدير السمة. للقراءة فقط [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | يررج كائن مخطط الزمني للرسوم المتحركة. للقراءة فقط [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | يررج نمط نص العنوان. للقراءة فقط [`ITextStyle`](../itextstyle). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | ينشئ ماستر سلايد جديد استنادًا إلى الحالي، يطبق سمة خارجية عليه ويطبق الماستر سلايد المُنشأ على جميع الشرائح التابعة. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | يررج سمة فعّالة لهذه الشريحة. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | يحدد ما إذا كان مثالي IBaseSlide الاثنين متساويين. يتم حساب القيمة المرجعة بناءً على هيكل الشريحة والمحتوى الثابت. تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى… متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرف الفريد، مثل SlideId، ولا المحتوى الديناميكي، مثل قيمة التاريخ الحالية في عنصر نائبة التاريخ. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | يبحث عن أول ظهور لشكل يحمل النص البديل المحدد. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | يررج مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذا الماستر سلايد. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | ينضم إلى السلاسل ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال القابلة للقبول. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | ينضم إلى السلاسل ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال القابلة للقبول. |

### انظر أيضًا

* class [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->