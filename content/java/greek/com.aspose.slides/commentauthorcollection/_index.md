---
title: CommentAuthorCollection
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει μια συλλογή από συγγραφείς σχολίων.
type: docs
url: /el/com.aspose.slides/commentauthorcollection/
---
**Κληρονόμηση:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Αντιπροσωπεύει μια συλλογή από συγγραφείς σχολίων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Add new author at the end of a collection. |
| [toArray()](#toArray--) | Creates and returns an array with all authors. |
| [findByName(String name)](#findByName-java.lang.String-) | Find author in a collection by name. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Find author in a collection by name and initials. |
| [removeAt(int index)](#removeAt-int-) | Removes the author at the specified index of the collection. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Removes the first occurrence of the specified author in a collection. |
| [clear()](#clear--) | Removes all authors from a collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


Gets the element at the specified index. Read-only [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```


Add new author at the end of a collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Name of a new author. |
| initials | java.lang.String | Initials of a new author. |

**Επιστρέφει:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - New [ICommentAuthor](../../com.aspose.slides/icommentauthor) object.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


Creates and returns an array with all authors.

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Πίνακας των [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


Find author in a collection by name.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Name of an author to find. |

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Συγγραφέας ή null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Find author in a collection by name and initials.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Name of an author to find. |
| initials | java.lang.String | Initials of an author to find. |

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Συγγραφέας ή null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the author at the specified index of the collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


Removes the first occurrence of the specified author in a collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | The author to remove from a collection. |

### clear() {#clear--}
```
public final void clear()
```


Removes all authors from a collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


Returns an enumerator that iterates through the collection.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


Returns a java iterator for the entire collection.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only Object.

**Επιστρέφει:**
java.lang.Object