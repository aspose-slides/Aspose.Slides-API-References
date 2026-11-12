---
title: VideoFrame
second_title: Aspose.Slides for Java API Reference
description: Represents a video clip on a slide.
type: docs
url: /com.aspose.slides/videoframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
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
| [getVolumeValue()](#getVolumeValue--) | Returns or sets the exact video volume as a percentage. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Returns or sets the exact video volume as a percentage. |
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
| [getCaptionTracks()](#getCaptionTracks--) | Gets the collection of closed captions associated with the video frame. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```


Determines whether a video is automatically rewinded to start as soon as the movie has finished playing. Read/write boolean.

**Returns:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```


Determines whether a video is automatically rewinded to start as soon as the movie has finished playing. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Determines whether a video is looped. Read/write boolean.

**Returns:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Determines whether a video is looped. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Determines whether a VideoFrame is hidden. Read/write boolean.

**Returns:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Determines whether a VideoFrame is hidden. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```


Returns or sets the exact video volume as a percentage. The value is expressed as a percentage from 0 to 100. Use this property to read or set volume values that are more precise than the predefined levels available through the \#getVolume.getVolume/\#setVolume(int).setVolume(int) property. Read/write  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Read the current exact volume and set it to 75.5 percent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```


Returns or sets the exact video volume as a percentage. The value is expressed as a percentage from 0 to 100. Use this property to read or set volume values that are more precise than the predefined levels available through the \#getVolume.getVolume/\#setVolume(int).setVolume(int) property. Read/write  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Read the current exact volume and set it to 75.5 percent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


Returns or sets the video play mode. Read/write [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returns:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


Returns or sets the video play mode. Read/write [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```


Determines whether a video is shown in full screen mode. Read/write boolean.

**Returns:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```


Determines whether a video is shown in full screen mode. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Returns or sets the name of an video file which is linked to a VideoFrame. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Returns or sets the name of an video file which is linked to a VideoFrame. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```


Returns or sets embedded video object. Read/write [IVideo](../../com.aspose.slides/ivideo).

**Returns:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```


Returns or sets embedded video object. Read/write [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
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
public final void setTrimFromStart(float value)
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
public final float getTrimFromEnd()
```


Trim end [ms]

**Returns:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


Trim end [ms]

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```


Gets the collection of closed captions associated with the video frame. This property is read-only and returns an [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) containing all caption tracks.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (!(shape instanceof IVideoFrame))
>              continue;
>          IVideoFrame videoFrame = (IVideoFrame) shape;
>          for (ICaptions captionTrack : videoFrame.getCaptionTracks())
>          {
>              // Extracts the captions binary data and saves them to the file
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
