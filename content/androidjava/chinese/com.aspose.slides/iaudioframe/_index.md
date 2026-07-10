---
title: IAudioFrame
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片上的音频剪辑。
type: docs
url: /zh/com.aspose.slides/iaudioframe/
---
**所有实现的接口：**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

表示幻灯片上的音频剪辑。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | 返回或设置起始轨道索引。 |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | 返回或设置起始轨道索引。 |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | 返回或设置起始轨道时间。 |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | 返回或设置起始轨道时间。 |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | 返回或设置最后轨道索引 读取/写入 int。 |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | 返回或设置最后轨道索引 读取/写入 int。 |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | 返回或设置最后轨道时间。 |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | 返回或设置最后轨道时间。 |
| [getVolume()](#getVolume--) | 返回或设置音频音量。 |
| [setVolume(int value)](#setVolume-int-) | 返回或设置音频音量。 |
| [getPlayMode()](#getPlayMode--) | 返回或设置音频播放模式。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 返回或设置音频播放模式。 |
| [getHideAtShowing()](#getHideAtShowing--) | 确定 AudioFrame 是否隐藏。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | 确定 AudioFrame 是否隐藏。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 确定 audio 是否循环。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 确定 audio 是否循环。 |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | 确定 audio 是否在幻灯片之间播放。 |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | 确定 audio 是否在幻灯片之间播放。 |
| [getRewindAudio()](#getRewindAudio--) | 确定 audio 是否在播放后自动倒回起点。 |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | 确定 audio 是否在播放后自动倒回起点。 |
| [getEmbedded()](#getEmbedded--) | 确定声音是否嵌入到演示文稿中。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或设置链接到 AudioFrame 的音频文件名称。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或设置链接到 AudioFrame 的音频文件名称。 |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | 返回或设置嵌入的音频对象。 |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | 返回或设置嵌入的音频对象。 |
| [getFadeInDuration()](#getFadeInDuration--) | 指定媒体初始淡入的时间持续量（毫秒）。 |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | 指定媒体初始淡入的时间持续量（毫秒）。 |
| [getFadeOutDuration()](#getFadeOutDuration--) | 指定媒体结束淡出的时间持续量（毫秒）。 |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | 指定媒体结束淡出的时间持续量（毫秒）。 |
| [getVolumeValue()](#getVolumeValue--) | 返回或设置音频音量（百分比）。 |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 返回或设置音频音量（百分比）。 |
| [getTrimFromStart()](#getTrimFromStart--) | 指定在播放期间从媒体开头移除的时间持续量（毫秒）。 |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 指定在播放期间从媒体开头移除的时间持续量（毫秒）。 |
| [getTrimFromEnd()](#getTrimFromEnd--) | 指定在播放期间从媒体末尾移除的时间持续量（毫秒）。 |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 指定在播放期间从媒体末尾移除的时间持续量（毫秒）。 |
| [getCaptionTracks()](#getCaptionTracks--) | 获取与音频帧关联的闭合字幕集合。 |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

返回或设置起始轨道索引。读取/写入 int。

**返回：**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

返回或设置起始轨道索引。读取/写入 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

返回或设置起始轨道时间。读取/写入 int。

**返回：**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

返回或设置起始轨道时间。读取/写入 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

返回或设置最后轨道索引 读取/写入 int。

**返回：**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

返回或设置最后轨道索引 读取/写入 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

返回或设置最后轨道时间。读取/写入 int。

**返回：**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

返回或设置最后轨道时间。读取/写入 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

返回或设置音频音量。读取/写入 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**返回：**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

返回或设置音频音量。读取/写入 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

返回或设置音频播放模式。读取/写入 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**返回：**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

返回或设置音频播放模式。读取/写入 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

确定 AudioFrame 是否隐藏。读取/写入 boolean。

**返回：**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

确定 AudioFrame 是否隐藏。读取/写入 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

确定 audio 是否循环。读取/写入 boolean。

**返回：**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

确定 audio 是否循环。读取/写入 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

确定 audio 是否在幻灯片之间播放。读取/写入 boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 设置音频在幻灯片间播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 设置音频在播放后自动倒回起点
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
public abstract void setPlayAcrossSlides(boolean value)
```

Determines whether an audio is playing across the slides. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 设置音频在幻灯片之间播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 设置音频在播放后自动倒回起点
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
public abstract boolean getRewindAudio()
```

Determines whether an audio is automatically rewinded to start after playing. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 设置音频在幻灯片之间播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 设置音频在播放后自动倒回起点
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
public abstract void setRewindAudio(boolean value)
```

Determines whether an audio is automatically rewinded to start after playing. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 设置音频在幻灯片之间播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 设置音频在播放后自动倒回起点
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
public abstract boolean getEmbedded()
```

Determines whether a sound is embedded to a presentation. Read-only boolean.

**Returns:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Returns or sets embedded audio object. Read/write [IAudio](../../com.aspose.slides/iaudio).

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Returns or sets embedded audio object. Read/write [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Specifies the time duration for the initial fade-in of the media in milliseconds. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置起始淡入的持续时间为200毫秒
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```
Specifies the time duration for the initial fade-in of the media in milliseconds. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置起始淡入的持续时间为200毫秒
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```
Specifies the time duration for the ending fade-out of the media in milliseconds. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置结束淡出的持续时间为500毫秒
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
```
public abstract void setFadeOutDuration(float value)
```
Specifies the time duration for the ending fade-out of the media in milliseconds. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置结束淡出的持续时间为500毫秒
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Returns or sets the audio volume in percents. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置音频音量为85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Returns or sets the audio volume in percents. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置音频音量为85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Read/write float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置起始剪裁时间 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
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
Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Read/write float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置起始剪裁时间 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
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
Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Read/write float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置结束剪裁时间 2 秒
>      audioFrame.setTrimFromEnd(2000f);
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
> 
> **Returns:**
> float
> ### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
> ```
```
public abstract void setTrimFromEnd(float value)
```
Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Read/write float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置结束剪裁时间 2 秒
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()


获取与音频帧关联的闭合字幕集合。此属性为只读，并返回一个包含所有字幕轨道的 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)。

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
>             // Save the caption track's binary data as a .vtt file
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

**返回：**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)