---
title: IVideoCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of Video objects.
type: docs
url: /com.aspose.slides/ivideocollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Represents a collection of Video objects.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Adds a copy of an video file from an another presentation. |
| [addVideo(InputStream stream)](#addVideo-java.io.InputStream-) | Creates and adds a video to a presentation from stream. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Creates and adds a video to a presentation from stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Creates and adds a video to a presentation from byte array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
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
public abstract IVideo addVideo(IVideo video)
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
public abstract IVideo addVideo(InputStream stream)
```


Creates and adds a video to a presentation from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add video file from. |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - Added [IVideo](../../com.aspose.slides/ivideo).
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
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
public abstract IVideo addVideo(byte[] videoData)
```


Creates and adds a video to a presentation from byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| videoData | byte[] | Video bytes. |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - Added video.
