---
title: LayoutSlide
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل شريحة تخطيط.
type: docs
weight: 7660
url: /ar/aspose.slides/layoutslide/
---
## LayoutSlide فئة

يمثل شريحة تخطيط.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returns slide's background. للقراءة فقط [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returns the collection of ActiveX controls on a slide. للقراءة فقط [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returns the slide's custom data. للقراءة فقط [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Returns a collection of drawing guides for the layout slide. للقراءة فقط [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Returns true if there exists at least one slide that depends on this layout slide. للقراءة فقط Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Returns HeaderFooter manager of the layout slide. للقراءة فقط [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Provides easy access to contained hyperlinks. للقراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Returns layout type of this layout slide. للقراءة فقط [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Returns or sets the master slide for a layout. قراءة/كتابة [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Returns or sets the name of a slide. قراءة/كتابة String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Returns the placeholder manager of the layout slide. للقراءة فقط [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returns IPresentation interface. للقراءة فقط [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returns the shapes of a slide. للقراءة فقط [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Specifies if shapes on the master slide should be shown on slides or not. قراءة/كتابة Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returns the ID of a slide. للقراءة فقط UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returns the Transition object which contains information about how the specified slide advances during a slide show. للقراءة فقط [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Returns the overriding theme manager. للقراءة فقط [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returns animation timeline object. للقراءة فقط [`IAnimationTimeLine`](../ianimationtimeline). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returns an effective theme for this slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Finds first occurrence of a shape with the specified alternative text. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Returns an array with all slides, which depend on this layout slide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Removes layout from presentation. |

### انظر أيضًا

* فئة [BaseSlide](../baseslide)
* واجهة [ILayoutSlide](../ilayoutslide)
* مساحة اسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->