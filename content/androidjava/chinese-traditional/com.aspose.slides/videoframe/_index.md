---
title: VideoFrame
second_title: Aspose.Slides 針對 Android 的 Java API 參考
description: 表示投影片上的影片剪輯。
type: docs
url: /zh-hant/com.aspose.slides/videoframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Represents a video clip on a slide.

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 確定影片在播放完畢後是否會自動倒帶並從頭開始播放。 |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 確定影片在播放完畢後是否會自動倒帶並從頭開始播放。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 確定影片是否循環播放。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 確定影片是否循環播放。 |
| [getHideAtShowing()](#getHideAtShowing--) | 確定 VideoFrame 是否被隱藏。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | 確定 VideoFrame 是否被隱藏。 |
| [getVolume()](#getVolume--) | 返回或設定音訊音量。 |
| [setVolume(int value)](#setVolume-int-) | 返回或設定音訊音量。 |
| [getPlayMode()](#getPlayMode--) | 返回或設定影片播放模式。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 返回或設定影片播放模式。 |
| [getFullScreenMode()](#getFullScreenMode--) | 確定影片是否以全螢幕模式顯示。 |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | 確定影片是否以全螢幕模式顯示。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或設定連結至 VideoFrame 的影片檔案名稱。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或設定連結至 VideoFrame 的影片檔案名稱。 |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 返回或設定嵌入的影片物件。 |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 返回或設定嵌入的影片物件。 |
| [getTrimFromStart()](#getTrimFromStart--) | 修剪起始點 [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 修剪起始點 [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 修剪結束 [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 修剪結束 [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | 取得與 video frame 相關聯的封閉字幕集合。 |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

確定影片在播放完畢後是否會自動倒帶並從頭開始播放。可讀寫 boolean.

**返回值:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

確定影片在播放完畢後是否會自動倒帶並從頭開始播放。可讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

確定影片是否循環播放。可讀寫 boolean.

**返回值:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

確定影片是否循環播放。可讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

確定 VideoFrame 是否被隱藏。可讀寫 boolean.

**返回值:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

確定 VideoFrame 是否被隱藏。可讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

返回或設定音訊音量。可讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**返回值:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

返回或設定音訊音量。可讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

返回或設定影片播放模式。可讀寫 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**返回值:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

返回或設定影片播放模式。可讀寫 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

確定影片是否以全螢幕模式顯示。可讀寫 boolean。

**返回值:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

確定影片是否以全螢幕模式顯示。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

返回或設定連結至 VideoFrame 的影片檔案名稱。可讀寫 String。

**返回值:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

返回或設定連結至 VideoFrame 的影片檔案名稱。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

返回或設定嵌入的影片物件。可讀寫 [IVideo](../../com.aspose.slides/ivideo)。

**返回值:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

返回或設定嵌入的影片物件。可讀寫 [IVideo](../../com.aspose.slides/ivideo)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

修剪起始點 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //設定修剪起始時間 1秒
>      videoFrame.setTrimFromStart(1000f);
>      //設定修剪結束時間 2秒
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

修剪起始點 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //設定修剪起始時間 1秒
>      videoFrame.setTrimFromStart(1000f);
>      //設定修剪結束時間 2秒
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

修剪結束 [ms]

**返回值:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

修剪結束 [ms]

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

取得與 video frame 相關聯的封閉字幕集合。此屬性是唯讀的，並返回一個包含所有字幕軌道的 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)。

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
>              // 擷取字幕的二進位資料並儲存至檔案
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)