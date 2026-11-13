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
| [getRewindVideo()](#getRewindVideo--) | Определяет, автоматически ли видео перематывается к началу сразу после завершения воспроизведения. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Определяет, автоматически ли видео перематывается к началу сразу после завершения воспроизведения. |
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
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Возвращает или задает встроенный видеообъект. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Возвращает или задает встроенный видеообъект. |
| [getTrimFromStart()](#getTrimFromStart--) | Обрезка начала [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Обрезка начала [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Обрезка конца [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Обрезка конца [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Получает коллекцию закрытых подписей, связанных с видеокадром. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Определяет, автоматически ли видео перематывается к началу сразу после завершения воспроизведения. Чтение/запись boolean.

**Возвращает:**
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

Определяет, зациклен ли видео. Чтение/запись boolean.

**Возвращает:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Определяет, зациклен ли видео. Чтение/запись boolean.

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

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Возвращает или задает точный уровень громкости видео в процентах. Значение выражается в процентах от 0 до 100. Используйте это свойство для чтения или установки более точных значений громкости, чем предопределённые уровни, доступные через свойство \#getVolume.getVolume/\#setVolume(int).setVolume(int). Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Прочитать текущий точный уровень громкости и установить его на 75,5 процента.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Возвращает или задает точный уровень громкости видео в процентах. Значение выражается в процентах от 0 до 100. Используйте это свойство для чтения или установки более точных значений громкости, чем предопределённые уровни, доступные через свойство \#getVolume.getVolume/\#setVolume(int).setVolume(int). Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Прочитать текущий точный уровень громкости и установить его на 75,5 процента.
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

Определяет, отображается ли видео в полноэкранном режиме. Чтение/запись boolean.

**Возвращает:**
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Определяет, отображается ли видео в полноэкранном режиме. Чтение/запись boolean.

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

Возвращает или задает встроенный видеообъект. Чтение/запись [IVideo](../../com.aspose.slides/ivideo).

**Возвращает:**
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Возвращает или задает встроенный видеообъект. Чтение/запись [IVideo](../../com.aspose.slides/ivideo).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
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

**Возвращает:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
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
public final float getTrimFromEnd()
```

Обрезка конца [ms]

**Возвращает:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Обрезка конца [ms]

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Получает коллекцию закрытых подписей, связанных с видеокадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../../com.aspose.slides/icaptionscollection), содержащий все дорожки подписей.

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