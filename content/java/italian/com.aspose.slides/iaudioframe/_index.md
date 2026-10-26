---
title: IAudioFrame
second_title: Riferimento API per Aspose.Slides per Java
description: Rappresenta una clip audio su una diapositiva.
type: docs
url: /it/com.aspose.slides/iaudioframe/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Rappresenta una clip audio su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Restituisce o imposta un indice di traccia di avvio. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Restituisce o imposta un indice di traccia di avvio. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Restituisce o imposta un tempo di traccia di avvio. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Restituisce o imposta un tempo di traccia di avvio. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Restituisce o imposta un indice di ultima traccia. Lettura/scrittura int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Restituisce o imposta un indice di ultima traccia. Lettura/scrittura int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Restituisce o imposta un tempo di ultima traccia. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Restituisce o imposta un tempo di ultima traccia. |
| [getVolume()](#getVolume--) | Restituisce o imposta il volume audio. |
| [setVolume(int value)](#setVolume-int-) | Restituisce o imposta il volume audio. |
| [getPlayMode()](#getPlayMode--) | Restituisce o imposta la modalità di riproduzione audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Restituisce o imposta la modalità di riproduzione audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina se un AudioFrame è nascosto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina se un AudioFrame è nascosto. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina se un audio è in loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina se un audio è in loop. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determina se un audio viene riprodotto attraverso le diapositive. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determina se un audio viene riprodotto attraverso le diapositive. |
| [getRewindAudio()](#getRewindAudio--) | Determina se un audio viene automaticamente riavvolto all'inizio dopo la riproduzione. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determina se un audio viene automaticamente riavvolto all'inizio dopo la riproduzione. |
| [getEmbedded()](#getEmbedded--) | Determina se un suono è incorporato in una presentazione. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce o imposta il nome di un file audio collegato a un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce o imposta il nome di un file audio collegato a un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Restituisce o imposta l'oggetto audio incorporato. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Restituisce o imposta l'oggetto audio incorporato. |
| [getFadeInDuration()](#getFadeInDuration--) | Specifica la durata in millisecondi del fade-in iniziale del media. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Specifica la durata in millisecondi del fade-in iniziale del media. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Specifica la durata in millisecondi del fade-out finale del media. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Specifica la durata in millisecondi del fade-out finale del media. |
| [getVolumeValue()](#getVolumeValue--) | Restituisce o imposta il volume audio in percentuale. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Restituisce o imposta il volume audio in percentuale. |
| [getTrimFromStart()](#getTrimFromStart--) | Specifica la durata da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Specifica la durata da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Specifica la durata da rimuovere dalla fine del media durante la riproduzione, in millisecondi. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Specifica la durata da rimuovere dalla fine del media durante la riproduzione, in millisecondi. |
| [getCaptionTracks()](#getCaptionTracks--) | Ottiene la raccolta di didascalie chiuse associate al frame audio. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Restituisce o imposta un indice di traccia di avvio. Lettura/scrittura int.

**Restituisce:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Restituisce o imposta un indice di traccia di avvio. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Restituisce o imposta un tempo di traccia di avvio. Lettura/scrittura int.

**Restituisce:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Restituisce o imposta un tempo di traccia di avvio. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Restituisce o imposta un indice di ultima traccia. Lettura/scrittura int.

**Restituisce:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Restituisce o imposta un indice di ultima traccia. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Restituisce o imposta un tempo di ultima traccia. Lettura/scrittura int.

**Restituisce:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Restituisce o imposta un tempo di ultima traccia. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

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

Restituisce o imposta la modalità di riproduzione audio. Lettura/scrittura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Restituisce:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Restituisce o imposta la modalità di riproduzione audio. Lettura/scrittura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Determina se un AudioFrame è nascosto. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Determina se un AudioFrame è nascosto. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Determina se un audio è in loop. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Determina se un audio è in loop. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Determina se un audio viene riprodotto attraverso le diapositive. Lettura/scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per la riproduzione attraverso le diapositive
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
public abstract void setPlayAcrossSlides(boolean value)
```

Determina se un audio viene riprodotto attraverso le diapositive. Lettura/scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per la riproduzione attraverso le diapositive
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
public abstract boolean getRewindAudio()
```

Determina se un audio viene automaticamente riavvolto all'inizio dopo la riproduzione. Lettura/scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per la riproduzione attraverso le diapositive
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
public abstract void setRewindAudio(boolean value)
```

Determina se un audio viene automaticamente riavvolto all'inizio dopo la riproduzione. Lettura/scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per la riproduzione attraverso le diapositive
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
public abstract boolean getEmbedded()
```

Determina se un suono è incorporato in una presentazione. Solo lettura boolean.

**Restituisce:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Restituisce o imposta il nome di un file audio collegato a un AudioFrame. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Restituisce o imposta il nome di un file audio collegato a un AudioFrame. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Restituisce o imposta l'oggetto audio incorporato. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Restituisce o imposta l'oggetto audio incorporato. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Specifica la durata in millisecondi del fade-in iniziale del media. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata del fade iniziale a 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Specifica la durata in millisecondi del fade-in iniziale del media. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata del fade iniziale a 200ms
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
public abstract float getFadeOutDuration()
```

Specifica la durata in millisecondi del fade-out finale del media. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata del fade finale a 500ms
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
public abstract void setFadeOutDuration(float value)
```

Specifica la durata in millisecondi del fade-out finale del media. Lettura/scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata del fade finale a 500ms
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
public abstract float getVolumeValue()
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
>      // Imposta il volume audio all'85%
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
public abstract void setVolumeValue(float value)
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
>      // Imposta il volume audio all'85%
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
public abstract float getTrimFromStart()
```

Specifica la durata da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. Lettura/scrittura float.

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

Specifica la durata da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. Lettura/scrittura float.

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
public abstract float getTrimFromEnd()
```

Specifica la durata da rimuovere dalla fine del media durante la riproduzione, in millisecondi. Lettura/scrittura float.

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
public abstract void setTrimFromEnd(float value)
```

Specifica la durata da rimuovere dalla fine del media durante la riproduzione, in millisecondi. Lettura/scrittura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il tempo di taglio finale a 2 secondi
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
public abstract ICaptionsCollection getCaptionTracks()
```

Ottiene la raccolta di didascalie chiuse associate al frame audio. Questa proprietà è di sola lettura e restituisce un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenente tutte le tracce di didascalia.

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
>             // Salva i dati binari della traccia di didascalia come file .vtt
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

**Restituisce:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)