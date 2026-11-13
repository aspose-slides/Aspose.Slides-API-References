---
title: IVideoFrame
second_title: Aspose.Slides for Java API 레퍼런스
description: 슬라이드의 비디오 클립을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ivideoframe/
---
**모든 구현된 인터페이스:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

슬라이드의 비디오 클립을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 비디오가 재생이 끝나자마자 자동으로 시작점으로 되감기되는지 여부를 결정합니다. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 비디오가 재생이 끝나자마자 자동으로 시작점으로 되감기되는지 여부를 결정합니다. |
| [getPlayLoopMode()](#getPlayLoopMode--) | 비디오가 반복 재생되는지 여부를 결정합니다. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 비디오가 반복 재생되는지 여부를 결정합니다. |
| [getHideAtShowing()](#getHideAtShowing--) | VideoFrame이 숨겨져 있는지 여부를 결정합니다. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | VideoFrame이 숨겨져 있는지 여부를 결정합니다. |
| [getVolume()](#getVolume--) | 오디오 볼륨을 가져오거나 설정합니다. |
| [setVolume(int value)](#setVolume-int-) | 오디오 볼륨을 가져오거나 설정합니다. |
| [getVolumeValue()](#getVolumeValue--) | 정확한 비디오 볼륨을 백분율로 가져오거나 설정합니다. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 정확한 비디오 볼륨을 백분율로 가져오거나 설정합니다. |
| [getPlayMode()](#getPlayMode--) | 비디오 재생 모드를 가져오거나 설정합니다. |
| [setPlayMode(int value)](#setPlayMode-int-) | 비디오 재생 모드를 가져오거나 설정합니다. |
| [getFullScreenMode()](#getFullScreenMode--) | 비디오가 전체 화면 모드로 표시되는지 여부를 결정합니다. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | 비디오가 전체 화면 모드로 표시되는지 여부를 결정합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame에 연결된 비디오 파일 이름을 가져오거나 설정합니다. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame에 연결된 비디오 파일 이름을 가져오거나 설정합니다. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 임베드된 비디오 객체를 가져오거나 설정합니다. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 임베드된 비디오 객체를 가져오거나 설정합니다. |
| [getTrimFromStart()](#getTrimFromStart--) | 시작 트림 [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 시작 트림 [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 끝 트림 [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 끝 트림 [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | 오디오 프레임과 연결된 폐쇄 캡션 컬렉션을 가져옵니다. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

비디오가 재생이 끝나자마자 자동으로 시작점으로 되감기되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

비디오가 재생이 끝나자마자 자동으로 시작점으로 되감기되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

비디오가 반복 재생되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

비디오가 반복 재생되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

VideoFrame이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

VideoFrame이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

오디오 볼륨을 가져오거나 설정합니다. 읽기/쓰기 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**반환:**  
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

오디오 볼륨을 가져오거나 설정합니다. 읽기/쓰기 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

정확한 비디오 볼륨을 백분율로 가져오거나 설정합니다. 값은 0에서 100까지의 백분율로 표현됩니다. 이 속성을 사용하여  Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) 속성을 통해 제공되는 미리 정의된 레벨보다 더 정밀한 볼륨 값을 읽거나 설정할 수 있습니다. 읽기/쓰기  float .

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

**반환:**  
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

정확한 비디오 볼륨을 백분율로 가져오거나 설정합니다. 값은 0에서 100까지의 백분율로 표현됩니다. 이 속성을 사용하여  Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) 속성을 통해 제공되는 미리 정의된 레벨보다 더 정밀한 볼륨 값을 읽거나 설정할 수 있습니다. 읽기/쓰기  float .

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

비디오 재생 모드를 가져오거나 설정합니다. 읽기/쓰기 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**반환:**  
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

비디오 재생 모드를 가져오거나 설정합니다. 읽기/쓰기 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

비디오가 전체 화면 모드로 표시되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

비디오가 전체 화면 모드로 표시되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

VideoFrame에 연결된 비디오 파일 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

VideoFrame에 연결된 비디오 파일 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

임베드된 비디오 객체를 가져오거나 설정합니다. 읽기/쓰기 [IVideo](../../com.aspose.slides/ivideo).

**반환:**  
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

임베드된 비디오 객체를 가져오거나 설정합니다. 읽기/쓰기 [IVideo](../../com.aspose.slides/ivideo).

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
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
>      //트리밍 시작 시간 1초 설정
>      videoFrame.setTrimFromStart(1000f);
>      //트리밍 끝 시간 2초 설정
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**  
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
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
>      //트리밍 시작 시간 1초 설정
>      videoFrame.setTrimFromStart(1000f);
>      //트리밍 끝 시간 2초 설정
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

끝 트림 [ms]

**반환:**  
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

끝 트림 [ms]

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

오디오 프레임과 연결된 폐쇄 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)를 반환합니다.

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
>              // 캡션 바이너리 데이터를 추출하여 파일에 저장합니다
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**  
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)