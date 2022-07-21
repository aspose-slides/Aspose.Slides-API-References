---
title: addAudioFrameEmbedded
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/shapecollection/addaudioframeembedded/
---

## addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)  method

 Adds a new audio frame with embedded audio file to the end of a collection.
 Embedded audio file can be a WAV only.
 It adds new audio into Presentation.Audios list.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | InputStream | Inout stream with audio data. |

### Returns
[AudioFrame](../../audioframe)


---


## addAudioFrameEmbedded(float x, float y, float width, float height, [Audio](../../audio) audio)  method

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

### Returns
[AudioFrame](../../audioframe)


---


