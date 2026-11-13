---
title: IVideoFrame
second_title: Aspose.Slides pro Java – reference API
description: Představuje videoklip na snímku.
type: docs
url: /cs/com.aspose.slides/ivideoframe/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Představuje video klip na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Určuje, zda se video po dokončení přehrávání automaticky přehraje od začátku. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Určuje, zda se video po dokončení přehrávání automaticky přehraje od začátku. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Určuje, zda je video přehráváno ve smyčce. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Určuje, zda je video přehráváno ve smyčce. |
| [getHideAtShowing()](#getHideAtShowing--) | Určuje, zda je VideoFrame skrytý. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Určuje, zda je VideoFrame skrytý. |
| [getVolume()](#getVolume--) | Vrací nebo nastavuje hlasitost zvuku. |
| [setVolume(int value)](#setVolume-int-) | Vrací nebo nastavuje hlasitost zvuku. |
| [getVolumeValue()](#getVolumeValue--) | Vrací nebo nastavuje přesnou hlasitost videa jako procento. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Vrací nebo nastavuje přesnou hlasitost videa jako procento. |
| [getPlayMode()](#getPlayMode--) | Vrací nebo nastavuje režim přehrávání videa. |
| [setPlayMode(int value)](#setPlayMode-int-) | Vrací nebo nastavuje režim přehrávání videa. |
| [getFullScreenMode()](#getFullScreenMode--) | Určuje, zda je video zobrazeno v režimu celé obrazovky. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Určuje, zda je video zobrazeno v režimu celé obrazovky. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Vrací nebo nastavuje vložený video objekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Vrací nebo nastavuje vložený video objekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Oříznutí od začátku [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Oříznutí od začátku [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Oříznutí na konci [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Oříznutí na konci [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Získává kolekci uzavřených titulků přidružených k audio rámečku. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Určuje, zda se video po dokončení přehrávání automaticky přehraje od začátku. Čtení/zápis boolean.

**Vrací:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Určuje, zda se video po dokončení přehrávání automaticky přehraje od začátku. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Určuje, zda je video přehráváno ve smyčce. Čtení/zápis boolean.

**Vrací:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Určuje, zda je video přehráváno ve smyčce. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Vrací nebo nastavuje přesnou hlasitost videa jako procento. Hodnota je vyjádřena v procentech od 0 do 100. Použijte tuto vlastnost k načtení nebo nastavení hodnot hlasitosti, které jsou přesnější než předdefinované úrovně dostupné přes vlastnost Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Čtení/zápis  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Přečtěte aktuální přesnou hlasitost a nastavte ji na 75,5 procent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Vrací nebo nastavuje přesnou hlasitost videa jako procento. Hodnota je vyjádřena v procentech od 0 do 100. Použijte tuto vlastnost k načtení nebo nastavení hodnot hlasitosti, které jsou přesnější než předdefinované úrovně dostupné přes vlastnost Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Čtení/zápis  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Přečtěte aktuální přesnou hlasitost a nastavte ji na 75,5 procent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Oříznutí od začátku [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //nastavte čas začátku oříznutí na 1 sekundu
>      videoFrame.setTrimFromStart(1000f);
>      //nastavte čas konce oříznutí na 2 sekundy
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

Oříznutí od začátku [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //nastavte čas začátku oříznutí na 1 sekundu
>      videoFrame.setTrimFromStart(1000f);
>      //nastavte čas konce oříznutí na 2 sekundy
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
public abstract float getTrimFromEnd()
```

Oříznutí na konci [ms]

**Vrací:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Oříznutí na konci [ms]

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Získává kolekci uzavřených titulků přidružených k audio rámečku. Tato vlastnost je pouze pro čtení a vrací [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) obsahující všechny stopy titulků.

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