---
title: AudioFrame
second_title: Aspose.Slides pro Java API Reference
description: Představuje zvukový klip na snímku.
type: docs
url: /cs/com.aspose.slides/audioframe/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Všechny implementované rozhraní:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Představuje zvukový klip na snímku.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Získá tvar AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Nastaví režim přehrávání na přehrání po kliknutí
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Nastaví hlasitost na nízkou
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Nastaví, aby se zvuk přehrával napříč snímky
>      audioFrame.setPlayAcrossSlides(true);
>      // Zakáže smyčku pro zvuk
>      audioFrame.setPlayLoopMode(false);
>      // Skryje AudioFrame během promítání
>      audioFrame.setHideAtShowing(true);
>      // Přetáčí zvuk na začátek po přehrání
>      audioFrame.setRewindAudio(true);
>      // Uloží soubor PowerPoint na disk
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Vrací nebo nastavuje index počáteční stopy. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Vrací nebo nastavuje index počáteční stopy. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Vrací nebo nastavuje čas počáteční stopy. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Vrací nebo nastavuje čas počáteční stopy. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Vrací nebo nastavuje poslední index stopy Číst/zapsat int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Vrací nebo nastavuje poslední index stopy Číst/zapsat int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Vrací nebo nastavuje čas koncové stopy. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Vrací nebo nastavuje čas koncové stopy. |
| [getVolume()](#getVolume--) | Vrací nebo nastavuje hlasitost zvuku. |
| [setVolume(int value)](#setVolume-int-) | Vrací nebo nastavuje hlasitost zvuku. |
| [getPlayMode()](#getPlayMode--) | Vrací nebo nastavuje režim přehrávání zvuku. |
| [setPlayMode(int value)](#setPlayMode-int-) | Vrací nebo nastavuje režim přehrávání zvuku. |
| [getHideAtShowing()](#getHideAtShowing--) | Určuje, zda je AudioFrame skrytý. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Určuje, zda je AudioFrame skrytý. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Určuje, zda je zvuk smyčkován. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Určuje, zda je zvuk smyčkován. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Určuje, zda se zvuk přehrává napříč snímky. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Určuje, zda se zvuk přehrává napříč snímky. |
| [getRewindAudio()](#getRewindAudio--) | Určuje, zda se zvuk po přehrání automaticky přetáčí na začátek. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Určuje, zda se zvuk po přehrání automaticky přetáčí na začátek. |
| [getEmbedded()](#getEmbedded--) | Určuje, zda je zvuk vložen do prezentace. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Vrací nebo nastavuje vložený zvukový objekt. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Vrací nebo nastavuje vložený zvukový objekt. |
| [getFadeInDuration()](#getFadeInDuration--) | Určuje časovou délku počátečního fade-in média v milisekundách. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Určuje časovou délku počátečního fade-in média v milisekundách. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Určuje časovou délku koncového fade-out média v milisekundách. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Určuje časovou délku koncového fade-out média v milisekundách. |
| [getVolumeValue()](#getVolumeValue--) | Vrací nebo nastavuje hlasitost zvuku v procentech. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Vrací nebo nastavuje hlasitost zvuku v procentech. |
| [getTrimFromStart()](#getTrimFromStart--) | Určuje časovou délku, která má být během přehrávání odebrána ze začátku média, v milisekundách. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Určuje časovou délku, která má být během přehrávání odebrána ze začátku média, v milisekundách. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Určuje časovou délku, která má být během přehrávání odebrána z konce média, v milisekundách. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Určuje časovou délku, která má být během přehrávání odebrána z konce média, v milisekundách. |
| [getCaptionTracks()](#getCaptionTracks--) | Získá kolekci uzavřených titulků spojených s audio snímkem. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Vrací nebo nastavuje index počáteční stopy. Číst/zapsat int .

**Vrací:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Vrací nebo nastavuje index počáteční stopy. Číst/zapsat int .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Vrací nebo nastavuje čas počáteční stopy. Číst/zapsat int .

**Vrací:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Vrací nebo nastavuje čas počáteční stopy. Číst/zapsat int .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Vrací nebo nastavuje poslední index stopy Číst/zapsat int .

**Vrací:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Vrací nebo nastavuje poslední index stopy Číst/zapsat int .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Vrací nebo nastavuje čas koncové stopy. Číst/zapsat int .

**Vrací:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Vrací nebo nastavuje čas koncové stopy. Číst/zapsat int .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Vrací nebo nastavuje hlasitost zvuku. Číst/zapsat [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Vrací:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Vrací nebo nastavuje hlasitost zvuku. Číst/zapsat [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Vrací nebo nastavuje režim přehrávání zvuku. Číst/zapsat [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Vrací:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Vrací nebo nastavuje režim přehrávání zvuku. Číst/zapsat [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Určuje, zda je AudioFrame skrytý. Číst/zapsat boolean .

**Vrací:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Určuje, zda je AudioFrame skrytý. Číst/zapsat boolean .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Určuje, zda je zvuk smyčkován. Číst/zapsat boolean .

**Vrací:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Určuje, zda je zvuk smyčkován. Číst/zapsat boolean .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Určuje, zda se zvuk přehrává napříč snímky. Číst/zapsat boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidá Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastaví Audio, aby se přehrával napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastaví Audio, aby se po přehrání automaticky přetáčelo na začátek
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Vrací:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Určuje, zda se zvuk přehrává napříč snímky. Číst/zapsat boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidá Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastaví Audio, aby se přehrával napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastaví Audio, aby se po přehrání automaticky přetáčelo na začátek
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

Určuje, zda se zvuk po přehrání automaticky přetáčí na začátek. Číst/zapsat boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidá Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastaví Audio, aby se přehrával napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastaví Audio, aby se po přehrání automaticky přetáčelo na začátek
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Vrací:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Určuje, zda se zvuk po přehrání automaticky přetáčí na začátek. Číst/zapsat boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidá Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastaví Audio, aby se přehrával napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastaví Audio, aby se po přehrání automaticky přetáčelo na začátek
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

Určuje, zda je zvuk vložen do prezentace. Pouze pro čtení boolean .

**Vrací:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame. Číst/zapsat String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame. Číst/zapsat String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Vrací nebo nastavuje vložený zvukový objekt. Číst/zapsat [IAudio](../../com.aspose.slides/iaudio).

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Vrací nebo nastavuje vložený zvukový objekt. Číst/zapsat [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Určuje časovou délku počátečního fade-in média v milisekundách. Číst/zapsat float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví dobu trvání počátečního přechodu na 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Určuje časovou délku počátečního fade-in média v milisekundách. Číst/zapsat float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví dobu trvání počátečního přechodu na 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

Určuje časovou délku koncového fade-out média v milisekundách. Číst/zapsat float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví dobu trvání koncového přechodu na 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Určuje časovou délku koncového fade-out média v milisekundách. Číst/zapsat float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví dobu trvání koncového přechodu na 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Vrací nebo nastavuje hlasitost zvuku v procentech. Číst/zapsat float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví hlasitost zvuku na 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Vrací nebo nastavuje hlasitost zvuku v procentech. Číst/zapsat float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví hlasitost zvuku na 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Určuje časovou délku, která má být během přehrávání odebrána ze začátku média, v milisekundách. Číst/zapsat float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví čas začátku ořezu na 1,5 sekundy
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Určuje časovou délku, která má být během přehrávání odebrána ze začátku média, v milisekundách. Číst/zapsat float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví čas začátku ořezu 1,5 sekundy
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Určuje časovou délku, která má být během přehrávání odebrána z konce média, v milisekundách. Číst/zapsat float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví čas koncového ořezu na 2 sekundy
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Určuje časovou délku, která má být během přehrávání odebrána z konce média, v milisekundách. Číst/zapsat float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastaví čas koncového ořezu na 2 sekundy
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Získá kolekci uzavřených titulků spojených s audio snímkem. Toto vlastnost je pouze pro čtení a vrací [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) obsahující všechny titulkové stopy.

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
>              // Uloží binární data titulkové stopy jako soubor .vtt
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

**Vrací:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)