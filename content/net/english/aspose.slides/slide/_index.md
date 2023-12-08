---
title: Slide
second_title: Aspose.Sildes for .NET API Reference
description: Represents a slide in a presentation.
type: docs
weight: 9420
url: /aspose.slides/slide/
---

## Slide class

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Properties

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returns slide's background. Read-only [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returns the collection of ActiveX controls on a slide. Read-only [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returns the slide's custom data. Read-only [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Returns HeaderFooter manager of the slide. Read-only [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Determines whether the specified slide is hidden during a slide show. Read/write Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Provides easy access to contained hyperlinks. Read-only [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Returns or sets the layout slide for the current slide. Read/write [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Returns or sets the name of a slide. Read/write String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Allow to access notes slide, add and remove it. Read-only [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returns IPresentation interface. Read-only [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returns the shapes of a slide. Read-only [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Specifies if shapes on the master slide should be shown on slides or not. Read/write Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returns the ID of a slide. Read-only UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Returns a number of slide. Index of slide in [`Slides`](../presentation/slides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returns the Transition object which contains information about how the specified slide advances during a slide show. Read-only [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Returns the overriding theme manager. Read-only [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returns animation timeline object. Read-only [`IAnimationTimeLine`](../ianimationtimeline). |

## Methods

| Name | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returns an effective theme for this slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Finds first occurrence of a shape with the specified alternative text. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Returns all slide comments added by specific author. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail)() | Returns a Thumbnail Image object (20% of real size). |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_4)(IRenderingOptions) | Returns a Thumbnail Bitmap object. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_7)(ITiffOptions) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_9)(Size) | Returns a Thumbnail Bitmap object with specified size. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_8)(float, float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_6)(IRenderingOptions, Size) | Returns a Thumbnail Bitmap object with specified size. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_5)(IRenderingOptions, float, float) | Returns a Thumbnail Bitmap object with custom scaling. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [Remove](../../aspose.slides/slide/remove)() | Removes slide from presentation. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_3)(IRenderingOptions, Graphics) | Renders certain slide to a Graphics object. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_5)(IRenderingOptions, Graphics, Size) | Renders certain slide to a Graphics object using specified size. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_4)(IRenderingOptions, Graphics, float, float) | Renders certain slide to a Graphics object with custom scaling. |
| [Reset](../../aspose.slides/slide/reset)() | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Saves content of slide as SVG file. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Saves content of slide as SVG file. |

### See Also

* class [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
