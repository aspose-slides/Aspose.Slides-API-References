---
title: VideoFrame
second_title: Aspose.Slides for Java API Referansı
description: Bir slaytta video klibi temsil eder.
type: docs
url: /tr/com.aspose.slides/videoframe/
---
**Miras:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Bir slaytta video klibi temsil eder.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bir video, film oynatması bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bir video, film oynatması bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bir videonun döngüde olup olmadığını belirler. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bir videonun döngüde olup olmadığını belirler. |
| [getHideAtShowing()](#getHideAtShowing--) | Bir VideoFrame'in gizli olup olmadığını belirler. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bir VideoFrame'in gizli olup olmadığını belirler. |
| [getVolume()](#getVolume--) | Ses seviyesini alır veya ayarlar. |
| [setVolume(int value)](#setVolume-int-) | Ses seviyesini alır veya ayarlar. |
| [getVolumeValue()](#getVolumeValue--) | Videonun tam ses seviyesini yüzde olarak alır veya ayarlar. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Videonun tam ses seviyesini yüzde olarak alır veya ayarlar. |
| [getPlayMode()](#getPlayMode--) | Video oynatma modunu alır veya ayarlar. |
| [setPlayMode(int value)](#setPlayMode-int-) | Video oynatma modunu alır veya ayarlar. |
| [getFullScreenMode()](#getFullScreenMode--) | Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame'e bağlanan bir video dosyasının adını alır veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame'e bağlanan bir video dosyasının adını alır veya ayarlar. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Gömülü video nesnesini alır veya ayarlar. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Gömülü video nesnesini alır veya ayarlar. |
| [getTrimFromStart()](#getTrimFromStart--) | Başlangıcı kırp [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Başlangıcı kırp [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Bitişi kırp [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Bitişi kırp [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Video çerçevesiyle ilişkili kapalı başlıkların koleksiyonunu alır. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Bir video, film oynatması bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Bir video, film oynatması bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Bir videonun döngüde olup olmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Bir videonun döngüde olup olmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Bir VideoFrame'in gizli olup olmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Bir VideoFrame'in gizli olup olmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Ses seviyesini alır veya ayarlar. Okuma/yazma [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Döndürür:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Ses seviyesini alır veya ayarlar. Okuma/yazma [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Videonun tam ses seviyesini yüzde olarak alır veya ayarlar. Değer 0 ile 100 arasında yüzde olarak ifade edilir. Bu özelliği, \#getVolume.getVolume/\#setVolume(int).setVolume(int) özelliği tarafından sağlanan önceden tanımlı seviyelerden daha hassas ses değerlerini okumak veya ayarlamak için kullanın. Okuma/yazma float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Mevcut tam ses seviyesini okuyun ve yüzde 75.5 olarak ayarlayın.
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
public final void setVolumeValue(float value)
```

Videonun tam ses seviyesini yüzde olarak alır veya ayarlar. Değer 0 ile 100 arasında yüzde olarak ifade edilir. Bu özelliği, \#getVolume.getVolume/\#setVolume(int).setVolume(int) özelliği tarafından sağlanan önceden tanımlı seviyelerden daha hassas ses değerlerini okumak veya ayarlamak için kullanın. Okuma/yazma float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Mevcut tam ses seviyesini okuyun ve yüzde 75.5 olarak ayarlayın.
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
public final int getPlayMode()
```

Video oynatma modunu alır veya ayarlar. Okuma/yazma [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Döndürür:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Video oynatma modunu alır veya ayarlar. Okuma/yazma [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

VideoFrame'e bağlanan bir video dosyasının adını alır veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

VideoFrame'e bağlanan bir video dosyasının adını alır veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Gömülü video nesnesini alır veya ayarlar. Okuma/yazma [IVideo](../../com.aspose.slides/ivideo).

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Gömülü video nesnesini alır veya ayarlar. Okuma/yazma [IVideo](../../com.aspose.slides/ivideo).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Başlangıcı kırp [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //kırpma başlangıç süresini 1 saniye olarak ayarla
>      videoFrame.setTrimFromStart(1000f);
>      //kırpma bitiş süresini 2 saniye olarak ayarla
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

Başlangıcı kırp [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //kırpma başlangıç süresini 1 saniye olarak ayarla
>      videoFrame.setTrimFromStart(1000f);
>      //kırpma bitiş süresini 2 saniye olarak ayarla
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

Bitişi kırp [ms]

**Döndürür:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Bitişi kırp [ms]

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Video çerçevesiyle ilişkili kapalı başlıkların koleksiyonunu alır. Bu özellik yalnızca okuma amaçlıdır ve tüm altyazı izlerini içeren bir [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) döndürür.

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
>              // Altyazı ikili verisini çıkarır ve dosyaya kaydeder
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