---
title: CommentAuthorCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/commentauthorcollection/
---

## CommentAuthorCollection class

 Represents a collection of comment authors.
 
### addAuthor {#addAuthor}

| Name | Description |
| --- | --- |
| addAuthor (String, String) | Add new author at the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of a new author. |
| initials | String | Initials of a new author. |

 **Returns:**
[CommentAuthor](../commentauthor)

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if author with the same name and initials is already added. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all authors from a collection. |

 **Returns:**
void


---


### findByName {#findByName}

| Name | Description |
| --- | --- |
| findByName (String) | Find author in a collection by name. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of an author to find. |

 **Returns:**
[CommentAuthor](../commentauthor)


---


### findByNameAndInitials {#findByNameAndInitials}

| Name | Description |
| --- | --- |
| findByNameAndInitials (String, String) | Find author in a collection by name and initials. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of an author to find. |
| initials | String | Initials of an author to find. |

 **Returns:**
[CommentAuthor](../commentauthor)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Returns:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. Read-only ICommentAuthor. |

 **Returns:**
[CommentAuthor](../commentauthor)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Returns:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Returns:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([CommentAuthor](../commentauthor)) | Removes the first occurrence of the specified author in a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| author | [CommentAuthor](../commentauthor) | The author to remove from a collection. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if author is already removed. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the author at the specified index of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if author is already removed. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Gets the number of elements actually contained in the collection. Read-only int. |

 **Returns:**
int


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray () | Creates and returns an array with all authors. |

 **Returns:**
[CommentAuthor](../commentauthor)


---


