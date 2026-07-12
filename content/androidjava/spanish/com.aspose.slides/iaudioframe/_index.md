---
title: IAudioFrame
second_title: Aspose.Slides para Android a través de la Referencia de API Java
description: Representa un clip de audio en una diapositiva.
type: docs
url: /es/com.aspose.slides/iaudioframe/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Representa un clip de audio en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Devuelve o establece un índice de pista de inicio. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Devuelve o establece un índice de pista de inicio. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Devuelve o establece un tiempo de pista de inicio. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Devuelve o establece un tiempo de pista de inicio. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Devuelve o establece un índice de última pista Lectura/escritura int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Devuelve o establece un índice de última pista Lectura/escritura int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Devuelve o establece un tiempo de última pista. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Devuelve o establece un tiempo de última pista. |
| [getVolume()](#getVolume--) | Devuelve o establece el volumen del audio. |
| [setVolume(int value)](#setVolume-int-) | Devuelve o establece el volumen del audio. |
| [getPlayMode()](#getPlayMode--) | Devuelve o establece el modo de reproducción del audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Devuelve o establece el modo de reproducción del audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina si un AudioFrame está oculto. Lectura/escritura boolean. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina si un AudioFrame está oculto. Lectura/escritura boolean. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina si un audio está en bucle. Lectura/escritura boolean. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina si un audio está en bucle. Lectura/escritura boolean. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determina si un audio se reproduce a través de las diapositivas. Lectura/escritura boolean. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determina si un audio se reproduce a través de las diapositivas. Lectura/escritura boolean. |
| [getRewindAudio()](#getRewindAudio--) | Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Lectura/escritura boolean. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Lectura/escritura boolean. |
| [getEmbedded()](#getEmbedded--) | Determina si un sonido está incrustado en una presentación. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve o establece el nombre de un archivo de audio enlazado a un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve o establece el nombre de un archivo de audio enlazado a un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Devuelve o establece un objeto de audio incrustado. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Devuelve o establece un objeto de audio incrustado. |
| [getFadeInDuration()](#getFadeInDuration--) | Especifica la duración en milisegundos del fundido de entrada inicial del medio. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Especifica la duración en milisegundos del fundido de entrada inicial del medio. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Especifica la duración en milisegundos del fundido de salida final del medio. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Especifica la duración en milisegundos del fundido de salida final del medio. |
| [getVolumeValue()](#getVolumeValue--) | Devuelve o establece el volumen del audio en porcentajes. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Devuelve o establece el volumen del audio en porcentajes. |
| [getTrimFromStart()](#getTrimFromStart--) | Especifica la duración en milisegundos que se eliminará del principio del medio durante la reproducción. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Especifica la duración en milisegundos que se eliminará del principio del medio durante la reproducción. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Especifica la duración en milisegundos que se eliminará del final del medio durante la reproducción. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Especifica la duración en milisegundos que se eliminará del final del medio durante la reproducción. |
| [getCaptionTracks()](#getCaptionTracks--) | Obtiene la colección de subtítulos cerrados asociados al audio frame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Devuelve o establece un índice de pista de inicio. Lectura/escritura int.

**Devuelve:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Devuelve o establece un índice de pista de inicio. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Devuelve o establece un tiempo de pista de inicio. Lectura/escritura int.

**Devuelve:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Devuelve o establece un tiempo de pista de inicio. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Devuelve o establece un índice de última pista Lectura/escritura int.

**Devuelve:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Devuelve o establece un índice de última pista Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Devuelve o establece un tiempo de última pista Lectura/escritura int.

**Devuelve:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Devuelve o establece un tiempo de última pista Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Devuelve o establece el volumen del audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Devuelve:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Devuelve o establece el volumen del audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Devuelve o establece el modo de reproducción del audio. Lectura/escritura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Devuelve:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Devuelve o establece el modo de reproducción del audio. Lectura/escritura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Determina si un AudioFrame está oculto. Lectura/escritura boolean.

**Devuelve:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Determina si un AudioFrame está oculto. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Determina si un audio está en bucle. Lectura/escritura boolean.

**Devuelve:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Determina si un audio está en bucle. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Determina si un audio se reproduce a través de las diapositivas. Lectura/escritura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Añadir marco de audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurar audio para reproducirse en todas las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar audio para rebobinar automáticamente al inicio después de reproducir
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
public abstract void setPlayAcrossSlides(boolean value)
```

Determina si un audio se reproduce a través de las diapositivas. Lectura/escritura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Añadir marco de audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurar audio para reproducirse en todas las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar audio para rebobinar automáticamente al inicio después de reproducir
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Lectura/escritura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Añadir marco de audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurar audio para reproducirse en todas las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar audio para rebobinar automáticamente al inicio después de reproducir
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
public abstract void setRewindAudio(boolean value)
```

Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Lectura/escritura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Añadir marco de audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurar audio para reproducirse en todas las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar audio para rebobinar automáticamente al inicio después de reproducir
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Determina si un sonido está incrustado en una presentación. Solo lectura boolean.

**Devuelve:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Devuelve o establece el nombre de un archivo de audio enlazado a un AudioFrame. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Devuelve o establece el nombre de un archivo de audio enlazado a un AudioFrame. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Devuelve o establece un objeto de audio incrustado. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Devuelve o establece un objeto de audio incrustado. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
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
public abstract void setFadeInDuration(float value)
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
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
public abstract void setFadeOutDuration(float value)
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Devuelve o establece el volumen del audio en porcentajes. Lectura/escritura float.

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


**Devuelve:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Devuelve o establece el volumen del audio en porcentajes. Lectura/escritura float.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Especifica la duración en milisegundos que se eliminará del principio del medio durante la reproducción. Lectura/escritura float.

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
public abstract void setTrimFromStart(float value)
```

Especifica la duración en milisegundos que se eliminará del principio del medio durante la reproducción. Lectura/escritura float.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```java
public abstract float getTrimFromEnd()
```

Especifica la duración en milisegundos que se eliminará del final del medio durante la reproducción. Lectura/escritura float.

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
public abstract void setTrimFromEnd(float value)
```

Especifica la duración en milisegundos que se eliminará del final del medio durante la reproducción. Lectura/escritura float.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Obtiene la colección de subtítulos cerrados asociados al audio frame. Esta propiedad es solo lectura y devuelve un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) que contiene todas las pistas de subtítulos.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>     for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>     {
>         if (shape instanceof IAudioFrame)
>         {
>             IAudioFrame audioFrame = (IAudioFrame) shape;
>             // Guardar los datos binarios de la pista de subtítulos como un archivo .vtt
>             for (ICaptions captionTrack : audioFrame.getCaptionTracks())
>             {
>                 FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                 fos.write(captionTrack.getBinaryData());
>                 fos.close();
>             }
>         }
>     }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)