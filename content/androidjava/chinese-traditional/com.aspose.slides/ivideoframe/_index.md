---
title: IVideoFrame
second_title: Aspose.Slides for Android via Java API 參考
description: 表示投影片上的影片剪輯。
type: docs
url: /zh-hant/com.aspose.slides/ivideoframe/
---
**所有已實作的介面：**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

代表投影片上的影片剪輯。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 判斷影片是否在播放結束後自動倒回至開始。 |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 判斷影片是否在播放結束後自動倒回至開始。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 判斷影片是否循環播放。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 判斷影片是否循環播放。 |
| [getHideAtShowing()](#getHideAtShowing--) | 判斷 VideoFrame 是否隱藏。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | 判斷 VideoFrame 是否隱藏。 |
| [getVolume()](#getVolume--) | 取得或設定音訊音量。 |
| [setVolume(int value)](#setVolume-int-) | 取得或設定音訊音量。 |
| [getPlayMode()](#getPlayMode--) | 取得或設定影片播放模式。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 取得或設定影片播放模式。 |
| [getFullScreenMode()](#getFullScreenMode--) | 判斷影片是否以全螢幕模式顯示。 |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | 判斷影片是否以全螢幕模式顯示。 |
| [getLinkPathLong()](#getLinkPathLong--) | 取得或設定連結至 VideoFrame 的影片檔案名稱。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 取得或設定連結至 VideoFrame 的影片檔案名稱。 |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 取得或設定嵌入式影片物件。 |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 取得或設定嵌入式影片物件。 |
| [getTrimFromStart()](#getTrimFromStart--) | 剪裁起始 [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 剪裁起始 [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 剪裁結束 [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 剪裁結束 [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | 取得與音訊框架相關聯的隱藏式字幕集合。 |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

判斷影片是否在播放結束後自動倒回至開始。讀寫 boolean。

**回傳：**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

判斷影片是否在播放結束後自動倒回至開始。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

判斷影片是否循環播放。讀寫 boolean。

**回傳：**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

判斷影片是否循環播放。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

判斷 VideoFrame 是否隱藏。讀寫 boolean。

**回傳：**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

判斷 VideoFrame 是否隱藏。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

取得或設定音訊音量。讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**回傳：**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

取得或設定音訊音量。讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

取得或設定影片播放模式。讀寫 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**回傳：**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

取得或設定影片播放模式。讀寫 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

判斷影片是否以全螢幕模式顯示。讀寫 boolean。

**回傳：**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

判斷影片是否以全螢幕模式顯示。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

取得或設定連結至 VideoFrame 的影片檔案名稱。讀寫 String。

**回傳：**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

取得或設定連結至 VideoFrame 的影片檔案名稱。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

取得或設定嵌入式影片物件。讀寫 [IVideo](../../com.aspose.slides/ivideo)。

**回傳：**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

取得或設定嵌入式影片物件。讀寫 [IVideo](../../com.aspose.slides/ivideo)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

剪裁起始 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //設定剪裁起始時間 1秒
>      videoFrame.setTrimFromStart(1000f);
>      //設定剪裁結束時間 2秒
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**回傳：**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

剪裁起始 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //設定剪裁起始時間 1秒
>      videoFrame.setTrimFromStart(1000f);
>      //設定剪裁結束時間 2秒
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

剪裁結束 [ms]

**回傳：**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

剪裁結束 [ms]

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

取得與音訊框架相關聯的隱藏式字幕集合。此屬性唯讀，返回一個 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)，其中包含所有字幕軌道。

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
>              // 提取字幕的二進位資料並將其儲存到檔案
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**回傳：**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)