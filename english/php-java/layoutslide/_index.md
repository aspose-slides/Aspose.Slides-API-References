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
| [getDependingSlides](/php-java/layoutslide/getdependingslides/)() | ISlide | Returns an array with all slides, which depend on this layout slide. |
| [getHeaderFooterManager](/php-java/layoutslide/getheaderfootermanager/)() | ILayoutSlideHeaderFooterManager | Returns HeaderFooter manager of the layout slide. Read-only ILayoutSlideHeaderFooterManager. |
| [getLayoutType](/php-java/layoutslide/getlayouttype/)() | byte | Returns layout type of this layout slide. Read-only SlideLayoutType. |
| [getMasterSlide](/php-java/layoutslide/getmasterslide/)() | IMasterSlide | Returns or sets the master slide for a layout. Read/write IMasterSlide. |
| [getShowMasterShapes](/php-java/layoutslide/getshowmastershapes/)() | boolean | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |
| [getThemeManager](/php-java/layoutslide/getthememanager/)() | IOverrideThemeManager | Returns the overriding theme manager. Read-only IOverrideThemeManager. |
| [hasDependingSlides](/php-java/layoutslide/hasdependingslides/)() | boolean | Returns true if there exists at least one slide that depends on this layout slide. Read-only boolean. |
| [remove](/php-java/layoutslide/remove/)() | void | Removes layout from presentation. |
| [setMasterSlide](/php-java/layoutslide/setmasterslide/)(IMasterSlide) | void | Returns or sets the master slide for a layout. Read/write IMasterSlide. |
| [setShowMasterShapes](/php-java/layoutslide/setshowmastershapes/)(boolean) | void | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |
