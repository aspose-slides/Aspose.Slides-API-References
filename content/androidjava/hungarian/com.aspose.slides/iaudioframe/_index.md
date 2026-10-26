---
title: IAudioFrame
second_title: Aspose.Slides Androidra a Java API hivatkozásból
description: Egy dián lévő audio klipet reprezentál.
type: docs
url: /hu/com.aspose.slides/iaudioframe/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Egy hangklipet reprezentál egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Visszaadja vagy beállítja a kezdő sáv indexet. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Visszaadja vagy beállítja a kezdő sáv indexet. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Visszaadja vagy beállítja a kezdő sáv időt. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Visszaadja vagy beállítja a kezdő sáv időt. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Visszaadja vagy beállítja az utolsó sáv indexet. Olvasás/írás int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Visszaadja vagy beállítja az utolsó sáv indexet. Olvasás/írás int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Visszaadja vagy beállítja az utolsó sáv időt. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Visszaadja vagy beállítja az utolsó sáv időt. |
| [getVolume()](#getVolume--) | Visszaadja vagy beállítja a hang hangerőt. |
| [setVolume(int value)](#setVolume-int-) | Visszaadja vagy beállítja a hang hangerőt. |
| [getPlayMode()](#getPlayMode--) | Visszaadja vagy beállítja a hang lejátszási módot. |
| [setPlayMode(int value)](#setPlayMode-int-) | Visszaadja vagy beállítja a hang lejátszási módot. |
| [getHideAtShowing()](#getHideAtShowing--) | Meghatározza, hogy egy AudioFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Meghatározza, hogy egy AudioFrame rejtett-e. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Meghatározza, hogy a hang ciklikus-e. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Meghatározza, hogy a hang ciklikus-e. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Meghatározza, hogy a hang a diákon át játszódik-e. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Meghatározza, hogy a hang a diákon át játszódik-e. |
| [getRewindAudio()](#getRewindAudio--) | Meghatározza, hogy a hang automatikusan újraindul-e a lejátszás után. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Meghatározza, hogy a hang automatikusan újraindul-e a lejátszás után. |
| [getEmbedded()](#getEmbedded--) | Meghatározza, hogy a hang be van-e ágyazva a prezentációba. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja egy audiofájl nevét, amely egy AudioFrame-hez van kapcsolva. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja egy audiofájl nevét, amely egy AudioFrame-hez van kapcsolva. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Visszaadja vagy beállítja a beágyazott audio objektumot. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Visszaadja vagy beállítja a beágyazott audio objektumot. |
| [getFadeInDuration()](#getFadeInDuration--) | Megadja a média kezdeti elhalványulásának időtartamát ezredmásodpercben. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Megadja a média kezdeti elhalványulásának időtartamát ezredmásodpercben. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Megadja a média befejező elhalványulásának időtartamát ezredmásodpercben. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Megadja a média befejező elhalványulásának időtartamát ezredmásodpercben. |
| [getVolumeValue()](#getVolumeValue--) | Visszaadja vagy beállítja a hang hangerőt százalékban. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Visszaadja vagy beállítja a hang hangerőt százalékban. |
| [getTrimFromStart()](#getTrimFromStart--) | Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. |
| [getCaptionTracks()](#getCaptionTracks--) | Lekéri a hangkerethez kapcsolódó zárt feliratok gyűjteményét. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```


Visszaadja vagy beállítja a kezdő sáv indexet. Olvasás/írás int.

**Visszatérési érték:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```


Visszaadja vagy beállítja a kezdő sáv indexet. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```


Visszaadja vagy beállítja a kezdő sáv időt. Olvasás/írás int.

**Visszatérési érték:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```


Visszaadja vagy beállítja a kezdő sáv időt. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```


Visszaadja vagy beállítja az utolsó sáv indexet. Olvasás/írás int.

**Visszatérési érték:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```


Visszaadja vagy beállítja az utolsó sáv indexet. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```


Visszaadja vagy beállítja az utolsó sáv időt. Olvasás/írás int.

**Visszatérési érték:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```


Visszaadja vagy beállítja az utolsó sáv időt. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```


Visszaadja vagy beállítja a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatérési érték:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```


Visszaadja vagy beállítja a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```


Visszaadja vagy beállítja a hang lejátszási módot. Olvasás/írás [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Visszatérési érték:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```


Visszaadja vagy beállítja a hang lejátszási módot. Olvasás/írás [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```


Meghatározza, hogy egy AudioFrame rejtett-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```


Meghatározza, hogy egy AudioFrame rejtett-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```


Meghatározza, hogy a hang ciklikus-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```


Meghatározza, hogy a hang ciklikus-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```


Meghatározza, hogy a hang a diákon át játszódik-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Hang beállítása, hogy a diákon át játszódjon
>       audioFrame.setPlayAcrossSlides(true);
>       // Hang beállítása, hogy a lejátszás után automatikusan újrainduljon a kezdeti állapotba
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Visszatérési érték:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```


Meghatározza, hogy a hang a diákon át játszódik-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Hang beállítása, hogy a diákon át játszódjon
>       audioFrame.setPlayAcrossSlides(true);
>       // Hang beállítása, hogy a lejátszás után automatikusan újrainduljon a kezdeti állapotba
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```


Meghatározza, hogy a hang automatikusan újraindul-e a lejátszás után. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Hang beállítása, hogy a diákon át játszódjon
>       audioFrame.setPlayAcrossSlides(true);
>       // Hang beállítása, hogy a lejátszás után automatikusan újrainduljon a kezdeti állapotba
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Visszatérési érték:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```


Meghatározza, hogy a hang automatikusan újraindul-e a lejátszás után. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Hang beállítása, hogy a diákon át játszódjon
>       audioFrame.setPlayAcrossSlides(true);
>       // Hang beállítása, hogy a lejátszás után automatikusan újrainduljon a kezdeti állapotba
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```


Meghatározza, hogy egy hang be van-e ágyazva a prezentációba. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Visszaadja vagy beállítja egy audiofájl nevét, amely egy AudioFrame-hez van kapcsolva. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Visszaadja vagy beállítja egy audiofájl nevét, amely egy AudioFrame-hez van kapcsolva. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```


Visszaadja vagy beállítja a beágyazott audio objektumot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```


Visszaadja vagy beállítja a beágyazott audio objektumot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```


Megadja a média kezdeti elhalványulásának időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a kezdő elhalványulás időtartamát 200 ms-re
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```


Megadja a média kezdeti elhalványulásának időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a kezdő elhalványulás időtartamát 200ms-re
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```


Megadja a média befejező elhalványulásának időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a befejező elhalványulás időtartamát 500 ms-re
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```


Megadja a média befejező elhalványulásának időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a befejező elhalványulás időtartamát 500 ms-re
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```


Visszaadja vagy beállítja a hanghangerőt százalékban. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // A hang hangerő beállítása 85%-ra
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```


Visszaadja vagy beállítja a hanghangerőt százalékban. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // A hang hangerő beállítása 85%-ra
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```


Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a kezdő vágási időt 1,5 másodperc
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```


Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a kezdő vágási időt 1,5 másodperc
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```


Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a végső vágási időt 2 másodperc
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```


Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>  
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```


Lekéri a hangkerethez kapcsolódó zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)-t ad vissza, amely minden felirat sávot tartalmaz.

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
>             // Mentse a felirat sáv bináris adatát .vtt fájlként
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

**Visszatérési érték:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)