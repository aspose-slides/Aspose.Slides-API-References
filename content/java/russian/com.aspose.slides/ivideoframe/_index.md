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

| Метод | Описание |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Определяет, будет ли видео автоматически перемотываться к началу сразу после завершения воспроизведения. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Определяет, будет ли видео автоматически перемотываться к началу сразу после завершения воспроизведения. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Определяет, зациклен ли видео. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Определяет, зациклен ли видео. |
| [getHideAtShowing()](#getHideAtShowing--) | Определяет, скрыт ли VideoFrame. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Определяет, скрыт ли VideoFrame. |
| [getVolume()](#getVolume--) | Возвращает или задает громкость аудио. |
| [setVolume(int value)](#setVolume-int-) | Возвращает или задает громкость аудио. |
| [getVolumeValue()](#getVolumeValue--) | Возвращает или задает точный уровень громкости видео в процентах. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Возвращает или задает точный уровень громкости видео в процентах. |
| [getPlayMode()](#getPlayMode--) | Возвращает или задает режим воспроизведения видео. |
| [setPlayMode(int value)](#setPlayMode-int-) | Возвращает или задает режим воспроизведения видео. |
| [getFullScreenMode()](#getFullScreenMode--) | Определяет, отображается ли видео в полноэкранном режиме. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Определяет, отображается ли видео в полноэкранном режиме. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задает имя видеофайла, связанного с VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задает имя видеофайла, связанного с VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Возвращает или задает встроенный объект видео. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Возвращает или задает встроенный объект видео. |
| [getTrimFromStart()](#getTrimFromStart--) | Обрезка начала [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Обрезка начала [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Обрезка конца [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Обрезка конца [ms] |
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

Определяет, зациклен ли видео. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Определяет, зациклен ли видео. Чтение/запись boolean.

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
### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Возвращает или задает точный уровень громкости видео в процентах. Значение выражено в процентах от 0 до 100. Используйте это свойство для чтения или задания значений громкости, более точных, чем предустановленные уровни, доступные через свойство Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Прочитать текущий точный уровень громкости и установить его на 75.5 процента.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Возвращает или задает точный уровень громкости видео в процентах. Значение выражено в процентах от 0 до 100. Используйте это свойство для чтения или задания значений громкости, более точных, чем предустановленные уровни, доступные через свойство Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Прочитать текущий точный уровень громкости и установить его на 75.5 процента.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
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

Обрезка начала [ms]

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

**Возвращаемое значение:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Обрезка начала [ms]

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
public abstract float getTrimFromEnd()
```

Обрезка конца [ms]

**Возвращаемое значение:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Обрезка конца [ms]

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