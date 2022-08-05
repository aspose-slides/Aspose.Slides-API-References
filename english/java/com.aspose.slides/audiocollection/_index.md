---
title: AudioCollection
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a collection of embedded audio files.
type: docs
weight: 22
url: /java/com.aspose.slides/audiocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Represents a collection of embedded audio files.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns a number of audio files in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Adds a copy of an audio file from an another presentation. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Creates and adds a audio to a presentation from stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Creates and adds a audio to a presentation from stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Creates and adds a audio to a presentation from byte array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies audios to specified array starting from specified index. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```


Returns a number of audio files in the collection. Read-only int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
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
public final IAudio addAudio(IAudio audio)
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
public final IAudio addAudio(InputStream stream)
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
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Creates and adds a audio to a presentation from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add video audio from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


Creates and adds a audio to a presentation from byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Audio bytes. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies audios to specified array starting from specified index.

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
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - An java.util.Iterator for the entire collection.
