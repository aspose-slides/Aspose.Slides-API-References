---
title: addAudioFrameEmbedded
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapecollection/addaudioframeembedded/
---

## addAudioFrameEmbeddedFromStream (ShapeCollection shapecollection, float x, float y, float width, float height, ReadStream audio_stream, Function callback)  function

 Adds a new audio frame with embedded audio file to the end of a collection.
 Embedded audio file can be a WAV only.
 It adds new audio into Presentation.Audios list.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapecollection | ShapeCollection  | link to self |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | ReadStream | Inout stream with audio data. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[AudioFrame](../../audioframe)


---


## addAudioFrameEmbedded(float x, float y, float width, float height, [Audio](../../audio) audio)  function

 Adds a new audio frame with embedded audio file to the end of a collection.
 It uses audio file from Presentation.Audios list.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio | [Audio](../../audio) | Audio from Presentation.Audios list. |

### Result
[AudioFrame](../../audioframe)


---


