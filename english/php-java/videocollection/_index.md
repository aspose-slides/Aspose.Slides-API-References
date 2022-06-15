---
title: VideoCollection
type: docs
weight: 0
url: /php-java/videocollection/
---

# VideoCollection class

 Represents a collection of Video objects.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addVideo](/slides/php-java/videocollection/addvideo/)(IVideo) | IVideo | Adds a copy of an video file from an another presentation. |
| [addVideo](/slides/php-java/videocollection/addvideo/)(InputStream) | IVideo | Creates and adds a video to a presentation from stream. |
| [addVideo](/slides/php-java/videocollection/addvideo/)(InputStream, int) | IVideo | Creates and adds a video to a presentation from stream. |
| [addVideo](/slides/php-java/videocollection/addvideo/)(byte[]) | IVideo | Creates and adds a video to a presentation from byte array. |
| [getSyncRoot](/slides/php-java/videocollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/videocollection/get_item/)(int) | IVideo | Gets the element at the specified index. Read-only IVideo. |
| [isSynchronized](/slides/php-java/videocollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/videocollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/videocollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [size](/slides/php-java/videocollection/size/)() | int | Returns a number of video files in the collection. Read-only int. |
