---
title: IAudioFrame
second_title: Справочник API Aspose.Slides для Java
description: Представляет аудио-клип на слайде.
type: docs
url: /ru/com.aspose.slides/iaudioframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Представляет аудио-клип на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Возвращает или задает индекс начального трека. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Возвращает или задает индекс начального трека. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Возвращает или задает время начала трека. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Возвращает или задает время начала трека. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Возвращает или задает индекс последнего трека. Чтение/запись int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Возвращает или задает индекс последнего трека. Чтение/запись int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Возвращает или задает время конца трека. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Возвращает или задает время конца трека. |
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
| [getRewindAudio()](#getRewindAudio--) | Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. |
| [getEmbedded()](#getEmbedded--) | Определяет, встроен ли звук в презентацию. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задает имя аудиофайла, связанного с AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задает имя аудиофайла, связанного с AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Возвращает или задает встроенный объект аудио. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Возвращает или задает встроенный объект аудио. |
| [getFadeInDuration()](#getFadeInDuration--) | Указывает длительность начального плавного появления медиа в миллисекундах. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Указывает длительность начального плавного появления медиа в миллисекундах. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Указывает длительность конечного плавного затухания медиа в миллисекундах. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Указывает длительность конечного плавного затухания медиа в миллисекундах. |
| [getVolumeValue()](#getVolumeValue--) | Возвращает или задает громкость аудио в процентах. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Возвращает или задает громкость аудио в процентах. |
| [getTrimFromStart()](#getTrimFromStart--) | Указывает длительность, которую следует удалить из начала медиа во время воспроизведения, в миллисекундах. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Указывает длительность, которую следует удалить из начала медиа во время воспроизведения, в миллисекундах. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Указывает длительность, которую следует удалить из конца медиа во время воспроизведения, в миллисекундах. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Указывает длительность, которую следует удалить из конца медиа во время воспроизведения, в миллисекундах. |
| [getCaptionTracks()](#getCaptionTracks--) | Получает коллекцию закрытых субтитров, связанных с AudioFrame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Возвращает или задает индекс начального трека. Чтение/запись int.

**Возвращаемое значение:**  
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Возвращает или задает индекс начального трека. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Возвращает или задает время начала трека. Чтение/запись int.

**Возвращаемое значение:**  
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Возвращает или задает время начала трека. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Возвращает или задает индекс последнего трека. Чтение/запись int.

**Возвращаемое значение:**  
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Возвращает или задает индекс последнего трека. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Возвращает или задает время конца трека. Чтение/запись int.

**Возвращаемое значение:**  
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Возвращает или задает время конца трека. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

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

Возвращает или задает режим воспроизведения аудио. Чтение/запись [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Возвращаемое значение:**  
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

**Возвращаемое значение:**  
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

**Возвращаемое значение:**  
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

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить Audio для воспроизведения на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить Audio для автоматической перемотки к началу после воспроизведения
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
public abstract void setPlayAcrossSlides(boolean value)
```

Определяет, воспроизводится ли аудио на всех слайдах. Чтение/запись boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить Audio для воспроизведения на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить Audio для автоматической перемотки к началу после воспроизведения
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

Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. Чтение/запись boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить Audio для воспроизведения на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить Audio для автоматической перемотки к началу после воспроизведения
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> 
```

**Возвращаемое значение:**  
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. Чтение/запись boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Добавить Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Установить Audio для воспроизведения на всех слайдах
>       audioFrame.setPlayAcrossSlides(true);
>       // Установить Audio для автоматической перемотки к началу после воспроизведения
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

Определяет, встроен ли звук в презентацию. Только для чтения boolean.

**Возвращаемое значение:**  
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Возвращает или задает имя аудиофайла, связанного с AudioFrame. Чтение/запись String.

**Возвращаемое значение:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Возвращает или задает имя аудиофайла, связанного с AudioFrame. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Возвращает или задает встроенный объект аудио. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Возвращаемое значение:**  
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Возвращает или задает встроенный объект аудио. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Указывает длительность начального плавного появления медиа в миллисекундах. Чтение/запись float.

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
public abstract void setFadeInDuration(float value)
```

Указывает длительность начального плавного появления медиа в миллисекундах. Чтение/запись float.

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
public abstract float getFadeOutDuration()
```

Указывает длительность конечного плавного затухания медиа в миллисекундах. Чтение/запись float.

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


**Возвращаемое значение:**  
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Указывает длительность конечного плавного затухания медиа в миллисекундах. Чтение/запись float.

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
public abstract float getVolumeValue()
```

Возвращает или задает громкость аудио в процентах. Чтение/запись float.

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
> 
```

**Возвращаемое значение:**  
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Возвращает или задает громкость аудио в процентах. Чтение/запись float.

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

Указывает длительность, которую следует удалить из начала медиа во время воспроизведения, в миллисекундах. Чтение/запись float.

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
> 
```

**Возвращаемое значение:**  
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Указывает длительность, которую следует удалить из начала медиа во время воспроизведения, в миллисекундах. Чтение/запись float.

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

Указывает длительность, которую следует удалить из конца медиа во время воспроизведения, в миллисекундах. Чтение/запись float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить время обрезки в конце 2 секунды
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**  
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Указывает длительность, которую следует удалить из конца медиа во время воспроизведения, в миллисекундах. Чтение/запись float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Установить время обрезки в конце 2 секунды
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

Получает коллекцию закрытых субтитров, связанных с AudioFrame. Это свойство только для чтения и возвращает [ICaptionsCollection](../../com.aspose.slides/icaptionscollection), содержащий все дорожки субтитров.

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
>             // Сохранить двоичные данные дорожки субтитров в файл .vtt
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


**Возвращаемое значение:**  
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)