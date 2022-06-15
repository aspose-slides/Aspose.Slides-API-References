---
title: MasterSlide
type: docs
weight: 0
url: /php-java/masterslide/
---

# MasterSlide class

 Represents a master slide in a presentation.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [applyExternalThemeToDependingSlides](/slides/php-java/masterslide/applyexternalthemetodependingslides/)(String) | IMasterSlide | Creates a new master slide based on the current one, applying an external theme to it and applies the created master slide to all dependent slides. |
| [getBodyStyle](/slides/php-java/masterslide/getbodystyle/)() | ITextStyle | Returns the style of a body text. Read-only ITextStyle. |
| [getDependingSlides](/slides/php-java/masterslide/getdependingslides/)() | ISlide | Returns an array with all slides, which depend on this master slide. |
| [getHeaderFooterManager](/slides/php-java/masterslide/getheaderfootermanager/)() | IMasterSlideHeaderFooterManager | Returns HeaderFooter manager of the master slide. Read-only IMasterSlideHeaderFooterManager. |
| [getLayoutSlides](/slides/php-java/masterslide/getlayoutslides/)() | IMasterLayoutSlideCollection | Returns the collection of child layout slides for this master slide. Read-only IMasterLayoutSlideCollection. You can access to alternative API for adding/inserting/removing/cloning layout slides by using ( IPresentation#getLayoutSlides) property. |
| [getName](/slides/php-java/masterslide/getname/)() | String | Returns or sets the name of a master slide. Read/write String. |
| [getOtherStyle](/slides/php-java/masterslide/getotherstyle/)() | ITextStyle | Returns the style of an other text. Read-only ITextStyle. |
| [getPreserve](/slides/php-java/masterslide/getpreserve/)() | boolean | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call MasterSlideCollection#removeUnused(boolean) Read/write boolean. |
| [getShowMasterShapes](/slides/php-java/masterslide/getshowmastershapes/)() | boolean | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |
| [getThemeManager](/slides/php-java/masterslide/getthememanager/)() | IMasterThemeManager | Returns the theme manager. Read-only IMasterThemeManager. |
| [getTitleStyle](/slides/php-java/masterslide/gettitlestyle/)() | ITextStyle | Returns the style of a title text. Read-only ITextStyle. |
| [hasDependingSlides](/slides/php-java/masterslide/hasdependingslides/)() | boolean | Returns true if there exists at least one slide that depends on this master slide. Read-only boolean. |
| [setName](/slides/php-java/masterslide/setname/)(String) | void | Returns or sets the name of a master slide. Read/write String. |
| [setPreserve](/slides/php-java/masterslide/setpreserve/)(boolean) | void | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call MasterSlideCollection#removeUnused(boolean) Read/write boolean. |
| [setShowMasterShapes](/slides/php-java/masterslide/setshowmastershapes/)(boolean) | void | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |
