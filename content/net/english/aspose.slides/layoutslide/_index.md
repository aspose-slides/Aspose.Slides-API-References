---
title: LayoutSlide
second_title: Aspose.Sildes for .NET API Reference
description: Represents a layout slide.
type: docs
weight: 7470
url: /aspose.slides/layoutslide/
---

## LayoutSlide class

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Properties

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returns slide's background. Read-only [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returns the collection of ActiveX controls on a slide. Read-only [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returns the slide's custom data. Read-only [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Returns true if there exists at least one slide that depends on this layout slide. Read-only Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Returns HeaderFooter manager of the layout slide. Read-only [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Provides easy access to contained hyperlinks. Read-only [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Returns layout type of this layout slide. Read-only [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Returns or sets the master slide for a layout. Read/write [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Returns or sets the name of a slide. Read/write String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Returns the placeholder manager of the layout slide. Read-only [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returns IPresentation interface. Read-only [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returns the shapes of a slide. Read-only [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Specifies if shapes on the master slide should be shown on slides or not. Read/write Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returns the ID of a slide. Read-only UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returns the Transition object which contains information about how the specified slide advances during a slide show. Read-only [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Returns the overriding theme manager. Read-only [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returns animation timeline object. Read-only [`IAnimationTimeLine`](../ianimationtimeline). |

## Methods

| Name | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returns an effective theme for this slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Finds first occurrence of a shape with the specified alternative text. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Returns an array with all slides, which depend on this layout slide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Removes layout from presentation. |

### See Also

* class [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
