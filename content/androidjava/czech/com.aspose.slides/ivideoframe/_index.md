---
title: IVideoFrame
second_title: Aspose.Slides pro Android přes referenci Java API
description: Představuje video klip na snímku.
type: docs
url: /cs/com.aspose.slides/ivideoframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Representuje video klip na snímku.
## Metody

| Method | Popis |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Určuje, zda se video automaticky přehraje od začátku, jakmile přehrávání skončí. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Určuje, zda se video automaticky přehraje od začátku, jakmile přehrávání skončí. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Určuje, zda je video v režimu smyčky. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Určuje, zda je video v režimu smyčky. |
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
| [getTrimFromStart()](#getTrimFromStart--) | Oříznutí začátku [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Oříznutí začátku [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Oříznutí konce [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Oříznutí konce [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Získává kolekci uzavřených titulků přiřazených k audio rámci. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```


Určuje, zda se video automaticky přehraje od začátku, jakmile přehrávání skončí. Čtení/zápis boolean.

**Vrací:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```


Určuje, zda se video automaticky přehraje od začátku, jakmile přehrávání skončí. Čtení/zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```


Určuje, zda je video v režimu smyčky. Čtení/zápis boolean.

**Vrací:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```


Určuje, zda je video v režimu smyčky. Čtení/zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```


Určuje, zda je VideoFrame skrytý. Čtení/zápis boolean.

**Vrací:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```


Určuje, zda je VideoFrame skrytý. Čtení/zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```


Vrací nebo nastavuje hlasitost zvuku. Čtení/zápis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Vrací:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```


Vrací nebo nastavuje hlasitost zvuku. Čtení/zápis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```


Vrací nebo nastavuje režim přehrávání videa. Čtení/zápis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Vrací:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```


Vrací nebo nastavuje režim přehrávání videa. Čtení/zápis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```


Určuje, zda je video zobrazeno v režimu celé obrazovky. Čtení/zápis boolean.

**Vrací:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```


Určuje, zda je video zobrazeno v režimu celé obrazovky. Čtení/zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. Čtení/zápis String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. Čtení/zápis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```


Vrací nebo nastavuje vložený video objekt. Čtení/zápis [IVideo](../../com.aspose.slides/ivideo).

**Vrací:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```


Vrací nebo nastavuje vložený video objekt. Čtení/zápis [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```


Oříznutí začátku [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //nastavte čas oříznutí na začátku 1 sekunda
>      videoFrame.setTrimFromStart(1000f);
>      //nastavte čas oříznutí na konci 2 sekundy
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```


Oříznutí začátku [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //nastavte čas oříznutí na začátku 1 sekunda
>      videoFrame.setTrimFromStart(1000f);
>      //nastavte čas oříznutí na konci 2 sekundy
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```


Oříznutí konce [ms]

**Vrací:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```


Oříznutí konce [ms]

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```


Získává kolekci uzavřených titulků přiřazených k audio rámci. Tato vlastnost je pouze pro čtení a vrací [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) obsahující všechny titulky.

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