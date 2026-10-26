---
title: AudioFrame
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een audio-fragment op een dia voor.
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

Stelt een audio-fragment op een dia voor.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Haalt de AudioFrame-vorm op
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Stelt de afspeelmodus in op afspelen bij klikken
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Stelt het volume in op Laag
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Stelt in dat audio over dia's wordt afgespeeld
>      audioFrame.setPlayAcrossSlides(true);
>      // Schakelt de lus voor de audio uit
>      audioFrame.setPlayLoopMode(false);
>      // Verbergt de AudioFrame tijdens de diavoorstelling
>      audioFrame.setHideAtShowing(true);
>      // Spoelt de audio terug naar het begin na afspelen
>      audioFrame.setRewindAudio(true);
>      // Slaat het PowerPoint-bestand op schijf
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Geeft of stelt een starttrack-index in. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Geeft of stelt een starttrack-index in. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Geeft of stelt een starttrack-tijd in. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Geeft of stelt een starttrack-tijd in. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Geeft of stelt een laatste track-index in Lezen/Schrijven  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Geeft of stelt een laatste track-index in Lezen/Schrijven  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Geeft of stelt een laatste track-tijd in. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Geeft of stelt een laatste track-tijd in. |
| [getVolume()](#getVolume--) | Geeft of stelt het audio-volume in. |
| [setVolume(int value)](#setVolume-int-) | Geeft of stelt het audio-volume in. |
| [getPlayMode()](#getPlayMode--) | Geeft of stelt de audio-afspeelmodus in. |
| [setPlayMode(int value)](#setPlayMode-int-) | Geeft of stelt de audio-afspeelmodus in. |
| [getHideAtShowing()](#getHideAtShowing--) | Bepaalt of een AudioFrame verborgen is. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bepaalt of een AudioFrame verborgen is. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bepaalt of een audio in een lus staat. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bepaalt of een audio in een lus staat. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Bepaalt of audio over de dia's wordt afgespeeld. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Bepaalt of audio over de dia's wordt afgespeeld. |
| [getRewindAudio()](#getRewindAudio--) | Bepaalt of audio automatisch naar het begin wordt teruggespoeld na afspelen. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Bepaalt of audio automatisch naar het begin wordt teruggespoeld na afspelen. |
| [getEmbedded()](#getEmbedded--) | Bepaalt of een geluid is ingebed in een presentatie. |
| [getLinkPathLong()](#getLinkPathLong--) | Geeft of stelt de naam van een audiobestand dat is gekoppeld aan een AudioFrame in. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Geeft of stelt de naam van een audiobestand dat is gekoppeld aan een AudioFrame in. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Geeft of stelt een ingebed audio-object in. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Geeft of stelt een ingebed audio-object in. |
| [getFadeInDuration()](#getFadeInDuration--) | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. |
| [getVolumeValue()](#getVolumeValue--) | Geeft of stelt het audio-volume in procenten. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Geeft of stelt het audio-volume in procenten. |
| [getTrimFromStart()](#getTrimFromStart--) | Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. |
| [getCaptionTracks()](#getCaptionTracks--) | Haalt de collectie ondertitels op die bij het audio-frame horen. |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Geeft of stelt een starttrack-index in Lezen/Schrijven  int .

**Retour:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Geeft of stelt een starttrack-index in Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Geeft of stelt een starttrack-tijd in Lezen/Schrijven  int .

**Retour:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Geeft of stelt een starttrack-tijd in Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Geeft of stelt een laatste track-index in Lezen/Schrijven  int .

**Retour:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Geeft of stelt een laatste track-index in Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Geeft of stelt een laatste track-tijd in Lezen/Schrijven  int .

**Retour:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Geeft of stelt een laatste track-tijd in Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getVolume() {#getVolume--}
```
public final int getVolume()
```

Geeft of stelt het audio-volume in Lezen/Schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retour:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Geeft of stelt het audio-volume in Lezen/Schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Geeft of stelt de audio-afspeelmodus in Lezen/Schrijven [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Retour:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Geeft of stelt de audio-afspeelmodus in Lezen/Schrijven [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Bepaalt of een AudioFrame verborgen is Lezen/Schrijven  boolean .

**Retour:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Bepaalt of een AudioFrame verborgen is Lezen/Schrijven  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Bepaalt of een audio in een lus staat Lezen/Schrijven  boolean .

**Retour:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Bepaalt of een audio in een lus staat Lezen/Schrijven  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Bepaalt of audio over de dia's wordt afgespeeld Lezen/Schrijven  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg een Audio Frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel audio in om over de dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel audio in om automatisch naar het begin terug te spoelen na het afspelen
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Retour:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Bepaalt of audio over de dia's wordt afgespeeld Lezen/Schrijven  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg een Audio Frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel audio in om over de dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel audio in om automatisch naar het begin terug te spoelen na het afspelen
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

Bepaalt of audio automatisch naar het begin wordt teruggespoeld na afspelen Lezen/Schrijven  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg een Audio Frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel audio in om over de dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel audio in om automatisch naar het begin terug te spoelen na het afspelen
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Retour:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Bepaalt of audio automatisch naar het begin wordt teruggespoeld na afspelen Lezen/Schrijven  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg een Audio Frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel audio in om over de dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel audio in om automatisch naar het begin terug te spoelen na het afspelen
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

Bepaalt of een geluid is ingebed in een presentatie Alleen-lezen  boolean .

**Retour:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Geeft of stelt de naam van een audiobestand dat is gekoppeld aan een AudioFrame in Lezen/Schrijven String.

**Retour:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Geeft of stelt de naam van een audiobestand dat is gekoppeld aan een AudioFrame in Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Geeft of stelt een ingebed audio-object in Lezen/Schrijven [IAudio](../../com.aspose.slides/iaudio).

**Retour:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Geeft of stelt een ingebed audio-object in Lezen/Schrijven [IAudio](../../com.aspose.slides/iaudio).

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


**Retour:**
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

Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. Lezen/Schrijven float.

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

**Retour:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. Lezen/Schrijven float.

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

Geeft of stelt het audio-volume in procenten Lezen/Schrijven float.

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

**Retour:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Geeft of stelt het audio-volume in procenten Lezen/Schrijven float.

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

Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de starttrimtijd in op 1,5 seconde
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lezen/Schrijven float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de starttrimtijd in op 1,5 seconde
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

Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lezen/Schrijven float.

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

**Retour:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lezen/Schrijven float.

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

Haalt de collectie ondertitels op die bij het audio-frame horen. Deze eigenschap is Alleen-lezen en retourneert een [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) met alle ondertitel-tracks.

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
>              // Sla de binaire gegevens van het ondertitelingsspoor op als een .vtt-bestand
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

**Retour:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)