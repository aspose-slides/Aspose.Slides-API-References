---
title: AudioFrame
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una clip audio su una diapositiva.
type: docs
url: /it/com.aspose.slides/audioframe/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Tutte le interfacce implementate:**
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
>      // Ottiene lo shape AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Imposta la modalità di riproduzione su clic
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Imposta il volume su Basso
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Imposta l'audio per la riproduzione su più diapositive
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
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Restituisce o imposta l'indice di traccia iniziale. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Restituisce o imposta l'indice di traccia iniziale. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Restituisce o imposta il tempo di traccia iniziale. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Restituisce o imposta il tempo di traccia iniziale. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Restituisce o imposta l'indice dell'ultima traccia Lettura/Scrittura int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Restituisce o imposta l'indice dell'ultima traccia Lettura/Scrittura int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Restituisce o imposta il tempo dell'ultima traccia. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Restituisce o imposta il tempo dell'ultima traccia. |
| [getVolume()](#getVolume--) | Restituisce o imposta il volume audio. |
| [setVolume(int value)](#setVolume-int-) | Restituisce o imposta il volume audio. |
| [getPlayMode()](#getPlayMode--) | Restituisce o imposta la modalità di riproduzione audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Restituisce o imposta la modalità di riproduzione audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina se un AudioFrame è nascosto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina se un AudioFrame è nascosto. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina se un audio è in loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina se un audio è in loop. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determina se l'audio è riprodotto su più diapositive. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determina se l'audio è riprodotto su più diapositive. |
| [getRewindAudio()](#getRewindAudio--) | Determina se l'audio è riavvolto automaticamente all'inizio dopo la riproduzione. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determina se l'audio è riavvolto automaticamente all'inizio dopo la riproduzione. |
| [getEmbedded()](#getEmbedded--) | Determina se un suono è incorporato in una presentazione. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce o imposta il nome di un file audio collegato a un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce o imposta il nome di un file audio collegato a un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Restituisce o imposta l'oggetto audio incorporato. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Restituisce o imposta l'oggetto audio incorporato. |
| [getFadeInDuration()](#getFadeInDuration--) | Specifica la durata temporale per l'effetto di fade-in iniziale dei media in millisecondi. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Specifica la durata temporale per l'effetto di fade-in iniziale dei media in millisecondi. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Specifica la durata temporale per l'effetto di fade-out finale dei media in millisecondi. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Specifica la durata temporale per l'effetto di fade-out finale dei media in millisecondi. |
| [getVolumeValue()](#getVolumeValue--) | Restituisce o imposta il volume audio in percentuale. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Restituisce o imposta il volume audio in percentuale. |
| [getTrimFromStart()](#getTrimFromStart--) | Specifica la durata temporale da rimuovere dall'inizio dei media durante la riproduzione, in millisecondi. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Specifica la durata temporale da rimuovere dall'inizio dei media durante la riproduzione, in millisecondi. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Specifica la durata temporale da rimuovere dalla fine dei media durante la riproduzione, in millisecondi. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Specifica la durata temporale da rimuovere dalla fine dei media durante la riproduzione, in millisecondi. |
| [getCaptionTracks()](#getCaptionTracks--) | Ottiene la collezione di sottotitoli chiusi associati al frame audio. |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Restituisce o imposta l'indice di traccia iniziale. Lettura/Scrittura int.

**Restituisce:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Restituisce o imposta l'indice di traccia iniziale. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Restituisce o imposta il tempo di traccia iniziale. Lettura/Scrittura int.

**Restituisce:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Restituisce o imposta il tempo di traccia iniziale. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Restituisce o imposta l'indice dell'ultima traccia Lettura/Scrittura int.

**Restituisce:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Restituisce o imposta l'indice dell'ultima traccia Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Restituisce o imposta il tempo dell'ultima traccia. Lettura/Scrittura int.

**Restituisce:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Restituisce o imposta il tempo dell'ultima traccia. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getVolume() {#getVolume--}
```
public final int getVolume()
```

Restituisce o imposta il volume audio. Lettura/Scrittura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Restituisce:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Restituisce o imposta il volume audio. Lettura/Scrittura [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Restituisce o imposta la modalità di riproduzione audio. Lettura/Scrittura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Restituisce:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Restituisce o imposta la modalità di riproduzione audio. Lettura/Scrittura [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Determina se un AudioFrame è nascosto. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Determina se un AudioFrame è nascosto. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Determina se un audio è in loop. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Determina se un audio è in loop. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Determina se l'audio è riprodotto su più diapositive. Lettura/Scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi frame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per la riproduzione su più diapositive
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

Determina se l'audio è riprodotto su più diapositive. Lettura/Scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi frame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per la riproduzione su più diapositive
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

Determina se l'audio è riavvolto automaticamente all'inizio dopo la riproduzione. Lettura/Scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi frame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per la riproduzione su più diapositive
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

Determina se l'audio è riavvolto automaticamente all'inizio dopo la riproduzione. Lettura/Scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Aggiungi frame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Imposta l'audio per la riproduzione su più diapositive
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

Determina se un suono è incorporato in una presentazione. Solo lettura boolean.

**Restituisce:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Restituisce o imposta il nome di un file audio collegato a un AudioFrame. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Restituisce o imposta il nome di un file audio collegato a un AudioFrame. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Restituisce o imposta l'oggetto audio incorporato. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Restituisce o imposta l'oggetto audio incorporato. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Specifică durata temporale per l'effetto di fade-in iniziale dei media in millisecondi. Lettura/Scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata del fade iniziale a 200 ms
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
public final void setFadeInDuration(float value)
```

Specifică durata temporale per l'effetto di fade-in iniziale dei media in millisecondi. Lettura/Scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata del fade iniziale a 200 ms
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

Specifică durata temporale per l'effetto di fade-out finale dei media in millisecondi. Lettura/Scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata del fade finale a 500 ms
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

Specifică durata temporale per l'effetto di fade-out finale dei media in millisecondi. Lettura/Scrittura float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta la durata del fade finale a 500 ms
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

Restituisce o imposta il volume audio in percentuale. Lettura/Scrittura float.

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
public final void setVolumeValue(float value)
```

Restituisce o imposta il volume audio in percentuale. Lettura/Scrittura float.

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
public final float getTrimFromStart()
```

Specifică durata temporale da rimuovere dall'inizio dei media durante la riproduzione, in millisecondi. Lettura/Scrittura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il tempo di taglio iniziale a 1.5 secondi
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

Specifică durata temporale da rimuovere dall'inizio dei media durante la riproduzione, in millisecondi. Lettura/Scrittura float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Imposta il tempo di taglio iniziale a 1.5 secondi
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

Specifică durata temporale da rimuovere dalla fine dei media durante la riproduzione, in millisecondi. Lettura/Scrittura float.

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

**Restituisce:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Specifică durata temporale da rimuovere dalla fine dei media durante la riproduzione, in millisecondi. Lettura/Scrittura float.

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
>              // Salva i dati binari della traccia dei sottotitoli come file .vtt
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