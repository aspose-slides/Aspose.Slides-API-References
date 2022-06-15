---
title: Slide
type: docs
weight: 0
url: /php-java/slide/
---

# Slide class

  Represents a slide in a presentation.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getHeaderFooterManager](/php-java/slide/getheaderfootermanager/)() | ISlideHeaderFooterManager | Returns HeaderFooter manager of the slide. Read-only ISlideHeaderFooterManager. |
| [getHidden](/php-java/slide/gethidden/)() | boolean | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |
| [getLayoutSlide](/php-java/slide/getlayoutslide/)() | ILayoutSlide | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |
| [getNotesSlideManager](/php-java/slide/getnotesslidemanager/)() | INotesSlideManager | Allow to access notes slide, add and remove it. Read-only INotesSlideManager. |
| [getShowMasterShapes](/php-java/slide/getshowmastershapes/)() | boolean | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |
| [getSlideComments](/php-java/slide/getslidecomments/)(ICommentAuthor) | IComment | Returns all slide comments added by specific author. |
| [getSlideNumber](/php-java/slide/getslidenumber/)() | int | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |
| [getThemeManager](/php-java/slide/getthememanager/)() | IOverrideThemeManager | Returns the overriding theme manager. Read-only IOverrideThemeManager. |
| [getThumbnail](/php-java/slide/getthumbnail/)(float, float) | BufferedImage | Returns a Thumbnail Bitmap object with custom scaling. |
| [getThumbnail](/php-java/slide/getthumbnail/)() | BufferedImage | Returns a Thumbnail Image object (20% of real size). |
| [getThumbnail](/php-java/slide/getthumbnail/)(Dimension) | BufferedImage | Returns a Thumbnail Bitmap object with specified size. |
| [getThumbnail](/php-java/slide/getthumbnail/)(ITiffOptions) | BufferedImage | Returns a Thumbnail tiff BufferedImage object with specified parameters. |
| [getThumbnail](/php-java/slide/getthumbnail/)(INotesCommentsLayoutingOptions) | BufferedImage | Returns a Thumbnail BufferedImage object. |
| [getThumbnail](/php-java/slide/getthumbnail/)(INotesCommentsLayoutingOptions, float, float) | BufferedImage | Returns a Thumbnail BufferedImage object with custom scaling. |
| [getThumbnail](/php-java/slide/getthumbnail/)(INotesCommentsLayoutingOptions, Dimension) | BufferedImage | Returns a Thumbnail BufferedImage object with specified size. |
| [getThumbnail](/php-java/slide/getthumbnail/)(IRenderingOptions) | BufferedImage | Returns a Thumbnail BufferedImage object. |
| [getThumbnail](/php-java/slide/getthumbnail/)(IRenderingOptions, float, float) | BufferedImage | Returns a Thumbnail BufferedImage object with custom scaling. |
| [getThumbnail](/php-java/slide/getthumbnail/)(IRenderingOptions, Dimension) | BufferedImage | Returns a Thumbnail BufferedImage object with specified size. |
| [joinPortionsWithSameFormatting](/php-java/slide/joinportionswithsameformatting/)() | void | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [remove](/php-java/slide/remove/)() | void | Removes slide from presentation. |
| [renderToGraphics](/php-java/slide/rendertographics/)(INotesCommentsLayoutingOptions, Graphics2D, int, int) | void | Renders certain slide to a Graphics object using specified size. |
| [renderToGraphics](/php-java/slide/rendertographics/)(INotesCommentsLayoutingOptions, Graphics2D, float) | void | Renders certain slide to a Graphics object using specified scale. |
| [renderToGraphics](/php-java/slide/rendertographics/)(INotesCommentsLayoutingOptions, Graphics2D) | void | Renders certain slide to a Graphics object. |
| [renderToGraphics](/php-java/slide/rendertographics/)(IRenderingOptions, Graphics2D) | void | Renders certain slide to a Graphics object. |
| [renderToGraphics](/php-java/slide/rendertographics/)(IRenderingOptions, Graphics2D, float, float) | void | Renders certain slide to a Graphics object with custom scaling. |
| [renderToGraphics](/php-java/slide/rendertographics/)(IRenderingOptions, Graphics2D, Dimension) | void | Renders certain slide to a Graphics object using specified size. |
| [reset](/php-java/slide/reset/)() | void | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [setHidden](/php-java/slide/sethidden/)(boolean) | void | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |
| [setLayoutSlide](/php-java/slide/setlayoutslide/)(ILayoutSlide) | void | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |
| [setShowMasterShapes](/php-java/slide/setshowmastershapes/)(boolean) | void | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |
| [setSlideNumber](/php-java/slide/setslidenumber/)(int) | void | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |
| [writeAsSvg](/php-java/slide/writeassvg/)(OutputStream) | void | Saves content of slide as SVG file. |
| [writeAsSvg](/php-java/slide/writeassvg/)(OutputStream, ISVGOptions) | void | Saves content of slide as SVG file. |
