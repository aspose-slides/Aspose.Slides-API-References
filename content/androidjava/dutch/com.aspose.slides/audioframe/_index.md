---
title: AudioFrame
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een audiofragment op een dia voor.
type: docs
url: /nl/com.aspose.slides/audioframe/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Stelt een audiofragment op een dia voor.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Haalt de AudioFrame vorm op
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Stelt de Play-modus in op OnClick
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Stelt het volume in op Low
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Stelt de audio in om over dia's af te spelen
>      audioFrame.setPlayAcrossSlides(true);
>      // Schakelt de lus voor de audio uit
>      audioFrame.setPlayLoopMode(false);
>      // Verbergt de AudioFrame tijdens de diavoorstelling
>      audioFrame.setHideAtShowing(true);
>      // Spoelt de audio terug naar het begin na het afspelen
>      audioFrame.setRewindAudio(true);
>      // Slaat het PowerPoint-bestand op schijf
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Geeft een starttrackindex terug of stelt deze in. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Geeft een starttrackindex terug of stelt deze in. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Geeft een starttracktijd terug of stelt deze in. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Geeft een starttracktijd terug of stelt deze in. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Geeft een laatste trackindex terug of stelt deze in Lezen/Schrijven  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Geeft een laatste trackindex terug of stelt deze in Lezen/Schrijven  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Geeft een laatste tracktijd terug of stelt deze in. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Geeft een laatste tracktijd terug of stelt deze in. |
| [getVolume()](#getVolume--) | Geeft het audio volume terug of stelt het in. |
| [setVolume(int value)](#setVolume-int-) | Geeft het audio volume terug of stelt het in. |
| [getPlayMode()](#getPlayMode--) | Geeft de audio afspeelmodus terug of stelt deze in. |
| [setPlayMode(int value)](#setPlayMode-int-) | Geeft de audio afspeelmodus terug of stelt deze in. |
| [getHideAtShowing()](#getHideAtShowing--) | Bepaalt of een AudioFrame verborgen is. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bepaalt of een AudioFrame verborgen is. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bepaalt of audio herhaald wordt. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bepaalt of audio herhaald wordt. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Bepaalt of audio over de dia’s heen wordt afgespeeld. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Bepaalt of audio over de dia’s heen wordt afgespeeld. |
| [getRewindAudio()](#getRewindAudio--) | Bepaalt of audio automatisch naar het begin wordt teruggespoeld na het afspelen. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Bepaalt of audio automatisch naar het begin wordt teruggespoeld na het afspelen. |
| [getEmbedded()](#getEmbedded--) | Bepaalt of een geluid is ingebed in een presentatie. |
| [getLinkPathLong()](#getLinkPathLong--) | Geeft de naam van een audiobestand terug of stelt deze in die is gekoppeld aan een AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Geeft de naam van een audiobestand terug of stelt deze in die is gekoppeld aan een AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Geeft een ingebed audio-object terug of stelt dit in. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Geeft een ingebed audio-object terug of stelt dit in. |
| [getFadeInDuration()](#getFadeInDuration--) | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Specificeert de tijdsduur voor de eind-fade-out van de media in milliseconden. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Specificeert de tijdsduur voor de eind-fade-out van de media in milliseconden. |
| [getVolumeValue()](#getVolumeValue--) | Geeft het audio volume in procenten terug of stelt dit in. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Geeft het audio volume in procenten terug of stelt dit in. |
| [getTrimFromStart()](#getTrimFromStart--) | Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens de weergave, in milliseconden. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens de weergave, in milliseconden. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens de weergave, in milliseconden. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens de weergave, in milliseconden. |
| [getCaptionTracks()](#getCaptionTracks--) | Haalt de verzameling ondertitels op die aan het audioframe zijn gekoppeld. |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Geeft een starttrackindex terug of stelt deze in. Lezen/Schrijven  int .

**Retourneert:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Geeft een starttrackindex terug of stelt deze in. Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Geeft een starttracktijd terug of stelt deze in. Lezen/Schrijven  int .

**Retourneert:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Geeft een starttracktijd terug of stelt deze in. Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Geeft een laatste trackindex terug of stelt deze in Lezen/Schrijven  int .

**Retourneert:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Geeft een laatste trackindex terug of stelt deze in Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Geeft een laatste tracktijd terug of stelt deze in. Lezen/Schrijven  int .

**Retourneert:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Geeft een laatste tracktijd terug of stelt deze in. Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Geeft het audio volume terug of stelt het in. Lezen/Schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retourneert:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Geeft het audio volume terug of stelt het in. Lezen/Schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Geeft de audio afspeelmodus terug of stelt deze in. Lezen/Schrijven [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Retourneert:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Geeft de audio afspeelmodus terug of stelt deze in. Lezen/Schrijven [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Bepaalt of een AudioFrame verborgen is. Lezen/Schrijven  boolean .

**Retourneert:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Bepaalt of een AudioFrame verborgen is. Lezen/Schrijven  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Bepaalt of audio herhaald wordt. Lezen/Schrijven  boolean .

**Retourneert:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Bepaalt of audio herhaald wordt. Lezen/Schrijven  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Bepaalt of audio over de dia’s heen wordt afgespeeld. Lezen/Schrijven  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg Audio Frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel Audio in om over dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel Audio in om automatisch terug te spoelen naar het begin na het afspelen
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Retourneert:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Bepaalt of audio over de dia’s heen wordt afgespeeld. Lezen/Schrijven  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg Audio Frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel Audio in om over dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel Audio in om automatisch terug te spoelen naar het begin na het afspelen
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

Bepaalt of audio automatisch naar het begin wordt teruggespoeld na het afspelen. Lezen/Schrijven  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg Audio Frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel Audio in om over dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel Audio in om automatisch terug te spoelen naar het begin na het afspelen
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Retourneert:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Bepaalt of audio automatisch naar het begin wordt teruggespoeld na het afspelen. Lezen/Schrijven  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg Audio Frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel Audio in om over dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel Audio in om automatisch terug te spoelen naar het begin na het afspelen
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

Bepaalt of een geluid is ingebed in een presentatie. Alleen-lezen  boolean .

**Retourneert:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Geeft de naam van een audiobestand terug of stelt deze in die is gekoppeld aan een AudioFrame. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Geeft de naam van een audiobestand terug of stelt deze in die is gekoppeld aan een AudioFrame. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Geeft een ingebed audio-object terug of stelt dit in. Lezen/Schrijven [IAudio](../../com.aspose.slides/iaudio).

**Retourneert:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Geeft een ingebed audio-object terug of stelt dit in. Lezen/Schrijven [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de duur van de startfade in op 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de duur van de startfade in op 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

Specificeert de tijdsduur voor de eind-fade-out van de media in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de duur van de eindfade in op 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Specificeert de tijdsduur voor de eind-fade-out van de media in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de duur van de eindfade in op 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Geeft het audio volume in procenten terug of stelt dit in. Lezen/Schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel het audio volume in op 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Geeft het audio volume in procenten terug of stelt dit in. Lezen/Schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel het audio volume in op 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens de weergave, in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de starttrimtijd in op 1,5 seconden
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens de weergave, in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de starttrimtijd in op 1,5 seconden
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens de weergave, in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de eindtrimtijd in op 2 seconden
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens de weergave, in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de eindtrimtijd in op 2 seconden
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Haalt de verzameling ondertitels op die aan het audioframe zijn gekoppeld. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) met alle ondertitel-tracks.

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
>              // Sla de binaire gegevens van de ondertiteltrack op als een .vtt bestand
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

**Retourneert:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)