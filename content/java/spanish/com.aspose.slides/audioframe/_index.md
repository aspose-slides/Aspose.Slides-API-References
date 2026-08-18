---
title: AudioFrame
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un clip de audio en una diapositiva.
type: docs
url: /es/com.aspose.slides/audioframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Representa un clip de audio en una diapositiva.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Obtiene la forma AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Establece el modo de reproducción para reproducir al hacer clic
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Establece el volumen a bajo
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Establece que el audio se reproduzca a través de diapositivas
>      audioFrame.setPlayAcrossSlides(true);
>      // Desactiva el bucle para el audio
>      audioFrame.setPlayLoopMode(false);
>      // Oculta el AudioFrame durante la presentación
>      audioFrame.setHideAtShowing(true);
>      // Rebobina el audio al inicio después de reproducir
>      audioFrame.setRewindAudio(true);
>      // Guarda el archivo PowerPoint en disco
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Obtiene o establece un índice de pista de inicio. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Obtiene o establece un índice de pista de inicio. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Obtiene o establece un tiempo de pista de inicio. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Obtiene o establece un tiempo de pista de inicio. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Obtiene o establece un índice de última pista Lectura/escritura  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Obtiene o establece un índice de última pista Lectura/escritura  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Obtiene o establece un tiempo de última pista. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Obtiene o establece un tiempo de última pista. |
| [getVolume()](#getVolume--) | Obtiene o establece el volumen del audio. |
| [setVolume(int value)](#setVolume-int-) | Obtiene o establece el volumen del audio. |
| [getPlayMode()](#getPlayMode--) | Obtiene o establece el modo de reproducción del audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Obtiene o establece el modo de reproducción del audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina si un AudioFrame está oculto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina si un AudioFrame está oculto. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina si un audio se reproduce en bucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina si un audio se reproduce en bucle. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determina si el audio se reproduce a través de las diapositivas. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determina si el audio se reproduce a través de las diapositivas. |
| [getRewindAudio()](#getRewindAudio--) | Determina si el audio se rebobina automáticamente al inicio después de reproducirse. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determina si el audio se rebobina automáticamente al inicio después de reproducirse. |
| [getEmbedded()](#getEmbedded--) | Determina si un sonido está incrustado en una presentación. |
| [getLinkPathLong()](#getLinkPathLong--) | Obtiene o establece el nombre de un archivo de audio vinculado a un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Obtiene o establece el nombre de un archivo de audio vinculado a un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Obtiene o establece el objeto de audio incrustado. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Obtiene o establece el objeto de audio incrustado. |
| [getFadeInDuration()](#getFadeInDuration--) | Especifica la duración en milisegundos del fundido de entrada inicial del medio. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Especifica la duración en milisegundos del fundido de entrada inicial del medio. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Especifica la duración en milisegundos del fundido de salida final del medio. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Especifica la duración en milisegundos del fundido de salida final del medio. |
| [getVolumeValue()](#getVolumeValue--) | Obtiene o establece el volumen del audio en porcentajes. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Obtiene o establece el volumen del audio en porcentajes. |
| [getTrimFromStart()](#getTrimFromStart--) | Especifica la duración en milisegundos que se debe eliminar del inicio del medio durante la reproducción. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Especifica la duración en milisegundos que se debe eliminar del inicio del medio durante la reproducción. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Especifica la duración en milisegundos que se debe eliminar del final del medio durante la reproducción. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Especifica la duración en milisegundos que se debe eliminar del final del medio durante la reproducción. |
| [getCaptionTracks()](#getCaptionTracks--) | Obtiene la colección de subtítulos cerrados asociados con el marco de audio. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Obtiene o establece un índice de pista de inicio. Lectura/escritura  int .

**Devuelve:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Obtiene o establece un índice de pista de inicio. Lectura/escritura  int .

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Obtiene o establece un tiempo de pista de inicio. Lectura/escritura  int .

**Devuelve:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Obtiene o establece un tiempo de pista de inicio. Lectura/escritura  int .

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Obtiene o establece un índice de última pista Lectura/escritura  int .

**Devuelve:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Obtiene o establece un índice de última pista Lectura/escritura  int .

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Obtiene o establece un tiempo de última pista. Lectura/escritura  int .

**Devuelve:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Obtiene o establece un tiempo de última pista. Lectura/escritura  int .

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Obtiene o establece el volumen del audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Devuelve:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Obtiene o establece el volumen del audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Obtiene o establece el modo de reproducción del audio. Lectura/escritura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Devuelve:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Obtiene o establece el modo de reproducción del audio. Lectura/escritura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Determina si un AudioFrame está oculto. Lectura/escritura  boolean .

**Devuelve:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Determina si un AudioFrame está oculto. Lectura/escritura  boolean .

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Determina si un audio se reproduce en bucle. Lectura/escritura  boolean .

**Devuelve:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Determina si un audio se reproduce en bucle. Lectura/escritura  boolean .

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Determina si el audio se reproduce a través de las diapositivas. Lectura/escritura  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Añadir marco de audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurar el audio para reproducir en todas las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar el audio para rebobinar automáticamente al inicio después de reproducir
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Devuelve:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Determina si el audio se reproduce a través de las diapositivas. Lectura/escritura  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Añadir marco de audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurar el audio para reproducir en todas las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar el audio para rebobinar automáticamente al inicio después de reproducir
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

Determina si el audio se rebobina automáticamente al inicio después de reproducirse. Lectura/escritura  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Añadir marco de audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurar el audio para reproducir en todas las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar el audio para rebobinar automáticamente al inicio después de reproducir
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Devuelve:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Determina si el audio se rebobina automáticamente al inicio después de reproducirse. Lectura/escritura  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Añadir marco de audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurar el audio para reproducir en todas las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar el audio para rebobinar automáticamente al inicio después de reproducir
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

Determina si un sonido está incrustado en una presentación. Solo lectura  boolean .

**Devuelve:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Obtiene o establece el nombre de un archivo de audio vinculado a un AudioFrame. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Obtiene o establece el nombre de un archivo de audio vinculado a un AudioFrame. Lectura/escritura String.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Obtiene o establece el objeto de audio incrustado. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Obtiene o establece el objeto de audio incrustado. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Especifica la duración en milisegundos del fundido de entrada inicial del medio. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer la duración del fundido inicial a 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Especifica la duración en milisegundos del fundido de entrada inicial del medio. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer la duración del fundido inicial a 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

Especifica la duración en milisegundos del fundido de salida final del medio. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer la duración del fundido final a 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Especifica la duración en milisegundos del fundido de salida final del medio. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer la duración del fundido final a 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Obtiene o establece el volumen del audio en porcentajes. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer el volumen de audio al 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
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

Obtiene o establece el volumen del audio en porcentajes. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer el volumen del audio al 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Especifica la duración en milisegundos que se debe eliminar del inicio del medio durante la reproducción. Lectura/escritura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer el tiempo de recorte inicial a 1.5 segundos
>      audioFrame.setTrimFromStart(1500f);
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

Especifica la duración en milisegundos que se debe eliminar del inicio del medio durante la reproducción. Lectura/escritura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer el tiempo de recorte inicial a 1.5 segundos
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Especifica la duración en milisegundos que se debe eliminar del final del medio durante la reproducción. Lectura/escritura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer el tiempo de recorte final a 2 segundos
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Especifica la duración en milisegundos que se debe eliminar del final del medio durante la reproducción. Lectura/escritura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer el tiempo de recorte final a 2 segundos
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Obtiene la colección de subtítulos cerrados asociados con el marco de audio. Esta propiedad es solo lectura y devuelve un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) que contiene todas las pistas de subtítulos.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (shape instanceof IAudioFrame)
>          {
>              IAudioFrame audioFrame = (IAudioFrame) shape;
>              // Guardar los datos binarios de la pista de subtítulos como un archivo .vtt
>              for (ICaptions captionTrack : audioFrame.getCaptionTracks()) {
>                  FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                  fos.write(captionTrack.getBinaryData());
>                  fos.close();
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)