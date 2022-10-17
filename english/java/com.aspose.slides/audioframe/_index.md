---
title: AudioFrame
second_title: Aspose.Slides for Java API Reference
description:   Represents an audio clip on a slide.
type: docs
weight: 23
url: /java/com.aspose.slides/audioframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Represents an audio clip on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Returns or sets a start track index. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Returns or sets a start track index. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Returns or sets a start track time. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Returns or sets a start track time. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Returns or sets a last track index Read/write int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Returns or sets a last track index Read/write int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Returns or sets a last track time. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Returns or sets a last track time. |
| [getVolume()](#getVolume--) | Returns or sets the audio volume. |
| [setVolume(int value)](#setVolume-int-) | Returns or sets the audio volume. |
| [getPlayMode()](#getPlayMode--) | Returns or sets the audio play mode. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returns or sets the audio play mode. |
| [getHideAtShowing()](#getHideAtShowing--) | Determines whether an AudioFrame is hidden. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determines whether an AudioFrame is hidden. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determines whether an audio is looped. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determines whether an audio is looped. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determines whether audio is playing across the slides. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determines whether audio is playing across the slides. |
| [getRewindAudio()](#getRewindAudio--) | Determines whether audio is automatically rewinded to start after playing. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determines whether audio is automatically rewinded to start after playing. |
| [getEmbedded()](#getEmbedded--) | Determines whether a sound is embedded to a presentation. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns or sets the name of an audio file which is linked to an AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns or sets the name of an audio file which is linked to an AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Returns or sets embedded audio object. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Returns or sets embedded audio object. |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```


Returns or sets a start track index. Read/write int.

**Returns:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```


Returns or sets a start track index. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```


Returns or sets a start track time. Read/write int.

**Returns:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```


Returns or sets a start track time. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```


Returns or sets a last track index Read/write int.

**Returns:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```


Returns or sets a last track index Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```


Returns or sets a last track time. Read/write int.

**Returns:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```


Returns or sets a last track time. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```


Returns or sets the audio volume. Read/write [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returns:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```


Returns or sets the audio volume. Read/write [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


Returns or sets the audio play mode. Read/write [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Returns:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


Returns or sets the audio play mode. Read/write [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Determines whether an AudioFrame is hidden. Read/write boolean.

**Returns:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Determines whether an AudioFrame is hidden. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Determines whether an audio is looped. Read/write boolean.

**Returns:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Determines whether an audio is looped. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```


Determines whether audio is playing across the slides. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Returns:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```


Determines whether audio is playing across the slides. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```


Determines whether audio is automatically rewinded to start after playing. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Returns:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```


Determines whether audio is automatically rewinded to start after playing. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```


Determines whether a sound is embedded to a presentation. Read-only boolean.

**Returns:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```


Returns or sets embedded audio object. Read/write [IAudio](../../com.aspose.slides/iaudio).

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```


Returns or sets embedded audio object. Read/write [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

