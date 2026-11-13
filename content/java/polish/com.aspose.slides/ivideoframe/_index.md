---
title: IVideoFrame
second_title: Aspose.Slides dla Java – referencja API
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

| Metoda | Opis |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Określa, czy wideo jest automatycznie przewijane do początku, gdy film zakończy odtwarzanie. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Określa, czy wideo jest automatycznie przewijane do początku, gdy film zakończy odtwarzanie. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Określa, czy wideo jest odtwarzane w pętli. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Określa, czy wideo jest odtwarzane w pętli. |
| [getHideAtShowing()](#getHideAtShowing--) | Określa, czy VideoFrame jest ukryty. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Określa, czy VideoFrame jest ukryty. |
| [getVolume()](#getVolume--) | Zwraca lub ustawia głośność dźwięku. |
| [setVolume(int value)](#setVolume-int-) | Zwraca lub ustawia głośność dźwięku. |
| [getVolumeValue()](#getVolumeValue--) | Zwraca lub ustawia dokładną głośność wideo jako procent. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Zwraca lub ustawia dokładną głośność wideo jako procent. |
| [getPlayMode()](#getPlayMode--) | Zwraca lub ustawia tryb odtwarzania wideo. |
| [setPlayMode(int value)](#setPlayMode-int-) | Zwraca lub ustawia tryb odtwarzania wideo. |
| [getFullScreenMode()](#getFullScreenMode--) | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca lub ustawia nazwę pliku wideo powiązanego z VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Zwraca lub ustawia nazwę pliku wideo powiązanego z VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Zwraca lub ustawia osadzony obiekt wideo. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Zwraca lub ustawia osadzony obiekt wideo. |
| [getTrimFromStart()](#getTrimFromStart--) | Początek przycięcia [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Początek przycięcia [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Koniec przycięcia [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Koniec przycięcia [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Pobiera kolekcję zamkniętych napisów powiązanych z ramką audio. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Określa, czy wideo jest automatycznie przewijane do początku, gdy film zakończy odtwarzanie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Określa, czy wideo jest automatycznie przewijane do początku, gdy film zakończy odtwarzanie. Odczyt/zapis boolean.

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

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Zwraca lub ustawia dokładną głośność wideo jako procent. Wartość jest wyrażona jako procent od 0 do 100. Użyj tej właściwości, aby odczytać lub ustawić bardziej precyzyjne wartości niż dostępne w predefiniowanych poziomach w właściwości Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Odczyt/zapis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Odczytaj bieżącą dokładną głośność i ustaw ją na 75.5 procent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Zwraca lub ustawia dokładną głośność wideo jako procent. Wartość jest wyrażona jako procent od 0 do 100. Użyj tej właściwości, aby odczytać lub ustawić bardziej precyzyjne wartości niż dostępne w predefiniowanych poziomach w właściwości Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Odczyt/zapis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Odczytaj bieżącą dokładną głośność i ustaw ją na 75.5 procent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

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

Początek przycięcia [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ustaw początkowy czas przycinania 1 sek.
>      videoFrame.setTrimFromStart(1000f);
>      //ustaw końcowy czas przycinania 2 sek.
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

Początek przycięcia [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ustaw początkowy czas przycinania 1 sek.
>      videoFrame.setTrimFromStart(1000f);
>      //ustaw końcowy czas przycinania 2 sek.
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

Koniec przycięcia [ms]

**Zwraca:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Koniec przycięcia [ms]

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Pobiera kolekcję zamkniętych napisów powiązanych z ramką audio. Ta właściwość jest tylko do odczytu i zwraca [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zawierający wszystkie ścieżki napisów.

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
>              // Pobiera binarne dane napisów i zapisuje je do pliku
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