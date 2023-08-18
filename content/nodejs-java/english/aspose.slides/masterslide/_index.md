---
title: MasterSlide
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/masterslide/
---

## MasterSlide class

 Represents a master slide in a presentation.
 

## Functions

| Name | Description |
| --- | --- |
| [applyExternalThemeToDependingSlides](applyexternalthemetodependingslides)(String) | Creates a new master slide based on the current one, applying an external theme to it and applies the created master slide to all dependent slides. |
| [getBodyStyle](getbodystyle)() | Returns the style of a body text. Read-only ITextStyle. |
| [getDependingSlides](getdependingslides)() | Returns an array with all slides, which depend on this master slide. |
| [getHeaderFooterManager](getheaderfootermanager)() | Returns HeaderFooter manager of the master slide. Read-only IMasterSlideHeaderFooterManager. |
| [getLayoutSlides](getlayoutslides)() | Returns the collection of child layout slides for this master slide. Read-only IMasterLayoutSlideCollection. You can access to alternative API for adding/inserting/removing/cloning layout slides by using ( IPresentation#getLayoutSlides) property. |
| [getName](getname)() | Returns or sets the name of a master slide. Read/write String. |
| [getOtherStyle](getotherstyle)() | Returns the style of an other text. Read-only ITextStyle. |
| [getPreserve](getpreserve)() | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call MasterSlideCollection#removeUnused(boolean) Read/write boolean. |
| [getShowMasterShapes](getshowmastershapes)() | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |
| [getThemeManager](getthememanager)() | Returns the theme manager. Read-only IMasterThemeManager. |
| [getTitleStyle](gettitlestyle)() | Returns the style of a title text. Read-only ITextStyle. |
| [hasDependingSlides](hasdependingslides)() | Returns true if there exists at least one slide that depends on this master slide. Read-only boolean. |
| [setName](setname)(String) | Returns or sets the name of a master slide. Read/write String. |
| [setPreserve](setpreserve)(boolean) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call MasterSlideCollection#removeUnused(boolean) Read/write boolean. |
| [setShowMasterShapes](setshowmastershapes)(boolean) | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |
