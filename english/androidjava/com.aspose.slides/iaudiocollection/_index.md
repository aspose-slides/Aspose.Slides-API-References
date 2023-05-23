---
title: IAudioCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of embedded audio files.
type: docs
weight: 645
url: /androidjava/com.aspose.slides/iaudiocollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Represents a collection of embedded audio files.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Adds a copy of an audio file from an another presentation. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Creates and adds a audio to a presentation from stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Creates and adds a audio to a presentation from stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Creates and adds a audio to a presentation from byte array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Gets the element at the specified index. Read-only [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Adds a copy of an audio file from an another presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Source audio. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


Creates and adds a audio to a presentation from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add audio from. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Creates and adds a audio to a presentation from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add video audio from. |
| loadingStreamBehavior | int | The [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) which will be applied to the stream. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Creates and adds a audio to a presentation from byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Audio bytes. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
