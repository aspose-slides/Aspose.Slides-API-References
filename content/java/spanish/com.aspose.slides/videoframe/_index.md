---
title: VideoFrame
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un fragmento de video en una diapositiva.
type: docs
url: /es/com.aspose.slides/videoframe/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Todas las interfaces implementadas:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Representa un fragmento de video en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina si un video está en bucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina si un video está en bucle. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina si un VideoFrame está oculto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina si un VideoFrame está oculto. |
| [getVolume()](#getVolume--) | Devuelve o establece el volumen de audio. |
| [setVolume(int value)](#setVolume-int-) | Devuelve o establece el volumen de audio. |
| [getVolumeValue()](#getVolumeValue--) | Devuelve o establece el volumen exacto del video como porcentaje. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Devuelve o establece el volumen exacto del video como porcentaje. |
| [getPlayMode()](#getPlayMode--) | Devuelve o establece el modo de reproducción del video. |
| [setPlayMode(int value)](#setPlayMode-int-) | Devuelve o establece el modo de reproducción del video. |
| [getFullScreenMode()](#getFullScreenMode--) | Determina si un video se muestra en modo de pantalla completa. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determina si un video se muestra en modo de pantalla completa. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Devuelve o establece el objeto de video incrustado. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Devuelve o establece el objeto de video incrustado. |
| [getTrimFromStart()](#getTrimFromStart--) | Recortar inicio [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Recortar inicio [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Recortar fin [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Recortar fin [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Obtiene la colección de subtítulos cerrados asociados con el marco de video. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. Lectura/escritura boolean.

**Devuelve:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Determina si un video está en bucle. Lectura/escritura boolean.

**Devuelve:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Determina si un video está en bucle. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Determina si un VideoFrame está oculto. Lectura/escritura boolean.

**Devuelve:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Determina si un VideoFrame está oculto. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Devuelve o establece el volumen de audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Devuelve:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Devuelve o establece el volumen de audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Devuelve o establece el volumen exacto del video como porcentaje. El valor se expresa como un porcentaje de 0 a 100. Use esta propiedad para leer o establecer valores de volumen más precisos que los niveles predefinidos disponibles a través de \#getVolume.getVolume/\#setVolume(int).setVolume(int). Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lea el volumen exacto actual y establézcalo al 75,5 por ciento.
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
public final void setVolumeValue(float value)
```

Devuelve o establece el volumen exacto del video como porcentaje. El valor se expresa como un porcentaje de 0 a 100. Use esta propiedad para leer o establecer valores de volumen más precisos que los niveles predefinidos disponibles a través de \#getVolume.getVolume/\#setVolume(int).setVolume(int). Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lea el volumen exacto actual y establézcalo al 75,5 por ciento.
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
public final int getPlayMode()
```

Devuelve o establece el modo de reproducción del video. Lectura/escritura [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Devuelve:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Devuelve o establece el modo de reproducción del video. Lectura/escritura [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Determina si un video se muestra en modo de pantalla completa. Lectura/escritura boolean.

**Devuelve:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Determina si un video se muestra en modo de pantalla completa. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Devuelve o establece el objeto de video incrustado. Lectura/escritura [IVideo](../../com.aspose.slides/ivideo).

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Devuelve o establece el objeto de video incrustado. Lectura/escritura [IVideo](../../com.aspose.slides/ivideo).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Recortar inicio [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //establecer tiempo de recorte de inicio 1 seg
>      videoFrame.setTrimFromStart(1000f);
>      //establecer tiempo de recorte de fin 2 seg
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Recortar inicio [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //establecer tiempo de recorte de inicio 1 seg
>      videoFrame.setTrimFromStart(1000f);
>      //establecer tiempo de recorte de fin 2 seg
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
public final float getTrimFromEnd()
```

Recortar fin [ms]

**Devuelve:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Recortar fin [ms]

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Obtiene la colección de subtítulos cerrados asociados con el frame de video. Esta propiedad es de solo lectura y devuelve un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) que contiene todas las pistas de subtítulos.

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