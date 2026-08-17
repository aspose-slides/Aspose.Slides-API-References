---
title: AudioFrame
second_title: Aspose.Slides Java API 参考
description: 表示幻灯片上的音频剪辑。
type: docs
url: /zh/com.aspose.slides/audioframe/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**实现的所有接口：**
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
>      // 播放后将音频倒回到开头
>      audioFrame.setRewindAudio(true);
>      // 将 PowerPoint 文件保存到磁盘
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | 返回或设置起始轨道索引。 |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | 返回或设置起始轨道索引。 |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | 返回或设置起始轨道时间。 |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | 返回或设置起始轨道时间。 |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | 返回或设置最后轨道索引。读/写 int 。 |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | 返回或设置最后轨道索引。读/写 int 。 |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | 返回或设置最后轨道时间。 |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | 返回或设置最后轨道时间。 |
| [getVolume()](#getVolume--) | 返回或设置音频音量。 |
| [setVolume(int value)](#setVolume-int-) | 返回或设置音频音量。 |
| [getPlayMode()](#getPlayMode--) | 返回或设置音频播放模式。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 返回或设置音频播放模式。 |
| [getHideAtShowing()](#getHideAtShowing--) | 确定 AudioFrame 是否隐藏。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | 确定 AudioFrame 是否隐藏。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 确定音频是否循环播放。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 确定音频是否循环播放。 |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | 确定音频是否跨幻灯片播放。 |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | 确定音频是否跨幻灯片播放。 |
| [getRewindAudio()](#getRewindAudio--) | 确定音频播放后是否自动倒回到起始位置。 |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | 确定音频播放后是否自动倒回到起始位置。 |
| [getEmbedded()](#getEmbedded--) | 确定声音是否嵌入演示文稿。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或设置链接到 AudioFrame 的音频文件名称。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或设置链接到 AudioFrame 的音频文件名称。 |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | 返回或设置嵌入的音频对象。 |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | 返回或设置嵌入的音频对象。 |
| [getFadeInDuration()](#getFadeInDuration--) | 指定媒体初始淡入的持续时间（毫秒）。 |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | 指定媒体初始淡入的持续时间（毫秒）。 |
| [getFadeOutDuration()](#getFadeOutDuration--) | 指定媒体结束淡出的持续时间（毫秒）。 |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | 指定媒体结束淡出的持续时间（毫秒）。 |
| [getVolumeValue()](#getVolumeValue--) | 返回或设置音频音量（百分比）。 |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 返回或设置音频音量（百分比）。 |
| [getTrimFromStart()](#getTrimFromStart--) | 指定在播放期间从媒体开头移除的时间长度（毫秒）。 |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 指定在播放期间从媒体开头移除的时间长度（毫秒）。 |
| [getTrimFromEnd()](#getTrimFromEnd--) | 指定在播放期间从媒体结尾移除的时间长度（毫秒）。 |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 指定在播放期间从媒体结尾移除的时间长度（毫秒）。 |
| [getCaptionTracks()](#getCaptionTracks--) | 获取与音频帧关联的闭合字幕集合。 |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

返回或设置起始轨道索引。读/写 int 。

**返回值：**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

返回或设置起始轨道索引。读/写 int 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

返回或设置起始轨道时间。读/写 int 。

**返回值：**
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

返回或设置最后轨道索引。读/写 int 。

**返回值：**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

返回或设置最后轨道索引。读/写 int 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

返回或设置最后轨道时间。读/写 int 。

**返回值：**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

返回或设置最后轨道时间。读/写 int 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

返回或设置音频音量。读/写 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**返回值：**
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

返回或设置音频播放模式。读/写 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**返回值：**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

返回或设置音频播放模式。读/写 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

确定 AudioFrame 是否隐藏。读/写 boolean 。

**返回值：**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

确定 AudioFrame 是否隐藏。读/写 boolean 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

确定音频是否循环播放。读/写 boolean 。

**返回值：**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

确定音频是否循环播放。读/写 boolean 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

确定音频是否跨幻灯片播放。读/写 boolean 。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 将音频设置为跨幻灯片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 将音频设置为播放后自动倒回到起始位置
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

确定音频是否跨幻灯片播放。读/写 boolean 。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 将音频设置为跨幻灯片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 将音频设置为播放后自动倒回到起始位置
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

确定音频播放后是否自动倒回到起始位置。读/写 boolean 。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 将音频设置为跨幻灯片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 将音频设置为播放后自动倒回到起始位置
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

确定音频播放后是否自动倒回到起始位置。读/写 boolean 。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 添加音频帧
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 将音频设置为跨幻灯片播放
>       audioFrame.setPlayAcrossSlides(true);
>       // 将音频设置为播放后自动倒回到起始位置
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

确定声音是否嵌入演示文稿。只读 boolean 。

**返回值：**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

返回或设置链接到 AudioFrame 的音频文件名称。读/写 String。

**返回值：**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

返回或设置链接到 AudioFrame 的音频文件名称。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

返回或设置嵌入的音频对象。读/写 [IAudio](../../com.aspose.slides/iaudio)。

**返回值：**
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

指定媒体初始淡入的持续时间（毫秒）。读/写 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置起始淡入的持续时间为 200 毫秒
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值：**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

指定媒体初始淡入的持续时间（毫秒）。读/写 float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置起始淡入的持续时间为 200 毫秒
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

指定媒体结束淡出的持续时间（毫秒）。读/写 float。

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

**返回值：**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

指定媒体结束淡出的持续时间（毫秒）。读/写 float。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

返回或设置音频音量（百分比）。读/写 float。

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
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值：**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

返回或设置音频音量（百分比）。读/写 float。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

指定在播放期间从媒体开头移除的时间长度（毫秒）。读/写 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置起始修剪时间 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值：**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

指定在播放期间从媒体开头移除的时间长度（毫秒）。读/写 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置起始修剪时间 1.5 秒
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

指定在播放期间从媒体结尾移除的时间长度（毫秒）。读/写 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置结束修剪时间 2 秒
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值：**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

指定在播放期间从媒体结尾移除的时间长度（毫秒）。读/写 float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 设置结束修剪时间 2 秒
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

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
>              // 将字幕轨道的二进制数据保存为 .vtt 文件
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

**返回值：**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)