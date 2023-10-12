---
title: AudioCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/audiocollection/
---

## AudioCollection class

 Represents a collection of embedded audio files.
 
### addAudio {#addAudio}

| Name | Description |
| --- | --- |
| addAudio ([Audio](../audio)) | Adds a copy of an audio file from an another presentation. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| audio | [Audio](../audio) | Source audio. |

 **Result**
[Audio](../audio)


---


### addAudioFromStream  {#addAudioFromStream }

| Name | Description |
| --- | --- |
| addAudioFromStream  (AudioCollection, ReadStream, Function) | Creates and adds a audio to a presentation from stream. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| audiocollection | AudioCollection  | link to self |
| stream | ReadStream | Stream to add audio from. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result**
[Audio](../audio)


---


### addAudioFromStream  {#addAudioFromStream }

| Name | Description |
| --- | --- |
| addAudioFromStream  (AudioCollection, ReadStream, int, Function) | Creates and adds a audio to a presentation from stream. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| audiocollection | AudioCollection  | link to self |
| stream | ReadStream | Stream to add video audio from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result**
[Audio](../audio)


---


### addAudio {#addAudio}

| Name | Description |
| --- | --- |
| addAudio (byte[]) | Creates and adds a audio to a presentation from byte array. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Audio bytes. |

 **Result**
[Audio](../audio)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Result**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. Read-only IAudio. |

 **Result**
[Audio](../audio)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Result**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Result**



---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns a number of audio files in the collection. Read-only int. |

 **Result**
int


---


