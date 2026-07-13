---
title: VideoFrame
second_title: Aspose.Slides dla Androida – odwołanie API Java
description: Reprezentuje klip wideo na slajdzie.
type: docs
url: /pl/com.aspose.slides/videoframe/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
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
| [getPlayMode()](#getPlayMode--) | Zwraca lub ustawia tryb odtwarzania wideo. |
| [setPlayMode(int value)](#setPlayMode-int-) | Zwraca lub ustawia tryb odtwarzania wideo. |
| [getFullScreenMode()](#getFullScreenMode--) | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca lub ustawia nazwę pliku wideo, który jest powiązany z VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Zwraca lub ustawia nazwę pliku wideo, który jest powiązany z VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Zwraca lub ustawia osadzony obiekt wideo. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Zwraca lub ustawia osadzony obiekt wideo. |
| [getTrimFromStart()](#getTrimFromStart--) | Przycięcie od początku [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Przycięcie od początku [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Przycięcie od końca [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Przycięcie od końca [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Pobiera kolekcję zamkniętych napisów powiązanych z klatką wideo. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```


Określa, czy wideo jest automatycznie przewijane do początku, gdy film zakończy odtwarzanie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```


Określa, czy wideo jest automatycznie przewijane do początku, gdy film zakończy odtwarzanie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Określa, czy wideo jest odtwarzane w pętli. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Określa, czy wideo jest odtwarzane w pętli. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Określa, czy VideoFrame jest ukryty. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Określa, czy VideoFrame jest ukryty. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```


Zwraca lub ustawia głośność dźwięku. Odczyt/zapis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Zwraca:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```


Zwraca lub ustawia głośność dźwięku. Odczyt/zapis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


Zwraca lub ustawia tryb odtwarzania wideo. Odczyt/zapis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Zwraca:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


Zwraca lub ustawia tryb odtwarzania wideo. Odczyt/zapis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```


Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```


Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Zwraca lub ustawia nazwę pliku wideo, który jest powiązany z VideoFrame. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Zwraca lub ustawia nazwę pliku wideo, który jest powiązany z VideoFrame. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```


Zwraca lub ustawia osadzony obiekt wideo. Odczyt/zapis [IVideo](../../com.aspose.slides/ivideo).

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```


Zwraca lub ustawia osadzony obiekt wideo. Odczyt/zapis [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```


Przycięcie od początku [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ustaw przycinanie od początku 1 sek
>      videoFrame.setTrimFromStart(1000f);
>      //ustaw przycinanie od końca 2 sek
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```


Przycięcie od początku [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ustaw przycinanie od początku 1 sek
>      videoFrame.setTrimFromStart(1000f);
>      //ustaw przycinanie od końca 2 sek
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
public final float getTrimFromEnd()
```


Przycięcie od końca [ms]

**Zwraca:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


Przycięcie od końca [ms]

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```


Pobiera kolekcję zamkniętych napisów powiązanych z klatką wideo. Ta właściwość jest tylko do odczytu i zwraca [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zawierający wszystkie ścieżki napisów.

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
>              // Wyodrębnia binarne dane napisów i zapisuje je do pliku
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