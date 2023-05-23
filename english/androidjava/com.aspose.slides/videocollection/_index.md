---
title: VideoCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of Video objects.
type: docs
weight: 608
url: /androidjava/com.aspose.slides/videocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Represents a collection of Video objects.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns a number of video files in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Adds a copy of an video file from an another presentation. |
| [addVideo(InputStream stream)](#addVideo-java.io.InputStream-) | Creates and adds a video to a presentation from stream. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Creates and adds a video to a presentation from stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Creates and adds a video to a presentation from byte array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies videos to specified array starting from specified index. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```


Returns a number of video files in the collection. Read-only int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


Gets the element at the specified index. Read-only [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


Adds a copy of an video file from an another presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Source video. |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - Added video.
### addVideo(InputStream stream) {#addVideo-java.io.InputStream-}
```
public final IVideo addVideo(InputStream stream)
```


Creates and adds a video to a presentation from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add video file from. |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - Added [Video](../../com.aspose.slides/video).
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Creates and adds a video to a presentation from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add video file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - Added [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


Creates and adds a video to a presentation from byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| videoData | byte[] | Video bytes. |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - Added video.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies videos to specified array starting from specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - An java.util.Iterator for the entire collection.
