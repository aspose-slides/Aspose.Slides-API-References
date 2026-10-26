---
title: AudioFrame
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta una clip audio su una diapositiva.
type: docs
url: /it/com.aspose.slides/audioframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Rappresenta una clip audio su una diapositiva.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Ottiene la forma AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Imposta la modalità di riproduzione su click
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Imposta il volume su Basso
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Imposta l'audio per la riproduzione attraverso le diapositive
>      audioFrame.setPlayAcrossSlides(true);
>      // Disattiva il loop per l'audio
>      audioFrame.setPlayLoopMode(false);
>      // Nasconde l'AudioFrame durante la presentazione
>      audioFrame.setHideAtShowing(true);
>      // Riavvolge l'audio all'inizio dopo la riproduzione
>      audioFrame.setRewindAudio(true);
>      // Salva il file PowerPoint su disco
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Restituisce o imposta un indice di traccia iniziale. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Restituisce o imposta un indice di traccia iniziale. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Restituisce o imposta il tempo di traccia iniziale. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Restituisce o imposta il tempo di traccia iniziale. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Restituisce o imposta un indice di ultima traccia Lettura/scrittura  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Restituisce o imposta un indice di ultima traccia Lettura/scrittura  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Restituisce o imposta il tempo di ultima traccia. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Restituisce o imposta il tempo di ultima traccia. |
| [getVolume()](#getVolume--) | Restituisce o imposta il volume audio. |
| [setVolume(int value)](#setVolume-int-) | Restituisce o imposta il volume audio. |
| [getPlayMode()](#getPlayMode--) | Restituisce o imposta la modalità di riproduzione audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Restituisce o imposta la modalità di riproduzione audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina se un AudioFrame è nascosto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina se un AudioFrame è nascosto. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina se l'audio è in loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina se l'audio è in loop. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determina se l'audio è riprodotto attraverso le diapositive. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determina se l'audio è riprodotto attraverso le diapositive. |
| [getRewindAudio()](#getRewindAudio--) | Determina se l'audio viene automaticamente riportato all'inizio dopo la riproduzione. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determina se l'audio viene automaticamente riportato all'inizio dopo la riproduzione. |
| [getEmbedded()](#getEmbedded--) | Determina se un suono è incorporato in una presentazione. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce o imposta il nome di un file audio collegato a un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce o imposta il nome di un file audio collegato a un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Restituisce o imposta l'oggetto audio incorporato. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Restituisce o imposta l'oggetto audio incorporato. |
| [getFadeInDuration()](#getFadeInDuration--) | Specifica la durata temporale per la dissolvenza iniziale del media in millisecondi. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Specifica la durata temporale per la dissolvenza iniziale del media in millisecondi. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Specifica la durata temporale per la dissolvenza finale del media in millisecondi. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Specifica la durata temporale per la dissolvenza finale del media in millisecondi. |
| [getVolumeValue()](#getVolumeValue--) | Restituisce o imposta il volume audio in percentuale. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Restituisce o imposta il volume audio in percentuale. |
| [getTrimFromStart()](#getTrimFromStart--) | Specifica la durata temporale da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Specifica la durata temporale da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Specifica la durata temporale da rimuovere dalla fine del media durante la riproduzione, in millisecondi. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Specifica la durata temporale da rimuovere dalla fine del media durante la riproduzione, in millisecondi. |
| [getCaptionTracks()](#getCaptionTracks--) | Ottiene la collezione di sottotitoli chiusi associati al frame audio. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Restituisce o imposta un indice di traccia iniziale. Lettura/scrittura  int .

**Restituisce:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Restituisce o imposta un indice di traccia iniziale. Lettura/scrittura  int .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Restituisce o imposta il tempo di traccia iniziale. Lettura/scrittura  int .

**Restituisce:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Restituisce o imposta il tempo di traccia iniziale. Lettura/scrittura  int .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Restituisce o imposta un indice di ultima traccia Lettura/scrittura  int .

**Restituisce:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Restituisce o imposta un indice di ultima traccia Lettura/scrittura  int .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Restituisce o imposta il tempo di ultima traccia. Lettura/scrittura  int .

**Restituisce:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Restituisce o imposta il tempo di ultima traccia. Lettura/scrittura  int .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Restituisce o imposta il volume audio. Lettura/scrittura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Restituisce:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Restituisce o imposta il volume audio. Lettura/scrittura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Restituisce o imposta la modalità di riproduzione audio. Lettura/scrittura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Restituisce:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Restituisce o imposta la modalità di riproduzione audio. Lettura/scrittura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Determina se un AudioFrame è nascosto. Lettura/scrittura  boolean .

**Restituisce:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Determina se un AudioFrame è nascosto. Lettura/scrittura  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Determina se l'audio è in loop. Lettura/scrittura  boolean .

**Restituisce:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Determina se l'audio è in loop. Lettura/scrittura  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Determina se l'audio è riprodotto attraverso le diapositive. Lettura/scrittura  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per riprodursi attraverso le diapositive
>       audioFrame.setPlayAcrossSlides(true);
>       // Imposta l'audio per riavvolgere automaticamente all'inizio dopo la riproduzione
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Restituisce:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Determina se l'audio è riprodotto attraverso le diapositive. Lettura/scrittura  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per riprodursi attraverso le diapositive
>       audioFrame.setPlayAcrossSlides(true);
>       // Imposta l'audio per riavvolgere automaticamente all'inizio dopo la riproduzione
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

Determina se l'audio viene automaticamente riportato all'inizio dopo la riproduzione. Lettura/scrittura  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per riprodursi attraverso le diapositive
>       audioFrame.setPlayAcrossSlides(true);
>       // Imposta l'audio per riavvolgere automaticamente all'inizio dopo la riproduzione
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Restituisce:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Determina se l'audio viene automaticamente riportato all'inizio dopo la riproduzione. Lettura/scrittura  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per riprodursi attraverso le diapositive
>       audioFrame.setPlayAcrossSlides(true);
>       // Imposta l'audio per riavvolgere automaticamente all'inizio dopo la riproduzione
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

Determina se un suono è incorporato in una presentazione. Solo lettura  boolean .

**Restituisce:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Restituisce o imposta il nome di un file audio collegato a un AudioFrame. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Restituisce o imposta il nome di un file audio collegato a un AudioFrame. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Restituisce o imposta l'oggetto audio incorporato. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Restituisce o imposta l'oggetto audio incorporato. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Specifică durata temporală pentru estomparea inițială a media în milisecunde. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata della dissolvenza iniziale a 200ms
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Specifică durata temporală pentru estomparea inițială a media în milisecunde. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata della dissolvenza iniziale a 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

Specifică durata temporală pentru estomparea finală a media în milisecunde. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata della dissolvenza finale a 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Specifică durata temporală pentru estomparea finală a media în milisecunde. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata della dissolvenza finale a 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Restituisce o imposta il volume audio in percentuale. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il volume audio al 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Restituisce o imposta il volume audio in percentuale. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il volume audio al 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Specifică durata temporală de eliminat din începutul media în timpul redării, în milisecunde. Lettura/scrittura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il tempo di ritaglio iniziale a 1,5 secondi
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Specifică durata temporală de eliminat din începutul media în timpul redării, în milisecunde. Lettura/scrittura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il tempo di ritaglio iniziale a 1,5 secondi
>      audioFrame.setTrimFromStart(1500f);
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
public final float getTrimFromEnd()
```

Specifică durata temporală de eliminat din sfârșitul media în timpul redării, în milisecunde. Lettura/scrittura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il tempo di ritaglio finale a 2 secondi
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Specifică durata temporală de eliminat din sfârșitul media în timpul redării, în milisecunde. Lettura/scrittura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il tempo di ritaglio finale a 2 secondi
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Ottiene la collezione di sottotitoli chiusi associati al frame audio. Questa proprietà è solo lettura e restituisce un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenente tutte le tracce di sottotitoli.

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
>              // Salva i dati binari della traccia di sottotitoli come file .vtt
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


**Restituisce:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)