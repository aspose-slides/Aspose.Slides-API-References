---
title: IAudioFrame
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bir slayttaki ses klibini temsil eder.
type: docs
url: /tr/com.aspose.slides/iaudioframe/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Bir slayttaki ses klibini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Başlangıç iz parçası indeksini getirir veya ayarlar. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Başlangıç iz parçası indeksini getirir veya ayarlar. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Başlangıç iz parçası zamanını getirir veya ayarlar. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Başlangıç iz parçası zamanını getirir veya ayarlar. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Son iz parçası indeksini getirir veya ayarlar. Okunur/Yazılır int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Son iz parçası indeksini getirir veya ayarlar. Okunur/Yazılır int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Son iz parçası zamanını getirir veya ayarlar. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Son iz parçası zamanını getirir veya ayarlar. |
| [getVolume()](#getVolume--) | Ses seviyesini getirir veya ayarlar. |
| [setVolume(int value)](#setVolume-int-) | Ses seviyesini getirir veya ayarlar. |
| [getPlayMode()](#getPlayMode--) | Ses çalma modunu getirir veya ayarlar. |
| [setPlayMode(int value)](#setPlayMode-int-) | Ses çalma modunu getirir veya ayarlar. |
| [getHideAtShowing()](#getHideAtShowing--) | Bir AudioFrame’in gizli olup olmadığını belirler. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bir AudioFrame’in gizli olup olmadığını belirler. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Sesin döngüye alınıp alınmadığını belirler. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Sesin döngüye alınıp alınmadığını belirler. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Sesin slaytlar arasında çalınıp çalınmadığını belirler. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Sesin slaytlar arasında çalınıp çalınmadığını belirler. |
| [getRewindAudio()](#getRewindAudio--) | Sesin oynatıldıktan sonra otomatik olarak başlangıca geri sarılıp sarılmadığını belirler. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Sesin oynatıldıktan sonra otomatik olarak başlangıca geri sarılıp sarılmadığını belirler. |
| [getEmbedded()](#getEmbedded--) | Sesin bir sunuma gömülü olup olmadığını belirler. |
| [getLinkPathLong()](#getLinkPathLong--) | AudioFrame’e bağlı bir ses dosyasının adını getirir veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | AudioFrame’e bağlı bir ses dosyasının adını getirir veya ayarlar. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Gömülü ses nesnesini getirir veya ayarlar. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Gömülü ses nesnesini getirir veya ayarlar. |
| [getFadeInDuration()](#getFadeInDuration--) | Ortamdaki ilk solma süresinin milisaniye cinsinden süresini belirtir. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Ortamdaki ilk solma süresinin milisaniye cinsinden süresini belirtir. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Ortamdaki bitiş solma süresinin milisaniye cinsinden süresini belirtir. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Ortamdaki bitiş solma süresinin milisaniye cinsinden süresini belirtir. |
| [getVolumeValue()](#getVolumeValue--) | Ses seviyesini yüzde olarak getirir veya ayarlar. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Ses seviyesini yüzde olarak getirir veya ayarlar. |
| [getTrimFromStart()](#getTrimFromStart--) | Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [getCaptionTracks()](#getCaptionTracks--) | Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Başlangıç iz parçası indeksini getirir veya ayarlar. Okunur/Yazılır int.

**Döndürür:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Başlangıç iz parçası indeksini getirir veya ayarlar. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Başlangıç iz parçası zamanını getirir veya ayarlar. Okunur/Yazılır int.

**Döndürür:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Başlangıç iz parçası zamanını getirir veya ayarlar. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Son iz parçası indeksini getirir veya ayarlar. Okunur/Yazılır int.

**Döndürür:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Son iz parçası indeksini getirir veya ayarlar. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Son iz parçası zamanını getirir veya ayarlar. Okunur/Yazılır int.

**Döndürür:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Son iz parçası zamanını getirir veya ayarlar. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Ses seviyesini getirir veya ayarlar. Okunur/Yazılır [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Döndürür:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Ses seviyesini getirir veya ayarlar. Okunur/Yazılır [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Ses çalma modunu getirir veya ayarlar. Okunur/Yazılır [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Döndürür:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Ses çalma modunu getirir veya ayarlar. Okunur/Yazılır [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bir AudioFrame’in gizli olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bir AudioFrame’in gizli olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Sesin döngüye alınıp alınmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Sesin döngüye alınıp alınmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Sesin slaytlar arasında çalınıp çalınmadığını belirler. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ses Çerçevesi Ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Sesin slaytlar arasında çalmasını ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Sesin oynatıldıktan sonra otomatik olarak başlangıca geri sarılmasını ayarla
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Döndürür:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Sesin slaytlar arasında çalınıp çalınmadığını belirler. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ses Çerçevesi Ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Sesin slaytlar arasında çalmasını ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Sesin oynatıldıktan sonra otomatik olarak başlangıca geri sarılmasını ayarla
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Sesin oynatıldıktan sonra otomatik olarak başlangıca geri sarılıp sarılmadığını belirler. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ses Çerçevesi Ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Sesin slaytlar arasında çalmasını ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Sesin oynatıldıktan sonra otomatik olarak başlangıca geri sarılmasını ayarla
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Döndürür:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Sesin oynatıldıktan sonra otomatik olarak başlangıca geri sarılıp sarılmadığını belirler. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ses Çerçevesi Ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Sesin slaytlar arasında çalmasını ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Sesin oynatıldıktan sonra otomatik olarak başlangıca geri sarılmasını ayarla
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Sesin bir sunuma gömülü olup olmadığını belirler. Yalnızca okunur boolean.

**Döndürür:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

AudioFrame’e bağlı bir ses dosyasının adını getirir veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

AudioFrame’e bağlı bir ses dosyasının adını getirir veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Gömülü ses nesnesini getirir veya ayarlar. Okunur/Yazılır [IAudio](../../com.aspose.slides/iaudio).

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Gömülü ses nesnesini getirir veya ayarlar. Okunur/Yazılır [IAudio](../../com.aspose.slides/iaudio).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Ortamdaki ilk solma süresinin milisaniye cinsinden süresini belirtir. Okunur/Yazılır float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Başlangıç solma süresini 200ms olarak ayarla
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Ortamdaki ilk solma süresinin milisaniye cinsinden süresini belirtir. Okunur/Yazılır float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Başlangıç solma süresini 200ms olarak ayarla
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Ortamdaki bitiş solma süresinin milisaniye cinsinden süresini belirtir. Okunur/Yazılır float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Bitiş solma süresini 500ms olarak ayarla
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Ortamdaki bitiş solma süresinin milisaniye cinsinden süresini belirtir. Okunur/Yazılır float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Bitiş solma süresini 500ms olarak ayarla
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Ses seviyesini yüzde olarak getirir veya ayarlar. Okunur/Yazılır float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ses seviyesini %85 olarak ayarla
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Ses seviyesini yüzde olarak getirir veya ayarlar. Okunur/Yazılır float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ses seviyesini %85 olarak ayarla
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. Okunur/Yazılır float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Başlangıç kırpma süresini 1.5 saniye olarak ayarla
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. Okunur/Yazılır float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Başlangıç kırpma süresini 1.5 saniye olarak ayarla
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. Okunur/Yazılır float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Son kırpma süresini 2 saniye olarak ayarla
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. Okunur/Yazılır float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Son kırpma süresini 2 saniye olarak ayarla
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik yalnızca okunur ve tüm altyazı izlerini içeren bir [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) döndürür.

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
>             // Altyazı izinin ikili verisini .vtt dosyası olarak kaydet
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


**Döndürür:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)