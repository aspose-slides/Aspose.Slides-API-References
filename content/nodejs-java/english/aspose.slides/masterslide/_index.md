---
title: MasterSlide
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/masterslide/
---

## MasterSlide class

 Represents a master slide in a presentation.
 
| Name | Description |
| --- | --- |
| applyExternalThemeToDependingSlides (String) | Creates a new master slide based on the current one, applying an external theme to it and applies the created master slide to all dependent slides. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the external theme file (.thmx). |

### Result
MasterSlide(../../masterslide)

### Error

| Error | Condition |
| --- | --- |
 | PptxReadException | When external theme cannot be applied. |


---


| Name | Description |
| --- | --- |
| getBodyStyle () | Returns the style of a body text. Read-only ITextStyle. |

### Result
TextStyle(../../textstyle)


---


| Name | Description |
| --- | --- |
| getDependingSlides () | Returns an array with all slides, which depend on this master slide. |

### Result
Slide(../../slide)


---


| Name | Description |
| --- | --- |
| getHeaderFooterManager () | Returns HeaderFooter manager of the master slide. Read-only IMasterSlideHeaderFooterManager. |

### Result
MasterSlideHeaderFooterManager(../../masterslideheaderfootermanager)


---


| Name | Description |
| --- | --- |
| getLayoutSlides () | Returns the collection of child layout slides for this master slide. Read-only IMasterLayoutSlideCollection. You can access to alternative API for adding/inserting/removing/cloning layout slides by using ( IPresentation#getLayoutSlides) property. |

### Result
MasterLayoutSlideCollection(../../masterlayoutslidecollection)


---


| Name | Description |
| --- | --- |
| getName () | Returns or sets the name of a master slide. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getOtherStyle () | Returns the style of an other text. Read-only ITextStyle. |

### Result
TextStyle(../../textstyle)


---


| Name | Description |
| --- | --- |
| getPreserve () | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call MasterSlideCollection#removeUnused(boolean) Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getShowMasterShapes () | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set {@code true} for master slide. |


---


| Name | Description |
| --- | --- |
| getThemeManager () | Returns the theme manager. Read-only IMasterThemeManager. |

### Result
MasterThemeManager(../../masterthememanager)


---


| Name | Description |
| --- | --- |
| getTitleStyle () | Returns the style of a title text. Read-only ITextStyle. |

### Result
TextStyle(../../textstyle)


---


| Name | Description |
| --- | --- |
| hasDependingSlides () | Returns true if there exists at least one slide that depends on this master slide. Read-only boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setName (String) | Returns or sets the name of a master slide. Read/write String. |


---


| Name | Description |
| --- | --- |
| setPreserve (boolean) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call MasterSlideCollection#removeUnused(boolean) Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set {@code true} for master slide. |


---


