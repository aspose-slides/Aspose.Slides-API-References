---
title: AudioFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет аудио-клип на слайде.
type: docs
url: /ru/com.aspose.slides/audioframe/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Все реализованные интерфейсы:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Представляет аудио-клип на слайде.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Получает форму AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Устанавливает режим воспроизведения: воспроизведение по щелчку
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Устанавливает громкость на низкую
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Устанавливает воспроизведение аудио на всех слайдах
>      audioFrame.setPlayAcrossSlides(true);
>      // Отключает зацикливание аудио
>      audioFrame.setPlayLoopMode(false);
>      // Скрывает AudioFrame во время показа слайдов
>      audioFrame.setHideAtShowing(true);
>      // Перематывает аудио к началу после воспроизведения
>      audioFrame.setRewindAudio(true);
>      // Сохраняет файл PowerPoint на диск
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Методы

| Метод | Описание |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Возвращает или задает индекс начального трека. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Возвращает или задает индекс начального трека. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Возвращает или задает время начального трека. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Возвращает или задает время начального трека. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Возвращает или задает индекс последнего трека. Чтение/запись int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Возвращает или задает индекс последнего трека. Чтение/запись int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Возвращает или задает время последнего трека. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Возвращает или задает время последнего трека. |
| [getVolume()](#getVolume--) | Возвращает или задает громкость аудио. |
| [setVolume(int value)](#setVolume-int-) | Возвращает или задает громкость аудио. |
| [getPlayMode()](#getPlayMode--) | Возвращает или задает режим воспроизведения аудио. |
| [setPlayMode(int value)](#setPlayMode-int-) | Возвращает или задает режим воспроизведения аудио. |
| [getHideAtShowing()](#getHideAtShowing--) | Определяет, скрыт ли AudioFrame. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Определяет, скрыт ли AudioFrame. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Определяет, зациклен ли аудио. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Определяет, зациклен ли аудио. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Определяет, воспроизводится ли аудио на всех слайдах. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Определяет, воспроизводится ли аудио на всех слайдах. |
| [getRewindAudio()](#getRewindAudio--) | Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. |
| [getEmbedded()](#getEmbedded--) | Определяет, встроен ли звук в презентацию. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задает имя аудиофайла, связанного с AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задает имя аудиофайла, связанного с AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Возвращает или задает встроенный объект аудио. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Возвращает или задает встроенный объект аудио. |
| [getFadeInDuration()](#getFadeInDuration--) | Указывает длительность начального плавного появления медиа в миллисекундах. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Указывает длительность начального плавного появления медиа в миллисекундах. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Указывает длительность окончательного плавного исчезновения медиа в миллисекундах. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Указывает длительность окончательного плавного исчезновения медиа в миллисекундах. |
| [getVolumeValue()](#getVolumeValue--) | Возвращает или задает громкость аудио в процентах. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Возвращает или задает громкость аудио в процентах. |
| [getTrimFromStart()](#getTrimFromStart--) | Указывает длительность, которую нужно удалить из начала медиа при воспроизведении, в миллисекундах. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Указывает длительность, которую нужно удалить из начала медиа при воспроизведении, в миллисекундах. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Указывает длительность, которую нужно удалить из конца медиа при воспроизведении, в миллисекундах. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Указывает длительность, которую нужно удалить из конца медиа при воспроизведении, в миллисекундах. |
| [getCaptionTracks()](#getCaptionTracks--) | Получает коллекцию закрытых субтитров, связанных с аудио-фреймом. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Возвращает или задает индекс начального трека. Чтение/запись int.

**Возвращаемое значение:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Возвращает или задает индекс начального трека. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Возвращает или задает время начального трека. Чтение/запись int.

**Возвращаемое значение:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Возвращает или задает время начального трека. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Возвращает или задает индекс последнего трека. Чтение/запись int.

**Возвращаемое значение:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Возвращает или задает индекс последнего трека. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Возвращает или задает время последнего трека. Чтение/запись int.

**Возвращаемое значение:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Возвращает или задает время последнего трека. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Возвращает или задает громкость аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Возвращаемое значение:**
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

Возвращает или задает режим воспроизведения аудио. Чтение/запись [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Возвращаемое значение:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Возвращает или задает режим воспроизведения аудио. Чтение/запись [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Определяет, скрыт ли AudioFrame. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Определяет, скрыт ли AudioFrame. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Определяет, зациклен ли аудио. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Определяет, зациклен ли аудио. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Определяет, воспроизводится ли аудио на всех слайдах. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить аудио-фрейм
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить воспроизведение аудио на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить автоматическое перемотивание аудио к началу после воспроизведения
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Возвращаемое значение:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Определяет, воспроизводится ли аудио на всех слайдах. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить аудио-фрейм
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить воспроизведение аудио на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить автоматическое перематывание аудио к началу после воспроизведения
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить аудио-фрейм
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить воспроизведение аудио на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить автоматическое перемотивание аудио к началу после воспроизведения
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Возвращаемое значение:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить аудио-фрейм
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить воспроизведение аудио на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить автоматическое перемотивание аудио к началу после воспроизведения
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

Определяет, встроен ли звук в презентацию. Только для чтения boolean.

**Возвращаемое значение:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Возвращает или задает имя аудиофайла, связанного с AudioFrame. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Возвращает или задает имя аудиофайла, связанного с AudioFrame. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Возвращает или задает встроенный объект аудио. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Возвращаемое значение:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Возвращает или задает встроенный объект аудио. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Указывает длительность начального плавного появления медиа в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить длительность начального затухания на 200 мс
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Указывает длительность начального плавного появления медиа в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить длительность начального затухания на 200 мс
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

Указывает длительность окончательного плавного исчезновения медиа в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить длительность окончательного затухания на 500 мс
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Указывает длительность окончательного плавного исчезновения медиа в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить длительность конечного затухания на 500 мс
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Возвращает или задает громкость аудио в процентах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить громкость аудио на 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Возвращает или задает громкость аудио в процентах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить громкость аудио на 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Указывает длительность, которую нужно удалить из начала медиа при воспроизведении, в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить время начала обрезки 1.5 секунды
>      audioFrame.setTrimFromStart(1500f);
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

Указывает длительность, которую нужно удалить из начала медиа при воспроизведении, в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить время начала обрезки 1.5 секунды
>      audioFrame.setTrimFromStart(1500f);
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

Указывает длительность, которую нужно удалить из конца медиа при воспроизведении, в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить время окончания обрезки 2 секунды
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Указывает длительность, которую нужно удалить из конца медиа при воспроизведении, в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить время окончания обрезки 2 секунды
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Получает коллекцию закрытых субтитров, связанных с аудио-фреймом. Это свойство только для чтения и возвращает [ICaptionsCollection](../../com.aspose.slides/icaptionscollection), содержащий все дорожки субтитров.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (shape instanceof IAudioFrame)
>          {
>              IAudioFrame audioFrame = (IAudioFrame) shape;
>              // Сохранить бинарные данные дорожки субтитров как файл .vtt
>              for (ICaptions captionTrack : audioFrame.getCaptionTracks()) {
>                  FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                  fos.write(captionTrack.getBinaryData());
>                  fos.close();
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)