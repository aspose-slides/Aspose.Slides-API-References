---
title: VideoFrame
second_title: Aspose.Slides para Android mediante la API de referencia de Java
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
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina si un video se reproduce en bucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina si un video se reproduce en bucle. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina si un VideoFrame está oculto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina si un VideoFrame está oculto. |
| [getVolume()](#getVolume--) | Devuelve o establece el volumen de audio. |
| [setVolume(int value)](#setVolume-int-) | Devuelve o establece el volumen de audio. |
| [getPlayMode()](#getPlayMode--) | Devuelve o establece el modo de reproducción del video. |
| [setPlayMode(int value)](#setPlayMode-int-) | Devuelve o establece el modo de reproducción del video. |
| [getFullScreenMode()](#getFullScreenMode--) | Determina si un video se muestra en modo de pantalla completa. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determina si un video se muestra en modo de pantalla completa. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Devuelve o establece el objeto de video incrustado. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Devuelve o establece el objeto de video incrustado. |
| [getTrimFromStart()](#getTrimFromStart--) | Recorte de inicio [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Recorte de inicio [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Recorte final [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Recorte final [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Obtiene la colección de subtítulos cerrados asociados al marco de video. |
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

Determina si un video se reproduce en bucle. Lectura/escritura boolean.

**Devuelve:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Determina si un video se reproduce en bucle. Lectura/escritura boolean.

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

Recorte de inicio [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //establecer tiempo de recorte de inicio 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //establecer tiempo de recorte final 2sec
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

Recorte de inicio [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //establecer tiempo de recorte de inicio 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //establecer tiempo de recorte final 2sec
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

Recorte final [ms]

**Devuelve:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Recorte final [ms]

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Obtiene la colección de subtítulos cerrados asociados al marco de video. Esta propiedad es solo lectura y devuelve un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) que contiene todas las pistas de subtítulos.

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