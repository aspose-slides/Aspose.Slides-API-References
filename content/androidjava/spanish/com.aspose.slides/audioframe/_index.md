---
title: AudioFrame
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un clip de audio en una diapositiva.
type: docs
url: /es/com.aspose.slides/audioframe/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Todas las interfaces implementadas:**
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
>      // Establece el volumen a Bajo
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Establece el audio para reproducirse a través de las diapositivas
>      audioFrame.setPlayAcrossSlides(true);
>      // Desactiva el bucle para el audio
>      audioFrame.setPlayLoopMode(false);
>      // Oculta el AudioFrame durante la presentación
>      audioFrame.setHideAtShowing(true);
>      // Retrocede el audio al inicio después de reproducirlo
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
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Devuelve o establece un índice de pista de inicio. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Devuelve o establece un índice de pista de inicio. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Devuelve o establece un tiempo de pista de inicio. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Devuelve o establece un tiempo de pista de inicio. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Devuelve o establece un índice de pista final Lectura/escritura  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Devuelve o establece un índice de pista final Lectura/escritura  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Devuelve o establece un tiempo de pista final. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Devuelve o establece un tiempo de pista final. |
| [getVolume()](#getVolume--) | Devuelve o establece el volumen del audio. |
| [setVolume(int value)](#setVolume-int-) | Devuelve o establece el volumen del audio. |
| [getPlayMode()](#getPlayMode--) | Devuelve o establece el modo de reproducción del audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Devuelve o establece el modo de reproducción del audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina si un AudioFrame está oculto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina si un AudioFrame está oculto. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina si un audio se reproduce en bucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina si un audio se reproduce en bucle. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determina si el audio se reproduce a través de las diapositivas. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determina si el audio se reproduce a través de las diapositivas. |
| [getRewindAudio()](#getRewindAudio--) | Determina si el audio se rebobina automáticamente al inicio después de reproducirse. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determina si el audio se rebobina automáticamente al inicio después de reproducirse. |
| [getEmbedded()](#getEmbedded--) | Determina si un sonido está incrustado en una presentación. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve o establece el nombre de un archivo de audio que está enlazado a un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve o establece el nombre de un archivo de audio que está enlazado a un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Devuelve o establece el objeto de audio incrustado. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Devuelve o establece el objeto de audio incrustado. |
| [getFadeInDuration()](#getFadeInDuration--) | Especifica la duración del fundido de entrada inicial de los medios en milisegundos. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Especifica la duración del fundido de entrada inicial de los medios en milisegundos. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Especifica la duración del fundido de salida final de los medios en milisegundos. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Especifica la duración del fundido de salida final de los medios en milisegundos. |
| [getVolumeValue()](#getVolumeValue--) | Devuelve o establece el volumen del audio en porcentajes. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Devuelve o establece el volumen del audio en porcentajes. |
| [getTrimFromStart()](#getTrimFromStart--) | Especifica la duración que se debe eliminar del comienzo de los medios durante la reproducción, en milisegundos. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Especifica la duración que se debe eliminar del comienzo de los medios durante la reproducción, en milisegundos. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Especifica la duración que se debe eliminar del final de los medios durante la reproducción, en milisegundos. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Especifica la duración que se debe eliminar del final de los medios durante la reproducción, en milisegundos. |
| [getCaptionTracks()](#getCaptionTracks--) | Obtiene la colección de subtítulos cerrados asociados al marco de audio. |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Devuelve o establece un índice de pista de inicio. Lectura/escritura  int .

**Devuelve:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Devuelve o establece un índice de pista de inicio. Lectura/escritura  int .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Devuelve o establece un tiempo de pista de inicio. Lectura/escritura  int .

**Devuelve:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrack(int value)
```

Devuelve o establece un tiempo de pista de inicio. Lectura/escritura  int .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Devuelve o establece un índice de pista final Lectura/escritura  int .

**Devuelve:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Devuelve o establece un índice de pista final Lectura/escritura  int .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Devuelve o establece un tiempo de pista final. Lectura/escritura  int .

**Devuelve:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Devuelve o establece un tiempo de pista final. Lectura/escritura  int .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getVolume() {#getVolume--}
```
public final int getVolume()
```

Devuelve o establece el volumen del audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Devuelve:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Devuelve o establece el volumen del audio. Lectura/escritura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Devuelve o establece el modo de reproducción del audio. Lectura/escritura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Devuelve:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Devuelve o establece el modo de reproducción del audio. Lectura/escritura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parámetros:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
>       // Configurar el audio para reproducir a través de las diapositivas
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
>       // Configurar el audio para reproducir a través de las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar el audio para rebobinar automáticamente al inicio después de reproducir
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
>       // Configurar el audio para reproducir a través de las diapositivas
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
>       // Configurar el audio para reproducir a través de las diapositivas
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurar el audio para rebobinar automáticamente al inicio después de reproducir
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
public final boolean getEmbedded()
```

Determina si un sonido está incrustado en una presentación. Solo lectura  boolean .

**Devuelve:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Devuelve o establece el nombre de un archivo de audio que está enlazado a un AudioFrame. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Devuelve o establece el nombre de un archivo de audio que está enlazado a un AudioFrame. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Devuelve o establece el objeto de audio incrustado. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Devuelve o establece el objeto de audio incrustado. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Especifica la duración del fundido de entrada inicial de los medios en milisegundos. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer la duración del fundido de inicio a 200 ms
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

Especifica la duración del fundido de entrada inicial de los medios en milisegundos. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer la duración del fundido inicial a 200 ms
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
public final float getFadeOutDuration()
```

Especifica la duración del fundido de salida final de los medios en milisegundos. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer la duración del fundido final a 500 ms
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

Especifica la duración del fundido de salida final de los medios en milisegundos. Lectura/escritura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer la duración del fundido final a 500 ms
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
public final float getVolumeValue()
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
public final void setVolumeValue(float value)
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
public final float getTrimFromStart()
```

Especifica la duración que se debe eliminar del comienzo de los medios durante la reproducción, en milisegundos. Lectura/escritura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer el tiempo de recorte de inicio a 1.5 segundos
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

Especifica la duración que se debe eliminar del comienzo de los medios durante la reproducción, en milisegundos. Lectura/escritura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Establecer el tiempo de recorte de inicio a 1.5 segundos
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
```
public final float getTrimFromEnd()
```

Especifica la duración que se debe eliminar del final de los medios durante la reproducción, en milisegundos. Lectura/escritura float.

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

Especifica la duración que se debe eliminar del final de los medios durante la reproducción, en milisegundos. Lectura/escritura float.

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
public final ICaptionsCollection getCaptionTracks()
```

Obtiene la colección de subtítulos cerrados asociados al marco de audio. Esta propiedad es solo lectura y devuelve un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) que contiene todas las pistas de subtítulos.

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