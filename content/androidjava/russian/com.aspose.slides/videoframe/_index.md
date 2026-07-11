---
title: VideoFrame
second_title: Aspose.Slides для Android через справочник Java API
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
| [getRewindVideo()](#getRewindVideo--) | Определяет, автоматически ли видео перематывается к началу сразу после завершения воспроизведения. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Определяет, автоматически ли видео перематывается к началу сразу после завершения воспроизведения. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Определяет, воспроизводится ли видео в режиме цикла. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Определяет, воспроизводится ли видео в режиме цикла. |
| [getHideAtShowing()](#getHideAtShowing--) | Определяет, скрыт ли VideoFrame. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Определяет, скрыт ли VideoFrame. |
| [getVolume()](#getVolume--) | Возвращает или задаёт громкость аудио. |
| [setVolume(int value)](#setVolume-int-) | Возвращает или задаёт громкость аудио. |
| [getPlayMode()](#getPlayMode--) | Возвращает или задаёт режим воспроизведения видео. |
| [setPlayMode(int value)](#setPlayMode-int-) | Возвращает или задаёт режим воспроизведения видео. |
| [getFullScreenMode()](#getFullScreenMode--) | Определяет, показывается ли видео в полноэкранном режиме. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Определяет, показывается ли видео в полноэкранном режиме. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задаёт имя видеофайла, связан-ного с VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задаёт имя видеофайла, связан-ного с VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Возвращает или задаёт встроенный видеoобъект. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Возвращает или задаёт встроенный видеoобъект. |
| [getTrimFromStart()](#getTrimFromStart--) | Начало обрезки [мс] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Начало обрезки [мс] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Конец обрезки [мс] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Конец обрезки [мс] |
| [getCaptionTracks()](#getCaptionTracks--) | Получает коллекцию закрытых субтитров, связанных с видеокадром. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Определяет, автоматически ли видео перематывается к началу сразу после завершения воспроизведения. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Определяет, автоматически ли видео перематывается к началу сразу после завершения воспроизведения. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Определяет, воспроизводится ли видео в режиме цикла. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Определяет, воспроизводится ли видео в режиме цикла. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Определяет, скрыт ли VideoFrame. Чтение/запись boolean.

**Возвращаемое значение:**
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

Возвращает или задаёт громкость аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Возвращаемое значение:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Возвращает или задаёт громкость аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Возвращает или задаёт режим воспроизведения видео. Чтение/запись [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Возвращаемое значение:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Возвращает или задаёт режим воспроизведения видео. Чтение/запись [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Определяет, показывается ли видео в полноэкранном режиме. Чтение/запись boolean.

**Возвращаемое значение:**
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

Возвращает или задаёт имя видеофайла, связан-ного с VideoFrame. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Возвращает или задаёт имя видеофайла, связан-ного с VideoFrame. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Возвращает или задаёт встроенный видеoобъект. Чтение/запись [IVideo](../../com.aspose.slides/ivideo).

**Возвращаемое значение:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Возвращает или задаёт встроенный видеoобъект. Чтение/запись [IVideo](../../com.aspose.slides/ivideo).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Начало обрезки [мс]

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


**Возвращаемое значение:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Начало обрезки [мс]

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
public final float getTrimFromEnd()
```

Конец обрезки [мс]

**Возвращаемое значение:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Конец обрезки [мс]

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Получает коллекцию закрытых субтитров, связанных с видеокадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../../com.aspose.slides/icaptionscollection), содержащий все дорожки субтитров.

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


**Возвращаемое значение:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)