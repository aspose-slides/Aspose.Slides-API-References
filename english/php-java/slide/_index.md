---
title: Slide
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/slide/
---

## Slide class

  Represents a slide in a presentation.
 

## Methods

| Name | Description |
| --- | --- |
| [getHeaderFooterManager](getheaderfootermanager)() | Returns HeaderFooter manager of the slide. Read-only ISlideHeaderFooterManager. |
| [getHidden](gethidden)() | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |
| [getLayoutSlide](getlayoutslide)() | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |
| [getNotesSlideManager](getnotesslidemanager)() | Allow to access notes slide, add and remove it. Read-only INotesSlideManager. |
| [getShowMasterShapes](getshowmastershapes)() | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |
| [getSlideComments](getslidecomments)(CommentAuthor) | Returns all slide comments added by specific author. |
| [getSlideNumber](getslidenumber)() | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |
| [getThemeManager](getthememanager)() | Returns the overriding theme manager. Read-only IOverrideThemeManager. |
| [getThumbnail](getthumbnail)(float, float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [getThumbnail](getthumbnail)() | Returns a Thumbnail Image object (20% of real size). |
| [getThumbnail](getthumbnail)(Dimension) | Returns a Thumbnail Bitmap object with specified size. |
| [getThumbnail](getthumbnail)(TiffOptions) | Returns a Thumbnail tiff BufferedImage object with specified parameters. |
| [getThumbnail](getthumbnail)(NotesCommentsLayoutingOptions) | Returns a Thumbnail BufferedImage object. |
| [getThumbnail](getthumbnail)(NotesCommentsLayoutingOptions, float, float) | Returns a Thumbnail BufferedImage object with custom scaling. |
| [getThumbnail](getthumbnail)(NotesCommentsLayoutingOptions, Dimension) | Returns a Thumbnail BufferedImage object with specified size. |
| [getThumbnail](getthumbnail)(RenderingOptions) | Returns a Thumbnail BufferedImage object. |
| [getThumbnail](getthumbnail)(RenderingOptions, float, float) | Returns a Thumbnail BufferedImage object with custom scaling. |
| [getThumbnail](getthumbnail)(RenderingOptions, Dimension) | Returns a Thumbnail BufferedImage object with specified size. |
| [joinPortionsWithSameFormatting](joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [remove](remove)() | Removes slide from presentation. |
| [renderToGraphics](rendertographics)(NotesCommentsLayoutingOptions, Graphics2D, int, int) | Renders certain slide to a Graphics object using specified size. |
| [renderToGraphics](rendertographics)(NotesCommentsLayoutingOptions, Graphics2D, float) | Renders certain slide to a Graphics object using specified scale. |
| [renderToGraphics](rendertographics)(NotesCommentsLayoutingOptions, Graphics2D) | Renders certain slide to a Graphics object. |
| [renderToGraphics](rendertographics)(RenderingOptions, Graphics2D) | Renders certain slide to a Graphics object. |
| [renderToGraphics](rendertographics)(RenderingOptions, Graphics2D, float, float) | Renders certain slide to a Graphics object with custom scaling. |
| [renderToGraphics](rendertographics)(RenderingOptions, Graphics2D, Dimension) | Renders certain slide to a Graphics object using specified size. |
| [reset](reset)() | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [setHidden](sethidden)(boolean) | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |
| [setLayoutSlide](setlayoutslide)(LayoutSlide) | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |
| [setShowMasterShapes](setshowmastershapes)(boolean) | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |
| [setSlideNumber](setslidenumber)(int) | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |
| [writeAsSvg](writeassvg)(OutputStream) | Saves content of slide as SVG file. |
| [writeAsSvg](writeassvg)(OutputStream, SVGOptions) | Saves content of slide as SVG file. |
