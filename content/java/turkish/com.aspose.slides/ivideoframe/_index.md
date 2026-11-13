---
title: IVideoFrame
second_title: Aspose.Slides için Java API Referansı
description: Bir slayttaki video klibi temsil eder.
type: docs
url: /tr/com.aspose.slides/ivideoframe/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Bir slayttaki video klibi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bir videonun film bitince otomatik olarak başa sarılıp sarılmayacağını belirler. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bir videonun film bitince otomatik olarak başa sarılıp sarılmayacağını belirler. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bir videonun döngüde olup olmadığını belirler. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bir videonun döngüde olup olmadığını belirler. |
| [getHideAtShowing()](#getHideAtShowing--) | Bir VideoFrame'in gizli olup olmadığını belirler. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bir VideoFrame'in gizli olup olmadığını belirler. |
| [getVolume()](#getVolume--) | Ses seviyesini döndürür veya ayarlar. |
| [setVolume(int value)](#setVolume-int-) | Ses seviyesini döndürür veya ayarlar. |
| [getVolumeValue()](#getVolumeValue--) | Tam video seviyesini yüzde olarak döndürür veya ayarlar. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Tam video seviyesini yüzde olarak döndürür veya ayarlar. |
| [getPlayMode()](#getPlayMode--) | Video oynatma modunu döndürür veya ayarlar. |
| [setPlayMode(int value)](#setPlayMode-int-) | Video oynatma modunu döndürür veya ayarlar. |
| [getFullScreenMode()](#getFullScreenMode--) | Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. |
| [getLinkPathLong()](#getLinkPathLong--) | Bir VideoFrame'e bağlı video dosyasının adını döndürür veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bir VideoFrame'e bağlı video dosyasının adını döndürür veya ayarlar. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Gömülü video nesnesini döndürür veya ayarlar. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Gömülü video nesnesini döndürür veya ayarlar. |
| [getTrimFromStart()](#getTrimFromStart--) | Başlangıç kırpma [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Başlangıç kırpma [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Bitiş kırpma [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Bitiş kırpma [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Bir videonun film bitince otomatik olarak başa sarılıp sarılmayacağını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Bir videonun film bitince otomatik olarak başa sarılıp sarılmayacağını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bir videonun döngüde olup olmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bir videonun döngüde olup olmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bir VideoFrame'in gizli olup olmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bir VideoFrame'in gizli olup olmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Ses seviyesini döndürür veya ayarlar. Okuma/yazma [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Döndürür:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Ses seviyesini döndürür veya ayarlar. Okuma/yazma [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Tam video seviyesini yüzde olarak döndürür veya ayarlar. Değer, %0 ile %100 arasında yüzde olarak ifade edilir. Bu özelliği, Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) özelliği aracılığıyla mevcut önceden tanımlı seviyelerden daha hassas ses değerlerini okumak veya ayarlamak için kullanın. Okuma/yazma float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Mevcut tam ses seviyesini okuyun ve %75,5'e ayarlayın.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
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

Tam video seviyesini yüzde olarak döndürür veya ayarlar. Değer, %0 ile %100 arasında yüzde olarak ifade edilir. Bu özelliği, Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) özelliği aracılığıyla mevcut önceden tanımlı seviyelerden daha hassas ses değerlerini okumak veya ayarlamak için kullanın. Okuma/yazma float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Mevcut tam ses seviyesini okuyun ve %75,5'e ayarlayın.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Video oynatma modunu döndürür veya ayarlar. Okuma/yazma [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Döndürür:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Video oynatma modunu döndürür veya ayarlar. Okuma/yazma [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Bir VideoFrame'e bağlı video dosyasının adını döndürür veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Bir VideoFrame'e bağlı video dosyasının adını döndürür veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Gömülü video nesnesini döndürür veya ayarlar. Okuma/yazma [IVideo](../../com.aspose.slides/ivideo).

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Gömülü video nesnesini döndürür veya ayarlar. Okuma/yazma [IVideo](../../com.aspose.slides/ivideo).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Başlangıç kırpma [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
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

Başlangıç kırpma [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
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

Bitiş kırpma [ms]

**Döndürür:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Bitiş kırpma [ms]

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik yalnızca okunabilir ve tüm altyazı izlerini içeren bir [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) döndürür.

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
>              // Altyazıların ikili verilerini çıkarır ve dosyaya kaydeder
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