---
title: IVideoFrame
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir slaytta video klibi temsil eder.
type: docs
url: /tr/com.aspose.slides/ivideoframe/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Bir slayt üzerindeki video klibi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bir video, film oynatımı bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bir video, film oynatımı bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bir videonun döngüde olup olmadığını belirler. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bir videonun döngüde olup olmadığını belirler. |
| [getHideAtShowing()](#getHideAtShowing--) | Bir VideoFrame'in gizli olup olmadığını belirler. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bir VideoFrame'in gizli olup olmadığını belirler. |
| [getVolume()](#getVolume--) | Ses seviyesini döndürür veya ayarlar. |
| [setVolume(int value)](#setVolume-int-) | Ses seviyesini döndürür veya ayarlar. |
| [getPlayMode()](#getPlayMode--) | Video oynatma modunu döndürür veya ayarlar. |
| [setPlayMode(int value)](#setPlayMode-int-) | Video oynatma modunu döndürür veya ayarlar. |
| [getFullScreenMode()](#getFullScreenMode--) | Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. |
| [getLinkPathLong()](#getLinkPathLong--) | Bir VideoFrame'e bağlanan video dosyasının adını döndürür veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bir VideoFrame'e bağlanan video dosyasının adını döndürür veya ayarlar. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Gömülü video nesnesini döndürür veya ayarlar. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Gömülü video nesnesini döndürür veya ayarlar. |
| [getTrimFromStart()](#getTrimFromStart--) | Başlangıç kesme [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Başlangıç kesme [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Bitiş kesme [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Bitiş kesme [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Ses çerçevesi ile ilişkili kapalı altyazıların koleksiyonunu alır. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Bir video, film oynatımı bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Bir video, film oynatımı bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bir videonun döngüde olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bir videonun döngüde olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bir VideoFrame'in gizli olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bir VideoFrame'in gizli olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Ses seviyesini döndürür veya ayarlar. Okunur/yazılabilir [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Döndürür:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Ses seviyesini döndürür veya ayarlar. Okunur/yazılabilir [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Video oynatma modunu döndürür veya ayarlar. Okunur/yazılabilir [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Döndürür:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Video oynatma modunu döndürür veya ayarlar. Okunur/yazılabilir [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Bir VideoFrame'e bağlanan video dosyasının adını döndürür veya ayarlar. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Bir VideoFrame'e bağlanan video dosyasının adını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Gömülü video nesnesini döndürür veya ayarlar. Okunur/yazılabilir [IVideo](../../com.aspose.slides/ivideo).

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Gömülü video nesnesini döndürür veya ayarlar. Okunur/yazılabilir [IVideo](../../com.aspose.slides/ivideo).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Başlangıç kesme [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //kırpma başlangıç zamanını 1 saniye olarak ayarla
>      videoFrame.setTrimFromStart(1000f);
>      //kırpma bitiş zamanını 2 saniye olarak ayarla
>      videoFrame.setTrimFromEnd(2000f);
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

Başlangıç kesme [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //kırpma başlangıç zamanını 1 saniye olarak ayarla
>      videoFrame.setTrimFromStart(1000f);
>      //kırpma bitiş zamanını 2 saniye olarak ayarla
>      videoFrame.setTrimFromEnd(2000f);
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

Bitiş kesme [ms]

**Döndürür:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Bitiş kesme [ms]

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Ses çerçevesi ile ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik salt okunur ve tüm altyazı izlerini içeren bir [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) döndürür.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (!(shape instanceof IVideoFrame))
>              continue;
>          IVideoFrame videoFrame = (IVideoFrame) shape;
>          for (ICaptions captionTrack : videoFrame.getCaptionTracks())
>          {
>              // Altyazıların ikili verisini çıkarır ve dosyaya kaydeder
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)