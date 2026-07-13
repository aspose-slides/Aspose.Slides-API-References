---
title: AudioFrame
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje zvukový klip na snímku.
type: docs
url: /cs/com.aspose.slides/audioframe/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Všechna implementovaná rozhraní:**
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
>      // Nastaví audio, aby se přehrávalo napříč snímky
>      audioFrame.setPlayAcrossSlides(true);
>      // Zakáže opakování pro audio
>      audioFrame.setPlayLoopMode(false);
>      // Skryje AudioFrame během prezentace
>      audioFrame.setHideAtShowing(true);
>      // Přetáčí audio na začátek po přehrání
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
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Vrací nebo nastavuje počáteční index stopy. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Vrací nebo nastavuje počáteční index stopy. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Vrací nebo nastavuje počáteční čas stopy. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Vrací nebo nastavuje počáteční čas stopy. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Vrací nebo nastavuje poslední index stopy Čtení/Zápis  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Vrací nebo nastavuje poslední index stopy Čtení/Zápis  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Vrací nebo nastavuje poslední čas stopy. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Vrací nebo nastavuje poslední čas stopy. |
| [getVolume()](#getVolume--) | Vrací nebo nastavuje hlasitost zvuku. |
| [setVolume(int value)](#setVolume-int-) | Vrací nebo nastavuje hlasitost zvuku. |
| [getPlayMode()](#getPlayMode--) | Vrací nebo nastavuje režim přehrávání audia. |
| [setPlayMode(int value)](#setPlayMode-int-) | Vrací nebo nastavuje režim přehrávání audia. |
| [getHideAtShowing()](#getHideAtShowing--) | Určuje, zda je AudioFrame skrytý. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Určuje, zda je AudioFrame skrytý. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Určuje, zda se audio opakuje. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Určuje, zda se audio opakuje. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Určuje, zda se audio přehrává napříč snímky. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Určuje, zda se audio přehrává napříč snímky. |
| [getRewindAudio()](#getRewindAudio--) | Určuje, zda se audio po přehrání automaticky přetáčí na začátek. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Určuje, zda se audio po přehrání automaticky přetáčí na začátek. |
| [getEmbedded()](#getEmbedded--) | Určuje, zda je zvuk vložen v prezentaci. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací nebo nastavuje název audio souboru, který je propojen s AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací nebo nastavuje název audio souboru, který je propojen s AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Vrací nebo nastavuje vložený audio objekt. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Vrací nebo nastavuje vložený audio objekt. |
| [getFadeInDuration()](#getFadeInDuration--) | Určuje časové trvání počátečního fade-in média v milisekundách. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Určuje časové trvání počátečního fade-in média v milisekundách. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Určuje časové trvání koncového fade-out média v milisekundách. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Určuje časové trvání koncového fade-out média v milisekundách. |
| [getVolumeValue()](#getVolumeValue--) | Vrací nebo nastavuje hlasitost zvuku v procentech. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Vrací nebo nastavuje hlasitost zvuku v procentech. |
| [getTrimFromStart()](#getTrimFromStart--) | Určuje časové trvání, které má být během přehrávání odebráno od začátku média, v milisekundách. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Určuje časové trvání, které má být během přehrávání odebráno od začátku média, v milisekundách. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Určuje časové trvání, které má být během přehrávání odebráno od konce média, v milisekundách. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Určuje časové trvání, které má být během přehrávání odebráno od konce média, v milisekundách. |
| [getCaptionTracks()](#getCaptionTracks--) | Získává kolekci closed captions přiřazených k audio frame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Vrací nebo nastavuje počáteční index stopy. Čtení/Zápis  int .

**Vrací:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Vrací nebo nastavuje počáteční index stopy. Čtení/Zápis  int .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Vrací nebo nastavuje počáteční čas stopy. Čtení/Zápis  int .

**Vrací:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Vrací nebo nastavuje počáteční čas stopy. Čtení/Zápis  int .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Vrací nebo nastavuje poslední index stopy Čtení/Zápis  int .

**Vrací:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Vrací nebo nastavuje poslední index stopy Čtení/Zápis  int .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Vrací nebo nastavuje poslední čas stopy. Čtení/Zápis  int .

**Vrací:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Vrací nebo nastavuje poslední čas stopy. Čtení/Zápis  int .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Vrací nebo nastavuje hlasitost zvuku. Čtení/Zápis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Vrací:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Vrací nebo nastavuje hlasitost zvuku. Čtení/Zápis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Vrací nebo nastavuje režim přehrávání audia. Čtení/Zápis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Vrací:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Vrací nebo nastavuje režim přehrávání audia. Čtení/Zápis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Určuje, zda je AudioFrame skrytý. Čtení/Zápis  boolean .

**Vrací:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Určuje, zda je AudioFrame skrytý. Čtení/Zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Určuje, zda se audio opakuje. Čtení/Zápis  boolean .

**Vrací:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Určuje, zda se audio opakuje. Čtení/Zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Určuje, zda se audio přehrává napříč snímky. Čtení/Zápis  boolean .

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidejte audio rámec
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastavte Audio, aby se přehrávalo napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastavte Audio, aby se po přehrání automaticky přetočilo na začátek
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

Určuje, zda se audio přehrává napříč snímky. Čtení/Zápis  boolean .

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidejte Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastavte Audio, aby se přehrávalo napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastavte Audio, aby se po přehrání automaticky přetočilo na začátek
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

Určuje, zda se audio po přehrání automaticky přetáčí na začátek. Čtení/Zápis  boolean .

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidejte Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastavte Audio, aby se přehrávalo napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastavte Audio, aby se po přehrání automaticky přetočilo na začátek
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

Určuje, zda se audio po přehrání automaticky přetáčí na začátek. Čtení/Zápis  boolean .

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidejte Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastavte Audio, aby se přehrávalo napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastavte Audio, aby se po přehrání automaticky přetočilo na začátek
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

Určuje, zda je zvuk vložen v prezentaci. Pouze pro čtení  boolean .

**Vrací:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Vrací nebo nastavuje název audio souboru, který je propojen s AudioFrame. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Vrací nebo nastavuje název audio souboru, který je propojen s AudioFrame. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Vrací nebo nastavuje vložený audio objekt. Čtení/Zápis [IAudio](../../com.aspose.slides/iaudio).

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Vrací nebo nastavuje vložený audio objekt. Čtení/Zápis [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Určuje časové trvání počátečního fade-in média v milisekundách. Čtení/Zápis float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte dobu trvání počátečního fade na 200ms
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

Určuje časové trvání počátečního fade-in média v milisekundách. Čtení/Zápis float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte dobu trvání počátečního fade na 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

Určuje časové trvání koncového fade-out média v milisekundách. Čtení/Zápis float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte dobu trvání koncového fade na 500ms
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

Určuje časové trvání koncového fade-out média v milisekundách. Čtení/Zápis float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte dobu trvání koncového fade na 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Vrací nebo nastavuje hlasitost zvuku v procentech. Čtení/Zápis float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte hlasitost audia na 85%
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

Vrací nebo nastavuje hlasitost zvuku v procentech. Čtení/Zápis float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte hlasitost audia na 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Určuje časové trvání, které má být během přehrávání odebráno od začátku média, v milisekundách. Čtení/Zápis float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte čas ořezu na začátku na 1,5 sekundy
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

Určuje časové trvání, které má být během přehrávání odebráno od začátku média, v milisekundách. Čtení/Zápis float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte čas ořezu na začátku 1,5 sekundy
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Určuje časové trvání, které má být během přehrávání odebráno od konce média, v milisekundách. Čtení/Zápis float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte čas ořezu na konci na 2 sekundy
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

Určuje časové trvání, které má být během přehrávání odebráno od konce média, v milisekundách. Čtení/Zápis float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavte čas ořezu na konci na 2 sekundy
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Získává kolekci closed captions přiřazených k audio frame. Toto vlastnost je pouze pro čtení a vrací [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) obsahující všechny caption tracks.

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
>              // Uložte binární data titulkového tracku jako soubor .vtt
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