---
title: IAudioFrame
second_title: Aspose.Slides for Java API Referansı
description: Bir slayttaki ses klibini temsil eder.
type: docs
url: /tr/com.aspose.slides/iaudioframe/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Bir slayttaki ses klibini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Başlangıç iz indeksini döndürür veya ayarlar. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Başlangıç iz indeksini döndürür veya ayarlar. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Başlangıç iz zamanını döndürür veya ayarlar. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Başlangıç iz zamanını döndürür veya ayarlar. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Son iz indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Son iz indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Son iz zamanını döndürür veya ayarlar. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Son iz zamanını döndürür veya ayarlar. |
| [getVolume()](#getVolume--) | Ses seviyesini döndürür veya ayarlar. |
| [setVolume(int value)](#setVolume-int-) | Ses seviyesini döndürür veya ayarlar. |
| [getPlayMode()](#getPlayMode--) | Ses oynatma modunu döndürür veya ayarlar. |
| [setPlayMode(int value)](#setPlayMode-int-) | Ses oynatma modunu döndürür veya ayarlar. |
| [getHideAtShowing()](#getHideAtShowing--) | Bir AudioFrame'in gizli olup olmadığını belirler. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bir AudioFrame'in gizli olup olmadığını belirler. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bir sesin döngüde olup olmadığını belirler. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bir sesin döngüde olup olmadığını belirler. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Bir sesin slaytlar boyunca çalıp çalmadığını belirler. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Bir sesin slaytlar boyunca çalıp çalmadığını belirler. |
| [getRewindAudio()](#getRewindAudio--) | Bir sesin çaldıktan sonra otomatik olarak başa sarılıp sarılmadığını belirler. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Bir sesin çaldıktan sonra otomatik olarak başa sarılıp sarılmadığını belirler. |
| [getEmbedded()](#getEmbedded--) | Bir sesin sunuma gömülü olup olmadığını belirler. |
| [getLinkPathLong()](#getLinkPathLong--) | Bir AudioFrame'e bağlanan ses dosyasının adını döndürür veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bir AudioFrame'e bağlanan ses dosyasının adını döndürür veya ayarlar. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Gömülü ses nesnesini döndürür veya ayarlar. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Gömülü ses nesnesini döndürür veya ayarlar. |
| [getFadeInDuration()](#getFadeInDuration--) | Ortamın başlangıçta solma süresini milisaniye cinsinden belirtir. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Ortamın başlangıçta solma süresini milisaniye cinsinden belirtir. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Ortamın son solma süresini milisaniye cinsinden belirtir. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Ortamın son solma süresini milisaniye cinsinden belirtir. |
| [getVolumeValue()](#getVolumeValue--) | Ses seviyesini yüzde olarak döndürür veya ayarlar. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Ses seviyesini yüzde olarak döndürür veya ayarlar. |
| [getTrimFromStart()](#getTrimFromStart--) | Oynatma sırasında medya başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Oynatma sırasında medya başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. |
| [getCaptionTracks()](#getCaptionTracks--) | Ses çerçevesiyle ilişkili kapalı altyazı koleksiyonunu alır. |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Başlangıç iz indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Döndürür:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Başlangıç iz indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Başlangıç iz zamanını döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Döndürür:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Başlangıç iz zamanını döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Son iz indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Döndürür:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Son iz indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Son iz zamanını döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Döndürür:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Son iz zamanını döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Ses seviyesini döndürür veya ayarlar. Okunabilir/Yazılabilir [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Döndürür:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Ses seviyesini döndürür veya ayarlar. Okunabilir/Yazılabilir [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Ses oynatma modunu döndürür veya ayarlar. Okunabilir/Yazılabilir [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Döndürür:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Ses oynatma modunu döndürür veya ayarlar. Okunabilir/Yazılabilir [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bir AudioFrame'in gizli olup olmadığını belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bir AudioFrame'in gizli olup olmadığını belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bir sesin döngüde olup olmadığını belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bir sesin döngüde olup olmadığını belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Bir sesin slaytlar boyunca çalıp çalmadığını belirler. Okunabilir/Yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ses Çerçevesi Ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Sesin slaytlar boyunca çalmasını ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Sesin çalındıktan sonra otomatik olarak başa sarılmasını ayarla
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

Bir sesin slaytlar boyunca çalıp çalmadığını belirler. Okunabilir/Yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ses Çerçevesi Ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Sesin slaytlar boyunca çalmasını ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Sesin çalındıktan sonra otomatik olarak başa sarılmasını ayarla
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

Bir sesin çaldıktan sonra otomatik olarak başa sarılıp sarılmadığını belirler. Okunabilir/Yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ses Çerçevesi Ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Sesin slaytlar boyunca çalmasını ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Sesin çalındıktan sonra otomatik olarak başa sarılmasını ayarla
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

Bir sesin çaldıktan sonra otomatik olarak başa sarılıp sarılmadığını belirler. Okunabilir/Yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ses Çerçevesi Ekle
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Sesin slaytlar boyunca çalmasını ayarla
>       audioFrame.setPlayAcrossSlides(true);
>       // Sesin çalındıktan sonra otomatik olarak başa sarılmasını ayarla
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

Bir sesin sunuma gömülü olup olmadığını belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Bir AudioFrame'e bağlanan ses dosyasının adını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Bir AudioFrame'e bağlanan ses dosyasının adını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Gömülü ses nesnesini döndürür veya ayarlar. Okunabilir/Yazılabilir [IAudio](../../com.aspose.slides/iaudio).

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Gömülü ses nesnesini döndürür veya ayarlar. Okunabilir/Yazılabilir [IAudio](../../com.aspose.slides/iaudio).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Ortamın başlangıçta solma süresini milisaniye cinsinden belirtir. Okunabilir/Yazılabilir float.

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

Ortamın başlangıçta solma süresini milisaniye cinsinden belirtir. Okunabilir/Yazılabilir float.

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

Ortamın son solma süresini milisaniye cinsinden belirtir. Okunabilir/Yazılabilir float.

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

Ortamın son solma süresini milisaniye cinsinden belirtir. Okunabilir/Yazılabilir float.

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

Ses seviyesini yüzde olarak döndürür veya ayarlar. Okunabilir/Yazılabilir float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ses hacmini %85 olarak ayarla
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

Ses seviyesini yüzde olarak döndürür veya ayarlar. Okunabilir/Yazılabilir float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ses hacmini %85 olarak ayarla
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

Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. Okunabilir/Yazılabilir float.

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

Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye cinsinden belirtir. Okunabilir/Yazılabilir float.

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

Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. Okunabilir/Yazılabilir float.

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

Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. Okunabilir/Yazılabilir float.

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

Ses çerçevesiyle ilişkili kapalı altyazı koleksiyonunu alır. Bu özellik yalnızca okunabilir ve tüm altyazı izlerini içeren bir [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) döndürür.

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
>             // Altyazı izinin ikili verisini bir .vtt dosyası olarak kaydet
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