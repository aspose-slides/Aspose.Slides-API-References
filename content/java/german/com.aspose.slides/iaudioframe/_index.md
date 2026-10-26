---
title: IAudioFrame
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Audioclip auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/iaudioframe/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Stellt einen Audioclip auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Gibt einen Start-Track-Index zurück oder legt ihn fest. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Gibt einen Start-Track-Index zurück oder legt ihn fest. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Gibt die Start-Track-Zeit zurück oder legt sie fest. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Gibt die Start-Track-Zeit zurück oder legt sie fest. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Gibt einen letzten Track-Index zurück oder legt ihn fest Lesen/Schreiben int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Gibt einen letzten Track-Index zurück oder legt ihn fest Lesen/Schreiben int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Gibt die letzte Track-Zeit zurück oder legt sie fest. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Gibt die letzte Track-Zeit zurück oder legt sie fest. |
| [getVolume()](#getVolume--) | Gibt die Audio-Lautstärke zurück oder legt sie fest. |
| [setVolume(int value)](#setVolume-int-) | Gibt die Audio-Lautstärke zurück oder legt sie fest. |
| [getPlayMode()](#getPlayMode--) | Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. |
| [setPlayMode(int value)](#setPlayMode-int-) | Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestimmt, ob ein AudioFrame ausgeblendet ist. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestimmt, ob ein AudioFrame ausgeblendet ist. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestimmt, ob ein Audio wiederholt wird. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestimmt, ob ein Audio wiederholt wird. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Bestimmt, ob ein Audio über die Folien hinweg abgespielt wird. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Bestimmt, ob ein Audio über die Folien hinweg abgespielt wird. |
| [getRewindAudio()](#getRewindAudio--) | Bestimmt, ob ein Audio nach der Wiedergabe automatisch zum Anfang zurückgespult wird. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Bestimmt, ob ein Audio nach der Wiedergabe automatisch zum Anfang zurückgespult wird. |
| [getEmbedded()](#getEmbedded--) | Bestimmt, ob ein Sound in die Präsentation eingebettet ist. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den Namen einer Audiodatei zurück oder legt ihn fest, die mit einem AudioFrame verknüpft ist. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den Namen einer Audiodatei zurück oder legt ihn fest, die mit einem AudioFrame verknüpft ist. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Gibt das eingebettete Audio-Objekt zurück oder legt es fest. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Gibt das eingebettete Audio-Objekt zurück oder legt es fest. |
| [getFadeInDuration()](#getFadeInDuration--) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. |
| [getVolumeValue()](#getVolumeValue--) | Gibt die Audio-Lautstärke in Prozent zurück oder legt sie fest. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Gibt die Audio-Lautstärke in Prozent zurück oder legt sie fest. |
| [getTrimFromStart()](#getTrimFromStart--) | Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt wird, in Millisekunden. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt wird, in Millisekunden. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden. |
| [getCaptionTracks()](#getCaptionTracks--) | Ruft die Sammlung der geschlossenen Untertitel ab, die mit dem Audio-Frame verknüpft sind. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Gibt einen Start-Track-Index zurück oder legt ihn fest. Lesen/Schreiben int.

**Rückgabe:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Gibt einen Start-Track-Index zurück oder legt ihn fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Gibt die Start-Track-Zeit zurück oder legt sie fest. Lesen/Schreiben int.

**Rückgabe:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Gibt die Start-Track-Zeit zurück oder legt sie fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Gibt einen letzten Track-Index zurück oder legt ihn fest. Lesen/Schreiben int.

**Rückgabe:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Gibt einen letzten Track-Index zurück oder legt ihn fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Gibt die letzte Track-Zeit zurück oder legt sie fest. Lesen/Schreiben int.

**Rückgabe:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Gibt die letzte Track-Zeit zurück oder legt sie fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Gibt die Audio-Lautstärke zurück oder legt sie fest. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabe:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Gibt die Audio-Lautstärke zurück oder legt sie fest. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. Lesen/Schreiben [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Rückgabe:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. Lesen/Schreiben [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bestimmt, ob ein AudioFrame ausgeblendet ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bestimmt, ob ein AudioFrame ausgeblendet ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bestimmt, ob ein Audio wiederholt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bestimmt, ob ein Audio wiederholt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Bestimmt, ob ein Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio so einstellen, dass es über alle Folien abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückspult
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Rückgabe:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Bestimmt, ob ein Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio so einstellen, dass es über alle Folien abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückspult
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Bestimmt, ob ein Audio nach der Wiedergabe automatisch zum Anfang zurückgespult wird. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio so einstellen, dass es über alle Folien abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückspult
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Rückgabe:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Bestimmt, ob ein Audio nach der Wiedergabe automatisch zum Anfang zurückgespult wird. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio so einstellen, dass es über alle Folien abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückspult
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Bestimmt, ob ein Sound in die Präsentation eingebettet ist. Nur lesen boolean.

**Rückgabe:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Gibt den Namen einer Audiodatei zurück oder legt ihn fest, die mit einem AudioFrame verknüpft ist. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Gibt den Namen einer Audiodatei zurück oder legt ihn fest, die mit einem AudioFrame verknüpft ist. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Gibt das eingebettete Audio-Objekt zurück oder legt es fest. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Gibt das eingebettete Audio-Objekt zurück oder legt es fest. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Dauer des anfänglichen Einblendens auf 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Dauer des anfänglichen Einblendeffekts auf 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Dauer des abschließenden Ausblendeffekts auf 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Dauer des abschließenden Ausblendeffekts auf 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Gibt die Audio-Lautstärke in Prozent zurück oder legt sie fest. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Audio-Lautstärke auf 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Gibt die Audio-Lautstärke in Prozent zurück oder legt sie fest. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Audio-Lautstärke auf 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt wird, in Millisekunden. Lesen/Schreiben float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Startbeschneidungszeit auf 1,5 Sekunden
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt wird, in Millisekunden. Lesen/Schreiben float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Startbeschneidungszeit auf 1,5 Sekunden
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden. Lesen/Schreiben float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Endbeschneidungszeit auf 2 Sekunden
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden. Lesen/Schreiben float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Endbeschneidungszeit auf 2 Sekunden
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Ruft die Sammlung der geschlossenen Untertitel ab, die mit dem Audio-Frame verknüpft sind. Diese Eigenschaft ist Nur lesen und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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
>             // Speichern Sie die Binärdaten der Untertitelspur als .vtt-Datei
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


**Rückgabe:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)