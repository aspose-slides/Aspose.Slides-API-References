---
title: VideoFrame
second_title: Aspose.Slides pro Java – API reference
description: Representuje video klip na snímku.
type: docs
url: /cs/com.aspose.slides/videoframe/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**  
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)  
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Představuje video klip na snímku.

## Metody

| Metoda | Popis |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Určuje, zda se video automaticky přetočí zpět na začátek, jakmile se přehrávání filmu dokončí. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Určuje, zda se video automaticky přetočí zpět na začátek, jakmile se přehrávání filmu dokončí. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Určuje, zda je video přehráváno ve smyčce. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Určuje, zda je video přehráváno ve smyčce. |
| [getHideAtShowing()](#getHideAtShowing--) | Určuje, zda je VideoFrame skrytý. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Určuje, zda je VideoFrame skrytý. |
| [getVolume()](#getVolume--) | Vrací nebo nastavuje úroveň hlasitosti zvuku. |
| [setVolume(int value)](#setVolume-int-) | Vrací nebo nastavuje úroveň hlasitosti zvuku. |
| [getVolumeValue()](#getVolumeValue--) | Vrací nebo nastavuje přesnou úroveň hlasitosti videa jako procento. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Vrací nebo nastavuje přesnou úroveň hlasitosti videa jako procento. |
| [getPlayMode()](#getPlayMode--) | Vrací nebo nastavuje režim přehrávání videa. |
| [setPlayMode(int value)](#setPlayMode-int-) | Vrací nebo nastavuje režim přehrávání videa. |
| [getFullScreenMode()](#getFullScreenMode--) | Určuje, zda je video zobrazeno v režimu celé obrazovky. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Určuje, zda je video zobrazeno v režimu celé obrazovky. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Vrací nebo nastavuje vložený video objekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Vrací nebo nastavuje vložený video objekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Začátek ořezu [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Začátek ořezu [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Konec ořezu [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Konec ořezu [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Získává kolekci skrytých titulků spojených s video frame. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Určuje, zda se video automaticky přetočí zpět na začátek, jakmile se přehrávání filmu dokončí. Čtení/zápis boolean.

**Vrací:**  
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Určuje, zda se video automaticky přetočí zpět na začátek, jakmile se přehrávání filmu dokončí. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Určuje, zda je video přehráváno ve smyčce. Čtení/zápis boolean.

**Vrací:**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Určuje, zda je video přehráváno ve smyčce. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Určuje, zda je VideoFrame skrytý. Čtení/zápis boolean.

**Vrací:**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Určuje, zda je VideoFrame skrytý. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Vrací nebo nastavuje úroveň hlasitosti zvuku. Čtení/zápis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Vrací:**  
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Vrací nebo nastavuje úroveň hlasitosti zvuku. Čtení/zápis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Vrací nebo nastavuje přesnou úroveň hlasitosti videa jako procento. Hodnota je vyjádřena v procentech od 0 do 100. Použijte tuto vlastnost pro čtení nebo nastavení hodnot hlasitosti s vyšší přesností než předdefinované úrovně dostupné přes \#getVolume.getVolume/\#setVolume(int).setVolume(int). Čtení/zápis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Přečtěte aktuální přesnou hlasitost a nastavte ji na 75.5 procenta.
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
public final void setVolumeValue(float value)
```

Vrací nebo nastavuje přesnou úroveň hlasitosti videa jako procento. Hodnota je vyjádřena v procentech od 0 do 100. Použijte tuto vlastnost pro čtení nebo nastavení hodnot hlasitosti s vyšší přesností než předdefinované úrovně dostupné přes \#getVolume.getVolume/\#setVolume(int).setVolume(int). Čtení/zápis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Přečtěte aktuální přesnou hlasitost a nastavte ji na 75.5 procenta.
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
public final int getPlayMode()
```

Vrací nebo nastavuje režim přehrávání videa. Čtení/zápis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Vrací:**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Vrací nebo nastavuje režim přehrávání videa. Čtení/zápis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Určuje, zda je video zobrazeno v režimu celé obrazovky. Čtení/zápis boolean.

**Vrací:**  
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Určuje, zda je video zobrazeno v režimu celé obrazovky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. Čtení/zápis String.

**Vrací:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Vrací nebo nastavuje vložený video objekt. Čtení/zápis [IVideo](../../com.aspose.slides/ivideo).

**Vrací:**  
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Vrací nebo nastavuje vložený video objekt. Čtení/zápis [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Začátek ořezu [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //nastavte čas ořezu na začátku 1 s
>      videoFrame.setTrimFromStart(1000f);
>      //nastavte čas ořezu na konci 2 s
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

Začátek ořezu [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //nastavte čas ořezu na začátku 1 s
>      videoFrame.setTrimFromStart(1000f);
>      //nastavte čas ořezu na konci 2 s
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

Získává kolekci skrytých titulků spojených s video frame. Tato vlastnost je jen pro čtení a vrací [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) obsahující všechny stopy titulků.

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