---
title: VideoFrame
second_title: Aspose.Slides for Java API リファレンス
description: スライド上のビデオクリップを表します。
type: docs
url: /ja/com.aspose.slides/videoframe/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)  
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

スライド上のビデオクリップを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | ビデオが再生完了した直後に自動的に先頭に巻き戻されるかどうかを判定します。 |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | ビデオが再生完了した直後に自動的に先頭に巻き戻されるかどうかを判定します。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | ビデオがループされるかどうかを判定します。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | ビデオがループされるかどうかを判定します。 |
| [getHideAtShowing()](#getHideAtShowing--) | VideoFrame が非表示かどうかを判定します。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | VideoFrame が非表示かどうかを判定します。 |
| [getVolume()](#getVolume--) | オーディオボリュームを取得または設定します。 |
| [setVolume(int value)](#setVolume-int-) | オーディオボリュームを取得または設定します。 |
| [getPlayMode()](#getPlayMode--) | ビデオ再生モードを取得または設定します。 |
| [setPlayMode(int value)](#setPlayMode-int-) | ビデオ再生モードを取得または設定します。 |
| [getFullScreenMode()](#getFullScreenMode--) | ビデオが全画面モードで表示されるかどうかを判定します。 |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | ビデオが全画面モードで表示されるかどうかを判定します。 |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame にリンクされたビデオファイルの名前を取得または設定します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame にリンクされたビデオファイルの名前を取得または設定します。 |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 埋め込みビデオオブジェクトを取得または設定します。 |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 埋め込みビデオオブジェクトを取得または設定します。 |
| [getTrimFromStart()](#getTrimFromStart--) | 開始位置のトリミング [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 開始位置のトリミング [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 終了位置のトリミング [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 終了位置のトリミング [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | ビデオフレームに関連付けられたクローズドキャプションのコレクションを取得します。 |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

ビデオが再生完了した直後に自動的に先頭に巻き戻されるかどうかを判定します。読み書き可能な boolean。

**戻り値:**  
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

ビデオが再生完了した直後に自動的に先頭に巻き戻されるかどうかを判定します。読み書き可能な boolean。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

ビデオがループされるかどうかを判定します。読み書き可能な boolean。

**戻り値:**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

ビデオがループされるかどうかを判定します。読み書き可能な boolean。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

VideoFrame が非表示かどうかを判定します。読み書き可能な boolean。

**戻り値:**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

VideoFrame が非表示かどうかを判定します。読み書き可能な boolean。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

オーディオボリュームを取得または設定します。読み書き可能な [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**戻り値:**  
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

オーディオボリュームを取得または設定します。読み書き可能な [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

ビデオ再生モードを取得または設定します。読み書き可能な [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**戻り値:**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

ビデオ再生モードを取得または設定します。読み書き可能な [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

ビデオが全画面モードで表示されるかどうかを判定します。読み書き可能な boolean。

**戻り値:**  
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

ビデオが全画面モードで表示されるかどうかを判定します。読み書き可能な boolean。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

VideoFrame にリンクされたビデオファイルの名前を取得または設定します。読み書き可能な String。

**戻り値:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

VideoFrame にリンクされたビデオファイルの名前を取得または設定します。読み書き可能な String。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

埋め込みビデオオブジェクトを取得または設定します。読み書き可能な [IVideo](../../com.aspose.slides/ivideo)。

**戻り値:**  
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

埋め込みビデオオブジェクトを取得または設定します。読み書き可能な [IVideo](../../com.aspose.slides/ivideo)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

開始位置のトリミング [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //トリミング開始時間を1秒に設定
>      videoFrame.setTrimFromStart(1000f);
>      //トリミング終了時間を2秒に設定
>      videoFrame.setTrimFromEnd(2000f);
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

開始位置のトリミング [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
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
public final float getTrimFromEnd()
```

終了位置のトリミング [ms]

**戻り値:**  
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

終了位置のトリミング [ms]

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

ビデオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) を返します。

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
>              //キャプションのバイナリデータを抽出し、ファイルに保存します
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