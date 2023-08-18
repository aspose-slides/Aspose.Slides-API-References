---
title: insertAudioFrameEmbedded
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapecollection/insertaudioframeembedded/
---

## insertAudioFrameEmbeddedFromStream (ShapeCollection shapecollection, int index, float x, float y, float width, float height, ReadStream audio_stream, Function callback)  function

 Insert an AudioFrame with embedded audio file.
 Embedded audio file sound can be a WAV only.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapecollection | ShapeCollection  | link to self |
| index | int | The zero-based index at which value should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | ReadStream | Audio stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[AudioFrame](../../audioframe)


---


## insertAudioFrameEmbedded(int index, float x, float y, float width, float height, [Audio](../../audio) audio)  function

 Insert an AudioFrame with embedded audio file.
 It uses audio file from Presentation.Audios list.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio | [Audio](../../audio) | Audio from Presentation.Audios list. |

### Result
[AudioFrame](../../audioframe)


---


