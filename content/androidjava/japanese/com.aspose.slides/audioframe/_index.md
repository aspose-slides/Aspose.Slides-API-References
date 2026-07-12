---
title: AudioFrame
second_title: Java API リファレンスを使用した Android 用 Aspose.Slides
description: スライド上のオーディオクリップを表します。
type: docs
url: /ja/com.aspose.slides/audioframe/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

スライド上のオーディオクリップを表します。

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // AudioFrame シェイプを取得します
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 再生モードをクリック時に再生に設定します
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // ボリュームを Low に設定します
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // オーディオをスライド全体で再生するように設定します
>      audioFrame.setPlayAcrossSlides(true);
>      // オーディオのループを無効にします
>      audioFrame.setPlayLoopMode(false);
>      // スライドショー中に AudioFrame を非表示にします
>      audioFrame.setHideAtShowing(true);
>      // 再生後にオーディオを開始位置に巻き戻します
>      audioFrame.setRewindAudio(true);
>      // PowerPoint ファイルをディスクに保存します
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | 開始トラックインデックスを取得または設定します。 |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | 開始トラックインデックスを取得または設定します。 |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | 開始トラック時間を取得または設定します。 |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | 開始トラック時間を取得または設定します。 |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | 最後のトラックインデックスを取得または設定します。読み取り/書き込み int。 |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | 最後のトラックインデックスを取得または設定します。読み取り/書き込み int。 |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | 最後のトラック時間を取得または設定します。 |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | 最後のトラック時間を取得または設定します。 |
| [getVolume()](#getVolume--) | オーディオボリュームを取得または設定します。 |
| [setVolume(int value)](#setVolume-int-) | オーディオボリュームを取得または設定します。 |
| [getPlayMode()](#getPlayMode--) | オーディオ再生モードを取得または設定します。 |
| [setPlayMode(int value)](#setPlayMode-int-) | オーディオ再生モードを取得または設定します。 |
| [getHideAtShowing()](#getHideAtShowing--) | AudioFrame が非表示かどうかを判定します。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | AudioFrame が非表示かどうかを判定します。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | オーディオがループ再生かどうかを判定します。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | オーディオがループ再生かどうかを判定します。 |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | オーディオがスライド全体で再生されるかどうかを判定します。 |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | オーディオがスライド全体で再生されるかどうかを判定します。 |
| [getRewindAudio()](#getRewindAudio--) | 再生後にオーディオが自動的に先頭へ巻き戻されるかどうかを判定します。 |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | 再生後にオーディオが自動的に先頭へ巻き戻されるかどうかを判定します。 |
| [getEmbedded()](#getEmbedded--) | サウンドがプレゼンテーションに埋め込まれているかどうかを判定します。 |
| [getLinkPathLong()](#getLinkPathLong--) | AudioFrame にリンクされたオーディオファイルの名前を取得または設定します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | AudioFrame にリンクされたオーディオファイルの名前を取得または設定します。 |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | 埋め込みオーディオオブジェクトを取得または設定します。 |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | 埋め込みオーディオオブジェクトを取得または設定します。 |
| [getFadeInDuration()](#getFadeInDuration--) | メディアの初期フェードイン時間（ミリ秒）を指定します。 |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | メディアの初期フェードイン時間（ミリ秒）を指定します。 |
| [getFadeOutDuration()](#getFadeOutDuration--) | メディアの終了フェードアウト時間（ミリ秒）を指定します。 |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | メディアの終了フェードアウト時間（ミリ秒）を指定します。 |
| [getVolumeValue()](#getVolumeValue--) | オーディオボリュームをパーセントで取得または設定します。 |
| [setVolumeValue(float value)](#setVolumeValue-float-) | オーディオボリュームをパーセントで取得または設定します。 |
| [getTrimFromStart()](#getTrimFromStart--) | 再生中にメディアの開始部分から除去する時間（ミリ秒）を指定します。 |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 再生中にメディアの開始部分から除去する時間（ミリ秒）を指定します。 |
| [getTrimFromEnd()](#getTrimFromEnd--) | 再生中にメディアの終了部分から除去する時間（ミリ秒）を指定します。 |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 再生中にメディアの終了部分から除去する時間（ミリ秒）を指定します。 |
| [getCaptionTracks()](#getCaptionTracks--) | オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。 |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

開始トラックインデックスを取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

開始トラックインデックスを取得または設定します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

開始トラック時間を取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrack(int value)
```

開始トラック時間を取得または設定します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

最後のトラックインデックスを取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

最後のトラックインデックスを取得または設定します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

最後のトラック時間を取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

最後のトラック時間を取得または設定します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

オーディオボリュームを取得または設定します。読み取り/書き込み [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**戻り値:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

オーディオボリュームを取得または設定します。読み取り/書き込み [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

オーディオ再生モードを取得または設定します。読み取り/書き込み [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**戻り値:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

オーディオ再生モードを取得または設定します。読み取り/書き込み [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

AudioFrame が非表示かどうかを判定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

AudioFrame が非表示かどうかを判定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

オーディオがループ再生かどうかを判定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

オーディオがループ再生かどうかを判定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

オーディオがスライド全体で再生されるかどうかを判定します。読み取り/書き込み boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio フレームを追加
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio をスライド全体で再生するように設定
>       audioFrame.setPlayAcrossSlides(true);
>       // 再生後に Audio を自動的に先頭へ巻き戻すように設定
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**戻り値:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

オーディオがスライド全体で再生されるかどうかを判定します。読み取り/書き込み boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio フレームを追加
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio をスライド全体で再生するように設定
>       audioFrame.setPlayAcrossSlides(true);
>       // 再生後に Audio を自動的に先頭へ巻き戻すように設定
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

再生後にオーディオが自動的に先頭へ巻き戻されるかどうかを判定します。読み取り/書き込み boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio フレームを追加
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio をスライド全体で再生するように設定
>       audioFrame.setPlayAcrossSlides(true);
>       // 再生後に Audio を自動的に先頭へ巻き戻すように設定
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**戻り値:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

再生後にオーディオが自動的に先頭へ巻き戻されるかどうかを判定します。読み取り/書き込み boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio フレームを追加
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio をスライド全体で再生するように設定
>       audioFrame.setPlayAcrossSlides(true);
>       // 再生後に Audio を自動的に先頭へ巻き戻すように設定
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

サウンドがプレゼンテーションに埋め込まれているかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

AudioFrame にリンクされたオーディオファイルの名前を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

AudioFrame にリンクされたオーディオファイルの名前を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

埋め込みオーディオオブジェクトを取得または設定します。読み取り/書き込み [IAudio](../../com.aspose.slides/iaudio)。

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

埋め込みオーディオオブジェクトを取得または設定します。読み取り/書き込み [IAudio](../../com.aspose.slides/iaudio)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

メディアの初期フェードイン時間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 開始フェードの持続時間を200msに設定します
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

メディアの初期フェードイン時間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 開始フェードの持続時間を200msに設定します
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

メディアの終了フェードアウト時間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 終了フェードの持続時間を500msに設定します
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

メディアの終了フェードアウト時間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 終了フェードの持続時間を500msに設定します
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> 
```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

オーディオボリュームをパーセントで取得または設定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // オーディオボリュームを85%に設定します
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

オーディオボリュームをパーセントで取得または設定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // オーディオボリュームを85%に設定します
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

再生中にメディアの開始部分から除去する時間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 開始トリミング時間を1.5秒に設定します
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

再生中にメディアの開始部分から除去する時間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 開始トリミング時間を1.5秒に設定します
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

再生中にメディアの終了部分から除去する時間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 終了トリミング時間を2秒に設定します
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

再生中にメディアの終了部分から除去する時間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 終了トリミング時間を2秒に設定します
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) を返します。

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
>              // キャプショントラックのバイナリデータを .vtt ファイルとして保存
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


**戻り値:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)