---
title: IAudioFrame
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド上のオーディオクリップを表します。
type: docs
url: /ja/com.aspose.slides/iaudioframe/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

スライド上のオーディオクリップを表します。
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
| [getVolume()](#getVolume--) | 音声ボリュームを取得または設定します。 |
| [setVolume(int value)](#setVolume-int-) | 音声ボリュームを取得または設定します。 |
| [getPlayMode()](#getPlayMode--) | 音声の再生モードを取得または設定します。 |
| [setPlayMode(int value)](#setPlayMode-int-) | 音声の再生モードを取得または設定します。 |
| [getHideAtShowing()](#getHideAtShowing--) | AudioFrame が非表示かどうかを判定します。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | AudioFrame が非表示かどうかを判定します。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 音声がループ再生かどうかを判定します。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 音声がループ再生かどうかを判定します。 |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | 音声がスライド間で再生されるかどうかを判定します。 |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | 音声がスライド間で再生されるかどうかを判定します。 |
| [getRewindAudio()](#getRewindAudio--) | 再生後に音声が自動的に先頭へ巻き戻されるかどうかを判定します。 |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | 再生後に音声が自動的に先頭へ巻き戻されるかどうかを判定します。 |
| [getEmbedded()](#getEmbedded--) | サウンドがプレゼンテーションに埋め込まれているかどうかを判定します。 |
| [getLinkPathLong()](#getLinkPathLong--) | AudioFrame にリンクされているオーディオファイルの名前を取得または設定します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | AudioFrame にリンクされているオーディオファイルの名前を取得または設定します。 |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | 埋め込まれたオーディオオブジェクトを取得または設定します。 |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | 埋め込まれたオーディオオブジェクトを取得または設定します。 |
| [getFadeInDuration()](#getFadeInDuration--) | メディアの初期フェードインの時間期間（ミリ秒）を指定します。 |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | メディアの初期フェードインの時間期間（ミリ秒）を指定します。 |
| [getFadeOutDuration()](#getFadeOutDuration--) | メディアの終了フェードアウトの時間期間（ミリ秒）を指定します。 |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | メディアの終了フェードアウトの時間期間（ミリ秒）を指定します。 |
| [getVolumeValue()](#getVolumeValue--) | 音声ボリュームをパーセンテージで取得または設定します。 |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 音声ボリュームをパーセンテージで取得または設定します。 |
| [getTrimFromStart()](#getTrimFromStart--) | 再生中にメディアの開始部分から除去する時間期間（ミリ秒）を指定します。 |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 再生中にメディアの開始部分から除去する時間期間（ミリ秒）を指定します。 |
| [getTrimFromEnd()](#getTrimFromEnd--) | 再生中にメディアの末尾から除去する時間期間（ミリ秒）を指定します。 |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 再生中にメディアの末尾から除去する時間期間（ミリ秒）を指定します。 |
| [getCaptionTracks()](#getCaptionTracks--) | オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。 |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

開始トラックインデックスを取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

開始トラックインデックスを取得または設定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

開始トラック時間を取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

開始トラック時間を取得または設定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

最後のトラックインデックスを取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

最後のトラックインデックスを取得または設定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

最後のトラック時間を取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

最後のトラック時間を取得または設定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

音声ボリュームを取得または設定します。読み取り/書き込み [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**戻り値:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

音声ボリュームを取得または設定します。読み取り/書き込み [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

音声の再生モードを取得または設定します。読み取り/書き込み [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**戻り値:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

音声の再生モードを取得または設定します。読み取り/書き込み [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

AudioFrame が非表示かどうかを判定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

AudioFrame が非表示かどうかを判定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

音声がループ再生かどうかを判定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

音声がループ再生かどうかを判定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

音声がスライド間で再生されるかどうかを判定します。読み取り/書き込み boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
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
public abstract void setPlayAcrossSlides(boolean value)
```

音声がスライド間で再生されるかどうかを判定します。読み取り/書き込み boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // オーディオフレームを追加
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // スライド全体でオーディオを再生するように設定
>       audioFrame.setPlayAcrossSlides(true);
>       // 再生後に自動的に先頭に巻き戻すようにオーディオを設定
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

再生後に音声が自動的に先頭へ巻き戻されるかどうかを判定します。読み取り/書き込み boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // オーディオフレームを追加
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // スライド全体でオーディオを再生するように設定
>       audioFrame.setPlayAcrossSlides(true);
>       // 再生後に自動的に先頭に巻き戻すようにオーディオを設定
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
public abstract void setRewindAudio(boolean value)
```

再生後に音声が自動的に先頭へ巻き戻されるかどうかを判定します。読み取り/書き込み boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // オーディオフレームを追加
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // スライド全体でオーディオを再生するように設定
>       audioFrame.setPlayAcrossSlides(true);
>       // 再生後に自動的に先頭に巻き戻すようにオーディオを設定
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

サウンドがプレゼンテーションに埋め込まれているかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

AudioFrame にリンクされているオーディオファイルの名前を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

AudioFrame にリンクされているオーディオファイルの名前を取得または設定します。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

埋め込まれたオーディオオブジェクトを取得または設定します。読み取り/書き込み [IAudio](../../com.aspose.slides/iaudio)。

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

埋め込まれたオーディオオブジェクトを取得または設定します。読み取り/書き込み [IAudio](../../com.aspose.slides/iaudio)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

メディアの初期フェードインの時間期間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 開始フェードの期間を200ミリ秒に設定します
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
public abstract void setFadeInDuration(float value)
```

メディアの初期フェードインの時間期間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 開始フェードの期間を200ミリ秒に設定します
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

メディアの終了フェードアウトの時間期間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 終了フェードの期間を500ミリ秒に設定します
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
public abstract void setFadeOutDuration(float value)
```

メディアの終了フェードアウトの時間期間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 終了フェードの期間を500ミリ秒に設定します
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

音声ボリュームをパーセンテージで取得または設定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // オーディオのボリュームを85%に設定します
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
public abstract void setVolumeValue(float value)
```

音声ボリュームをパーセンテージで取得または設定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // オーディオのボリュームを85%に設定します
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

再生中にメディアの開始部分から除去する時間期間（ミリ秒）を指定します。読み取り/書き込み float。

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
public abstract void setTrimFromStart(float value)
```

再生中にメディアの開始部分から除去する時間期間（ミリ秒）を指定します。読み取り/書き込み float。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

再生中にメディアの末尾から除去する時間期間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 終端トリミング時間を2秒に設定します
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

再生中にメディアの末尾から除去する時間期間（ミリ秒）を指定します。読み取り/書き込み float。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 終端トリミング時間を2秒に設定します
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) を返します。

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
>             // キャプショントラックのバイナリデータを .vtt ファイルとして保存
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


**戻り値:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)