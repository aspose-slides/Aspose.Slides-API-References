---
title: AudioFrame
second_title: Aspose.Slides for Java API 參考文件
description: 代表投影片上的音訊剪輯。
type: docs
url: /zh-hant/com.aspose.slides/audioframe/
---
**繼承：**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**所有已實作的介面：**  
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)  
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

代表投影片上的音訊剪輯。

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // 取得 AudioFrame 形狀
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 設定播放模式為點擊播放
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // 設定音量為低
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // 設定音訊於投影片間播放
>      audioFrame.setPlayAcrossSlides(true);
>      // 停用音訊的循環播放
>      audioFrame.setPlayLoopMode(false);
>      // 在投影片放映時隱藏 AudioFrame
>      audioFrame.setHideAtShowing(true);
>      // 在播放後將音訊倒回起始點
>      audioFrame.setRewindAudio(true);
>      // 將 PowerPoint 檔案儲存至磁碟
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | 返回或設定起始軌道索引。 |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | 返回或設定起始軌道索引。 |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | 返回或設定起始軌道時間。 |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | 返回或設定起始軌道時間。 |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | 返回或設定最後軌道索引 讀寫  int。 |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | 返回或設定最後軌道索引 讀寫  int。 |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | 返回或設定最後軌道時間。 |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | 返回或設定最後軌道時間。 |
| [getVolume()](#getVolume--) | 返回或設定音訊音量。 |
| [setVolume(int value)](#setVolume-int-) | 返回或設定音訊音量。 |
| [getPlayMode()](#getPlayMode--) | 返回或設定音訊播放模式。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 返回或設定音訊播放模式。 |
| [getHideAtShowing()](#getHideAtShowing--) | 判斷 AudioFrame 是否隱藏。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | 判斷 AudioFrame 是否隱藏。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 判斷音訊是否循環播放。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 判斷音訊是否循環播放。 |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | 判斷音訊是否在投影片間播放。 |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | 判斷音訊是否在投影片間播放。 |
| [getRewindAudio()](#getRewindAudio--) | 判斷音訊在播放完畢後是否自動倒回開始。 |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | 判斷音訊在播放完畢後是否自動倒回開始。 |
| [getEmbedded()](#getEmbedded--) | 判斷聲音是否嵌入至簡報。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或設定連結至 AudioFrame 的音訊檔案名稱。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或設定連結至 AudioFrame 的音訊檔案名稱。 |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | 返回或設定嵌入的音訊物件。 |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | 返回或設定嵌入的音訊物件。 |
| [getFadeInDuration()](#getFadeInDuration--) | 指定媒體初始淡入的時間持續量（毫秒）。 |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | 指定媒體初始淡入的時間持續量（毫秒）。 |
| [getFadeOutDuration()](#getFadeOutDuration--) | 指定媒體結束淡出的時間持續量（毫秒）。 |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | 指定媒體結束淡出的時間持續量（毫秒）。 |
| [getVolumeValue()](#getVolumeValue--) | 返回或設定音訊音量（百分比）。 |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 返回或設定音訊音量（百分比）。 |
| [getTrimFromStart()](#getTrimFromStart--) | 指定在播放期間從媒體開頭移除的時間持續量（毫秒）。 |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 指定在播放期間從媒體開頭移除的時間持續量（毫秒）。 |
| [getTrimFromEnd()](#getTrimFromEnd--) | 指定在播放期間從媒體結尾移除的時間持續量（毫秒）。 |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 指定在播放期間從媒體結尾移除的時間持續量（毫秒）。 |
| [getCaptionTracks()](#getCaptionTracks--) | 取得與音訊畫格相關聯的封閉式字幕集合。 |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

返回或設定起始軌道索引。讀寫  int 。

**返回：**  
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

返回或設定起始軌道索引。讀寫  int 。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

返回或設定起始軌道時間。讀寫  int 。

**返回：**  
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

返回或設定起始軌道時間。讀寫  int 。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

返回或設定最後軌道索引 讀寫  int 。

**返回：**  
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

返回或設定最後軌道索引 讀寫  int 。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

返回或設定最後軌道時間。讀寫  int 。

**返回：**  
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

返回或設定最後軌道時間。讀寫  int 。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

返回或設定音訊音量。讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**返回：**  
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

返回或設定音訊音量。讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

返回或設定音訊播放模式。讀寫 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**返回：**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

返回或設定音訊播放模式。讀寫 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

判斷 AudioFrame 是否隱藏。讀寫  boolean 。

**返回：**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

判斷 AudioFrame 是否隱藏。讀寫  boolean 。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

判斷音訊是否循環播放。讀寫  boolean 。

**返回：**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

判斷音訊是否循環播放。讀寫  boolean 。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

判斷音訊是否在投影片間播放。讀寫  boolean 。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 新增音訊框架
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 設定音訊跨投影片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 設定音訊在播放後自動倒回起始
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**返回：**  
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

判斷音訊是否在投影片間播放。讀寫  boolean 。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 新增音訊框架
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 設定音訊跨投影片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 設定音訊在播放後自動倒回起始
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

判斷音訊在播放完畢後是否自動倒回開始。讀寫  boolean 。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 新增音訊框架
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 設定音訊跨投影片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 設定音訊在播放後自動倒回起始
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**返回：**  
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

判斷音訊在播放完畢後是否自動倒回開始。讀寫  boolean 。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 新增音訊框架
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 設定音訊跨投影片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 設定音訊在播放後自動倒回起始
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

判斷聲音是否嵌入至簡報。唯讀  boolean 。

**返回：**  
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

返回或設定連結至 AudioFrame 的音訊檔案名稱。讀寫 String。

**返回：**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

返回或設定連結至 AudioFrame 的音訊檔案名稱。讀寫 String。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

返回或設定嵌入的音訊物件。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

**返回：**  
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

返回或設定嵌入的音訊物件。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

指定媒體初始淡入的時間持續量（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定起始淡入的持續時間為 200 毫秒
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**  
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

指定媒體初始淡入的時間持續量（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定起始淡入的持續時間為 200 毫秒
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

指定媒體結束淡出的時間持續量（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定結束淡出的持續時間為 500 毫秒
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**  
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

指定媒體結束淡出的時間持續量（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定結束淡出的持續時間為 500 毫秒
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

返回或設定音訊音量（百分比）。讀寫 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定音訊音量為 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**  
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

返回或設定音訊音量（百分比）。讀寫 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定音訊音量為 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

指定在播放期間從媒體開頭移除的時間持續量（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定起始修剪時間 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**  
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public        ️   
```

指定在播放期間從媒體開頭移除的時間持續量（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定起始修剪時間 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

指定在播放期間從媒體結尾移除的時間持續量（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定結束修剪時間 2 秒
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**  
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

指定在播放期間從媒體結尾移除的時間持續量（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定結束修剪時間 2 秒
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

取得與音訊畫格相關聯的封閉式字幕集合。此屬性唯讀，返回一個 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)，其中包含所有字幕軌道。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (shape instanceof IAudioFrame)
>          {
>              IAudioFrame audioFrame = (IAudioFrame) shape;
>              // 將字幕軌道的二進位資料儲存為 .vtt 檔案
>              for (ICaptions captionTrack : audioFrame.getCaptionTracks()) {
>                  FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                  fos.write(captionTrack.getBinaryData());
>                  fos.close();
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**  
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)