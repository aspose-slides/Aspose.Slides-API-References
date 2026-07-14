---
title: IVideoFrame
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 슬라이드에 있는 비디오 클립을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ivideoframe/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

슬라이드에 있는 비디오 클립을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | 동영상이 재생이 끝나자마자 자동으로 시작 지점으로 되감기 되는지 여부를 결정합니다. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | 동영상이 재생이 끝나자마자 자동으로 시작 지점으로 되감기 되는지 여부를 결정합니다. |
| [getPlayLoopMode()](#getPlayLoopMode--) | 동영상이 반복되는지 여부를 결정합니다. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 동영상이 반복되는지 여부를 결정합니다. |
| [getHideAtShowing()](#getHideAtShowing--) | VideoFrame이 숨겨져 있는지 여부를 결정합니다. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | VideoFrame이 숨겨져 있는지 여부를 결정합니다. |
| [getVolume()](#getVolume--) | 오디오 볼륨을 반환하거나 설정합니다. |
| [setVolume(int value)](#setVolume-int-) | 오디오 볼륨을 반환하거나 설정합니다. |
| [getPlayMode()](#getPlayMode--) | 비디오 재생 모드를 반환하거나 설정합니다. |
| [setPlayMode(int value)](#setPlayMode-int-) | 비디오 재생 모드를 반환하거나 설정합니다. |
| [getFullScreenMode()](#getFullScreenMode--) | 동영상이 전체 화면 모드로 표시되는지 여부를 결정합니다. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | 동영상이 전체 화면 모드로 표시되는지 여부를 결정합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | 임베디드 비디오 객체를 반환하거나 설정합니다. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | 임베디드 비디오 객체를 반환하거나 설정합니다. |
| [getTrimFromStart()](#getTrimFromStart--) | 시작 트림 [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 시작 트림 [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | 끝 트림 [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 끝 트림 [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | 오디오 프레임과 연관된 폐쇄 캡션 컬렉션을 가져옵니다. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

동영상이 재생이 끝나자마자 자동으로 시작 지점으로 되감기 되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

동영상이 재생이 끝나자마자 자동으로 시작 지점으로 되감기 되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

동영상이 반복되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

동영상이 반복되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

오디오 볼륨을 반환하거나 설정합니다. 읽기/쓰기 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**반환:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

오디오 볼륨을 반환하거나 설정합니다. 읽기/쓰기 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

비디오 재생 모드를 반환하거나 설정합니다. 읽기/쓰기 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**반환:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

비디오 재생 모드를 반환하거나 설정합니다. 읽기/쓰기 [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

동영상이 전체 화면 모드로 표시되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

동영상이 전체 화면 모드로 표시되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

임베디드 비디오 객체를 반환하거나 설정합니다. 읽기/쓰기 [IVideo](../../com.aspose.slides/ivideo).

**반환:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

임베디드 비디오 객체를 반환하거나 설정합니다. 읽기/쓰기 [IVideo](../../com.aspose.slides/ivideo).

**매개변수:**
| 매개변수 | 형식 | 설명 |
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
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //트리밍 시작 시간 1초 설정
>      videoFrame.setTrimFromStart(1000f);
>      //트리밍 종료 시간 2초 설정
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
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //트리밍 시작 시간 1초 설정
>      videoFrame.setTrimFromStart(1000f);
>      //트리밍 종료 시간 2초 설정
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

오디오 프레임과 연관된 폐쇄 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)를 반환합니다.

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