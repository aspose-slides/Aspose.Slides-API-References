---
title: IVideoFrame
second_title: Aspose.Slides for Java API Reference
description: Represents a video clip on a slide.
type: docs
weight: 1103
url: /java/com.aspose.slides/ivideoframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Represents a video clip on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Determines whether a video is automatically rewinded to start as soon as the movie has finished playing. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Determines whether a video is automatically rewinded to start as soon as the movie has finished playing. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determines whether a video is looped. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determines whether a video is looped. |
| [getHideAtShowing()](#getHideAtShowing--) | Determines whether a VideoFrame is hidden. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determines whether a VideoFrame is hidden. |
| [getVolume()](#getVolume--) | Returns or sets the audio volume. |
| [setVolume(int value)](#setVolume-int-) | Returns or sets the audio volume. |
| [getPlayMode()](#getPlayMode--) | Returns or sets the video play mode. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returns or sets the video play mode. |
| [getFullScreenMode()](#getFullScreenMode--) | Determines whether a video is shown in full screen mode. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determines whether a video is shown in full screen mode. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns or sets the name of an video file which is linked to a VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns or sets the name of an video file which is linked to a VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Returns or sets embedded video object. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Returns or sets embedded video object. |
| [getTrimFromStart()](#getTrimFromStart--) | Trim start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trim start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trim end [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trim end [ms] |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```


Determines whether a video is automatically rewinded to start as soon as the movie has finished playing. Read/write boolean.

**Returns:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```


Determines whether a video is automatically rewinded to start as soon as the movie has finished playing. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```


Determines whether a video is looped. Read/write boolean.

**Returns:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```


Determines whether a video is looped. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```


Determines whether a VideoFrame is hidden. Read/write boolean.

**Returns:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```


Determines whether a VideoFrame is hidden. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```


Returns or sets the audio volume. Read/write [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returns:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```


Returns or sets the audio volume. Read/write [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```


Returns or sets the video play mode. Read/write [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returns:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```


Returns or sets the video play mode. Read/write [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```


Determines whether a video is shown in full screen mode. Read/write boolean.

**Returns:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```


Determines whether a video is shown in full screen mode. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Returns or sets the name of an video file which is linked to a VideoFrame. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Returns or sets the name of an video file which is linked to a VideoFrame. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```


Returns or sets embedded video object. Read/write [IVideo](../../com.aspose.slides/ivideo).

**Returns:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```


Returns or sets embedded video object. Read/write [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```


Trim start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```


Trim start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```


Trim end [ms]

**Returns:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```


Trim end [ms]

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

