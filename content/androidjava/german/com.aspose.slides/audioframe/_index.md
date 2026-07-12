---
title: AudioFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Audioclip auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/audioframe/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Stellt einen Audioclip auf einer Folie dar.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Ermittelt das AudioFrame-Shape
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Setzt den Wiedergabemodus auf Klick
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Setzt die Lautstärke auf niedrig
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Setzt das Audio auf Wiedergabe über Folien hinweg
>      audioFrame.setPlayAcrossSlides(true);
>      // Deaktiviert die Schleife für das Audio
>      audioFrame.setPlayLoopMode(false);
>      // Versteckt das AudioFrame während der Präsentation
>      audioFrame.setHideAtShowing(true);
>      // Spult das Audio nach dem Abspielen zum Anfang zurück
>      audioFrame.setRewindAudio(true);
>      // Speichert die PowerPoint-Datei auf die Festplatte
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Gibt einen Start-Track-Index zurück oder legt ihn fest. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Gibt einen Start-Track-Index zurück oder legt ihn fest. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Gibt eine Start-Track-Zeit zurück oder legt sie fest. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Gibt eine Start-Track-Zeit zurück oder legt sie fest. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Gibt einen letzten Track-Index zurück oder legt ihn fest. Lesen/Schreiben  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Gibt einen letzten Track-Index zurück oder legt ihn fest. Lesen/Schreiben  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Gibt eine letzte Track-Zeit zurück oder legt sie fest. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Gibt eine letzte Track-Zeit zurück oder legt sie fest. |
| [getVolume()](#getVolume--) | Gibt die Audio-Lautstärke zurück oder legt sie fest. |
| [setVolume(int value)](#setVolume-int-) | Gibt die Audio-Lautstärke zurück oder legt sie fest. |
| [getPlayMode()](#getPlayMode--) | Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. |
| [setPlayMode(int value)](#setPlayMode-int-) | Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. |
| [getHideAtShowing()](#getHideAtShowing--) | Ermittelt, ob ein AudioFrame ausgeblendet ist. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Ermittelt, ob ein AudioFrame ausgeblendet ist. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Ermittelt, ob ein Audio wiederholt wird. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Ermittelt, ob ein Audio wiederholt wird. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Ermittelt, ob Audio über die Folien hinweg abgespielt wird. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Ermittelt, ob Audio über die Folien hinweg abgespielt wird. |
| [getRewindAudio()](#getRewindAudio--) | Ermittelt, ob Audio nach dem Abspielen automatisch zum Start zurückgespult wird. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Ermittelt, ob Audio nach dem Abspielen automatisch zum Start zurückgespult wird. |
| [getEmbedded()](#getEmbedded--) | Ermittelt, ob ein Ton in eine Präsentation eingebettet ist. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den Namen einer Audiodatei zurück oder legt ihn fest, die mit einem AudioFrame verknüpft ist. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den Namen einer Audiodatei zurück oder legt ihn fest, die mit einem AudioFrame verknüpft ist. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Gibt ein eingebettetes Audioobjekt zurück oder legt es fest. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Gibt ein eingebettetes Audioobjekt zurück oder legt es fest. |
| [getFadeInDuration()](#getFadeInDuration--) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. |
| [getVolumeValue()](#getVolumeValue--) | Gibt die Audio-Lautstärke in Prozent zurück oder legt sie fest. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Gibt die Audio-Lautstärke in Prozent zurück oder legt sie fest. |
| [getTrimFromStart()](#getTrimFromStart--) | Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. |
| [getCaptionTracks()](#getCaptionTracks--) | Ruft die Sammlung geschlossener Untertitel ab, die dem Audio-Frame zugeordnet sind. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```


Gibt einen Start-Track-Index zurück oder legt ihn fest. Lesen/Schreiben  int .

**Rückgabe:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```


Gibt einen Start-Track-Index zurück oder legt ihn fest. Lesen/Schreiben  int .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```


Gibt eine Start-Track-Zeit zurück oder legt sie fest. Lesen/Schreiben  int .

**Rückgabe:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```


Gibt eine Start-Track-Zeit zurück oder legt sie fest. Lesen/Schreiben  int .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```


Gibt einen letzten Track-Index zurück oder legt ihn fest. Lesen/Schreiben  int .

**Rückgabe:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```


Gibt einen letzten Track-Index zurück oder legt ihn fest. Lesen/Schreiben  int .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```


Gibt eine letzte Track-Zeit zurück oder legt sie fest. Lesen/Schreiben  int .

**Rückgabe:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```


Gibt eine letzte Track-Zeit zurück oder legt sie fest. Lesen/Schreiben  int .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```


Gibt die Audio-Lautstärke zurück oder legt sie fest. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabe:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```


Gibt die Audio-Lautstärke zurück oder legt sie fest. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. Lesen/Schreiben [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Rückgabe:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. Lesen/Schreiben [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Ermittelt, ob ein AudioFrame ausgeblendet ist. Lesen/Schreiben  boolean .

**Rückgabe:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Ermittelt, ob ein AudioFrame ausgeblendet ist. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Ermittelt, ob ein Audio wiederholt wird. Lesen/Schreiben  boolean .

**Rückgabe:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Ermittelt, ob ein Audio wiederholt wird. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```


Ermittelt, ob Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio soll über die Folien hinweg abgespielt werden
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio soll nach dem Abspielen automatisch zum Anfang zurückgespult werden
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
public final void setPlayAcrossSlides(boolean value)
```


Ermittelt, ob Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio über die Folien hinweg abspielen
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio nach dem Abspielen automatisch zum Anfang zurückspulen
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
public final boolean getRewindAudio()
```


Ermittelt, ob Audio nach dem Abspielen automatisch zum Start zurückgespult wird. Lesen/Schreiben  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio über die Folien hinweg abspielen
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio nach dem Abspielen automatisch zum Anfang zurückspulen
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
public final void setRewindAudio(boolean value)
```


Ermittelt, ob Audio nach dem Abspielen automatisch zum Start zurückgespult wird. Lesen/Schreiben  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio über die Folien hinweg abspielen
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio nach dem Abspielen automatisch zum Anfang zurückspulen
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
public final boolean getEmbedded()
```


Ermittelt, ob ein Ton in eine Präsentation eingebettet ist. Schreibgeschützt  boolean .

**Rückgabe:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Gibt den Namen einer Audiodatei zurück oder legt ihn fest, die mit einem AudioFrame verknüpft ist. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Gibt den Namen einer Audiodatei zurück oder legt ihn fest, die mit einem AudioFrame verknüpft ist. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```


Gibt ein eingebettetes Audioobjekt zurück oder legt es fest. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```


Gibt ein eingebettetes Audioobjekt zurück oder legt es fest. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
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
>      // Setzt die Dauer des anfänglichen Einblendens auf 200 ms
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
public final void setFadeInDuration(float value)
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
>      // Setzt die Dauer des anfänglichen Einblendens auf 200 ms
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
public final float getFadeOutDuration()
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
>      // Setzt die Dauer des abschließenden Ausblendens auf 500 ms
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
public final void setFadeOutDuration(float value)
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
>      // Setzt die Dauer des abschließenden Ausblendens auf 500 ms
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
public final float getVolumeValue()
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
>      // Setzt die Audio-Lautstärke auf 85%
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
public final void setVolumeValue(float value)
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
>      // Setzt die Audio-Lautstärke auf 85%
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
public final float getTrimFromStart()
```


Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Lesen/Schreiben float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setzt die Start-Trimmzeit auf 1,5 Sekunden
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```


Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Lesen/Schreiben float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setzt die Start-Trimmzeit auf 1,5 Sekunden
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
public final float getTrimFromEnd()
```


Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Lesen/Schreiben float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setzt die End-Trimmzeit auf 2 Sekunden
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Lesen/Schreiben float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Setzt die End-Trimmzeit auf 2 Sekunden
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
public final ICaptionsCollection getCaptionTracks()
```


Ruft die Sammlung geschlossener Untertitel ab, die dem Audio-Frame zugeordnet sind. Diese Eigenschaft ist schreibgeschützt und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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
>              // Speichert die Binärdaten der Untertitelspur als .vtt-Datei
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

**Rückgabe:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)