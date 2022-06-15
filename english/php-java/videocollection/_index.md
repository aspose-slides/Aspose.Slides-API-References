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
| [addVideo](/php-java/videocollection/addvideo/)(IVideo) | IVideo | Adds a copy of an video file from an another presentation. |
| [addVideo](/php-java/videocollection/addvideo/)(InputStream) | IVideo | Creates and adds a video to a presentation from stream. |
| [addVideo](/php-java/videocollection/addvideo/)(InputStream, int) | IVideo | Creates and adds a video to a presentation from stream. |
| [addVideo](/php-java/videocollection/addvideo/)(byte[]) | IVideo | Creates and adds a video to a presentation from byte array. |
| [getSyncRoot](/php-java/videocollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/videocollection/get_item/)(int) | IVideo | Gets the element at the specified index. Read-only IVideo. |
| [isSynchronized](/php-java/videocollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/videocollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/videocollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [size](/php-java/videocollection/size/)() | int | Returns a number of video files in the collection. Read-only int. |
