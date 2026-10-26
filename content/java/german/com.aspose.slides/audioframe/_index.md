---
title: AudioFrame
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Audio-Clip auf einer Folie dar.
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

Stellt einen Audio-Clip auf einer Folie dar.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Ruft das AudioFrame-Shape ab
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Setzt den Wiedergabemodus auf Abspielen bei Klick
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Setzt die Lautstärke auf Niedrig
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Setzt das Audio so, dass es über Folien hinweg abgespielt wird
>      audioFrame.setPlayAcrossSlides(true);
>      // Deaktiviert die Wiederholung für das Audio
>      audioFrame.setPlayLoopMode(false);
>      // Blendet das AudioFrame während der Bildschirmpräsentation aus
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
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Gibt einen Start-Track-Index zurück oder setzt ihn. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Gibt einen Start-Track-Index zurück oder setzt ihn. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Gibt einen Start-Track-Zeitwert zurück oder setzt ihn. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Gibt einen Start-Track-Zeitwert zurück oder setzt ihn. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Gibt einen letzten Track-Index zurück oder setzt ihn. Lesen/Schreiben int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Gibt einen letzten Track-Index zurück oder setzt ihn. Lesen/Schreiben int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Gibt einen letzten Track-Zeitwert zurück oder setzt ihn. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Gibt einen letzten Track-Zeitwert zurück oder setzt ihn. |
| [getVolume()](#getVolume--) | Gibt die Audio-Lautstärke zurück oder setzt sie. |
| [setVolume(int value)](#setVolume-int-) | Gibt die Audio-Lautstärke zurück oder setzt sie. |
| [getPlayMode()](#getPlayMode--) | Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. |
| [setPlayMode(int value)](#setPlayMode-int-) | Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestimmt, ob ein AudioFrame ausgeblendet ist. Lesen/Schreiben boolean. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestimmt, ob ein AudioFrame ausgeblendet ist. Lesen/Schreiben boolean. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestimmt, ob Audio wiederholt wird. Lesen/Schreiben boolean. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestimmt, ob Audio wiederholt wird. Lesen/Schreiben boolean. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben boolean. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben boolean. |
| [getRewindAudio()](#getRewindAudio--) | Bestimmt, ob Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lesen/Schreiben boolean. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Bestimmt, ob Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lesen/Schreiben boolean. |
| [getEmbedded()](#getEmbedded--) | Bestimmt, ob ein Sound in eine Präsentation eingebettet ist. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Gibt ein eingebettetes Audio-Objekt zurück oder setzt es. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Gibt ein eingebettetes Audio-Objekt zurück oder setzt es. |
| [getFadeInDuration()](#getFadeInDuration--) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. |
| [getVolumeValue()](#getVolumeValue--) | Gibt die Audio-Lautstärke in Prozent zurück oder setzt sie. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Gibt die Audio-Lautstärke in Prozent zurück oder setzt sie. |
| [getTrimFromStart()](#getTrimFromStart--) | Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt wird, in Millisekunden. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt wird, in Millisekunden. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden. |
| [getCaptionTracks()](#getCaptionTracks--) | Ruft die Sammlung geschlossener Untertitel ab, die dem Audioframe zugeordnet sind. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Gibt einen Start-Track-Index zurück oder setzt ihn. Lesen/Schreiben int.

**Rückgabewert:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Gibt einen Start-Track-Index zurück oder setzt ihn. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Gibt einen Start-Track-Zeitwert zurück oder setzt ihn. Lesen/Schreiben int.

**Rückgabewert:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Gibt einen Start-Track-Zeitwert zurück oder setzt ihn. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Gibt einen letzten Track-Index zurück oder setzt ihn. Lesen/Schreiben int.

**Rückgabewert:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Gibt einen letzten Track-Index zurück oder setzt ihn. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Gibt einen letzten Track-Zeitwert zurück oder setzt ihn. Lesen/Schreiben int.

**Rückgabewert:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Gibt einen letzten Track-Zeitwert zurück oder setzt ihn. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Gibt die Audio-Lautstärke zurück oder setzt sie. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabewert:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Gibt die Audio-Lautstärke zurück oder setzt sie. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. Lesen/Schreiben [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Rückgabewert:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. Lesen/Schreiben [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Bestimmt, ob ein AudioFrame ausgeblendet ist. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Bestimmt, ob ein AudioFrame ausgeblendet ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Bestimmt, ob Audio wiederholt wird. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Bestimmt, ob Audio wiederholt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Setzt das Audio so, dass es über die Folien hinweg abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Setzt das Audio so, dass es nach dem Abspielen automatisch zum Anfang zurückspult
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Rückgabewert:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Setzt das Audio so, dass es über die Folien hinweg abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Setzt das Audio so, dass es nach dem Abspielen automatisch zum Anfang zurückspult
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

Bestimmt, ob Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Setzt das Audio so, dass es über die Folien hinweg abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Setzt das Audio so, dass es nach dem Abspielen automatisch zum Anfang zurückspult
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Rückgabewert:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Bestimmt, ob Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio-Frame hinzufügen
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Setzt das Audio so, dass es über die Folien hinweg abgespielt wird
>       audioFrame.setPlayAcrossSlides(true);
>       // Setzt das Audio so, dass es nach dem Abspielen automatisch zum Anfang zurückspult
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

Bestimmt, ob ein Sound in eine Präsentation eingebettet ist. Nur lesbar boolean.

**Rückgabewert:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Gibt ein eingebettetes Audio-Objekt zurück oder setzt es. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Rückgabewert:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Gibt ein eingebettetes Audio-Objekt zurück oder setzt es. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

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
>      // Setzt die Dauer des anfänglichen Einblendens auf 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
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
>      // Setzt die Dauer des anfänglichen Einblendens auf 200ms
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
>      // Setzt die Dauer des abschließenden Ausblendens auf 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
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
>      // Setzt die Dauer des abschließenden Ausblendens auf 500ms
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

Gibt die Audio-Lautstärke in Prozent zurück oder setzt sie. Lesen/Schreiben float.

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


**Rückgabewert:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Gibt die Audio-Lautstärke in Prozent zurück oder setzt sie. Lesen/Schreiben float.

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
>      // Setzt die Start-Trimmszeit auf 1,5 Sekunden
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
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
>      // Setzt die Start-Trimmszeit auf 1,5 Sekunden
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
>      // Setzt die End-Trimmszeit auf 2 Sekunden
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
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
>      // Setzt die End-Trimmszeit auf 2 Sekunden
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

Ruft die Sammlung geschlossener Untertitel ab, die dem Audioframe zugeordnet sind. Diese Eigenschaft ist nur lesbar und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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


**Rückgabewert:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)