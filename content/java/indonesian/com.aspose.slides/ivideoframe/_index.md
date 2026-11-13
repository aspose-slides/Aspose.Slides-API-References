---
title: IVideoFrame
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili klip video pada slide.
type: docs
url: /id/com.aspose.slides/ivideoframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Mewakili klip video pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Menentukan apakah video secara otomatis diputar ulang ke awal begitu film selesai diputar. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Menentukan apakah video secara otomatis diputar ulang ke awal begitu film selesai diputar. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Menentukan apakah video diulang. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Menentukan apakah video diulang. |
| [getHideAtShowing()](#getHideAtShowing--) | Menentukan apakah VideoFrame disembunyikan. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Menentukan apakah VideoFrame disembunyikan. |
| [getVolume()](#getVolume--) | Mengembalikan atau mengatur volume audio. |
| [setVolume(int value)](#setVolume-int-) | Mengembalikan atau mengatur volume audio. |
| [getVolumeValue()](#getVolumeValue--) | Mengembalikan atau mengatur volume video secara persentase. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Mengembalikan atau mengatur volume video secara persentase. |
| [getPlayMode()](#getPlayMode--) | Mengembalikan atau mengatur mode pemutaran video. |
| [setPlayMode(int value)](#setPlayMode-int-) | Mengembalikan atau mengatur mode pemutaran video. |
| [getFullScreenMode()](#getFullScreenMode--) | Menentukan apakah video ditampilkan dalam mode layar penuh. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Menentukan apakah video ditampilkan dalam mode layar penuh. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan atau mengatur nama berkas video yang ditautkan ke VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan atau mengatur nama berkas video yang ditautkan ke VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Mengembalikan atau mengatur objek video yang disematkan. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Mengembalikan atau mengatur objek video yang disematkan. |
| [getTrimFromStart()](#getTrimFromStart--) | Potong awal [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Potong awal [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Potong akhir [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Potong akhir [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Mendapatkan koleksi caption tertutup yang terkait dengan frame audio. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Menentukan apakah video secara otomatis diputar ulang ke awal begitu film selesai diputar. **Baca/tulis** boolean.

**Mengembalikan:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Menentukan apakah video secara otomatis diputar ulang ke awal begitu film selesai diputar. **Baca/tulis** boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Menentukan apakah video diulang. **Baca/tulis** boolean.

**Mengembalikan:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Menentukan apakah video diulang. **Baca/tulis** boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Menentukan apakah VideoFrame disembunyikan. **Baca/tulis** boolean.

**Mengembalikan:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Menentukan apakah VideoFrame disembunyikan. **Baca/tulis** boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Mengembalikan atau mengatur volume audio. **Baca/tulis** [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Mengembalikan:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Mengembalikan atau mengatur volume audio. **Baca/tulis** [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Mengembalikan atau mengatur volume video secara persentase. Nilai diungkapkan sebagai persentase dari 0 hingga 100. Gunakan properti ini untuk membaca atau mengatur nilai volume yang lebih tepat daripada level yang sudah ditentukan melalui properti Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). **Baca/tulis** float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Baca volume tepat saat ini dan atur menjadi 75,5 persen.
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
public abstract void setVolumeValue(float value)
```

Mengembalikan atau mengatur volume video secara persentase. Nilai diungkapkan sebagai persentase dari 0 hingga 100. Gunakan properti ini untuk membaca atau mengatur nilai volume yang lebih tepat daripada level yang sudah ditentukan melalui properti Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). **Baca/tulis** float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Baca volume tepat saat ini dan atur menjadi 75,5 persen.
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
public abstract int getPlayMode()
```

Mengembalikan atau mengatur mode pemutaran video. **Baca/tulis** [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Mengembalikan:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Mengembalikan atau mengatur mode pemutaran video. **Baca/tulis** [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Menentukan apakah video ditampilkan dalam mode layar penuh. **Baca/tulis** boolean.

**Mengembalikan:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Menentukan apakah video ditampilkan dalam mode layar penuh. **Baca/tulis** boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Mengembalikan atau mengatur nama berkas video yang ditautkan ke VideoFrame. **Baca/tulis** String.

**Mengembalikan:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Mengembalikan atau mengatur nama berkas video yang ditautkan ke VideoFrame. **Baca/tulis** String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Mengembalikan atau mengatur objek video yang disematkan. **Baca/tulis** [IVideo](../../com.aspose.slides/ivideo).

**Mengembalikan:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Mengembalikan atau mengatur objek video yang disematkan. **Baca/tulis** [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Potong awal [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //atur waktu pemotongan mulai 1 detik
>      videoFrame.setTrimFromStart(1000f);
>      //atur waktu pemotongan akhir 2 detik
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Potong awal [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //atur waktu pemotongan mulai 1 detik
>      videoFrame.setTrimFromStart(1000f);
>      //atur waktu pemotongan akhir 2 detik
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
public abstract float getTrimFromEnd()
```

Potong akhir [ms]

**Mengembalikan:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Potong akhir [ms]

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Mendapatkan koleksi caption tertutup yang terkait dengan frame audio. Properti ini hanya baca dan mengembalikan [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) yang berisi semua trek caption.

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