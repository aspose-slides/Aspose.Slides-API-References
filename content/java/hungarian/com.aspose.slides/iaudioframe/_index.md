---
title: IAudioFrame
second_title: Aspose.Slides a Java API-referencia
description: Hangklipet reprezentál a dián.
type: docs
url: /hu/com.aspose.slides/iaudioframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Hangklipet reprezentál a dián.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Visszaad vagy beállít egy kezdő sáv indexet. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Visszaad vagy beállít egy kezdő sáv indexet. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Visszaad vagy beállít egy kezdő sáv időt. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Visszaad vagy beállít egy kezdő sáv időt. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Visszaad vagy beállít egy utolsó sáv indexet Olvasás/írás int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Visszaad vagy beállít egy utolsó sáv indexet Olvasás/írás int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Visszaad vagy beállít egy utolsó sáv időt. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Visszaad vagy beállít egy utolsó sáv időt. |
| [getVolume()](#getVolume--) | Visszaad vagy beállít a hang hangerőt. |
| [setVolume(int value)](#setVolume-int-) | Visszaad vagy beállít a hang hangerőt. |
| [getPlayMode()](#getPlayMode--) | Visszaad vagy beállít a hang lejátszási módot. |
| [setPlayMode(int value)](#setPlayMode-int-) | Visszaad vagy beállít a hang lejátszási módot. |
| [getHideAtShowing()](#getHideAtShowing--) | Megállapítja, hogy egy AudioFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Megállapítja, hogy egy AudioFrame rejtett-e. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Megállapítja, hogy a hang ismétlődik-e. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Megállapítja, hogy a hang ismétlődik-e. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Megállapítja, hogy a hang a diákon át lejátszásra kerül-e. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Megállapítja, hogy a hang a diákon át lejátszásra kerül-e. |
| [getRewindAudio()](#getRewindAudio--) | Megállapítja, hogy a hang a lejátszás után automatikusan visszatekerődik-e a kezdetre. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Megállapítja, hogy a hang a lejátszás után automatikusan visszatekerődik-e a kezdetre. |
| [getEmbedded()](#getEmbedded--) | Megállapítja, hogy a hang beágyazott-e egy prezentációba. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaad vagy beállít egy audiofájl nevét, amely egy AudioFrame-hez kapcsolódik. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaad vagy beállít egy audiofájl nevét, amely egy AudioFrame-hez kapcsolódik. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Visszaad vagy beállít beágyazott audio objektumot. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Visszaad vagy beállít beágyazott audio objektumot. |
| [getFadeInDuration()](#getFadeInDuration--) | Meghatározza a média kezdeti fade-in időtartamát ezredmásodpercben. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Meghatározza a média kezdeti fade-in időtartamát ezredmásodpercben. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Meghatározza a média végső fade-out időtartamát ezredmásodpercben. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Meghatározza a média végső fade-out időtartamát ezredmásodpercben. |
| [getVolumeValue()](#getVolumeValue--) | Visszaad vagy beállít a hang hangerőt százalékban. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Visszaad vagy beállít a hang hangerőt százalékban. |
| [getTrimFromStart()](#getTrimFromStart--) | Meghatározza a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Meghatározza a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Meghatározza a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Meghatározza a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. |
| [getCaptionTracks()](#getCaptionTracks--) | Lekéri a hangkerethez kapcsolódó lezárt feliratok gyűjteményét. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Visszaad vagy beállít egy kezdő sáv indexet. Olvasás/írás int.

**Visszatérési érték:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Visszaad vagy beállít egy kezdő sáv indexet. Olvasás/írás int.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Visszaad vagy beállít egy kezdő sáv időt. Olvasás/írás int.

**Visszatérési érték:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Visszaad vagy beállít egy kezdő sáv időt. Olvasás/írás int.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Visszaad vagy beállít egy utolsó sáv indexet Olvasás/írás int.

**Visszatérési érték:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Visszaad vagy beállít egy utolsó sáv indexet Olvasás/írás int.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Visszaad vagy beállít egy utolsó sáv időt. Olvasás/írás int.

**Visszatérési érték:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Visszaad vagy beállít egy utolsó sáv időt. Olvasás/írás int.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Visszaad vagy beállít a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatérési érték:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Visszaad vagy beállít a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Visszaad vagy beállít a hang lejátszási módot. Olvasás/írás [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Visszatérési érték:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Visszaad vagy beállít a hang lejátszási módot. Olvasás/írás [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Megállapítja, hogy egy AudioFrame rejtett-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Megállapítja, hogy egy AudioFrame rejtett-e. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Megállapítja, hogy a hang ismétlődik-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Megállapítja, hogy a hang ismétlődik-e. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Megállapítja, hogy a hang a diákon át lejátszásra kerül-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
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

Megállapítja, hogy a hang a diákon át lejátszásra kerül-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Megállapítja, hogy a hang a lejátszás után automatikusan visszatekerődik-e a kezdetre. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
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

Megállapítja, hogy a hang a lejátszás után automatikusan visszatekerődik-e a kezdetre. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // A hangot beállítja, hogy a diákokon át lejátszódjon
>       audioFrame.setPlayAcrossSlides(true);
>       // A hang automatikusan visszatekerődik a kezdőpontra a lejátszás után
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Megállapítja, hogy a hang beágyazott-e egy prezentációba. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Visszaad vagy beállít egy audiofájl nevét, amely egy AudioFrame-hez kapcsolódik. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Visszaad vagy beállít egy audiofájl nevét, amely egy AudioFrame-hez kapcsolódik. Olvasás/írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Visszaad vagy beállít beágyazott audio objektumot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Visszaad vagy beállít beágyazott audio objektumot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Meghatározza a média kezdeti fade-in időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a kezdő fade időtartamát 200 ms-re
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

Meghatározza a média kezdeti fade-in időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Set the duration of the starting fade for 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Meghatározza a média végső fade-out időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a befejező fade időtartamát 500 ms-re
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

Meghatározza a média végső fade-out időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a befejező fade időtartamát 500 ms-re
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Visszaad vagy beállít a hang hangerőt százalékban. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a hanghangerőt 85%
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

Visszaad vagy beállít a hang hangerőt százalékban. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a hanghangerőt 85%-ra
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Meghatározza a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás float.

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

Meghatározza a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás float.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Meghatározza a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a végi vágási időt 2 másodperc
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

Meghatározza a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a végi vágási időt 2 másodperc
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Lekéri a hangkerethez kapcsolódó lezárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) objektumot ad vissza, amely tartalmazza az összes feliratsávot.

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
>             // Mentse el a felirat sáv bináris adatait .vtt fájlként
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