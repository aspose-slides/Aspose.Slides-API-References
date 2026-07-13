---
title: IAudioFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett ljudklipp på en bild.
type: docs
url: /sv/com.aspose.slides/iaudioframe/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Representerar ett ljudklipp på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Returnerar eller anger ett startspårindex. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Returnerar eller anger ett startspårindex. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Returnerar eller anger en startspårtid. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Returnerar eller anger en startspårtid. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Returnerar eller anger ett sista spårindex Läs/skriv int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Returnerar eller anger ett sista spårindex Läs/skriv int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Returnerar eller anger en sista spårtid. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Returnerar eller anger en sista spårtid. |
| [getVolume()](#getVolume--) | Returnerar eller anger ljudvolymen. |
| [setVolume(int value)](#setVolume-int-) | Returnerar eller anger ljudvolymen. |
| [getPlayMode()](#getPlayMode--) | Returnerar eller anger ljuduppspelningsläge. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returnerar eller anger ljuduppspelningsläge. |
| [getHideAtShowing()](#getHideAtShowing--) | Fastställer om en AudioFrame är dold. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Fastställer om en AudioFrame är dold. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Fastställer om ett ljud är loopat. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Fastställer om ett ljud är loopat. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Fastställer om ett ljud spelas över bilderna. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Fastställer om ett ljud spelas över bilderna. |
| [getRewindAudio()](#getRewindAudio--) | Fastställer om ett ljud automatiskt spolas tillbaka till början efter uppspelning. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Fastställer om ett ljud automatiskt spolas tillbaka till början efter uppspelning. |
| [getEmbedded()](#getEmbedded--) | Fastställer om ett ljud är inbäddat i en presentation. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller anger namnet på en ljudfil som är länkat till en AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller anger namnet på en ljudfil som är länkat till en AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Returnerar eller anger inbäddat ljudobjekt. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Returnerar eller anger inbäddat ljudobjekt. |
| [getFadeInDuration()](#getFadeInDuration--) | Anger tidslängden för den initiala avtoningen av mediet i millisekunder. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Anger tidslängden för den initiala avtoningen av mediet i millisekunder. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Anger tidslängden för den avslutande avtoningen av mediet i millisekunder. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Anger tidslängden för den avslutande avtoningen av mediet i millisekunder. |
| [getVolumeValue()](#getVolumeValue--) | Returnerar eller anger ljudvolymen i procent. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Returnerar eller anger ljudvolymen i procent. |
| [getTrimFromStart()](#getTrimFromStart--) | Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. |
| [getCaptionTracks()](#getCaptionTracks--) | Hämtar samlingen av stängda undertexter som är associerade med ljudramen. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Returnerar eller anger ett startspårindex. Läs/skriv int.

**Returnerar:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Returnerar eller anger ett startspårindex. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Returnerar eller anger en startspårtid. Läs/skriv int.

**Returnerar:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Returnerar eller anger en startspårtid. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Returnerar eller anger ett sista spårindex Läs/skriv int.

**Returnerar:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Returnerar eller anger ett sista spårindex Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Returnerar eller anger en sista spårtid. Läs/skriv int.

**Returnerar:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Returnerar eller anger en sista spårtid. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Returnerar eller anger ljudvolymen. Läs/skriv [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returnerar:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Returnerar eller anger ljudvolymen. Läs/skriv [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Returnerar eller anger ljuduppspelningsläge. Läs/skriv [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Returnerar:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Returnerar eller anger ljuduppspelningsläge. Läs/skriv [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Fastställer om en AudioFrame är dold. Läs/skriv boolean.

**Returnerar:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Fastställer om en AudioFrame är dold. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Fastställer om ett ljud är loopat. Läs/skriv boolean.

**Returnerar:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Fastställer om ett ljud är loopat. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Fastställer om ett ljud spelas över bilderna. Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Lägg till ljudram
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ställ in ljudet att spelas över bilderna
>       audioFrame.setPlayAcrossSlides(true);
>       // Ställ in ljudet att automatiskt spolas tillbaka till början efter uppspelning
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
public abstract void setPlayAcrossSlides(boolean value)
```

Fastställer om ett ljud spelas över bilderna. Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Lägg till ljudram
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ställ in ljudet att spelas över bilderna
>       audioFrame.setPlayAcrossSlides(true);
>       // Ställ in ljudet att automatiskt spolas tillbaka till början efter uppspelning
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
public abstract boolean getRewindAudio()
```

Fastställer om ett ljud automatiskt spolas tillbaka till början efter uppspelning. Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Lägg till ljudram
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ställ in ljudet att spelas över bilderna
>       audioFrame.setPlayAcrossSlides(true);
>       // Ställ in ljudet att automatiskt spolas tillbaka till början efter uppspelning
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
public abstract void setRewindAudio(boolean value)
```

Fastställer om ett ljud automatiskt spolas tillbaka till början efter uppspelning. Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Lägg till ljudram
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ställ in ljudet att spelas över bilderna
>       audioFrame.setPlayAcrossSlides(true);
>       // Ställ in ljudet att automatiskt spolas tillbaka till början efter uppspelning
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
public abstract boolean getEmbedded()
```

Fastställer om ett ljud är inbäddat i en presentation. Endast läsbar boolean.

**Returnerar:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Returnerar eller anger namnet på en ljudfil som är länkat till en AudioFrame. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Returnerar eller anger namnet på en ljudfil som är länkat till en AudioFrame. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Returnerar eller anger inbäddat ljudobjekt. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Returnerar eller anger inbäddat ljudobjekt. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Anger tidslängden för den initiala avtoningen av mediet i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in varaktigheten för den initiala avtoningen till 200 ms
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
public abstract void setFadeInDuration(float value)
```

Anger tidslängden för den initiala avtoningen av mediet i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in varaktigheten för den inledande avtoningen till 200 ms
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
public abstract float getFadeOutDuration()
```

Anger tidslängden för den avslutande avtoningen av mediet i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in varaktigheten för den avslutande avtoningen till 500 ms
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
public abstract void setFadeOutDuration(float value)
```

Anger tidslängden för den avslutande avtoningen av mediet i millisekunder. Läs/skriv float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ställ in varaktigheten för den avslutande avtoningen till 500ms
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
public abstract float getVolumeValue()
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
public abstract void setVolumeValue(float value)
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
public abstract float getTrimFromStart()
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
>      // Ställ in starttrimningstiden 1,5 sekunder
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
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
>      // Ställ in starttrimningstiden 1,5 sekunder
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
public abstract float getTrimFromEnd()
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
>      // Ställ in sluttrimningstiden 2 sekunder
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
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
>      // Ställ in sluttrimningstiden 2 sekunder
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
public abstract ICaptionsCollection getCaptionTracks()
```

Hämtar samlingen av stängda undertexter som är associerade med ljudramen. Denna egenskap är skrivskyddad och returnerar en [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) som innehåller alla undertextspår.

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
>             // Spara bildtextspårets binära data som en .vtt-fil
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

**Returnerar:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)