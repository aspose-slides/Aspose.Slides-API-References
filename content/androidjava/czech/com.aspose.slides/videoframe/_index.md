---
title: VideoFrame
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje video klip na snímku.
type: docs
url: /cs/com.aspose.slides/videoframe/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Všechny implementované rozhraní:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Představuje video klip na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Určuje, zda se video automaticky přetočí na začátek, jakmile se film dokončí. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Určuje, zda se video automaticky přetočí na začátek, jakmile se film dokončí. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Určuje, zda se video přehrává ve smyčce. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Určuje, zda se video přehrává ve smyčce. |
| [getHideAtShowing()](#getHideAtShowing--) | Určuje, zda je VideoFrame skrytý. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Určuje, zda je VideoFrame skrytý. |
| [getVolume()](#getVolume--) | Vrací nebo nastavuje hlasitost zvuku. |
| [setVolume(int value)](#setVolume-int-) | Vrací nebo nastavuje hlasitost zvuku. |
| [getPlayMode()](#getPlayMode--) | Vrací nebo nastavuje režim přehrávání videa. |
| [setPlayMode(int value)](#setPlayMode-int-) | Vrací nebo nastavuje režim přehrávání videa. |
| [getFullScreenMode()](#getFullScreenMode--) | Určuje, zda je video zobrazeno v režimu celé obrazovky. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Určuje, zda je video zobrazeno v režimu celé obrazovky. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Vrací nebo nastavuje vložený video objekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Vrací nebo nastavuje vložený video objekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Počátek ořezu [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Počátek ořezu [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Konec ořezu [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Konec ořezu [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Získá kolekci uzavřených titulků spojených s video rámcem. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```


Určuje, zda se video automaticky přetočí na začátek, jakmile se film dokončí. Číst/zapisovat boolean.

**Vrací:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```


Určuje, zda se video automaticky přetočí na začátek, jakmile se film dokončí. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Určuje, zda se video přehrává ve smyčce. Číst/zapisovat boolean.

**Vrací:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Určuje, zda se video přehrává ve smyčce. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Určuje, zda je VideoFrame skrytý. Číst/zapisovat boolean.

**Vrací:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Určuje, zda je VideoFrame skrytý. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```


Vrací nebo nastavuje hlasitost zvuku. Číst/zapisovat [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Vrací:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```


Vrací nebo nastavuje hlasitost zvuku. Číst/zapisovat [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


Vrací nebo nastavuje režim přehrávání videa. Číst/zapisovat [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Vrací:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


Vrací nebo nastavuje režim přehrávání videa. Číst/zapisovat [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```


Určuje, zda je video zobrazeno v režimu celé obrazovky. Číst/zapisovat boolean.

**Vrací:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```


Určuje, zda je video zobrazeno v režimu celé obrazovky. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. Číst/zapisovat String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. Číst/zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```


Vrací nebo nastavuje vložený video objekt. Číst/zapisovat [IVideo](../../com.aspose.slides/ivideo).

**Vrací:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```


Vrací nebo nastavuje vložený video objekt. Číst/zapisovat [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```


Počátek ořezu [ms]

--------------------

> ``` 
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //nastavit čas ořezu na začátku 1 s
>      videoFrame.setTrimFromStart(1000f);
>      //nastavit čas ořezu na konci 2 s
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```


Počátek ořezu [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //nastavit čas ořezu na začátku 1 s
>      videoFrame.setTrimFromStart(1000f);
>      //nastavit čas ořezu na konci 2 s
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```


Konec ořezu [ms]

**Vrací:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


Konec ořezu [ms]

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```


Získá kolekci uzavřených titulků spojených s video rámcem. Tato vlastnost je pouze ke čtení a vrací [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) obsahující všechny stopy titulků.

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
>              // Extrahuje binární data titulků a uloží je do souboru
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)