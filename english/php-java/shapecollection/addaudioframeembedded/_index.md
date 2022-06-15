---
title: addAudioFrameEmbedded
type: docs
weight: 20
url: /php-java/shapecollection/addaudioframeembedded/
---

# addAudioFrameEmbedded(float, float, float, float, java.io.InputStream) method

 Adds a new audio frame with embedded audio file to the end of a collection.
 Embedded audio file can be a WAV only.
 It adds new audio into Presentation.Audios list.
 

##  Parameters

| name | description |
| --- | --- |
| x | X coordinate of a new audio frame. |
| y | Y coordinate of a new audio frame. |
| width | Width of a new audio frame. |
| height | Height of a new audio frame. |
| audio_stream | Inout stream with audio data. |

##  Returns
Created AudioFrame object.


# addAudioFrameEmbedded(float, float, float, float, com.aspose.slides.IAudio) method

 Adds a new audio frame with embedded audio file to the end of a collection.
 It uses audio file from Presentation.Audios list.
 

##  Parameters

| name | description |
| --- | --- |
| x | X coordinate of a new audio frame. |
| y | Y coordinate of a new audio frame. |
| width | Width of a new audio frame. |
| height | Height of a new audio frame. |
| audio | Audio from Presentation.Audios list. |

##  Returns
Created AudioFrame object.


