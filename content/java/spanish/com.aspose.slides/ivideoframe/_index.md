---
title: IVideoFrame
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un clip de video en una diapositiva.
type: docs
url: /es/com.aspose.slides/ivideoframe/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Representa un clip de vídeo en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina si un video se reproduce en bucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina si un video se reproduce en bucle. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina si un VideoFrame está oculto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina si un VideoFrame está oculto. |
| [getVolume()](#getVolume--) | Devuelve o establece el volumen de audio. |
| [setVolume(int value)](#setVolume-int-) | Devuelve o establece el volumen de audio. |
| [getVolumeValue()](#getVolumeValue--) | Devuelve o establece el volumen exacto del video como un porcentaje. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Devuelve o establece el volumen exacto del video como un porcentaje. |
| [getPlayMode()](#getPlayMode--) | Devuelve o establece el modo de reproducción del video. |
| [setPlayMode(int value)](#setPlayMode-int-) | Devuelve o establece el modo de reproducción del video. |
| [getFullScreenMode()](#getFullScreenMode--) | Determina si un video se muestra en modo de pantalla completa. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determina si un video se muestra en modo de pantalla completa. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Devuelve o establece el objeto de video incrustado. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Devuelve o establece el objeto de video incrustado. |
| [getTrimFromStart()](#getTrimFromStart--) | Recorte inicial [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Recorte inicial [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Recorte final [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Recorte final [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Obtiene la colección de subtítulos cerrados asociados al marco de audio. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. Lectura/escritura booleano.

**Devuelve:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Determina si un video se reproduce en bucle. Lectura/escritura booleano.

**Devuelve:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Determina si un video se reproduce en bucle. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Determina si un VideoFrame está oculto. Lectura/escritura booleano.

**Devuelve:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Determina si un VideoFrame está oculto. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Devuelve o establece el volumen de audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Devuelve:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Devuelve o establece el volumen de audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Devuelve o establece el volumen exacto del video como un porcentaje. El valor se expresa como un porcentaje de 0 a 100. Utilice esta propiedad para leer o establecer valores de volumen más precisos que los niveles predefinidos disponibles a través de la propiedad Volumen (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lee el volumen exacto actual y establézcalo al 75,5 por ciento.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Devuelve o establece el volumen exacto del video como un porcentaje. El valor se expresa como un porcentaje de 0 a 100. Utilice esta propiedad para leer o establecer valores de volumen más precisos que los niveles predefinidos disponibles a través de la propiedad Volumen (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lee el volumen exacto actual y establézcalo al 75,5 por ciento.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Devuelve o establece el modo de reproducción del video. Lectura/escritura [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Devuelve:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Devuelve o establece el modo de reproducción del video. Lectura/escritura [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Determina si un video se muestra en modo de pantalla completa. Lectura/escritura booleano.

**Devuelve:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Determina si un video se muestra en modo de pantalla completa. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Devuelve o establece el objeto de video incrustado. Lectura/escritura [IVideo](../../com.aspose.slides/ivideo).

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Devuelve o establece el objeto de video incrustado. Lectura/escritura [IVideo](../../com.aspose.slides/ivideo).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Recorte inicial [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //establece tiempo de inicio del recorte 1 seg
>      videoFrame.setTrimFromStart(1000f);
>      //establece tiempo de fin del recorte 2 seg
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Recorte inicial [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //establece tiempo de inicio del recorte 1 seg
>      videoFrame.setTrimFromStart(1000f);
>      //establece tiempo de fin del recorte 2 seg
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Recorte final [ms]

**Devuelve:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Recorte final [ms]

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Obtiene la colección de subtítulos cerrados asociados al marco de audio. Esta propiedad es de solo lectura y devuelve un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) que contiene todas las pistas de subtítulos.

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
>              // Extrae los datos binarios de los subtítulos y los guarda en el archivo
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)