---
title: IVideoFrame
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje klip wideo na slajdzie.
type: docs
url: /pl/com.aspose.slides/ivideoframe/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Reprezentuje klip wideo na slajdzie.
## Metody

| Method | Description |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Określa, czy wideo jest automatycznie przewijane do początku po zakończeniu odtwarzania filmu. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Określa, czy wideo jest automatycznie przewijane do początku po zakończeniu odtwarzania filmu. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Określa, czy wideo jest odtwarzane w pętli. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Określa, czy wideo jest odtwarzane w pętli. |
| [getHideAtShowing()](#getHideAtShowing--) | Określa, czy VideoFrame jest ukryty. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Określa, czy VideoFrame jest ukryty. |
| [getVolume()](#getVolume--) | Zwraca lub ustawia głośność dźwięku. |
| [setVolume(int value)](#setVolume-int-) | Zwraca lub ustawia głośność dźwięku. |
| [getPlayMode()](#getPlayMode--) | Zwraca lub ustawia tryb odtwarzania wideo. |
| [setPlayMode(int value)](#setPlayMode-int-) | Zwraca lub ustawia tryb odtwarzania wideo. |
| [getFullScreenMode()](#getFullScreenMode--) | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca lub ustawia nazwę pliku wideo powiązanego z VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Zwraca lub ustawia nazwę pliku wideo powiązanego z VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Zwraca lub ustawia osadzony obiekt wideo. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Zwraca lub ustawia osadzony obiekt wideo. |
| [getTrimFromStart()](#getTrimFromStart--) | Przycinanie od początku [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Przycinanie od początku [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Przycinanie od końca [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Przycinanie od końca [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Pobiera kolekcję napisów zamkniętych powiązanych z ramką audio. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Określa, czy wideo jest automatycznie przewijane do początku po zakończeniu odtwarzania filmu. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Określa, czy wideo jest automatycznie przewijane do początku po zakończeniu odtwarzania filmu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Określa, czy wideo jest odtwarzane w pętli. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Określa, czy wideo jest odtwarzane w pętli. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Określa, czy VideoFrame jest ukryty. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Określa, czy VideoFrame jest ukryty. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Zwraca lub ustawia głośność dźwięku. Odczyt/zapis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Zwraca:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Zwraca lub ustawia głośność dźwięku. Odczyt/zapis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Zwraca lub ustawia tryb odtwarzania wideo. Odczyt/zapis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Zwraca:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Zwraca lub ustawia tryb odtwarzania wideo. Odczyt/zapis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Zwraca lub ustawia nazwę pliku wideo powiązanego z VideoFrame. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Zwraca lub ustawia nazwę pliku wideo powiązanego z VideoFrame. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Zwraca lub ustawia osadzony obiekt wideo. Odczyt/zapis [IVideo](../../com.aspose.slides/ivideo).

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Zwraca lub ustawia osadzony obiekt wideo. Odczyt/zapis [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Przycinanie od początku [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ustaw czas przycięcia początkowego 1 sek
>      videoFrame.setTrimFromStart(1000f);
>      //ustaw czas przycięcia końcowego 2 sek
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Przycinanie od początku [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ustaw czas przycięcia początkowego 1 sek
>      videoFrame.setTrimFromStart(1000f);
>      //ustaw czas przycięcia końcowego 2 sek
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Przycinanie od końca [ms]

**Zwraca:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Przycinanie od końca [ms]

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Pobiera kolekcję napisów zamkniętych powiązanych z ramką audio. Ta właściwość jest tylko do odczytu i zwraca [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zawierający wszystkie ścieżki napisów.

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
>              // Pobiera dane binarne napisów i zapisuje je do pliku
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)