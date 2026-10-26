---
title: IVideoFrame
second_title: Справочник API Aspose.Slides для Java
description: Представляет видеоклип на слайде.
type: docs
url: /ru/com.aspose.slides/ivideoframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Представляет видеоклип на слайде.

## Методы

| Method | Description |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Определяет, будет ли видео автоматически перемотываться к началу сразу после завершения воспроизведения. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Определяет, будет ли видео автоматически перемотываться к началу сразу после завершения воспроизведения. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Определяет, воспроизводится ли видео в режиме цикла. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Определяет, воспроизводится ли видео в режиме цикла. |
| [getHideAtShowing()](#getHideAtShowing--) | Определяет, скрыт ли VideoFrame. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Определяет, скрыт ли VideoFrame. |
| [getVolume()](#getVolume--) | Возвращает или задает громкость аудио. |
| [setVolume(int value)](#setVolume-int-) | Возвращает или задает громкость аудио. |
| [getPlayMode()](#getPlayMode--) | Возвращает или задает режим воспроизведения видео. |
| [setPlayMode(int value)](#setPlayMode-int-) | Возвращает или задает режим воспроизведения видео. |
| [getFullScreenMode()](#getFullScreenMode--) | Определяет, отображается ли видео в полноэкранном режиме. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Определяет, отображается ли видео в полноэкранном режиме. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задает имя видеофайла, связанного с VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задает имя видеофайла, связанного с VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Возвращает или задает встроенный объект видео. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Возвращает или задает встроенный объект видео. |
| [getTrimFromStart()](#getTrimFromStart--) | Начало обрезки [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Начало обрезки [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Конец обрезки [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Конец обрезки [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Получает коллекцию закрытых субтитров, связанных с аудио-кадром. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Определяет, будет ли видео автоматически перемотываться к началу сразу после завершения воспроизведения. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Определяет, будет ли видео автоматически перемотываться к началу сразу после завершения воспроизведения. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Определяет, воспроизводится ли видео в режиме цикла. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Определяет, воспроизводится ли видео в режиме цикла. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Определяет, скрыт ли VideoFrame. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Определяет, скрыт ли VideoFrame. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Возвращает или задает громкость аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Возвращаемое значение:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Возвращает или задает громкость аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Возвращает или задает режим воспроизведения видео. Чтение/запись [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Возвращаемое значение:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Возвращает или задает режим воспроизведения видео. Чтение/запись [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Определяет, отображается ли видео в полноэкранном режиме. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Определяет, отображается ли видео в полноэкранном режиме. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Возвращает или задает имя видеофайла, связанного с VideoFrame. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```java
public abstract void setLinkPathLong(String value)
```

Возвращает или задает имя видеофайла, связанного с VideoFrame. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Возвращает или задает встроенный объект видео. Чтение/запись [IVideo](../../com.aspose.slides/ivideo).

**Возвращаемое значение:**
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Возвращает или задает встроенный объект видео. Чтение/запись [IVideo](../../com.aspose.slides/ivideo).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Начало обрезки [ms]

--------------------

> ```markdown
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //установить время начала обрезки 1 сек
>      videoFrame.setTrimFromStart(1000f);
>      //установить время окончания обрезки 2 сек
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Начало обрезки [ms]

--------------------

> ```markdown
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //установить время начала обрезки 1 сек
>      videoFrame.setTrimFromStart(1000f);
>      //установить время окончания обрезки 2 сек
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
public abstract float getTrimFromEnd()
```

Конец обрезки [ms]

**Возвращаемое значение:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Конец обрезки [ms]

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Получает коллекцию закрытых субтитров, связанных с аудио-кадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../../com.aspose.slides/icaptionscollection), содержащий все дорожки субтитров.

--------------------

> ```markdown
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


**Возвращаемое значение:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)