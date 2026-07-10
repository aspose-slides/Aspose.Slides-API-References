---
title: VideoFrame
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片上的视频剪辑。
type: docs
url: /zh/com.aspose.slides/videoframe/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**所有实现的接口:**  
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)  
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

表示幻灯片上的视频剪辑。  
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 确定视频是否在影片播放完毕后自动倒回到开始。 |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 确定视频是否在影片播放完毕后自动倒回到开始。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 确定视频是否循环播放。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 确定视频是否循环播放。 |
| [getHideAtShowing()](#getHideAtShowing--) | 确定 VideoFrame 是否隐藏。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | 确定 VideoFrame 是否隐藏。 |
| [getVolume()](#getVolume--) | 返回或设置音频音量。 |
| [setVolume(int value)](#setVolume-int-) | 返回或设置音频音量。 |
| [getPlayMode()](#getPlayMode--) | 返回或设置视频播放模式。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 返回或设置视频播放模式。 |
| [getFullScreenMode()](#getFullScreenMode--) | 确定视频是否以全屏模式显示。 |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | 确定视频是否以全屏模式显示。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或设置链接到 VideoFrame 的视频文件名称。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或设置链接到 VideoFrame 的视频文件名称。 |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 返回或设置嵌入的视频对象。 |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 返回或设置嵌入的视频对象。 |
| [getTrimFromStart()](#getTrimFromStart--) | 修剪开始 [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 修剪开始 [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 修剪结束 [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 修剪结束 [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | 获取与视频帧关联的字幕集合。 |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

确定视频是否在影片播放完毕后自动倒回到开始。读/写 boolean。

**返回：**  
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

确定视频是否在影片播放完毕后自动倒回到开始。读/写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

确定视频是否循环播放。读/写 boolean。

**返回：**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

确定视频是否循环播放。读/写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

确定 VideoFrame 是否隐藏。读/写 boolean。

**返回：**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

确定 VideoFrame 是否隐藏。读/写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

返回或设置音频音量。读/写 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**返回：**  
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

返回或设置音频音量。读/写 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

返回或设置视频播放模式。读/写 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**返回：**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

返回或设置视频播放模式。读/写 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

确定视频是否以全屏模式显示。读/写 boolean。

**返回：**  
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

确定视频是否以全屏模式显示。读/写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

返回或设置链接到 VideoFrame 的视频文件名称。读/写 String。

**返回：**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

返回或设置链接到 VideoFrame 的视频文件名称。读/写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

返回或设置嵌入的视频对象。读/写 [IVideo](../../com.aspose.slides/ivideo)。

**返回：**  
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

返回或设置嵌入的视频对象。读/写 [IVideo](../../com.aspose.slides/ivideo)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

修剪开始 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //设置修剪开始时间 1秒
>      videoFrame.setTrimFromStart(1000f);
>      //设置修剪结束时间 2秒
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

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
>      IVideo video = pres.getVideos().addVideo(videoData);
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


获取与视频帧关联的字幕集合。此属性为只读，返回一个 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)，其中包含所有字幕轨道。

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

**返回：**  
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)