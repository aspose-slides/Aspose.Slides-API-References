---
title: AudioFrame
second_title: Aspose.Slides för Java API-referens
description: Representerar ett ljudklipp på en bild.
type: docs
url: /sv/com.aspose.slides/audioframe/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Representerar ett ljudklipp på en bild.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Hämtar AudioFrame-formen
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Ställer in uppspelningsläget till att spela vid klick
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Ställer in volymen till Låg
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Ställer in att ljudet spelas över bildspresentationen
>      audioFrame.setPlayAcrossSlides(true);
>      // Inaktiverar loop för ljudet
>      audioFrame.setPlayLoopMode(false);
>      // Döljer AudioFrame under bildspelet
>      audioFrame.setHideAtShowing(true);
>      // Spolar tillbaka ljudet till början efter uppspelning
>      audioFrame.setRewindAudio(true);
>      // Sparar PowerPoint-filen till disk
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Returnerar eller anger ett startspårindex. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Returnerar eller anger ett startspårindex. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Returnerar eller anger en startspårtid. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Returnerar eller anger en startspårtid. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Returnerar eller anger ett sista spårindex Läs/skriv  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Returnerar eller anger ett sista spårindex Läs/skriv  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Returnerar eller anger en sista spårtid. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Returnerar eller anger en sista spårtid. |
| [getVolume()](#getVolume--) | Returnerar eller anger ljudvolymen. |
| [setVolume(int value)](#setVolume-int-) | Returnerar eller anger ljudvolymen. |
| [getPlayMode()](#getPlayMode--) | Returnerar eller anger uppspelningsläget för ljudet. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returnerar eller anger uppspelningsläget för ljudet. |
| [getHideAtShowing()](#getHideAtShowing--) | Avgör om ett AudioFrame är dolt. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Avgör om ett AudioFrame är dolt. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Avgör om ett ljud är i loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Avgör om ett ljud är i loop. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Avgör om ljud spelas upp över bildspresentationen. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Avgör om ljud spelas upp över bildspresentationen. |
| [getRewindAudio()](#getRewindAudio--) | Avgör om ljud automatiskt spolas tillbaka till början efter uppspelning. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Avgör om ljud automatiskt spolas tillbaka till början efter uppspelning. |
| [getEmbedded()](#getEmbedded--) | Avgör om ett ljud är inbäddat i en presentation. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller anger namnet på en ljudfil som är länkad till ett AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller anger namnet på en ljudfil som är länkad till ett AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Returnerar eller anger inbäddat ljudobjekt. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Returnerar eller anger inbäddat ljudobjekt. |
| [getFadeInDuration()](#getFadeInDuration--) | Anger tidslängden för den initiala fade-in av mediet i millisekunder. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Anger tidslängden för den initiala fade-in av mediet i millisekunder. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Anger tidslängden för den avslutande fade-out av mediet i millisekunder. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Anger tidslängden för den avslutande fade-out av mediet i millisekunder. |
| [getVolumeValue()](#getVolumeValue--) | Returnerar eller anger ljudvolymen i procent. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Returnerar eller anger ljudvolymen i procent. |
| [getTrimFromStart()](#getTrimFromStart--) | Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. |
| [getCaptionTracks()](#getCaptionTracks--) | Hämtar samlingen av stängda undertexter som är associerade med audio-ramen. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Returnerar eller anger ett startspårindex. Läs/skriv  int .

**Returnerar:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Returnerar eller anger ett startspårindex. Läs/skriv  int .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Returnerar eller anger en startspårtid. Läs/skriv  int .

**Returnerar:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Returnerar eller anger en startspårtid. Läs/skriv  int .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Returnerar eller anger ett sista spårindex Läs/skriv  int .

**Returnerar:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Returnerar eller anger ett sista spårindex Läs/skriv  int .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Returnerar eller anger en sista spårtid. Läs/skriv  int .

**Returnerar:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Returnerar eller anger en sista spårtid. Läs/skriv  int .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Returnerar eller anger ljudvolymen. Läs/skriv [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returnerar:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Returnerar eller anger ljudvolymen. Läs/skriv [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Returnerar eller anger uppspelningsläget för ljudet. Läs/skriv [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Returnerar:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Returnerar eller anger uppspelningsläget för ljudet. Läs/skriv [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Avgör om ett AudioFrame är dolt. Läs/skriv  boolean .

**Returnerar:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Avgör om ett AudioFrame är dolt. Läs/skriv  boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Avgör om ett ljud är i loop. Läs/skriv  boolean .

**Returnerar:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Avgör om ett ljud är i loop. Läs/skriv  boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Avgör om ljud spelas upp över bildspresentationen. Läs/skriv  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Lägg till Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ställ in Audio för att spelas över bildspresentationen
>       audioFrame.setPlayAcrossSlides(true);
>       // Ställ in Audio för att automatiskt spola tillbaka till början efter uppspelning
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Returnerar:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Avgör om ljud spelas upp över bildspresentationen. Läs/skriv  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Lägg till Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ställ in Audio för att spelas över bildspresentationen
>       audioFrame.setPlayAcrossSlides(true);
>       // Ställ in Audio för att automatiskt spola tillbaka till början efter uppspelning
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

Avgör om ljud automatiskt spolas tillbaka till början efter uppspelning. Läs/skriv  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Lägg till Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ställ in Audio för att spelas över bildspresentationen
>       audioFrame.setPlayAcrossSlides(true);
>       // Ställ in Audio för att automatiskt spola tillbaka till början efter uppspelning
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Returnerar:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Avgör om ljud automatiskt spolas tillbaka till början efter uppspelning. Läs/skriv  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Lägg till Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ställ in Audio för att spelas över bildspresentationen
>       audioFrame.setPlayAcrossSlides(true);
>       // Ställ in Audio för att automatiskt spola tillbaka till början efter uppspelning
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

Avgör om ett ljud är inbäddat i en presentation. Endast läsning  boolean .

**Returnerar:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Returnerar eller anger namnet på en ljudfil som är länkad till ett AudioFrame. Läs/skriv String.

**Returnerar:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Returnerar eller anger namnet på en ljudfil som är länkad till ett AudioFrame. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Returnerar eller anger inbäddat ljudobjekt. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Returnerar eller anger inbäddat ljudobjekt. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Anger tidslängden för den initiala fade-in av mediet i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in varaktigheten för den initiala fade-in till 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Anger tidslängden för den initiala fade-in av mediet i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in varaktigheten för den initiala fade-in till 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

Anger tidslängden för den avslutande fade-out av mediet i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in varaktigheten för den avslutande fade-out till 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Anger tidslängden för den avslutande fade-out av mediet i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in varaktigheten för den avslutande fade-out till 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Returnerar eller anger ljudvolymen i procent. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in ljudvolymen till 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Returnerar eller anger ljudvolymen i procent. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in ljudvolymen till 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in starttrimningstid 1,5 sekunder
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in starttrimningstid 1,5 sekunder
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in sluttrimningstid 2 sekunder
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in sluttrimningstid 2 sekunder
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Hämtar samlingen av stängda undertexter som är associerade med audio-ramen. Denna egenskap är skrivskyddad och returnerar ett [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) som innehåller alla undertextspår.

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
>              // Spara undertextspårets binära data som en .vtt-fil
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

**Returnerar:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)