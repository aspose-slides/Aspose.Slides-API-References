---
title: CommentAuthorCollection
type: docs
weight: 0
url: /php-java/commentauthorcollection/
---

# CommentAuthorCollection class

 Represents a collection of comment authors.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addAuthor](/slides/php-java/commentauthorcollection/addauthor/)(String, String) | ICommentAuthor | Add new author at the end of a collection. |
| [clear](/slides/php-java/commentauthorcollection/clear/)() | void | Removes all authors from a collection. |
| [findByName](/slides/php-java/commentauthorcollection/findbyname/)(String) | ICommentAuthor | Find author in a collection by name. |
| [findByNameAndInitials](/slides/php-java/commentauthorcollection/findbynameandinitials/)(String, String) | ICommentAuthor | Find author in a collection by name and initials. |
| [getSyncRoot](/slides/php-java/commentauthorcollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/commentauthorcollection/get_item/)(int) | ICommentAuthor | Gets the element at the specified index. Read-only ICommentAuthor. |
| [isSynchronized](/slides/php-java/commentauthorcollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/commentauthorcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/commentauthorcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/slides/php-java/commentauthorcollection/remove/)(ICommentAuthor) | void | Removes the first occurrence of the specified author in a collection. |
| [removeAt](/slides/php-java/commentauthorcollection/removeat/)(int) | void | Removes the author at the specified index of the collection. |
| [size](/slides/php-java/commentauthorcollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
| [toArray](/slides/php-java/commentauthorcollection/toarray/)() | ICommentAuthor | Creates and returns an array with all authors. |
