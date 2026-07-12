---
title: AudioFrame
second_title: Android için Aspose.Slides Java API Referansı
description: Bir slayttaki ses klibini temsil eder.
type: docs
url: /tr/com.aspose.slides/audioframe/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Bir slayttaki ses klibini temsil eder.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // AudioFrame şekilini alır
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Oynatma modunu tıklamayla oynatacak şekilde ayarlar
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Ses seviyesini Düşük olarak ayarlar
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Sesin slaytlar arasında çalmasını ayarlar
>      audioFrame.setPlayAcrossSlides(true);
>      // Ses için döngüyü devre dışı bırakır
>      audioFrame.setPlayLoopMode(false);
>      // Slayt gösterisi sırasında AudioFrame'i gizler
>      audioFrame.setHideAtShowing(true);
>      // Ses çalındıktan sonra başa sarılmasını sağlar
>      audioFrame.setRewindAudio(true);
>      // PowerPoint dosyasını diske kaydeder
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Başlangıç iz parçası indeksini döndürür veya ayarlar. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Başlangıç iz parçası indeksini döndürür veya ayarlar. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Başlangıç iz parçası zamanını döndürür veya ayarlar. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Başlangıç iz parçası zamanını döndürür veya ayarlar. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Son iz parçası indeksini döndürür veya ayarlar Okuma/yazma  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Son iz parçası indeksini döndürür veya ayarlar Okuma/yazma  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Son iz parçası zamanını döndürür veya ayarlar. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Son iz parçası zamanını döndürür veya ayarlar. |
| [getVolume()](#getVolume--) | Ses düzeyini döndürür veya ayarlar. |
| [setVolume(int value)](#setVolume-int-) | Ses düzeyini döndürür veya ayarlar. |
| [getPlayMode()](#getPlayMode--) | Ses oynatma modunu döndürür veya ayarlar. |
| [setPlayMode(int value)](#setPlayMode-int-) | Ses oynatma modunu döndürür veya ayarlar. |
| [getHideAtShowing()](#getHideAtShowing--) | Bir AudioFrame'in gizli olup olmadığını belirler. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bir AudioFrame'in gizli olup olmadığını belirler. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Sesin döngüde olup olmadığını belirler. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Sesin döngüde olup olmadığını belirler. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Sesin slaytlar arasında çalınıp çalınmadığını belirler. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Sesin slaytlar arasında çalınıp çalınmadığını belirler. |
| [getRewindAudio()](#getRewindAudio--) | Sesin çalındıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Sesin çalındıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler. |
| [getEmbedded()](#getEmbedded--) | Sesin bir sunuma gömülü olup olmadığını belirler. |
| [getLinkPathLong()](#getLinkPathLong--) | Bir AudioFrame'e bağlı bir ses dosyasının adını döndürür veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bir AudioFrame'e bağlı bir ses dosyasının adını döndürür veya ayarlar. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Gömülü ses nesnesini döndürür veya ayarlar. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Gömülü ses nesnesini döndürür veya ayarlar. |
| [getFadeInDuration()](#getFadeInDuration--) | Medyanın ilk solma süresini milisaniye cinsinden belirtir. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Medyanın ilk solma süresini milisaniye cinsinden belirtir. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Medyanın bitiş solma süresini milisaniye cinsinden belirtir. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Medyanın bitiş solma süresini milisaniye cinsinden belirtir. |
| [getVolumeValue()](#getVolumeValue--) | Ses düzeyini yüzde olarak döndürür veya ayarlar. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Ses düzeyini yüzde olarak döndürür veya ayarlar. |
| [getTrimFromStart()](#getTrimFromStart--) | Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [getCaptionTracks()](#getCaptionTracks--) | Ses çerçevesiyle ilişkili kapalı altyazı koleksiyonunu alır. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Başlangıç iz parçası indeksini döndürür veya ayarlar Okuma/yazma  int .

**Döndürür:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Başlangıç iz parçası indeksini döndürür veya ayarlar Okuma/yazma  int .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Başlangıç iz parçası zamanını döndürür veya ayarlar Okuma/yazma  int .

**Döndürür:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Başlangıç iz parçası zamanını döndürür veya ayarlar Okuma/yazma  int .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Son iz parçası indeksini döndürür veya ayarlar Okuma/yazma  int .

**Döndürür:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Son iz parçası indeksini döndürür veya ayarlar Okuma/yazma  int .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Son iz parçası zamanını döndürür veya ayarlar Okuma/yazma  int .

**Döndürür:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Son iz parçası zamanını döndürür veya ayarlar Okuma/yazma  int .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Ses düzeyini döndürür veya ayarlar Okuma/yazma [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Döndürür:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Ses düzeyini döndürür veya ayarlar Okuma/yazma [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Ses oynatma modunu döndürür veya ayarlar Okuma/yazma [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Döndürür:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Ses oynatma modunu döndürür veya ayarlar Okuma/yazma [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Bir AudioFrame'in gizli olup olmadığını belirler Okuma/yazma  boolean .

**Döndürür:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Bir AudioFrame'in gizli olup olmadığını belirler Okuma/yazma  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Sesin döngüde olup olmadığını belirler Okuma/yazma  boolean .

**Döndürür:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Sesin döngüde olup olmadığını belirler Okuma/yazma  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Sesin slaytlar arasında çalınıp çalınmadığını belirler Okuma/yazma  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio Frame ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio'yu slaytlar arasında çalacak şekilde ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio'yu oynatıldıktan sonra otomatik olarak başa saracak şekilde ayarla
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
public final void setPlayAcrossSlides(boolean value)
```

Sesin slaytlar arasında çalınıp çalınmadığını belirler Okuma/yazma  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio Frame ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio'yu slaytlar arasında çalacak şekilde ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio'yu oynatıldıktan sonra otomatik olarak başa saracak şekilde ayarla
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
public final boolean getRewindAudio()
```

Sesin çalındıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler Okuma/yazma  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio Frame ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio'yu slaytlar arasında çalacak şekilde ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio'yu oynatıldıktan sonra otomatik olarak başa saracak şekilde ayarla
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
public final void setRewindAudio(boolean value)
```

Sesin çalındıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler Okuma/yazma  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Audio Frame ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Audio'yu slaytlar arasında çalacak şekilde ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Audio'yu oynatıldıktan sonra otomatik olarak başa saracak şekilde ayarla
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
public final boolean getEmbedded()
```

Sesin bir sunuma gömülü olup olmadığını belirler Salt okunur  boolean .

**Döndürür:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Bir AudioFrame'e bağlı bir ses dosyasının adını döndürür veya ayarlar Okuma/yazma String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Bir AudioFrame'e bağlı bir ses dosyasının adını döndürür veya ayarlar Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Gömülü ses nesnesini döndürür veya ayarlar Okuma/yazma [IAudio](../../com.aspose.slides/iaudio).

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Gömülü ses nesnesini döndürür veya ayarlar Okuma/yazma [IAudio](../../com.aspose.slides/iaudio).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Medyanın ilk solma süresini milisaniye cinsinden belirtir Okuma/yazma float.

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
public final void setFadeInDuration(float value)
```

Medyanın ilk solma süresini milisaniye cinsinden belirtir Okuma/yazma float.

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
public final float getFadeOutDuration()
```

Medyanın bitiş solma süresini milisaniye cinsinden belirtir Okuma/yazma float.

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
public final void setFadeOutDuration(float value)
```

Medyanın bitiş solma süresini milisaniye cinsinden belirtir Okuma/yazma float.

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
public final float getVolumeValue()
```

Ses düzeyini yüzde olarak döndürür veya ayarlar Okuma/yazma float.

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
public final void setVolumeValue(float value)
```

Ses düzeyini yüzde olarak döndürür veya ayarlar Okuma/yazma float.

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
public final float getTrimFromStart()
```

Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir Okuma/yazma float.

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
public final void setTrimFromStart(float value)
```

Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir Okuma/yazma float.

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
public final float getTrimFromEnd()
```

Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir Okuma/yazma float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Bitiş kırpma süresini 2 saniye olarak ayarla
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir Okuma/yazma float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Bitiş kırpma süresini 2 saniye olarak ayarla
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
public final ICaptionsCollection getCaptionTracks()
```

Ses çerçevesiyle ilişkili kapalı altyazı koleksiyonunu alır. Bu özellik salt okunur olup tüm altyazı izlerini içeren bir [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) döndürür.

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
>              // Caption izinin ikili verisini .vtt dosyası olarak kaydet
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


**Döndürür:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)