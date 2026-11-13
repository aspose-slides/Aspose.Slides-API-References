---
title: VideoFrame
second_title: Aspose.Slides for Java API 참조
description: 슬라이드에 있는 비디오 클립을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/videoframe/
---
**상속:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**구현된 모든 인터페이스:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

슬라이드에 있는 비디오 클립을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 동영상이 재생이 끝나면 자동으로 시작점으로 되감는지 여부를 결정합니다. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 동영상이 재생이 끝나면 자동으로 시작점으로 되감는지 여부를 결정합니다. |
| [getPlayLoopMode()](#getPlayLoopMode--) | 동영상이 반복 재생되는지 여부를 결정합니다. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 동영상이 반복 재생되는지 여부를 결정합니다. |
| [getHideAtShowing()](#getHideAtShowing--) | VideoFrame이 숨겨져 있는지 여부를 결정합니다. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | VideoFrame이 숨겨져 있는지 여부를 결정합니다. |
| [getVolume()](#getVolume--) | 오디오 볼륨을 반환하거나 설정합니다. |
| [setVolume(int value)](#setVolume-int-) | 오디오 볼륨을 반환하거나 설정합니다. |
| [getVolumeValue()](#getVolumeValue--) | 비디오 볼륨을 백분율로 정확히 반환하거나 설정합니다. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 비디오 볼륨을 백분율로 정확히 반환하거나 설정합니다. |
| [getPlayMode()](#getPlayMode--) | 비디오 재생 모드를 반환하거나 설정합니다. |
| [setPlayMode(int value)](#setPlayMode-int-) | 비디오 재생 모드를 반환하거나 설정합니다. |
| [getFullScreenMode()](#getFullScreenMode--) | 동영상이 전체 화면 모드로 표시되는지 여부를 결정합니다. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | 동영상이 전체 화면 모드로 표시되는지 여부를 결정합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 내장 비디오 객체를 반환하거나 설정합니다. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 내장 비디오 객체를 반환하거나 설정합니다. |
| [getTrimFromStart()](#getTrimFromStart--) | 시작 트림 [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 시작 트림 [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 끝 트림 [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 끝 트림 [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | 비디오 프레임과 연결된 폐쇄 자막 컬렉션을 가져옵니다. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```


동영상이 재생이 끝나면 자동으로 시작점으로 되감는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```


동영상이 재생이 끝나면 자동으로 시작점으로 되감는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


동영상이 반복 재생되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


동영상이 반복 재생되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


 VideoFrame이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


 VideoFrame이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public final int getVolume()
```


오디오 볼륨을 반환하거나 설정합니다. 읽기/쓰기 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**반환값:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```


오디오 볼륨을 반환하거나 설정합니다. 읽기/쓰기 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```


비디오 볼륨을 백분율로 정확히 반환하거나 설정합니다. 값은 0에서 100까지의 백분율로 표현됩니다. 이 속성은 \#getVolume.getVolume/\#setVolume(int).setVolume(int) 속성을 통해 제공되는 미리 정의된 레벨보다 더 정밀한 볼륨 값을 읽거나 설정하는 데 사용됩니다. 읽기/쓰기 float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 현재 정확한 볼륨을 읽고 75.5%로 설정합니다.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```


비디오 볼륨을 백분율로 정확히 반환하거나 설정합니다. 값은 0에서 100까지의 백분율로 표현됩니다. 이 속성은 \#getVolume.getVolume/\#setVolume(int).setVolume(int) 속성을 통해 제공되는 미리 정의된 레벨보다 더 정밀한 볼륨 값을 읽거나 설정하는 데 사용됩니다. 읽기/쓰기 float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 현재 정확한 볼륨을 읽고 75.5%로 설정합니다.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


비디오 재생 모드를 반환하거나 설정합니다. 읽기/쓰기 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**반환값:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


비디오 재생 모드를 반환하거나 설정합니다. 읽기/쓰기 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```


동영상이 전체 화면 모드로 표시되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```


동영상이 전체 화면 모드로 표시되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```


내장 비디오 객체를 반환하거나 설정합니다. 읽기/쓰기 [IVideo](../../com.aspose.slides/ivideo).

**반환값:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```


내장 비디오 객체를 반환하거나 설정합니다. 읽기/쓰기 [IVideo](../../com.aspose.slides/ivideo).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```


시작 트림 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //시작 트리밍 시간을 1초로 설정
>      videoFrame.setTrimFromStart(1000f);
>      //끝 트리밍 시간을 2초로 설정
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```


시작 트림 [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //시작 트리밍 시간을 1초로 설정
>      videoFrame.setTrimFromStart(1000f);
>      //끝 트리밍 시간을 2초로 설정
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```


끝 트림 [ms]

**반환값:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


끝 트림 [ms]

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```


비디오 프레임과 연결된 폐쇄 자막 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)를 반환합니다.

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
>              // 캡션 바이너리 데이터를 추출하여 파일에 저장합니다.
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)