---
title: LayoutSlide
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นตัวแทนของสไลด์เลเอาต์.
type: docs
weight: 7660
url: /th/aspose.slides/layoutslide/
---
## คลาส LayoutSlide

Represent a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returns slide's background. อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returns the collection of ActiveX controls on a slide. อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returns the slide's custom data. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Returns a collection of drawing guides for the layout slide. อ่านอย่างเดียว [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Returns true if there exists at least one slide that depends on this layout slide. อ่านอย่างเดียว Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Returns HeaderFooter manager of the layout slide. อ่านอย่างเดียว [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Provides easy access to contained hyperlinks. อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Returns layout type of this layout slide. อ่านอย่างเดียว [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Returns or sets the master slide for a layout. อ่าน/เขียน [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Returns or sets the name of a slide. อ่าน/เขียน String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Returns the placeholder manager of the layout slide. อ่านอย่างเดียว [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returns IPresentation interface. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returns the shapes of a slide. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Specifies if shapes on the master slide should be shown on slides or not. อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returns the ID of a slide. อ่านอย่างเดียว UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returns the Transition object which contains information about how the specified slide advances during a slide show. อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Returns the overriding theme manager. อ่านอย่างเดียว [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returns animation timeline object. อ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returns an effective theme for this slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings, etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Finds first occurrence of a shape with the specified alternative text. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Returns an array with all slides, which depend on this layout slide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Removes layout from presentation. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [ILayoutSlide](../ilayoutslide)
* เนมส페ซ [Aspose.Slides](../../aspose.slides)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->