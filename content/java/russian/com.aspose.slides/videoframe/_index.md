---
title: VideoFrame
second_title: Справочник API Aspose.Slides для Java
description: Представляет видеоклип на слайде.
type: docs
url: /ru/com.aspose.slides/videoframe/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Все реализованные интерфейсы:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Представляет видеоклип на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Determines whether a video is automatically rewinded to start as soon as the movie has finished playing. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Determines whether a video is automatically rewinded to start as soon as the movie has finished playing. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determines whether a video is looped. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determines whether a video is looped. |
| [getHideAtShowing()](#getHideAtShowing--) | Determines whether a VideoFrame is hidden. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determines whether a VideoFrame is hidden. |
| [getVolume()](#getVolume--) | Returns or sets the audio volume. |
| [setVolume(int value)](#setVolume-int-) | Returns or sets the audio volume. |
| [getPlayMode()](#getPlayMode--) | Returns or sets the video play mode. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returns or sets the video play mode. |
| [getFullScreenMode()](#getFullScreenMode--) | Determines whether a video is shown in full screen mode. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determines whether a video is shown in full screen mode. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns or sets the name of an video file which is linked to a VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns or sets the name of an video file which is linked to a VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Returns or sets embedded video object. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Returns or sets embedded video object. |
| [getTrimFromStart()](#getTrimFromStart--) | Trim start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trim start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trim end [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trim end [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Gets the collection of closed captions associated with the video frame. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```


Определяет, будет ли видео автоматически перемотано в начало сразу после завершения воспроизведения. Чтение/запись boolean.

**Возвращает:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```


Определяет, будет ли видео автоматически перемотано в начало сразу после завершения воспроизведения. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Определяет, будет ли видео воспроизводиться в цикле. Чтение/запись boolean.

**Возвращает:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Определяет, будет ли видео воспроизводиться в цикле. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Определяет, скрыт ли VideoFrame. Чтение/запись boolean.

**Возвращает:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Определяет, скрыт ли VideoFrame. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```


Возвращает или задает громкость аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Возвращает:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```


Возвращает или задает громкость аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


Возвращает или задает режим воспроизведения видео. Чтение/запись [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Возвращает:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


Возвращает или задает режим воспроизведения видео. Чтение/запись [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```


Определяет, показывается ли видео в полноэкранном режиме. Чтение/запись boolean.

**Возвращает:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```


Определяет, показывается ли видео в полноэкранном режиме. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Возвращает или задает имя видеофайла, связанного с VideoFrame. Чтение/запись String.

**Возвращает:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Возвращает или задает имя видеофайла, связанного с VideoFrame. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```


Возвращает или задает встроенный объект видео. Чтение/запись [IVideo](../../com.aspose.slides/ivideo).

**Возвращает:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```


Возвращает или задает встроенный объект видео. Чтение/запись [IVideo](../../com.aspose.slides/ivideo).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```


Обрезка начала [мс]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //установить время начала обрезки 1сек
>      videoFrame.setTrimFromStart(1000f);
>      //установить время окончания обрезки 2сек
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```


Обрезка начала [мс]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //установить время начала обрезки 1сек
>      videoFrame.setTrimFromStart(1000f);
>      //установить время окончания обрезки 2сек
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```


Обрезка конца [мс]

**Возвращает:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


Обрезка конца [мс]

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```


Возвращает коллекцию закрытых субтитров, связанных с видеокадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../../com.aspose.slides/icaptionscollection), содержащий все дорожки субтитров.

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
>              // Извлекает бинарные данные субтитров и сохраняет их в файл
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)