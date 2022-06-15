---
title: LayoutSlide
type: docs
weight: 0
url: /php-java/layoutslide/
---

# LayoutSlide class

 Represents a layout slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getDependingSlides](/slides/php-java/layoutslide/getdependingslides/)() | ISlide | Returns an array with all slides, which depend on this layout slide. |
| [getHeaderFooterManager](/slides/php-java/layoutslide/getheaderfootermanager/)() | ILayoutSlideHeaderFooterManager | Returns HeaderFooter manager of the layout slide. Read-only ILayoutSlideHeaderFooterManager. |
| [getLayoutType](/slides/php-java/layoutslide/getlayouttype/)() | byte | Returns layout type of this layout slide. Read-only SlideLayoutType. |
| [getMasterSlide](/slides/php-java/layoutslide/getmasterslide/)() | IMasterSlide | Returns or sets the master slide for a layout. Read/write IMasterSlide. |
| [getShowMasterShapes](/slides/php-java/layoutslide/getshowmastershapes/)() | boolean | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |
| [getThemeManager](/slides/php-java/layoutslide/getthememanager/)() | IOverrideThemeManager | Returns the overriding theme manager. Read-only IOverrideThemeManager. |
| [hasDependingSlides](/slides/php-java/layoutslide/hasdependingslides/)() | boolean | Returns true if there exists at least one slide that depends on this layout slide. Read-only boolean. |
| [remove](/slides/php-java/layoutslide/remove/)() | void | Removes layout from presentation. |
| [setMasterSlide](/slides/php-java/layoutslide/setmasterslide/)(IMasterSlide) | void | Returns or sets the master slide for a layout. Read/write IMasterSlide. |
| [setShowMasterShapes](/slides/php-java/layoutslide/setshowmastershapes/)(boolean) | void | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |
