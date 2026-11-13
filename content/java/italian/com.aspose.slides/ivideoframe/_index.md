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
| [getVolumeValue()](#getVolumeValue--) | Restituisce o imposta il volume video esatto come percentuale. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Restituisce o imposta il volume video esatto come percentuale. |
| [getPlayMode()](#getPlayMode--) | Restituisce o imposta la modalità di riproduzione del video. |
| [setPlayMode(int value)](#setPlayMode-int-) | Restituisce o imposta la modalità di riproduzione del video. |
| [getFullScreenMode()](#getFullScreenMode--) | Determina se un video è mostrato in modalità a schermo intero. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determina se un video è mostrato in modalità a schermo intero. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce o imposta il nome di un file video collegato a un VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce o imposta il nome di un file video collegato a un VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Restituisce o imposta l'oggetto video incorporato. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Restituisce o imposta l'oggetto video incorporato. |
| [getTrimFromStart()](#getTrimFromStart--) | Taglio inizio [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Taglio inizio [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Taglio fine [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Taglio fine [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Ottiene la raccolta di sottotitoli chiusi associati al fotogramma audio. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Determina se un video viene automaticamente riavvolto all'inizio non appena il filmato ha terminato la riproduzione. Lettura/Scrittura booleano.

**Restituisce:**  
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Determina se un video viene automaticamente riavvolto all'inizio non appena il filmato ha terminato la riproduzione. Lettura/Scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Determina se un video è in loop. Lettura/Scrittura booleano.

**Restituisce:**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Determina se un video è in loop. Lettura/Scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Determina se un VideoFrame è nascosto. Lettura/Scrittura booleano.

**Restituisce:**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Determina se un VideoFrame è nascosto. Lettura/Scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Restituisce o imposta il volume audio. Lettura/Scrittura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Restituisce:**  
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Restituisce o imposta il volume audio. Lettura/Scrittura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Restituisce o imposta il volume video esatto come percentuale. Il valore è espresso come percentuale da 0 a 100. Utilizzare questa proprietà per leggere o impostare valori di volume più precisi rispetto ai livelli predefiniti disponibili tramite la proprietà Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Lettura/Scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Leggi il volume esatto corrente e impostalo al 75,5 percento.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**  
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Restituisce o imposta il volume video esatto come percentuale. Il valore è espresso come percentuale da 0 a 100. Utilizzare questa proprietà per leggere o impostare valori di volume più precisi rispetto ai livelli predefiniti disponibili tramite la proprietà Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Lettura/Scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Leggi il volume esatto corrente e impostalo al 75,5 percento.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Restituisce o imposta la modalità di riproduzione del video. Lettura/Scrittura [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Restituisce:**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Restituisce o imposta la modalità di riproduzione del video. Lettura/Scrittura [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Determina se un video è mostrato in modalità a schermo intero. Lettura/Scrittura booleano.

**Restituisce:**  
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Determina se un video è mostrato in modalità a schermo intero. Lettura/Scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Restituisce o imposta il nome di un file video collegato a un VideoFrame. Lettura/Scrittura String.

**Restituisce:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Restituisce o imposta il nome di un file video collegato a un VideoFrame. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Restituisce o imposta l'oggetto video incorporato. Lettura/Scrittura [IVideo](../../com.aspose.slides/ivideo).

**Restituisce:**  
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Restituisce o imposta l'oggetto video incorporato. Lettura/Scrittura [IVideo](../../com.aspose.slides/ivideo).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Taglio inizio [ms]

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

Taglio inizio [ms]

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

Taglio fine [ms]

**Restituisce:**  
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Taglio fine [ms]

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Ottiene la raccolta di sottotitoli chiusi associati al fotogramma audio. Questa proprietà è sola lettura e restituisce un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenente tutte le tracce di didascalia.

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