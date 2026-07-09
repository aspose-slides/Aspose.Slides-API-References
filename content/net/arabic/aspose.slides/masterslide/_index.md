---
title: MasterSlide
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل شريحة رئيسية في عرض تقديمي.
type: docs
weight: 8030
url: /ar/aspose.slides/masterslide/
---
## MasterSlide فئة

يمثل شريحة رئيسية في عرض تقديمي.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | إرجاع خلفية الشريحة. قراءة فقط [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | إرجاع نمط نص الجسم. قراءة فقط [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | إرجاع مجموعة عناصر تحكم ActiveX على الشريحة. قراءة فقط [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | إرجاع بيانات مخصصة للشريحة. قراءة فقط [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | إرجاع مجموعة من أدلة الرسم للشريحة الرئيسية. قراءة فقط [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | إرجاع true إذا كان هناك على الأقل شريحة واحدة تعتمد على هذه الشريحة الرئيسية. قراءة فقط Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | إرجاع مدير HeaderFooter للشريحة الرئيسية. قراءة فقط [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | يوفر وصولًا سهلاً إلى الروابط التشعبية المحتواة. قراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | إرجاع مجموعة شرائح تخطيط فرعية لهذه الشريحة الرئيسية. قراءة فقط [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | إرجاع أو تعيين اسم الشريحة الرئيسية. قراءة/كتابة String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | إرجاع نمط نص آخر. قراءة فقط [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | إرجاع واجهة IPresentation. قراءة فقط [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تلي تلك الشريحة الرئيسية. ملاحظة: Aspose.Slides لن يزيل أي شريحة رئيسية غير مستخدمة بنفسه، لإزالة الشرائح الرئيسية غير المستخدمة فعليًا استدعِ [`RemoveUnused`](../masterslidecollection/removeunused) قراءة/كتابة Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | إرجاع أشكال الشريحة. قراءة فقط [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها فإن هذه الخاصية تُرجع دائمًا `false`. قراءة/كتابة Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | إرجاع معرف الشريحة. قراءة فقط UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | إرجاع كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. قراءة فقط [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | إرجاع مدير السمة. قراءة فقط [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | إرجاع كائن جدول زمني للرسوم المتحركة. قراءة فقط [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | إرجاع نمط نص العنوان. قراءة فقط [`ITextStyle`](../itextstyle). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | إنشاء شريحة رئيسية جديدة اعتمادًا على الحالية، وتطبيق سمة خارجية عليها وتطبيق الشريحة الرئيسية التي تم إنشاؤها على جميع الشرائح التابعة. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | إرجاع سمة فعّالة لهذه الشريحة. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | يحدد ما إذا كان مثليي IBaseSlide متساويين. يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرف الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في عنصر نائب التاريخ. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | يجد أول ظهور لشكل يحتوي على النص البديل المحدد. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | إرجاع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسية. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | يجمع السلاسل ذات التنسيق نفسه في جميع الفقرات لجميع الأشكال المقبولة. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | يجمع السلاسل ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |

### انظر أيضًا

* فئة [BaseSlide](../baseslide)
* واجهة [IMasterSlide](../imasterslide)
* مساحة أسماء [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->