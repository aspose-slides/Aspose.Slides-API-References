---
title: CommentAuthorCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/commentauthorcollection/
---

## CommentAuthorCollection class

 Represents a collection of comment authors.
 
| [addAuthor] ([String], [String]) | Add new author at the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of a new author. |
| initials | [String] | Initials of a new author. |

### Result
[CommentAuthor]


---


| [clear] () | Removes all authors from a collection. |


---


| [findByName] ([String]) | Find author in a collection by name. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of an author to find. |

### Result
[CommentAuthor]


---


| [findByNameAndInitials] ([String], [String]) | Find author in a collection by name and initials. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of an author to find. |
| initials | [String] | Initials of an author to find. |

### Result
[CommentAuthor]


---


| [getSyncRoot] () | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) | Gets the element at the specified index. Read-only ICommentAuthor. |

### Result
[CommentAuthor]


---


| [isSynchronized] () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () | Returns a java iterator for the entire collection. |

### Result



---


| [remove] ([CommentAuthor]) | Removes the first occurrence of the specified author in a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| author | [CommentAuthor] | The author to remove from a collection. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if author is already removed. |


---


| [removeAt] ([int]) | Removes the author at the specified index of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index of the element to remove. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if author is already removed. |


---


| [size] () | Gets the number of elements actually contained in the collection. Read-only int. |

### Result
int


---


| [toArray] () | Creates and returns an array with all authors. |

### Result
[CommentAuthor]


---


