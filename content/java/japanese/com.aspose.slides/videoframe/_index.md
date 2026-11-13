---
title: VideoFrame
second_title: Aspose.Slides for Java API リファレンス
description: スライド上のビデオクリップを表します。
type: docs
url: /ja/com.aspose.slides/videoframe/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)  
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

スライド上のビデオクリップを表します。

## Methods

| メソッド | 説明 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 映画の再生が終了した直後にビデオが自動的に先頭に巻き戻されるかどうかを判定します。 |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 映画の再生が終了した直後にビデオが自動的に先頭に巻き戻されるかどうかを判定します。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | ビデオがループ再生されるかどうかを判定します。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | ビデオがループ再生されるかどうかを判定します。 |
| [getHideAtShowing()](#getHideAtShowing--) | VideoFrame が非表示かどうかを判定します。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | VideoFrame が非表示かどうかを判定します。 |
| [getVolume()](#getVolume--) | オーディオボリュームを取得または設定します。 |
| [setVolume(int value)](#setVolume-int-) | オーディオボリュームを取得または設定します。 |
| [getVolumeValue()](#getVolumeValue--) | ビデオボリュームをパーセンテージで正確に取得または設定します。 |
| [setVolumeValue(float value)](#setVolumeValue-float-) | ビデオボリュームをパーセンテージで正確に取得または設定します。 |
| [getPlayMode()](#getPlayMode--) | ビデオ再生モードを取得または設定します。 |
| [setPlayMode(int value)](#setPlayMode-int-) | ビデオ再生モードを取得または設定します。 |
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
| [getCaptionTracks()](#getCaptionTracks--) | ビデオフレームに関連付けられたクローズドキャプションのコレクションを取得します。 |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

映画の再生が終了した直後にビデオが自動的に先頭に巻き戻されるかどうかを判定します。読み取り/書き込み boolean.

**Returns:**  
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

映画の再生が終了した直後にビデオが自動的に先頭に巻き戻されるかどうかを判定します。読み取り/書き込み boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

ビデオがループ再生されるかどうかを判定します。読み取り/書き込み boolean.

**Returns:**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

ビデオがループ再生されるかどうかを判定します。読み取り/書き込み boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

VideoFrame が非表示かどうかを判定します。読み取り/書き込み boolean.

**Returns:**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

VideoFrame が非表示かどうかを判定します。読み取り/書き込み boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

オーディオボリュームを取得または設定します。読み取り/書き込み [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returns:**  
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

オーディオボリュームを取得または設定します。読み取り/書き込み [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

ビデオボリュームをパーセンテージで正確に取得または設定します。値は 0 から 100 のパーセンテージで表されます。#getVolume.getVolume/#setVolume(int) プロパティよりも細かい音量を読み書きする場合に使用します。読み取り/書き込み float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 現在の正確な音量を読み取り、75.5% に設定します。
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
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

ビデオボリュームをパーセンテージで正確に取得または設定します。値は 0 から 100 のパーセンテージで表されます。#getVolume.getVolume/#setVolume(int) プロパティよりも細かい音量を読み書きする場合に使用します。読み取り/書き込み float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 現在の正確な音量を読み取り、75.5% に設定します。
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

ビデオ再生モードを取得または設定します。読み取り/書き込み [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returns:**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

ビデオ再生モードを取得または設定します。読み取り/書き込み [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

ビデオが全画面モードで表示されるかどうかを判定します。読み取り/書き込み boolean.

**Returns:**  
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

ビデオが全画面モードで表示されるかどうかを判定します。読み取り/書き込み boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

VideoFrame にリンクされたビデオファイルの名前を取得または設定します。読み取り/書き込み String.

**Returns:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

VideoFrame にリンクされたビデオファイルの名前を取得または設定します。読み取り/書き込み String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

埋め込みビデオオブジェクトを取得または設定します。読み取り/書き込み [IVideo](../../com.aspose.slides/ivideo).

**Returns:**  
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

埋め込みビデオオブジェクトを取得または設定します。読み取り/書き込み [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

開始トリム [ms]

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

**Returns:**  
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

開始トリム [ms]

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

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

終了トリム [ms]

**Returns:**  
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

終了トリム [ms]

**Parameters:**  
| Parameter | Type | Description |
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
>              // キャプションのバイナリデータを抽出し、ファイルに保存します。
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**  
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)