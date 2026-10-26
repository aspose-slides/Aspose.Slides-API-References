---
title: IVideoFrame
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una clip video su una diapositiva.
type: docs
url: /it/com.aspose.slides/ivideoframe/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Rappresenta una clip video su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Determina se un video viene automaticamente riavvolto all'inizio non appena il filmato ha terminato la riproduzione. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Determina se un video viene automaticamente riavvolto all'inizio non appena il filmato ha terminato la riproduzione. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina se un video è in loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina se un video è in loop. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina se un VideoFrame è nascosto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina se un VideoFrame è nascosto. |
| [getVolume()](#getVolume--) | Restituisce o imposta il volume audio. |
| [setVolume(int value)](#setVolume-int-) | Restituisce o imposta il volume audio. |
| [getPlayMode()](#getPlayMode--) | Restituisce o imposta la modalità di riproduzione video. |
| [setPlayMode(int value)](#setPlayMode-int-) | Restituisce o imposta la modalità di riproduzione video. |
| [getFullScreenMode()](#getFullScreenMode--) | Determina se un video è mostrato in modalità a schermo intero. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determina se un video è mostrato in modalità a schermo intero. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce o imposta il nome di un file video collegato a un VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce o imposta il nome di un file video collegato a un VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Restituisce o imposta l'oggetto video incorporato. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Restituisce o imposta l'oggetto video incorporato. |
| [getTrimFromStart()](#getTrimFromStart--) | Ritaglio iniziale [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Ritaglio iniziale [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Ritaglio finale [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Ritaglio finale [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Ottiene la raccolta di sottotitoli chiusi associati al frame audio. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```


Determina se un video viene automaticamente riavvolto all'inizio non appena il filmato ha terminato la riproduzione. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```


Determina se un video viene automaticamente riavvolto all'inizio non appena il filmato ha terminato la riproduzione. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```


Determina se un video è in loop. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```


Determina se un video è in loop. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```


Determina se un VideoFrame è nascosto. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```


Determina se un VideoFrame è nascosto. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```


Restituisce o imposta il volume audio. Lettura/scrittura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Restituisce:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```


Restituisce o imposta il volume audio. Lettura/scrittura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```


Restituisce o imposta la modalità di riproduzione video. Lettura/scrittura [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Restituisce:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```


Restituisce o imposta la modalità di riproduzione video. Lettura/scrittura [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```


Determina se un video è mostrato in modalità a schermo intero. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```


Determina se un video è mostrato in modalità a schermo intero. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Restituisce o imposta il nome di un file video collegato a un VideoFrame. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Restituisce o imposta il nome di un file video collegato a un VideoFrame. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```


Restituisce o imposta l'oggetto video incorporato. Lettura/scrittura [IVideo](../../com.aspose.slides/ivideo).

**Restituisce:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```


Restituisce o imposta l'oggetto video incorporato. Lettura/scrittura [IVideo](../../com.aspose.slides/ivideo).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```


Ritaglio iniziale [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //imposta il tempo di inizio del ritaglio a 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //imposta il tempo di fine del ritaglio a 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```


Ritaglio iniziale [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //imposta il tempo di inizio del ritaglio a 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //imposta il tempo di fine del ritaglio a 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```


Ritaglio finale [ms]

**Restituisce:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```


Ritaglio finale [ms]

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```


Ottiene la raccolta di sottotitoli chiusi associati al frame audio. Questa proprietà è di sola lettura e restituisce un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenente tutte le tracce di sottotitoli.

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
>              // Estrae i dati binari dei sottotitoli e li salva nel file
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)