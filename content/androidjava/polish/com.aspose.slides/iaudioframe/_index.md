---
title: IAudioFrame
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje klip audio na slajdzie.
type: docs
url: /pl/com.aspose.slides/iaudioframe/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Reprezentuje klip audio na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Zwraca lub ustawia indeks ścieżki początkowej. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Zwraca lub ustawia indeks ścieżki początkowej. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Zwraca lub ustawia czas początkowy ścieżki. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Zwraca lub ustawia czas początkowy ścieżki. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Zwraca lub ustawia indeks ostatniej ścieżki Odczyt/zapis int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Zwraca lub ustawia indeks ostatniej ścieżki Odczyt/zapis int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Zwraca lub ustawia czas ostatniej ścieżki. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Zwraca lub ustawia czas ostatniej ścieżki. |
| [getVolume()](#getVolume--) | Zwraca lub ustawia głośność audio. |
| [setVolume(int value)](#setVolume-int-) | Zwraca lub ustawia głośność audio. |
| [getPlayMode()](#getPlayMode--) | Zwraca lub ustawia tryb odtwarzania audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Zwraca lub ustawia tryb odtwarzania audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Określa, czy AudioFrame jest ukryty. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Określa, czy AudioFrame jest ukryty. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Określa, czy audio jest zapętlone. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Określa, czy audio jest zapętlone. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Określa, czy audio odtwarza się na wszystkich slajdach. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Określa, czy audio odtwarza się na wszystkich slajdach. |
| [getRewindAudio()](#getRewindAudio--) | Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. |
| [getEmbedded()](#getEmbedded--) | Określa, czy dźwięk jest osadzony w prezentacji. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca lub ustawia nazwę pliku audio, który jest powiązany z AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Zwraca lub ustawia nazwę pliku audio, który jest powiązany z AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Zwraca lub ustawia osadzony obiekt audio. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Zwraca lub ustawia osadzony obiekt audio. |
| [getFadeInDuration()](#getFadeInDuration--) | Określa czas trwania początkowego fade-in mediów w milisekundach. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Określa czas trwania początkowego fade-in mediów w milisekundach. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Określa czas trwania końcowego fade-out mediów w milisekundach. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Określa czas trwania końcowego fade-out mediów w milisekundach. |
| [getVolumeValue()](#getVolumeValue--) | Zwraca lub ustawia głośność audio w procentach. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Zwraca lub ustawia głośność audio w procentach. |
| [getTrimFromStart()](#getTrimFromStart--) | Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. |
| [getCaptionTracks()](#getCaptionTracks--) | Pobiera kolekcję zamkniętych napisów powiązanych z ramką audio. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Zwraca lub ustawia indeks ścieżki początkowej. Odczyt/zapis int.

**Zwraca:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Zwraca lub ustawia indeks ścieżki początkowej. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Zwraca lub ustawia czas początkowy ścieżki. Odczyt/zapis int.

**Zwraca:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Zwraca lub ustawia czas początkowy ścieżki. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Zwraca lub ustawia indeks ostatniej ścieżki Odczyt/zapis int.

**Zwraca:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Zwraca lub ustawia indeks ostatniej ścieżki Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Zwraca lub ustawia czas ostatniej ścieżki. Odczyt/zapis int.

**Zwraca:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Zwraca lub ustawia czas ostatniej ścieżki. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Zwraca lub ustawia głośność audio. Odczyt/zapis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Zwraca:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Zwraca lub ustawia głośność audio. Odczyt/zapis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Zwraca lub ustawia tryb odtwarzania audio. Odczyt/zapis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Zwraca:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Zwraca lub ustawia tryb odtwarzania audio. Odczyt/zapis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Określa, czy AudioFrame jest ukryty. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Określa, czy AudioFrame jest ukryty. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Określa, czy audio jest zapętlone. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Określa, czy audio jest zapętlone. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Określa, czy audio odtwarza się na wszystkich slajdach. Odczyt/zapis boolean.

**Zwraca:**
boolean
--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Dodaj ramkę audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ustaw odtwarzanie audio na wszystkich slajdach
>       audioFrame.setPlayAcrossSlides(true);
>       // Ustaw audio, aby automatycznie przewijało się do początku po odtworzeniu
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Zwraca:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Określa, czy audio odtwarza się na wszystkich slajdach. Odczyt/zapis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Dodaj ramkę audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ustaw odtwarzanie audio na wszystkich slajdach
>       audioFrame.setPlayAcrossSlides(true);
>       // Ustaw audio, aby automatycznie przewijało się do początku po odtworzeniu
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Odczyt/zapis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Dodaj ramkę audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ustaw odtwarzanie audio na wszystkich slajdach
>       audioFrame.setPlayAcrossSlides(true);
>       // Ustaw audio, aby automatycznie przewijało się do początku po odtworzeniu
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Zwraca:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Odczyt/zapis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Dodaj ramkę audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ustaw odtwarzanie audio na wszystkich slajdach
>       audioFrame.setPlayAcrossSlides(true);
>       // Ustaw audio, aby automatycznie przewijało się do początku po odtworzeniu
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Określa, czy dźwięk jest osadzony w prezentacji. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Zwraca lub ustawia nazwę pliku audio, który jest powiązany z AudioFrame. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Zwraca lub ustawia nazwę pliku audio, który jest powiązany z AudioFrame. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Zwraca lub ustawia osadzony obiekt audio. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Zwraca lub ustawia osadzony obiekt audio. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Określa czas trwania początkowego fade-in mediów w milisekundach. Odczyt/zapis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw czas trwania początkowego zaniku na 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Określa czas trwania początkowego fade-in mediów w milisekundach. Odczyt/zapis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw czas trwania początkowego zaniku na 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Określa czas trwania końcowego fade-out mediów w milisekundach. Odczyt/zapis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw czas trwania końcowego zaniku na 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Określa czas trwania końcowego fade-out mediów w milisekundach. Odczyt/zapis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw czas trwania końcowego zaniku na 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Zwraca lub ustawia głośność audio w procentach. Odczyt/zapis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw głośność audio na 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Zwraca lub ustawia głośność audio w procentach. Odczyt/zapis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw głośność audio na 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Odczyt/zapis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw czas przycinania od początku na 1,5 sekundy
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Odczyt/zapis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw czas przycinania od początku na 1,5 sekundy
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. Odczyt/zapis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw czas przycinania od końca na 2 sekundy
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. Odczyt/zapis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ustaw czas przycinania od końca na 2 sekundy
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Pobiera kolekcję zamkniętych napisów powiązanych z ramką audio. Ta właściwość jest tylko do odczytu i zwraca [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zawierający wszystkie ścieżki napisów.

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
>             // Zapisz binarne dane ścieżki napisów jako plik .vtt
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

**Zwraca:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)