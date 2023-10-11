---
title: LayoutSlide
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/layoutslide/
---

## LayoutSlide class

 Represents a layout slide.
 
| [getDependingSlides] () Returns an array with all slides, which depend on this layout slide. |

### Result
[Slide]


---


| [getHeaderFooterManager] () Returns HeaderFooter manager of the layout slide. Read-only ILayoutSlideHeaderFooterManager. |

### Result
[LayoutSlideHeaderFooterManager]


---


| [getLayoutType] () Returns layout type of this layout slide. Read-only SlideLayoutType. |

### Result
byte


---


| [getMasterSlide] () Returns or sets the master slide for a layout. Read/write IMasterSlide. |

### Result
[MasterSlide]


---


| [getShowMasterShapes] () Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |

### Result
boolean


---


| [getThemeManager] () Returns the overriding theme manager. Read-only IOverrideThemeManager. |

### Result
[NotesSlideThemeManager], [ChartThemeManager], [BaseOverrideThemeManager], [LayoutSlideThemeManager], [SlideThemeManager]


---


| [hasDependingSlides] () Returns true if there exists at least one slide that depends on this layout slide. Read-only boolean. |

### Result
boolean


---


| [remove] () Removes layout from presentation. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is already removed from presentation or if layout is used in presentation (its HasDependingSlides property is true). To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. |


---


| [setMasterSlide] ([MasterSlide]) Returns or sets the master slide for a layout. Read/write IMasterSlide. |


---


| [setShowMasterShapes] ([boolean]) Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |


---


