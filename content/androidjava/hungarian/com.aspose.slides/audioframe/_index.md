---
title: AudioFrame
second_title: Aspose.Slides Androidhoz a Java API hivatkozás alapján
description: Egy dián található audio klipe.
type: docs
url: /hu/com.aspose.slides/audioframe/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Minden megvalósított interfész:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Az dián egy hangklipet képvisel.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Lekéri az AudioFrame alakzatot
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Beállítja a lejátszási módot kattintásra
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Beállítja a hangerőt alacsonyra
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Beállítja, hogy a hang a diákon át lejátszódjon
>      audioFrame.setPlayAcrossSlides(true);
>      // Letiltja a hang ismétlését
>      audioFrame.setPlayLoopMode(false);
>      // Elrejti az AudioFrame-et a diavetítés során
>      audioFrame.setHideAtShowing(true);
>      // A lejátszás után a hangot visszatekeri a kezdetre
>      audioFrame.setRewindAudio(true);
>      // Mentés a PowerPoint fájlt a lemezre
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Visszaadja vagy beállítja a kezdő sáv indexét. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Visszaadja vagy beállítja a kezdő sáv indexét. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Visszaadja vagy beállítja a kezdő sáv időpontját. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Visszaadja vagy beállítja a kezdő sáv időpontját. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Visszaadja vagy beállítja az utolsó sáv indexét Olvasás/írás  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Visszaadja vagy beállítja az utolsó sáv indexét Olvasás/írás  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Visszaadja vagy beállítja az utolsó sáv időpontját. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Visszaadja vagy beállítja az utolsó sáv időpontját. |
| [getVolume()](#getVolume--) | Visszaadja vagy beállítja a hanghangerőt. |
| [setVolume(int value)](#setVolume-int-) | Visszaadja vagy beállítja a hanghangerőt. |
| [getPlayMode()](#getPlayMode--) | Visszaadja vagy beállítja a hanglejátszási módot. |
| [setPlayMode(int value)](#setPlayMode-int-) | Visszaadja vagy beállítja a hanglejátszási módot. |
| [getHideAtShowing()](#getHideAtShowing--) | Meghatározza, hogy egy AudioFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Meghatározza, hogy egy AudioFrame rejtett-e. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Meghatározza, hogy a hang ismétlődik-e. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Meghatározza, hogy a hang ismétlődik-e. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Meghatározza, hogy a hang a diákon át játszódik-e. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Meghatározza, hogy a hang a diákon át játszódik-e. |
| [getRewindAudio()](#getRewindAudio--) | Meghatározza, hogy a hang automatikusan visszatekerődik-e a kezdetre lejátszás után. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Meghatározza, hogy a hang automatikusan visszatekerődik-e a kezdetre lejátszás után. |
| [getEmbedded()](#getEmbedded--) | Meghatározza, hogy a hang be van-e ágyazva a prezentációba. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja egy audiofájl nevét, amely egy AudioFrame-hez van kapcsolva. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja egy audiofájl nevét, amely egy AudioFrame-hez van kapcsolva. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Visszaadja vagy beállítja a beágyazott audio objektumot. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Visszaadja vagy beállítja a beágyazott audio objektumot. |
| [getFadeInDuration()](#getFadeInDuration--) | Meghatározza a média kezdeti elhalványulásának időtartamát ezredmásodpercben. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Meghatározza a média kezdeti elhalványulásának időtartamát ezredmásodpercben. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Meghatározza a média befejező elhalványulásának időtartamát ezredmásodpercben. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Meghatározza a média befejező elhalványulásának időtartamát ezredmásodpercben. |
| [getVolumeValue()](#getVolumeValue--) | Visszaadja vagy beállítja a hang hangerőt százalékban. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Visszaadja vagy beállítja a hang hangerőt százalékban. |
| [getTrimFromStart()](#getTrimFromStart--) | Meghatározza a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Meghatározza a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Meghatározza a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Meghatározza a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. |
| [getCaptionTracks()](#getCaptionTracks--) | Visszaadja a hangkerethez kapcsolódó lezárt feliratok gyűjteményét. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Visszaadja vagy beállítja a kezdő sáv indexét. Olvasás/írás  int .

**Visszatér:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Visszaadja vagy beállítja a kezdő sáv indexét. Olvasás/írás  int .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Visszaadja vagy beállítja a kezdő sáv időpontját. Olvasás/írás  int .

**Visszatér:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Visszaadja vagy beállítja a kezdő sáv időpontját. Olvasás/írás  int .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Visszaadja vagy beállítja az utolsó sáv indexét Olvasás/írás  int .

**Visszatér:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Visszaadja vagy beállítja az utolsó sáv indexét Olvasás/írás  int .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Visszaadja vagy beállítja az utolsó sáv időpontját. Olvasás/írás  int .

**Visszatér:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Visszaadja vagy beállítja az utolsó sáv időpontját. Olvasás/írás  int .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Visszaadja vagy beállítja a hanghangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatér:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Visszaadja vagy beállítja a hanghangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Visszaadja vagy beállítja a hanglejátszási módot. Olvasás/írás [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Visszatér:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Visszaadja vagy beállítja a hanglejátszási módot. Olvasás/írás [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Meghatározza, hogy egy AudioFrame rejtett-e. Olvasás/írás  boolean .

**Visszatér:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Meghatározza, hogy egy AudioFrame rejtett-e. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Meghatározza, hogy a hang ismétlődik-e. Olvasás/írás  boolean .

**Visszatér:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Meghatározza, hogy a hang ismétlődik-e. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Meghatározza, hogy a hang a diákon át játszódik-e. Olvasás/írás  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Hang lejátszása a diákon át
>       audioFrame.setPlayAcrossSlides(true);
>       // Hang automatikus visszatekerése a lejátszás után a kezdetre
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Visszatér:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Meghatározza, hogy a hang a diákon át játszódik-e. Olvasás/írás  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Hang lejátszása a diákon át
>       audioFrame.setPlayAcrossSlides(true);
>       // Hang automatikus visszatekerése a lejátszás után a kezdetre
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
public final boolean getRewindAudio()
```

Meghatározza, hogy a hang automatikusan visszatekerődik-e a kezdetre lejátszás után. Olvasás/írás  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Hang lejátszása a diákon át
>       audioFrame.setPlayAcrossSlides(true);
>       // Hang automatikus visszatekerése a lejátszás után a kezdetre
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Visszatér:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Meghatározza, hogy a hang automatikusan visszatekerődik-e a kezdetre lejátszás után. Olvasás/írás  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Hangkeret hozzáadása
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Hang lejátszása a diákon át
>       audioFrame.setPlayAcrossSlides(true);
>       // Hang automatikus visszatekerése a lejátszás után a kezdetre
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
public final boolean getEmbedded()
```

Meghatározza, hogy a hang be van-e ágyazva a prezentációba. Csak olvasás  boolean .

**Visszatér:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Visszaadja vagy beállítja egy audiofájl nevét, amely egy AudioFrame-hez van kapcsolva. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Visszaadja vagy beállítja egy audiofájl nevét, amely egy AudioFrame-hez van kapcsolva. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Visszaadja vagy beállítja a beágyazott audio objektumot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Visszaadja vagy beállítja a beágyazott audio objektumot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Meghatározza a média kezdeti elhalványulásának időtartamát ezredmásodpercben. Olvasás/írás float.

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

**Visszatér:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Meghatározza a média kezdeti elhalványulásának időtartamát ezredmásodpercben. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Állítsa be a kezdeti elhalványulás időtartamát 200 ms-re
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
public final float getFadeOutDuration()
```

Meghatározza a média befejező elhalványulásának időtartamát ezredmásodpercben. Olvasás/írás float.

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


**Visszatér:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Meghatározza a média befejező elhalványulásának időtartamát ezredmásodpercben. Olvasás/írás float.

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
public final float getVolumeValue()
```

Visszaadja vagy beállítja a hang hangerőt százalékban. Olvasás/írás float.

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
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Visszaadja vagy beállítja a hang hangerőt százalékban. Olvasás/írás float.

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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
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
>      // Állítsa be a kezdő vágási időt 1,5 másodpercre
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
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
>      // Állítsa be a kezdő vágási időt 1,5 másodpercre
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
public final float getTrimFromEnd()
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
>      // Állítsa be a végső vágási időt 2 másodpercre
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
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
>      // Állítsa be a végső vágási időt 2 másodpercre
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Visszaadja a hangkerethez kapcsolódó lezárt feliratok gyűjteményét. Ez a tulajdonság csak olvasás, és egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) objektumot ad vissza, amely az összes felirat sávot tartalmazza.

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
>              // Mentse a felirat sáv bináris adatát .vtt fájlba
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


**Visszatér:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)