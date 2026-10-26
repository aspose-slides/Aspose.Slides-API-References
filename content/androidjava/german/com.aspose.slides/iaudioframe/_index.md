---
title: IAudioFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Gibt einen Startspur-Index zurück oder setzt ihn. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Gibt einen Startspur-Index zurück oder setzt ihn. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Gibt die Startspurzeit zurück oder setzt sie. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Gibt die Startspurzeit zurück oder setzt sie. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Gibt einen letzten Spur-Index zurück oder setzt ihn. Lese-/Schreibzugriff int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Gibt einen letzten Spur-Index zurück oder setzt ihn. Lese-/Schreibzugriff int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Gibt die letzte Spurzeit zurück oder setzt sie. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Gibt die letzte Spurzeit zurück oder setzt sie. |
| [getVolume()](#getVolume--) | Gibt die Lautstärke zurück oder setzt sie. |
| [setVolume(int value)](#setVolume-int-) | Gibt die Lautstärke zurück oder setzt sie. |
| [getPlayMode()](#getPlayMode--) | Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. |
| [setPlayMode(int value)](#setPlayMode-int-) | Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestimmt, ob ein AudioFrame ausgeblendet ist. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestimmt, ob ein AudioFrame ausgeblendet ist. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestimmt, ob ein Audio wiederholt wird. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestimmt, ob ein Audio wiederholt wird. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Bestimmt, ob ein Audio über alle Folien hinweg abgespielt wird. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Bestimmt, ob ein Audio über alle Folien hinweg abgespielt wird. |
| [getRewindAudio()](#getRewindAudio--) | Bestimmt, ob ein Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Bestimmt, ob ein Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. |
| [getEmbedded()](#getEmbedded--) | Bestimmt, ob ein Sound in die Präsentation eingebettet ist. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Gibt das eingebettete Audio-Objekt zurück oder setzt es. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Gibt das eingebettete Audio-Objekt zurück oder setzt es. |
| [getFadeInDuration()](#getFadeInDuration--) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. |
| [getVolumeValue()](#getVolumeValue--) | Gibt die Lautstärke in Prozent zurück oder setzt sie. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Gibt die Lautstärke in Prozent zurück oder setzt sie. |
| [getTrimFromStart()](#getTrimFromStart--) | Gibt die zu Beginn der Wiedergabe zu entfernende Zeitdauer in Millisekunden an. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Gibt die zu Beginn der Wiedergabe zu entfernende Zeitdauer in Millisekunden an. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Gibt die am Ende der Wiedergabe zu entfernende Zeitdauer in Millisekunden an. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Gibt die am Ende der Wiedergabe zu entfernende Zeitdauer in Millisekunden an. |
| [getCaptionTracks()](#getCaptionTracks--) | Ruft die Sammlung geschlossener Untertitel ab, die mit dem Audioframe verbunden sind. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Gibt einen Startspur-Index zurück oder setzt ihn. Lese-/Schreibzugriff int.

**Rückgabe:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Gibt einen Startspur-Index zurück oder setzt ihn. Lese-/Schreibzugriff int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Gibt die Startspurzeit zurück oder setzt sie. Lese-/Schreibzugriff int.

**Rückgabe:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Gibt die Startspurzeit zurück oder setzt sie. Lese-/Schreibzugriff int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Gibt einen letzten Spur-Index zurück oder setzt ihn. Lese-/Schreibzugriff int.

**Rückgabe:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Gibt einen letzten Spur-Index zurück oder setzt ihn. Lese-/Schreibzugriff int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Gibt die letzte Spurzeit zurück oder setzt sie. Lese-/Schreibzugriff int.

**Rückgabe:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Gibt die letzte Spurzeit zurück oder setzt sie. Lese-/Schreibzugriff int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Gibt die Lautstärke zurück oder setzt sie. Lese-/Schreibzugriff [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabe:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Gibt die Lautstärke zurück oder setzt sie. Lese-/Schreibzugriff [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. Lese-/Schreibzugriff [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Rückgabe:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. Lese-/Schreibzugriff [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bestimmt, ob ein AudioFrame ausgeblendet ist. Lese-/Schreibzugriff boolean.

**Rückgabe:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bestimmt, ob ein AudioFrame ausgeblendet ist. Lese-/Schreibzugriff boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bestimmt, ob ein Audio wiederholt wird. Lese-/Schreibzugriff boolean.

**Rückgabe:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bestimmt, ob ein Audio wiederholt wird. Lese-/Schreibzugriff boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Bestimmt, ob ein Audio über alle Folien hinweg abgespielt wird. Lese-/Schreibzugriff boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio so einstellen, dass es über die Folien hinweg abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückgespult wird
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

Bestimmt, ob ein Audio über alle Folien hinweg abgespielt wird. Lese-/Schreibzugriff boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio so einstellen, dass es über die Folien hinweg abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückgespult wird
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

Bestimmt, ob ein Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lese-/Schreibzugriff boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio so einstellen, dass es über die Folien hinweg abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückgespult wird
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

Bestimmt, ob ein Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lese-/Schreibzugriff boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio so einstellen, dass es über die Folien hinweg abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückgespult wird
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

Bestimmt, ob ein Sound in die Präsentation eingebettet ist. Nur Lesezugriff boolean.

**Rückgabe:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. Lese-/Schreibzugriff String.

**Rückgabe:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. Lese-/Schreibzugriff String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Gibt das eingebettete Audio-Objekt zurück oder setzt es. Lese-/Schreibzugriff [IAudio](../../com.aspose.slides/iaudio).

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Gibt das eingebettete Audio-Objekt zurück oder setzt es. Lese-/Schreibzugriff [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Lese-/Schreibzugriff float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Dauer des startenden Einblendens auf 200 ms
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

Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Lese-/Schreibzugriff float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Dauer des startenden Einblendens auf 200ms
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

Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. Lese-/Schreibzugriff float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Dauer des abschließenden Ausblendens auf 500ms
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

Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. Lese-/Schreibzugriff float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Dauer des abschließenden Ausblendens auf 500ms
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

Gibt die Lautstärke in Prozent zurück oder setzt sie. Lese-/Schreibzugriff float.

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

Gibt die Lautstärke in Prozent zurück oder setzt sie. Lese-/Schreibzugriff float.

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

Gibt die zu Beginn der Wiedergabe zu entfernende Zeitdauer in Millisekunden an. Lese-/Schreibzugriff float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Startzeit für das Trimmen auf 1,5 Sekunden
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

Gibt die zu Beginn der Wiedergabe zu entfernende Zeitdauer in Millisekunden an. Lese-/Schreibzugriff float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Startzeit für das Trimmen auf 1,5 Sekunden
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

Gibt die am Ende der Wiedergabe zu entfernende Zeitdauer in Millisekunden an. Lese-/Schreibzugriff float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Endzeit für das Trimmen auf 2 Sekunden
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

Gibt die am Ende der Wiedergabe zu entfernende Zeitdauer in Millisekunden an. Lese-/Schreibzugriff float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setze die Endzeit für das Trimmen auf 2 Sekunden
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

Ruft die Sammlung geschlossener Untertitel ab, die dem Audioframe zugeordnet sind. Diese Eigenschaft ist nur Lesezugriff und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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
>             // Speichere die binären Daten der Untertitelspur als .vtt-Datei
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