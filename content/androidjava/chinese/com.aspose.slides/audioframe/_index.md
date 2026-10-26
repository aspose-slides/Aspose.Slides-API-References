---
title: AudioFrame
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片上的音频剪辑。
type: docs
url: /zh/com.aspose.slides/audioframe/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**所有实现的接口：**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

表示幻灯片上的音频剪辑。

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // 获取 AudioFrame 形状
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 将播放模式设置为点击播放
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // 将音量设置为低
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // 将音频设置为跨幻灯片播放
>      audioFrame.setPlayAcrossSlides(true);
>      // 禁用音频循环
>      audioFrame.setPlayLoopMode(false);
>      // 在幻灯片放映期间隐藏 AudioFrame
>      audioFrame.setHideAtShowing(true);
>      // 在播放后将音频倒回到开始
>      audioFrame.setRewindAudio(true);
>      // 将 PowerPoint 文件保存到磁盘
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Returns or sets a start track index. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Returns or sets a start track index. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Returns or sets a start track time. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Returns or sets a start track time. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Returns or sets a last track index Read/write  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Returns or sets a last track index Read/write  int . |
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
| [getFadeInDuration()](#getFadeInDuration--) | Specifies the time duration for the initial fade-in of the media in milliseconds. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Specifies the time duration for the initial fade-in of the media in milliseconds. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Specifies the time duration for the ending fade-out of the media in milliseconds. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Specifies the time duration for the ending fade-out of the media in milliseconds. |
| [getVolumeValue()](#getVolumeValue--) | Returns or sets the audio volume in percents. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Returns or sets the audio volume in percents. |
| [getTrimFromStart()](#getTrimFromStart--) | Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Specifies the time duration to be removed from the end of the media during playback, in milliseconds. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Specifies the time duration to be removed from the end of the media during playback, in milliseconds. |
| [getCaptionTracks()](#getCaptionTracks--) | Gets the collection of closed captions associated with the audio frame. |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```

public final int getAudioCdStartTrack()
```

Returns or sets a start track index. Read/write  int .

**Returns:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Returns or sets a start track index. Read/write  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Returns or sets a start track time. Read/write  int .

**Returns:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

返回或设置起始轨道时间。读/写 int 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```
Returns or sets a last track index Read/write  int .

**Returns:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Returns or sets a last track index Read/write  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Returns or sets a last track time. Read/write  int .

**Returns:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Returns or sets a last track time. Read/write  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

返回或设置音频音量。读/写 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**Returns:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

返回或设置音频音量。读/写 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

返回或设置音频播放模式。读/写 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**Returns:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

返回或设置音频播放模式。读/写 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

确定 AudioFrame 是否隐藏。读/写  boolean .

**Returns:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Determines whether an AudioFrame is hidden. Read/write  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

确定音频是否循环。读/写  boolean .

**Returns:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```
确定音频是否循环。读/写  boolean .

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

确定音频是否跨幻灯片播放。读/写  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 设置音频跨幻灯片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 设置音频在播放后自动倒回到开始
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**返回值：**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Determines whether audio is playing across the slides. Read/write  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 设置音频跨幻灯片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 设置音频在播放后自动倒回到开始
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

确定音频在播放后是否自动倒回到开始。读/写  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 设置音频跨幻灯片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 设置音频在播放后自动倒回到开始
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**返回值：**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

确定音频在播放后是否自动倒回到开始。读/写  boolean .

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 设置音频跨幻灯片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 设置音频在播放后自动倒回到开始
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

确定声音是否嵌入到演示文稿中。只读  boolean .

**Returns:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```
返回或设置链接到 AudioFrame 的音频文件名称。读/写 String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

返回或设置链接到 AudioFrame 的音频文件名称。读/写 String.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```
返回或设置嵌入的音频对象。读/写 [IAudio](../../com.aspose.slides/iaudio)。

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

返回或设置嵌入的音频对象。读/写 [IAudio](../../com.aspose.slides/iaudio)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
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
>      // 将起始淡入持续时间设置为 200 毫秒
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
public final void setFadeInDuration(float value)
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
>      // 将起始淡入的持续时间设置为 200 毫秒
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
public final float getFadeOutDuration()
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
>      // 将结束淡出的持续时间设置为 500 毫秒
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
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
>      // 将结束淡出的持续时间设置为 500 毫秒
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
public final float getVolumeValue()
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
>      // 设置音频音量为 85%
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
public final void setVolumeValue(float value)
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
>      // 将音频音量设置为 85%
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
public final float getTrimFromStart()
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
>      // 设置起始裁剪时间 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
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
>      // 设置起始裁剪时间 1.5 秒
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
public final float getTrimFromEnd()
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
>      // 设置起始裁剪时间 1.5 秒
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
public final void setTrimFromEnd(float value)
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
>      // 设置结束裁剪时间 2 秒
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
public final ICaptionsCollection getCaptionTracks()


获取与音频帧关联的闭合字幕集合。此属性为只读，并返回一个 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)，其中包含所有字幕轨道。

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
>              // Save the caption track's binary data as a .vtt file
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