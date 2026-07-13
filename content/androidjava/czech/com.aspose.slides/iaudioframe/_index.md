---
title: IAudioFrame
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje zvukový klip na snímku.
type: docs
url: /cs/com.aspose.slides/iaudioframe/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Představuje zvukový klip na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Vrací nebo nastavuje index počáteční stopy. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Vrací nebo nastavuje index počáteční stopy. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Vrací nebo nastavuje čas počáteční stopy. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Vrací nebo nastavuje čas počáteční stopy. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Vrací nebo nastavuje poslední index stopy. Čtení/zápis int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Vrací nebo nastavuje poslední index stopy. Čtení/zápis int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Vrací nebo nastavuje poslední čas stopy. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Vrací nebo nastavuje poslední čas stopy. |
| [getVolume()](#getVolume--) | Vrací nebo nastavuje hlasitost zvuku. |
| [setVolume(int value)](#setVolume-int-) | Vrací nebo nastavuje hlasitost zvuku. |
| [getPlayMode()](#getPlayMode--) | Vrací nebo nastavuje režim přehrávání zvuku. |
| [setPlayMode(int value)](#setPlayMode-int-) | Vrací nebo nastavuje režim přehrávání zvuku. |
| [getHideAtShowing()](#getHideAtShowing--) | Určuje, zda je AudioFrame skrytý. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Určuje, zda je AudioFrame skrytý. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Určuje, zda se audio opakuje. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Určuje, zda se audio opakuje. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Určuje, zda se audio přehrává napříč snímky. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Určuje, zda se audio přehrává napříč snímky. |
| [getRewindAudio()](#getRewindAudio--) | Určuje, zda se audio automaticky přetočí na začátek po přehrání. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Určuje, zda se audio automaticky přetočí na začátek po přehrání. |
| [getEmbedded()](#getEmbedded--) | Určuje, zda je zvuk vložen do prezentace. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Vrací nebo nastavuje vložený audio objekt. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Vrací nebo nastavuje vložený audio objekt. |
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
| [getCaptionTracks()](#getCaptionTracks--) | Získává kolekci uzavřených titulků spojených s audio snímkem. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Vrací nebo nastavuje index počáteční stopy. Čtení/zápis int.

**Vrací:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Vrací nebo nastavuje index počáteční stopy. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Vrací nebo nastavuje čas počáteční stopy. Čtení/zápis int.

**Vrací:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Vrací nebo nastavuje čas počáteční stopy. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Vrací nebo nastavuje poslední index stopy. Čtení/zápis int.

**Vrací:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Vrací nebo nastavuje poslední index stopy. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Vrací nebo nastavuje poslední čas stopy. Čtení/zápis int.

**Vrací:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Vrací nebo nastavuje poslední čas stopy. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Vrací nebo nastavuje hlasitost zvuku. Čtení/zápis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Vrací:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Vrací nebo nastavuje hlasitost zvuku. Čtení/zápis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Vrací nebo nastavuje režim přehrávání zvuku. Čtení/zápis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Vrací:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Vrací nebo nastavuje režim přehrávání zvuku. Čtení/zápis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Určuje, zda je AudioFrame skrytý. Čtení/zápis boolean.

**Vrací:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Určuje, zda je AudioFrame skrytý. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Určuje, zda se audio opakuje. Čtení/zápis boolean.

**Vrací:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Určuje, zda se audio opakuje. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Určuje, zda se audio přehrává napříč snímky. Čtení/zápis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidat zvukový rámec
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastavit audio k přehrávání napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastavit audio, aby se po přehrání automaticky přetočilo na začátek
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
public abstract void setPlayAcrossSlides(boolean value)
```

Určuje, zda se audio přehrává napříč snímky. Čtení/zápis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidat zvukový rámec
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastavit audio k přehrávání napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastavit audio, aby se po přehrání automaticky přetočilo na začátek
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
public abstract boolean getRewindAudio()
```

Určuje, zda se audio automaticky přetočí na začátek po přehrání. Čtení/zápis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidat zvukový rámec
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastavit audio k přehrávání napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastavit audio, aby se po přehrání automaticky přetočilo na začátek
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
public abstract void setRewindAudio(boolean value)
```

Určuje, zda se audio automaticky přetočí na začátek po přehrání. Čtení/zápis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Přidat zvukový rámec
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Nastavit audio k přehrávání napříč snímky
>       audioFrame.setPlayAcrossSlides(true);
>       // Nastavit audio, aby se po přehrání automaticky přetočilo na začátek
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
public abstract boolean getEmbedded()
```

Určuje, zda je zvuk vložen do prezentace. Pouze pro čtení boolean.

**Vrací:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame. Čtení/zápis String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Vrací nebo nastavuje vložený audio objekt. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Vrací nebo nastavuje vložený audio objekt. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Určuje časovou délku počátečního fade-in média v milisekundách. Čtení/zápis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit dobu trvání počátečního fade na 200ms
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
public abstract void setFadeInDuration(float value)
```

Určuje časovou délku počátečního fade-in média v milisekundách. Čtení/zápis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit dobu trvání počátečního fade na 200ms
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
public abstract float getFadeOutDuration()
```

Určuje časovou délku koncového fade-out média v milisekundách. Čtení/zápis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit dobu trvání koncového fade na 500 ms
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
public abstract void setFadeOutDuration(float value)
```

Určuje časovou délku koncového fade-out média v milisekundách. Čtení/zápis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit dobu trvání koncového fade na 500 ms
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
public abstract float getVolumeValue()
```

Vrací nebo nastavuje hlasitost zvuku v procentech. Čtení/zápis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit hlasitost zvuku na 85 %
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
public abstract void setVolumeValue(float value)
```

Vrací nebo nastavuje hlasitost zvuku v procentech. Čtení/zápis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit hlasitost zvuku na 85 %
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
public abstract float getTrimFromStart()
```

Určuje časovou délku, která má být během přehrávání odebrána ze začátku média, v milisekundách. Čtení/zápis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit čas ořezu od začátku na 1,5 sekundy
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Určuje časovou délku, která má být během přehrávání odebrána ze začátku média, v milisekundách. Čtení/zápis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit čas ořezu od začátku 1,5 sekundy
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
public abstract float getTrimFromEnd()
```

Určuje časovou délku, která má být během přehrávání odebrána z konce média, v milisekundách. Čtení/zápis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit čas ořezu na konci na 2 sekundy
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Určuje časovou délku, která má být během přehrávání odebrána z konce média, v milisekundách. Čtení/zápis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Nastavit čas ořezu na konci 2 sekundy
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
public abstract ICaptionsCollection getCaptionTracks()
```

Získává kolekci uzavřených titulků spojených s audio snímkem. Tato vlastnost je pouze pro čtení a vrací [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) obsahující všechny titulkové stopy.

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
>             // Uložit binární data titulkové stopy jako soubor .vtt
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

**Vrací:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)