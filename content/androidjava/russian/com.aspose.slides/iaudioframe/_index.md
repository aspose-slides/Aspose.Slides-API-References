---
title: IAudioFrame
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет аудиоклип на слайде.
type: docs
url: /ru/com.aspose.slides/iaudioframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Представляет аудиоклип на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Возвращает или задает начальный индекс дорожки. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Возвращает или задает начальный индекс дорожки. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Возвращает или задает начальное время дорожки. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Возвращает или задает начальное время дорожки. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Возвращает или задает последний индекс дорожки. Чтение/запись int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Возвращает или задает последний индекс дорожки. Чтение/запись int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Возвращает или задает последнее время дорожки. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Возвращает или задает последнее время дорожки. |
| [getVolume()](#getVolume--) | Возвращает или задает громкость аудио. |
| [setVolume(int value)](#setVolume-int-) | Возвращает или задает громкость аудио. |
| [getPlayMode()](#getPlayMode--) | Возвращает или задает режим воспроизведения аудио. |
| [setPlayMode(int value)](#setPlayMode-int-) | Возвращает или задает режим воспроизведения аудио. |
| [getHideAtShowing()](#getHideAtShowing--) | Определяет, скрыт ли AudioFrame. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Определяет, скрыт ли AudioFrame. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Определяет, воспроизводится ли аудио в цикле. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Определяет, воспроизводится ли аудио в цикле. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Определяет, воспроизводится ли аудио на всех слайдах. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Определяет, воспроизводится ли аудио на всех слайдах. |
| [getRewindAudio()](#getRewindAudio--) | Определяет, будет ли аудио автоматически перемотано к началу после воспроизведения. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Определяет, будет ли аудио автоматически перемотано к началу после воспроизведения. |
| [getEmbedded()](#getEmbedded--) | Определяет, встроен ли звук в презентацию. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задает имя аудио-файла, связанного с AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задает имя аудио-файла, связанного с AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Возвращает или задает встроенный аудио-объект. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Возвращает или задает встроенный аудио-объект. |
| [getFadeInDuration()](#getFadeInDuration--) | Задает длительность начального плавного появления медиа в миллисекундах. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Задает длительность начального плавного появления медиа в миллисекундах. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Задает длительность конечного плавного исчезновения медиа в миллисекундах. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Задает длительность конечного плавного исчезновения медиа в миллисекундах. |
| [getVolumeValue()](#getVolumeValue--) | Возвращает или задает громкость аудио в процентах. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Возвращает или задает громкость аудио в процентах. |
| [getTrimFromStart()](#getTrimFromStart--) | Задает длительность, которую нужно удалить из начала медиа во время воспроизведения, в миллисекундах. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Задает длительность, которую нужно удалить из начала медиа во время воспроизведения, в миллисекундах. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Задает длительность, которую нужно удалить из конца медиа во время воспроизведения, в миллисекундах. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Задает длительность, которую нужно удалить из конца медиа во время воспроизведения, в миллисекундах. |
| [getCaptionTracks()](#getCaptionTracks--) | Получает коллекцию закрытых субтитров, связанных с аудио-кадром. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Возвращает или задает начальный индекс дорожки. Чтение/запись int.

**Возвращает:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Возвращает или задает начальный индекс дорожки. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Возвращает или задает начальное время дорожки. Чтение/запись int.

**Возвращает:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Возвращает или задает начальное время дорожки. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Возвращает или задает последний индекс дорожки. Чтение/запись int.

**Возвращает:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Возвращает или задает последний индекс дорожки. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Возвращает или задает последнее время дорожки. Чтение/запись int.

**Возвращает:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Возвращает или задает последнее время дорожки. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Возвращает или задает громкость аудио. Чтение/запись [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Возвращает:**
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

Возвращает или задает режим воспроизведения аудио. Чтение/запись [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Возвращает:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Возвращает или задает режим воспроизведения аудио. Чтение/запись [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Определяет, скрыт ли AudioFrame. Чтение/запись boolean.

**Возвращает:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Определяет, скрыт ли AudioFrame. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Определяет, воспроизводится ли аудио в цикле. Чтение/запись boolean.

**Возвращает:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Определяет, воспроизводится ли аудио в цикле. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Определяет, воспроизводится ли аудио на всех слайдах. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить аудио-кадр
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить воспроизведение аудио на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить автоматическую перемотку аудио к началу после воспроизведения
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Возвращает:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Определяет, воспроизводится ли аудио на всех слайдах. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить аудио-кадр
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить воспроизведение аудио на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить автоматическую перемотку аудио к началу после воспроизведения
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
public abstract boolean getRewindAudio()
```

Определяет, будет ли аудио автоматически перемотано к началу после воспроизведения. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить аудио-кадр
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить воспроизведение аудио на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить автоматическую перемотку аудио к началу после воспроизведения
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Возвращает:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Определяет, будет ли аудио автоматически перемотано к началу после воспроизведения. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить аудио-кадр
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить воспроизведение аудио на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить автоматическую перемотку аудио к началу после воспроизведения
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
public abstract boolean getEmbedded()
```

Определяет, встроен ли звук в презентацию. Только чтение boolean.

**Возвращает:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Возвращает или задает имя аудио-файла, связанного с AudioFrame. Чтение/запись String.

**Возвращает:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Возвращает или задает имя аудио-файла, связанного с AudioFrame. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Возвращает или задает встроенный аудио-объект. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Возвращает:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Возвращает или задает встроенный аудио-объект. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Задает длительность начального плавного появления медиа в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить длительность начального затухания на 200мс
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Задает длительность начального плавного появления медиа в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить длительность начального затухания на 200мс
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
public abstract float getFadeOutDuration()
```

Задает длительность конечного плавного исчезновения медиа в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить длительность конечного затухания на 500мс
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Задает длительность конечного плавного исчезновения медиа в миллисекундах. Чтение/запись float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить длительность конечного затухания на 500мс
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
public abstract float getVolumeValue()
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

**Возвращает:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
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
public abstract float getTrimFromStart()
```

Задает длительность, которую нужно удалить из начала медиа во время воспроизведения, в миллисекундах. Чтение/запись float.

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

**Возвращает:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Задает длительность, которую нужно удалить из начала медиа во время воспроизведения, в миллисекундах. Чтение/запись float.

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
public abstract float getTrimFromEnd()
```

Задает длительность, которую нужно удалить из конца медиа во время воспроизведения, в миллисекундах. Чтение/запись float.

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

**Возвращает:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Задает длительность, которую нужно удалить из конца медиа во время воспроизведения, в миллисекундах. Чтение/запись float.

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
public abstract ICaptionsCollection getCaptionTracks()
```

Получает коллекцию закрытых субтитров, связанных с аудио-кадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../../com.aspose.slides/icaptionscollection), содержащий все дорожки субтитров.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>     for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>     {
>         if (shape instanceof IAudioFrame)
>         {
>             IAudioFrame audioFrame = (IAudioFrame) shape;
>             // Сохранить двоичные данные дорожки субтитров как файл .vtt
>             for (ICaptions captionTrack : audioFrame.getCaptionTracks())
>             {
>                 FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                 fos.write(captionTrack.getBinaryData());
>                 fos.close();
>             }
>         }
>     }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)