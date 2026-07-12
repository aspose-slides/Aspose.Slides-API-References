---
title: VideoFrame
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir slayttaki video klibi temsil eder.
type: docs
url: /tr/com.aspose.slides/videoframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Bir slayttaki video klibi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bir video, film çalması bittiğinde otomatik olarak başlangıca geri sarılıp sarılmayacağını belirler. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bir video, film çalması bittiğinde otomatik olarak başlangıca geri sarılıp sarılmayacağını belirler. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bir videonun döngüde olup olmadığını belirler. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bir videonun döngüde olup olmadığını belirler. |
| [getHideAtShowing()](#getHideAtShowing--) | Bir VideoFrame'in gizli olup olmadığını belirler. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bir VideoFrame'in gizli olup olmadığını belirler. |
| [getVolume()](#getVolume--) | Ses seviyesini döndürür veya ayarlar. |
| [setVolume(int value)](#setVolume-int-) | Ses seviyesini döndürür veya ayarlar. |
| [getPlayMode()](#getPlayMode--) | Video oynatma modunu döndürür veya ayarlar. |
| [setPlayMode(int value)](#setPlayMode-int-) | Video oynatma modunu döndürür veya ayarlar. |
| [getFullScreenMode()](#getFullScreenMode--) | Bir videonun tam ekran modunda gösterilip gösterilmediğini belirler. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bir videonun tam ekran modunda gösterilip gösterilmediğini belirler. |
| [getLinkPathLong()](#getLinkPathLong--) | Bir VideoFrame'e bağlı bir video dosyasının adını döndürür veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bir VideoFrame'e bağlı bir video dosyasının adını döndürür veya ayarlar. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Gömülü video nesnesini döndürür veya ayarlar. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Gömülü video nesnesini döndürür veya ayarlar. |
| [getTrimFromStart()](#getTrimFromStart--) | Başlangıç kırpma [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Başlangıç kırpma [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Bitiş kırpma [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Bitiş kırpma [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Video çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Bir video, film çalması bittiğinde otomatik olarak başlangıca geri sarılıp sarılmayacağını belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Bir video, film çalması bittiğinde otomatik olarak başlangıca geri sarılıp sarılmayacağını belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Bir videonun döngüde olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Bir videonun döngüde olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Bir VideoFrame'in gizli olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Bir VideoFrame'in gizli olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Ses seviyesini döndürür veya ayarlar. Okunabilir/yazılabilir [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Döndürür:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Ses seviyesini döndürür veya ayarlar. Okunabilir/yazılabilir [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Video oynatma modunu döndürür veya ayarlar. Okunabilir/yazılabilir [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Döndürür:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Video oynatma modunu döndürür veya ayarlar. Okunabilir/yazılabilir [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Bir videonun tam ekran modunda gösterilip gösterilmediğini belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Bir videonun tam ekran modunda gösterilip gösterilmediğini belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Bir VideoFrame'e bağlı bir video dosyasının adını döndürür veya ayarlar. Okunabilir/yazılabilir String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Bir VideoFrame'e bağlı bir video dosyasının adını döndürür veya ayarlar. Okunabilir/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Gömülü video nesnesini döndürür veya ayarlar. Okunabilir/yazılabilir [IVideo](../../com.aspose.slides/ivideo).

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Gömülü video nesnesini döndürür veya ayarlar. Okunabilir/yazılabilir [IVideo](../../com.aspose.slides/ivideo).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Başlangıç kırpma [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set kırpma başlangıç zamanını 1sn
>      videoFrame.setTrimFromStart(1000f);
>      //set kırpma bitiş zamanını 2sn
>      videoFrame.setTrimFromEnd(2000f);
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

Başlangıç kırpma [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //kırpma başlangıç zamanını 1sn ayarla
>      videoFrame.setTrimFromStart(1000f);
>      //kırpma bitiş zamanını 2sn ayarla
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
public final float getTrimFromEnd()
```

Bitiş kırpma [ms]

**Döndürür:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Bitiş kırpma [ms]

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Video çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik sadece okuma amaçlıdır ve tüm altyazı izlerini içeren bir [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) döndürür.

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
>              // Altyazıların ikili verilerini çıkartır ve dosyaya kaydeder
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