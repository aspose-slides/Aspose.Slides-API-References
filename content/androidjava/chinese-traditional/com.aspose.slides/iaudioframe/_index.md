---
title: IAudioFrame
second_title: Aspose.Slides for Android Java API 參考
description: 表示投影片上的音訊剪輯。
type: docs
url: /zh-hant/com.aspose.slides/iaudioframe/
---
**所有實作的介面:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

表示投影片上的音訊剪輯。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | 返回或設定起始音軌索引。 |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | 返回或設定起始音軌索引。 |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | 返回或設定起始音軌時間。 |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | 返回或設定起始音軌時間。 |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | 返回或設定最後音軌索引 讀寫 int。 |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | 返回或設定最後音軌索引 讀寫 int。 |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | 返回或設定最後音軌時間。 |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | 返回或設定最後音軌時間。 |
| [getVolume()](#getVolume--) | 返回或設定音訊音量。 |
| [setVolume(int value)](#setVolume-int-) | 返回或設定音訊音量。 |
| [getPlayMode()](#getPlayMode--) | 返回或設定音訊播放模式。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 返回或設定音訊播放模式。 |
| [getHideAtShowing()](#getHideAtShowing--) | 判斷 AudioFrame 是否隱藏。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | 判斷 AudioFrame 是否隱藏。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 判斷音訊是否循環播放。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 判斷音訊是否循環播放。 |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | 判斷音訊是否跨投影片播放。 |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | 判斷音訊是否跨投影片播放。 |
| [getRewindAudio()](#getRewindAudio--) | 判斷音訊在播放後是否自動倒帶至開始。 |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | 判斷音訊在播放後是否自動倒帶至開始。 |
| [getEmbedded()](#getEmbedded--) | 判斷聲音是否嵌入至簡報。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或設定連結至 AudioFrame 的音訊檔案名稱。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或設定連結至 AudioFrame 的音訊檔案名稱。 |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | 返回或設定嵌入的音訊物件。 |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | 返回或設定嵌入的音訊物件。 |
| [getFadeInDuration()](#getFadeInDuration--) | 指定媒體初始淡入的時間持續時間（毫秒）。 |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | 指定媒體初始淡入的時間持續時間（毫秒）。 |
| [getFadeOutDuration()](#getFadeOutDuration--) | 指定媒體結束淡出的時間持續時間（毫秒）。 |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | 指定媒體結束淡出的時間持續時間（毫秒）。 |
| [getVolumeValue()](#getVolumeValue--) | 返回或設定音訊音量（百分比）。 |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 返回或設定音訊音量（百分比）。 |
| [getTrimFromStart()](#getTrimFromStart--) | 指定在播放過程中從媒體開始位置移除的時間持續時間（毫秒）。 |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 指定在播放過程中從媒體開始位置移除的時間持續時間（毫秒）。 |
| [getTrimFromEnd()](#getTrimFromEnd--) | 指定在播放過程中從媒體結尾移除的時間持續時間（毫秒）。 |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 指定在播放過程中從媒體結尾移除的時間持續時間（毫秒）。 |
| [getCaptionTracks()](#getCaptionTracks--) | 取得與音訊框架相關的隱藏式字幕集合。 |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

返回或設定起始音軌索引。讀寫 int。

**回傳：**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

返回或設定起始音軌索引。讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

返回或設定起始音軌時間。讀寫 int。

**回傳：**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

返回或設定起始音軌時間。讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

返回或設定最後音軌索引 讀寫 int。

**回傳：**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

返回或設定最後音軌索引 讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

返回或設定最後音軌時間。讀寫 int。

**回傳：**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

返回或設定最後音軌時間。讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

返回或設定音訊音量。讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**回傳：**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

返回或設定音訊音量。讀寫 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

返回或設定音訊播放模式。讀寫 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**回傳：**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

返回或設定音訊播放模式。讀寫 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

判斷 AudioFrame 是否隱藏。讀寫 boolean。

**回傳：**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

判斷 AudioFrame 是否隱藏。讀寫 boolean。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

判斷音訊是否循環播放。讀寫 boolean。

**回傳：**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

判斷音訊是否循環播放。讀寫 boolean。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

判斷音訊是否跨投影片播放。讀寫 boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 新增音訊框架
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 設定音訊跨投影片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 設定音訊在播放後自動倒帶回起點
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**回傳：**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

判斷音訊是否跨投影片播放。讀寫 boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 新增音訊框架
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 設定音訊跨投影片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 設定音訊在播放後自動倒帶回起點
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

判斷音訊在播放後是否自動倒帶至開始。讀寫 boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 新增音訊框架
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 設定音訊跨投影片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 設定音訊在播放後自動倒帶回起點
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**回傳：**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

判斷音訊在播放後是否自動倒帶至開始。讀寫 boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 新增音訊框架
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 設定音訊跨投影片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 設定音訊在播放後自動倒帶回起點
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

判斷聲音是否嵌入至簡報。唯讀 boolean。

**回傳：**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

返回或設定連結至 AudioFrame 的音訊檔案名稱。讀寫 String。

**回傳：**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

返回或設定連結至 AudioFrame 的音訊檔案名稱。讀寫 String。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

返回或設定嵌入的音訊物件。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

**回傳：**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

返回或設定嵌入的音訊物件。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

指定媒體初始淡入的時間持續時間（毫秒）。讀寫 float。

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


**回傳：**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

指定媒體初始淡入的時間持續時間（毫秒）。讀寫 float。

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

指定媒體結束淡出的時間持續時間（毫秒）。讀寫 float。

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


**回傳：**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

指定媒體結束淡出的時間持續時間（毫秒）。讀寫 float。

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
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


**回傳：**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

指定在播放過程中從媒體開始位置移除的時間持續時間（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定開始剪裁時間 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
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

指定在播放過程中從媒體開始位置移除的時間持續時間（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定開始剪裁時間 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

指定在播放過程中從媒體結尾移除的時間持續時間（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定結束剪裁時間 2 秒
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**回傳：**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

指定在播放過程中從媒體結尾移除的時間持續時間（毫秒）。讀寫 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 設定結束剪裁時間 2 秒
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

取得與音訊框架相關的隱藏式字幕集合。此屬性唯讀，回傳一個 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)，其中包含所有字幕軌道。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>     for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>     {
>         if (shape instanceof IAudioFrame)
>         {
>             IAudioFrame audioFrame = (IAudioFrame) shape;
>             // 將字幕軌道的二進位資料儲存為 .vtt 檔案
>             for (ICaptions captionTrack : audioFrame.getCaptionTracks())
>             {
>                 FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                 fos.write(captionTrack.getBinaryData());
>                 fos.close();
>             }
>         }
>     }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**回傳：**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)