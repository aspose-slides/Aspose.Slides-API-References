---
title: VideoFrame
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili klip video pada slide.
type: docs
url: /id/com.aspose.slides/videoframe/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Mewakili klip video pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Menentukan apakah video secara otomatis diputar ulang ke awal segera setelah film selesai diputar. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Menentukan apakah video secara otomatis diputar ulang ke awal segera setelah film selesai diputar. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Menentukan apakah video diputar berulang. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Menentukan apakah video diputar berulang. |
| [getHideAtShowing()](#getHideAtShowing--) | Menentukan apakah VideoFrame disembunyikan. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Menentukan apakah VideoFrame disembunyikan. |
| [getVolume()](#getVolume--) | Mengembalikan atau mengatur volume audio. |
| [setVolume(int value)](#setVolume-int-) | Mengembalikan atau mengatur volume audio. |
| [getVolumeValue()](#getVolumeValue--) | Mengembalikan atau mengatur volume video yang tepat sebagai persentase. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Mengembalikan atau mengatur volume video yang tepat sebagai persentase. |
| [getPlayMode()](#getPlayMode--) | Mengembalikan atau mengatur mode pemutaran video. |
| [setPlayMode(int value)](#setPlayMode-int-) | Mengembalikan atau mengatur mode pemutaran video. |
| [getFullScreenMode()](#getFullScreenMode--) | Menentukan apakah video ditampilkan dalam mode layar penuh. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Menentukan apakah video ditampilkan dalam mode layar penuh. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan atau mengatur nama berkas video yang terhubung ke VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan atau mengatur nama berkas video yang terhubung ke VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Mengembalikan atau mengatur objek video tersemat. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Mengembalikan atau mengatur objek video tersemat. |
| [getTrimFromStart()](#getTrimFromStart--) | Pemotongan awal [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Pemotongan awal [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Pemotongan akhir [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Pemotongan akhir [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Mendapatkan koleksi caption tertutup yang terkait dengan video frame. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Menentukan apakah video secara otomatis diputar ulang ke awal segera setelah film selesai diputar. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Menentukan apakah video secara otomatis diputar ulang ke awal segera setelah film selesai diputar. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Menentukan apakah video diputar berulang. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Menentukan apakah video diputar berulang. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Menentukan apakah VideoFrame disembunyikan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Menentukan apakah VideoFrame disembunyikan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Mengembalikan atau mengatur volume audio. Baca/tulis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Mengembalikan:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Mengembalikan atau mengatur volume audio. Baca/tulis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Mengembalikan atau mengatur volume video yang tepat sebagai persentase. Nilai diungkapkan sebagai persentase dari 0 hingga 100. Gunakan properti ini untuk membaca atau mengatur nilai volume yang lebih presisi daripada tingkat yang telah ditentukan tersedia melalui properti \#getVolume.getVolume/\#setVolume(int).setVolume(int). Baca/tulis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Baca volume tepat saat ini dan setel ke 75,5 persen.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Mengembalikan atau mengatur volume video yang tepat sebagai persentase. Nilai diungkapkan sebagai persentase dari 0 hingga 100. Gunakan properti ini untuk membaca atau mengatur nilai volume yang lebih presisi daripada tingkat yang telah ditentukan tersedia melalui properti \#getVolume.getVolume/\#setVolume(int).setVolume(int). Baca/tulis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Baca volume tepat saat ini dan setel ke 75,5 persen.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Mengembalikan atau mengatur mode pemutaran video. Baca/tulis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Mengembalikan:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Mengembalikan atau mengatur mode pemutaran video. Baca/tulis [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Menentukan apakah video ditampilkan dalam mode layar penuh. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Menentukan apakah video ditampilkan dalam mode layar penuh. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Mengembalikan atau mengatur nama berkas video yang terhubung ke VideoFrame. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Mengembalikan atau mengatur nama berkas video yang terhubung ke VideoFrame. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Mengembalikan atau mengatur objek video tersemat. Baca/tulis [IVideo](../../com.aspose.slides/ivideo).

**Mengembalikan:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Mengembalikan atau mengatur objek video tersemat. Baca/tulis [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Pemotongan awal [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //atur waktu pemangkasan mulai 1 detik
>      videoFrame.setTrimFromStart(1000f);
>      //atur waktu pemangkasan akhir 2 detik
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Pemotongan awal [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //atur waktu pemangkasan mulai 1 detik
>      videoFrame.setTrimFromStart(1000f);
>      //atur waktu pemangkasan akhir 2 detik
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Pemotongan akhir [ms]

**Mengembalikan:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Pemotongan akhir [ms]

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Mendapatkan koleksi caption tertutup yang terkait dengan video frame. Properti ini bersifat baca-saja dan mengembalikan sebuah [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) yang berisi semua trek caption.

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
>              // Mengekstrak data biner caption dan menyimpannya ke file
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)