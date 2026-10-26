---
title: VideoFrame
second_title: Aspose.Slides for Android の Java API リファレンス
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
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 動画が再生終了した直後に自動的に先頭に巻き戻されるかどうかを決定します。 |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 動画が再生終了した直後に自動的に先頭に巻き戻されるかどうかを決定します。 |
| [getPlayLoopMode()](#getPlayLoopMode--) | 動画がループするかどうかを決定します。 |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 動画がループするかどうかを決定します。 |
| [getHideAtShowing()](#getHideAtShowing--) | VideoFrame が非表示かどうかを決定します。 |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | VideoFrame が非表示かどうかを決定します。 |
| [getVolume()](#getVolume--) | オーディオボリュームを取得または設定します。 |
| [setVolume(int value)](#setVolume-int-) | オーディオボリュームを取得または設定します。 |
| [getPlayMode()](#getPlayMode--) | ビデオ再生モードを取得または設定します。 |
| [setPlayMode(int value)](#setPlayMode-int-) | ビデオ再生モードを取得または設定します。 |
| [getFullScreenMode()](#getFullScreenMode--) | 動画が全画面モードで表示されるかどうかを決定します。 |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | 動画が全画面モードで表示されるかどうかを決定します。 |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame にリンクされているビデオファイルの名前を取得または設定します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame にリンクされているビデオファイルの名前を取得または設定します。 |
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

動画が再生終了した直後に自動的に先頭に巻き戻されるかどうかを決定します。読み取り/書き込み boolean.

**戻り値:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

動画が再生終了した直後に自動的に先頭に巻き戻されるかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

動画がループするかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

動画がループするかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

VideoFrame が非表示かどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

VideoFrame が非表示かどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
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

ビデオ再生モードを取得または設定します。読み取り/書き込み [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**戻り値:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

ビデオ再生モードを取得または設定します。読み取り/書き込み [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

動画が全画面モードで表示されるかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

動画が全画面モードで表示されるかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

VideoFrame にリンクされているビデオファイルの名前を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

VideoFrame にリンクされているビデオファイルの名前を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

埋め込みビデオオブジェクトを取得または設定します。読み取り/書き込み [IVideo](../../com.aspose.slides/ivideo)。

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

埋め込みビデオオブジェクトを取得または設定します。読み取り/書き込み [IVideo](../../com.aspose.slides/ivideo)。

**パラメーター:**
| パラメーター | 型 | 説明 |
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


**戻り値:**
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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

終了トリム [ms]

**戻り値:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

終了トリム [ms]

**パラメーター:**
| パラメーター | 型 | 説明 |
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
>              // Extracts the captions binary data and saves them to the file
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