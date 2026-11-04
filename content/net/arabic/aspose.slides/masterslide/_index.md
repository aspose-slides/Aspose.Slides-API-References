---
title: MasterSlide
second_title: مرجع API لـ Aspose.Sildes لمنصة .NET
description: يمثل شريحة رئيسية في عرض تقديمي.
type: docs
weight: 8050
url: /ar/aspose.slides/masterslide/
---
## فئة MasterSlide

يمثل شريحة رئيسية في عرض تقديمي.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | يرجع خلفية الشريحة. للقراءة فقط [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | يرجع نمط نص الجسم. للقراءة فقط [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | يرجع مجموعة عناصر التحكم ActiveX على الشريحة. للقراءة فقط [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | يرجع البيانات المخصصة للشريحة. للقراءة فقط [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | يرجع مجموعة من إرشادات الرسم للشريحة الرئيسية. للقراءة فقط [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسية. قابل للقراءة والكتابة Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | يرجع مدير HeaderFooter للشريحة الرئيسية. للقراءة فقط [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | يوفر وصولًا سهلاً إلى الروابط التشعبية المحتواة. للقراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | يرجع مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسية. للقراءة فقط [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | يرجع أو يضبط اسم الشريحة الرئيسية. قابل للقراءة والكتابة String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | يرجع نمط نص آخر. للقراءة فقط [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | يرجع واجهة IPresentation. للقراءة فقط [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عندما تُحذف جميع الشرائح التي تلي تلك الشريحة الرئيسية. ملاحظة: Aspose.Slides لن يقوم أبدًا بإزالة أي شريحة رئيسية غير مستخدمة بنفسه، لإزالة الشرائح الرئيسية غير المستخدمة فعليًا استدعِ [`RemoveUnused`](../masterslidecollection/removeunused). قابل للقراءة والكتابة Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | يرجع أشكال الشريحة. للقراءة فقط [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة إلى الشريحة الرئيسية نفسها، تعيد هذه الخاصية دائمًا `false`. قابل للقراءة والكتابة Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | يرجع معرّف الشريحة. للقراءة فقط UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | يرجع كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة خلال عرض الشرائح. للقراءة فقط [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | يرجع مدير السمة. للقراءة فقط [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | يرجع كائن خط الزمن للرسوم المتحركة. للقراءة فقط [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | يرجع نمط نص العنوان. للقراءة فقط [`ITextStyle`](../itextstyle). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | ينشئ شريحة رئيسية جديدة بناءً على الحالية، يطبق سمة خارجية عليها ويطبق الشريحة الرئيسية التي تم إنشاؤها على جميع الشرائح التابعة. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | يرجع سمة فعّالة لهذه الشريحة. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | يحدد ما إذا كانت مثيلتا IBaseSlide متساويتين. يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى... متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في العنصر النائب Date. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | يبحث عن أول ظهور لشكل يملك النص البديل المحدد. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | يرجع مصفوفة بجميع الشرائح التي تعتمد على هذه الشريحة الرئيسية. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | ينضمّ النصوص (runs) ذات التنسيق نفسه في جميع الفقرات لجميع الأشكال المقبولة. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | ينضمّ النصوص ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |

### انظر أيضًا

* فئة [BaseSlide](../baseslide)
* واجهة [IMasterSlide](../imasterslide)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->