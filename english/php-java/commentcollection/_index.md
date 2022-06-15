---
title: CommentCollection
type: docs
weight: 0
url: /php-java/commentcollection/
---

# CommentCollection class

 Represents a collection of comments of one author.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addComment](/php-java/commentcollection/addcomment/)(String, ISlide, Point2D.Float, Date) | IComment | Add new comment at the end of a collection. |
| [addModernComment](/php-java/commentcollection/addmoderncomment/)(String, ISlide, IShape, Point2D.Float, Date) | IModernComment | Add new modern comment at the end of a collection. |
| [clear](/php-java/commentcollection/clear/)() | void | Removes all comments from a collection. |
| [findCommentByIdx](/php-java/commentcollection/findcommentbyidx/)(int) | IComment | Finds a comment in the collection by index. |
| [getSyncRoot](/php-java/commentcollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/commentcollection/get_item/)(int) | IComment | Gets the element at the specified index. Read-only Comment. |
| [insertComment](/php-java/commentcollection/insertcomment/)(int, String, ISlide, Point2D.Float, Date) | IComment | Insert new comment to a collection at the specified index. |
| [insertModernComment](/php-java/commentcollection/insertmoderncomment/)(int, String, ISlide, IShape, Point2D.Float, Date) | IModernComment | Insert new modern comment to a collection at the specified index. |
| [isSynchronized](/php-java/commentcollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/commentcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/commentcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/php-java/commentcollection/remove/)(IComment) | void | Removes the first occurrence of the specified comment in a collection. |
| [removeAt](/php-java/commentcollection/removeat/)(int) | void | Removes the element at the specified index in a collection. |
| [size](/php-java/commentcollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
| [toArray](/php-java/commentcollection/toarray/)() | IComment | Creates and returns an array with all comments. |
| [toArray](/php-java/commentcollection/toarray/)(int, int) | IComment | Creates and returns an array with all comments from the specified range. |
