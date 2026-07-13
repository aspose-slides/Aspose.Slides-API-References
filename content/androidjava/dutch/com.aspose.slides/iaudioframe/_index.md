---
title: IAudioFrame
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een audiofragment op een dia voor.
type: docs
url: /nl/com.aspose.slides/iaudioframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Stelt een audiofragment op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Retourneert of stelt een starttrackindex in. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Retourneert of stelt een starttrackindex in. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Retourneert of stelt een starttracktijd in. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Retourneert of stelt een starttracktijd in. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Retourneert of stelt een laatste trackindex in Lezen/schrijven int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Retourneert of stelt een laatste trackindex in Lezen/schrijven int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Retourneert of stelt een laatste tracktijd in. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Retourneert of stelt een laatste tracktijd in. |
| [getVolume()](#getVolume--) | Retourneert of stelt het audio-volume in. |
| [setVolume(int value)](#setVolume-int-) | Retourneert of stelt het audio-volume in. |
| [getPlayMode()](#getPlayMode--) | Retourneert of stelt de audio-afspeelmodus in. |
| [setPlayMode(int value)](#setPlayMode-int-) | Retourneert of stelt de audio-afspeelmodus in. |
| [getHideAtShowing()](#getHideAtShowing--) | Bepaalt of een AudioFrame verborgen is. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bepaalt of een AudioFrame verborgen is. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bepaalt of een audio in lus wordt afgespeeld. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bepaalt of een audio in lus wordt afgespeeld. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Bepaalt of een audio over de dia's wordt afgespeeld. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Bepaalt of een audio over de dia's wordt afgespeeld. |
| [getRewindAudio()](#getRewindAudio--) | Bepaalt of een audio automatisch terugspoelt naar het begin na het afspelen. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Bepaalt of een audio automatisch terugspoelt naar het begin na het afspelen. |
| [getEmbedded()](#getEmbedded--) | Bepaalt of een geluid in een presentatie is ingebed. |
| [getLinkPathLong()](#getLinkPathLong--) | Retourneert of stelt de naam van een audiobestand in dat gekoppeld is aan een AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retourneert of stelt de naam van een audiobestand in dat gekoppeld is aan een AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Retourneert of stelt een ingebed audio-object in. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Retourneert of stelt een ingebed audio-object in. |
| [getFadeInDuration()](#getFadeInDuration--) | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. |
| [getVolumeValue()](#getVolumeValue--) | Retourneert of stelt het audio-volume in procenten. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Retourneert of stelt het audio-volume in procenten. |
| [getTrimFromStart()](#getTrimFromStart--) | Specificeert de tijdsduur die aan het begin van de media tijdens het afspelen moet worden verwijderd, in milliseconden. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Specificeert de tijdsduur die aan het begin van de media tijdens het afspelen moet worden verwijderd, in milliseconden. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Specificeert de tijdsduur die aan het einde van de media tijdens het afspelen moet worden verwijderd, in milliseconden. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Specificeert de tijdsduur die aan het einde van de media tijdens het afspelen moet worden verwijderd, in milliseconden. |
| [getCaptionTracks()](#getCaptionTracks--) | Haalt de verzameling ondertitels op die aan het audioframe zijn gekoppeld. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Retourneert of stelt een starttrackindex in. Lezen/schrijven int.

**Retourneert:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Retourneert of stelt een starttrackindex in. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Retourneert of stelt een starttracktijd in. Lezen/schrijven int.

**Retourneert:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Retourneert of stelt een starttracktijd in. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Retourneert of stelt een laatste trackindex in Lezen/schrijven int.

**Retourneert:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Retourneert of stelt een laatste trackindex in Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Retourneert of stelt een laatste tracktijd in Lezen/schrijven int.

**Retourneert:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Retourneert of stelt een laatste tracktijd in Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Retourneert of stelt het audio-volume in Lezen/schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retourneert:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Retourneert of stelt het audio-volume in Lezen/schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Retourneert of stelt de audio-afspeelmodus in Lezen/schrijven [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Retourneert:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Retourneert of stelt de audio-afspeelmodus in Lezen/schrijven [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bepaalt of een AudioFrame verborgen is. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bepaalt of een AudioFrame verborgen is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bepaalt of een audio in lus wordt afgespeeld. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bepaalt of een audio in lus wordt afgespeeld. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Bepaalt of een audio over de dia's wordt afgespeeld. Lezen/schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg Audio-frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel audio in om over de dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel audio in om automatisch terug te spoelen naar het begin na het afspelen
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
public abstract void setPlayAcrossSlides(boolean value)
```

Bepaalt of een audio over de dia's wordt afgespeeld. Lezen/schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg Audio-frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel audio in om over de dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel audio in om automatisch terug te spoelen naar het begin na het afspelen
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Bepaalt of een audio automatisch terugspoelt naar het begin na het afspelen. Lezen/schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg Audio-frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel audio in om over de dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel audio in om automatisch terug te spoelen naar het begin na het afspelen
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
public abstract void setRewindAudio(boolean value)
```

Bepaalt of een audio automatisch terugspoelt naar het begin na het afspelen. Lezen/schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Voeg Audio-frame toe
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Stel audio in om over de dia's af te spelen
>       audioFrame.setPlayAcrossSlides(true);
>       // Stel audio in om automatisch terug te spoelen naar het begin na het afspelen
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Bepaalt of een geluid in een presentatie is ingebed. Alleen-lezen boolean.

**Retourneert:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Retourneert of stelt de naam van een audiobestand in dat gekoppeld is aan een AudioFrame. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Retourneert of stelt de naam van een audiobestand in dat gekoppeld is aan een AudioFrame. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Retourneert of stelt een ingebed audio-object in. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

**Retourneert:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Retourneert of stelt een ingebed audio-object in. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Lezen/schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de duur van de beginnende fade in op 200ms
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
public abstract void setFadeInDuration(float value)
```

Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Lezen/schrijven float.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. Lezen/schrijven float.

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
public abstract void setFadeOutDuration(float value)
```

Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. Lezen/schrijven float.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Retourneert of stelt het audio-volume in procenten. Lezen/schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel het audio-volume in op 85%
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
public abstract void setVolumeValue(float value)
```

Retourneert of stelt het audio-volume in procenten. Lezen/schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel het audio-volume in op 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Specificeert de tijdsduur die aan het begin van de media tijdens het afspelen moet worden verwijderd, in milliseconden. Lezen/schrijven float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de start trimtijd in op 1,5 seconden
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Specificeert de tijdsduur die aan het begin van de media tijdens het afspelen moet worden verwijderd, in milliseconden. Lezen/schrijven float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Stel de start trimtijd in op 1,5 seconden
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Specificeert de tijdsduur die aan het einde van de media tijdens het afspelen moet worden verwijderd, in milliseconden. Lezen/schrijven float.

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
public abstract void setTrimFromEnd(float value)
```

Specificeert de tijdsduur die aan het einde van de media tijdens het afspelen moet worden verwijderd, in milliseconden. Lezen/schrijven float.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Haalt de verzameling ondertitels op die aan het audioframe zijn gekoppeld. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) met alle ondertitel-tracks.

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
>             // Sla de binaire gegevens van het ondertitelingsspoor op als een .vtt-bestand
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

**Retourneert:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)