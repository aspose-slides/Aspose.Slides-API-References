---
title: IVideoFrame
second_title: Aspose.Slides for Java API 參考文件
description: 代表投影片上的影片剪輯。
type: docs
url: /zh-hant/com.aspose.slides/ivideoframe/
---
**所有已實作的介面:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

代表投影片上的影片剪輯。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 判斷影片是否在播放完畢後自動倒帶至開頭。 |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 判斷影片是否在播放完畢後自動倒帶至開頭。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 判斷影片是否循環播放。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 判斷影片是否循環播放。 |
| [getHideAtShowing()](#getHideAtShowing--) | 判斷 VideoFrame 是否隱藏。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | 判斷 VideoFrame 是否隱藏。 |
| [getVolume()](#getVolume--) | 取得或設定音訊音量。 |
| [setVolume(int value)](#setVolume-int-) | 取得或設定音訊音量。 |
| [getVolumeValue()](#getVolumeValue--) | 取得或設定影片的精確音量（百分比）。 |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 取得或設定影片的精確音量（百分比）。 |
| [getPlayMode()](#getPlayMode--) | 取得或設定影片播放模式。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 取得或設定影片播放模式。 |
| [getFullScreenMode()](#getFullScreenMode--) | 判斷影片是否以全螢幕模式顯示。 |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | 判斷影片是否以全螢幕模式顯示。 |
| [getLinkPathLong()](#getLinkPathLong--) | 取得或設定連結至 VideoFrame 的影片檔案名稱。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 取得或設定連結至 VideoFrame 的影片檔案名稱。 |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 取得或設定嵌入式影片物件。 |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 取得或設定嵌入式影片物件。 |
| [getTrimFromStart()](#getTrimFromStart--) | 剪裁開始 [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 剪裁開始 [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 剪裁結束 [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 剪裁結束 [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | 取得與音訊框相關的字幕集合。 |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

判斷影片是否在播放完畢後自動倒帶至開頭。可讀寫 boolean。

**返回值:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

判斷影片是否在播放完畢後自動倒帶至開頭。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

判斷影片是否循環播放。可讀寫 boolean。

**返回值:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

判斷影片是否循環播放。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

判斷 VideoFrame 是否隱藏。可讀寫 boolean。

**返回值:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

判斷 VideoFrame 是否隱藏。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

取得或設定音訊音量。可讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**返回值:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

取得或設定音訊音量。可讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

取得或設定影片的精確音量（百分比）。該數值以 0 到 100 的百分比表示。使用此屬性可讀寫比透過 Volume（\#getVolume.getVolume/\#setVolume(int).setVolume(int)）屬性提供的預先定義等級更精確的音量值。可讀寫 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 讀取目前的精確音量並將其設定為 75.5 百分比。
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

取得或設定影片的精確音量（百分比）。該數值以 0 到 100 的百分比表示。使用此屬性可讀寫比透過 Volume（\#getVolume.getVolume/\#setVolume(int).setVolume(int)）屬性提供的預先定義等級更精確的音量值。可讀寫 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 讀取目前的精確音量並將其設定為 75.5 百分比。
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

取得或設定影片播放模式。可讀寫 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**返回值:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

取得或設定影片播放模式。可讀寫 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

判斷影片是否以全螢幕模式顯示。可讀寫 boolean。

**返回值:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

判斷影片是否以全螢幕模式顯示。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

取得或設定連結至 VideoFrame 的影片檔案名稱。可讀寫 String。

**返回值:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

取得或設定連結至 VideoFrame 的影片檔案名稱。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

取得或設定嵌入式影片物件。可讀寫 [IVideo](../../com.aspose.slides/ivideo)。

**返回值:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

取得或設定嵌入式影片物件。可讀寫 [IVideo](../../com.aspose.slides/ivideo)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

剪裁開始 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //設定修剪開始時間 1秒
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
public abstract void setTrimFromStart(float value)
```

剪裁開始 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //設定修剪開始時間 1秒
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
public abstract float getTrimFromEnd()
```

剪裁結束 [ms]

**返回值:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

剪裁結束 [ms]

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

取得與音訊框相關的字幕集合。此屬性為唯讀，並回傳包含所有字幕軌道的 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)。

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
>              // 提取字幕的二進位資料並保存到檔案
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