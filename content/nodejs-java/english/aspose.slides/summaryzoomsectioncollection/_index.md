---
title: SummaryZoomSectionCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/summaryzoomsectioncollection/
---

## SummaryZoomSectionCollection class

 Represents a collection of Summary Zoom Section objects.
 

## Functions

| Name | Description |
| --- | --- |
| [addSummaryZoomSection]([Section](../section)) | Creates new Summary Zoom Section object and add it to the collection |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../../section) | Section for a new Summary Zoom Section element ISection If an element for this section already exists in the collection, the existing element is returned. |

### Result
[SummaryZoomSection](../../summaryzoomsection)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


| [clear]() | Removes all SummaryZoomSection objects from the collection. |


---


| [getSummarySection]([Section](../section)) | Returns Summary Zoom Section element for the given section. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../../section) | Section to find ISection |

### Result
[SummaryZoomSection](../../summaryzoomsection)


---


| [getSyncRoot]() | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item](int) | Gets the element at the specified index. Read-only ISummaryZoomSection. |

### Result
[SummaryZoomSection](../../summaryzoomsection)


---


| [indexOf]([SummaryZoomSection](../summaryzoomsection)) | Returns an index of the specified SummaryZoomSection object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [SummaryZoomSection](../../summaryzoomsection) | SummaryZoomSection object to find ISummaryZoomSection. |

### Result
int


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


| [removeSummaryZoomSection]([Section](../section)) | Remove Summary Zoom Section object from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../../section) | Section for which the Summary Zoom Section element is to be removed ISection. |


---


| [size]() | Gets the number of elements actually contained in the collection. Read-only int. |

### Result
int


---


