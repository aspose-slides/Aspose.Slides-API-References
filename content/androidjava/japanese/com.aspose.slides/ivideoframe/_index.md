---
title: IVideoFrame
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド上のビデオクリップを表します。
type: docs
url: /ja/com.aspose.slides/ivideoframe/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

スライド上のビデオクリップを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | ムービーの再生が終了した直後に、ビデオが自動的に先頭に巻き戻されるかどうかを判定します。 |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | ムービーの再生が終了した直後に、ビデオが自動的に先頭に巻き戻されるかどうかを判定します。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | ビデオがループ再生されるかどうかを判定します。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | ビデオがループ再生されるかどうかを判定します。 |
| [getHideAtShowing()](#getHideAtShowing--) | VideoFrame が非表示かどうかを判定します。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | VideoFrame が非表示かどうかを判定します。 |
| [getVolume()](#getVolume--) | オーディオのボリュームを取得または設定します。 |
| [setVolume(int value)](#setVolume-int-) | オーディオのボリュームを取得または設定します。 |
| [getPlayMode()](#getPlayMode--) | ビデオの再生モードを取得または設定します。 |
| [setPlayMode(int value)](#setPlayMode-int-) | ビデオの再生モードを取得または設定します。 |
| [getFullScreenMode()](#getFullScreenMode--) | ビデオが全画面モードで表示されるかどうかを判定します。 |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | ビデオが全画面モードで表示されるかどうかを判定します。 |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame にリンクされたビデオファイルの名前を取得または設定します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame にリンクされたビデオファイルの名前を取得または設定します。 |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 埋め込みビデオオブジェクトを取得または設定します。 |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 埋め込みビデオオブジェクトを取得または設定します。 |
| [getTrimFromStart()](#getTrimFromStart--) | 開始トリム [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 開始トリム [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 終了トリム [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 終了トリム [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | オーディオ フレームに関連付けられたクローズドキャプションのコレクションを取得します。 |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```


ムービーの再生が終了した直後に、ビデオが自動的に先頭に巻き戻されるかどうかを判定します。 読み書き boolean.

**戻り値:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```


ムービーの再生が終了した直後に、ビデオが自動的に先頭に巻き戻されるかどうかを判定します。 読み書き boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```


ビデオがループ再生されるかどうかを判定します。 読み書き boolean.

**戻り値:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```


ビデオがループ再生されるかどうかを判定します。 読み書き boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```


VideoFrame が非表示かどうかを判定します。 読み書き boolean.

**戻り値:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```


VideoFrame が非表示かどうかを判定します。 読み書き boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```


オーディオのボリュームを取得または設定します。 読み書き [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**戻り値:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```


オーディオのボリュームを取得または設定します。 読み書き [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```


ビデオの再生モードを取得または設定します。 読み書き [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**戻り値:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```


ビデオの再生モードを取得または設定します。 読み書き [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```


ビデオが全画面モードで表示されるかどうかを判定します。 読み書き boolean.

**戻り値:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```


ビデオが全画面モードで表示されるかどうかを判定します。 読み書き boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


VideoFrame にリンクされたビデオファイルの名前を取得または設定します。 読み書き String.

**戻り値:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


VideoFrame にリンクされたビデオファイルの名前を取得または設定します。 読み書き String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```


埋め込みビデオオブジェクトを取得または設定します。 読み書き [IVideo](../../com.aspose.slides/ivideo).

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```


埋め込みビデオオブジェクトを取得または設定します。 読み書き [IVideo](../../com.aspose.slides/ivideo).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```


開始トリム [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //トリミング開始時間を 1秒に設定
>      videoFrame.setTrimFromStart(1000f);
>      //トリミング終了時間を 2秒に設定
>      videoFrame.setTrimFromEnd(2000f);
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


開始トリム [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //トリミング開始時間を1秒に設定
>      videoFrame.setTrimFromStart(1000f);
>      //トリミング終了時間を2秒に設定
>      videoFrame.setTrimFromEnd(2000f);
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


終了トリム [ms]

**戻り値:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```


終了トリム [ms]

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```


オーディオ フレームに関連付けられたクローズドキャプションのコレクションを取得します。 このプロパティは読み取り専用であり、すべてのキャプショントラックを含む [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) を返します。

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
>              // キャプションのバイナリデータを抽出し、ファイルに保存します
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)