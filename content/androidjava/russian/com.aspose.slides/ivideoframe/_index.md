---
title: IVideoFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет видеоклип на слайде.
type: docs
url: /ru/com.aspose.slides/ivideoframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Представляет видеоклип на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Определяет, автоматически ли перематывается видео к началу сразу после завершения воспроизведения. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Определяет, автоматически ли перематывается видео к началу сразу после завершения воспроизведения. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Определяет, зациклено ли видео. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Определяет, зациклено ли видео. |
| [getHideAtShowing()](#getHideAtShowing--) | Определяет, скрыт ли VideoFrame. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Определяет, скрыт ли VideoFrame. |
| [getVolume()](#getVolume--) | Возвращает или задает уровень громкости аудио. |
| [setVolume(int value)](#setVolume-int-) | Возвращает или задает уровень громкости аудио. |
| [getPlayMode()](#getPlayMode--) | Возвращает или задает режим воспроизведения видео. |
| [setPlayMode(int value)](#setPlayMode-int-) | Возвращает или задает режим воспроизведения видео. |
| [getFullScreenMode()](#getFullScreenMode--) | Определяет, отображается ли видео в полноэкранном режиме. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Определяет, отображается ли видео в полноэкранном режиме. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задает имя видеофайла, связанного с VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задает имя видеофайла, связанного с VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Возвращает или задает встроенный объект видео. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Возвращает или задает встроенный объект видео. |
| [getTrimFromStart()](#getTrimFromStart--) | Обрезать начало [мс] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Обрезать начало [мс] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Обрезать конец [мс] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Обрезать конец [мс] |
| [getCaptionTracks()](#getCaptionTracks--) | Получает коллекцию закрытых субтитров, связанных с аудио-кадром. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Определяет, автоматически ли перематывается видео к началу сразу после завершения воспроизведения. Чтение/запись boolean.

**Возвращает:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Определяет, автоматически ли перематывается видео к началу сразу после завершения воспроизведения. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Определяет, зациклено ли видео. Чтение/запись boolean.

**Возвращает:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Определяет, зациклено ли видео. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Определяет, скрыт ли VideoFrame. Чтение/запись boolean.

**Возвращает:**
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

Возвращает или задает уровень громкости аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Возвращает:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Возвращает или задает уровень громкости аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Возвращает или задает режим воспроизведения видео. Чтение/запись [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Возвращает:**
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

**Возвращает:**
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

**Возвращает:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
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

**Возвращает:**
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

Обрезать начало [мс]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //установить время начала обрезки 1 сек
>      videoFrame.setTrimFromStart(1000f);
>      //установить время окончания обрезки 2 сек
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Обрезать начало [мс]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
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

Обрезать конец [мс]

**Возвращает:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Обрезать конец [мс]

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
>              // Извлекает двоичные данные субтитров и сохраняет их в файл
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