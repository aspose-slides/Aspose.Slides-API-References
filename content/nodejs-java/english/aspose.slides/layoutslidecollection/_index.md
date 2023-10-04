---
title: LayoutSlideCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/layoutslidecollection/
---

## LayoutSlideCollection class

 Represents a base class for collection of a layout slides.
 

## Functions

| Name | Description |
| --- | --- |
| [getByType](byte) | Returns the first layout slide of specified type. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | byte | A type of layout slide to find. |

### Result
[LayoutSlide](../../layoutslide)


---


| [getSyncRoot]() | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item](int) | Returns the layout slide by index. Read-only LayoutSlide. |

### Result
[LayoutSlide](../../layoutslide)


---


| [isSynchronized]() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator]() | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava]() | Returns a java iterator for the entire collection. |

### Result



---


| [remove]([LayoutSlide](../layoutslide)) | Removes a layout from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [LayoutSlide](../../layoutslide) | The layout slide to remove from the collection. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove function to simplify code. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


| [removeUnused]() | Removes unused layout slides (layout slides whose HasDependingSlides is false). |


---


| [size]() | Returns the number of layout slides in a collection. Read-only int. |

### Result
int


---


