---
title: IAudioFrame
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili klip audio pada slide.
type: docs
url: /id/com.aspose.slides/iaudioframe/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Mewakili klip audio pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Mengembalikan atau mengatur indeks trek mulai. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Mengembalikan atau mengatur indeks trek mulai. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Mengembalikan atau mengatur waktu trek mulai. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Mengembalikan atau mengatur waktu trek mulai. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Mengembalikan atau mengatur indeks trek terakhir Baca/tulis int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Mengembalikan atau mengatur indeks trek terakhir Baca/tulis int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Mengembalikan atau mengatur waktu trek terakhir. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Mengembalikan atau mengatur waktu trek terakhir. |
| [getVolume()](#getVolume--) | Mengembalikan atau mengatur volume audio. |
| [setVolume(int value)](#setVolume-int-) | Mengembalikan atau mengatur volume audio. |
| [getPlayMode()](#getPlayMode--) | Mengembalikan atau mengatur mode pemutaran audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Mengembalikan atau mengatur mode pemutaran audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Menentukan apakah AudioFrame disembunyikan. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Menentukan apakah AudioFrame disembunyikan. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Menentukan apakah audio diputar berulang. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Menentukan apakah audio diputar berulang. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Menentukan apakah audio diputar di seluruh slide. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Menentukan apakah audio diputar di seluruh slide. |
| [getRewindAudio()](#getRewindAudio--) | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. |
| [getEmbedded()](#getEmbedded--) | Menentukan apakah suara disematkan ke presentasi. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan atau mengatur nama file audio yang ditautkan ke AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan atau mengatur nama file audio yang ditautkan ke AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Mengembalikan atau mengatur objek audio yang disematkan. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Mengembalikan atau mengatur objek audio yang disematkan. |
| [getFadeInDuration()](#getFadeInDuration--) | Menentukan durasi waktu untuk fade-in awal media dalam milidetik. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Menentukan durasi waktu untuk fade-in awal media dalam milidetik. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. |
| [getVolumeValue()](#getVolumeValue--) | Mengembalikan atau mengatur volume audio dalam persen. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Mengembalikan atau mengatur volume audio dalam persen. |
| [getTrimFromStart()](#getTrimFromStart--) | Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. |
| [getCaptionTracks()](#getCaptionTracks--) | Mendapatkan koleksi caption tertutup yang terkait dengan frame audio. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Mengembalikan atau mengatur indeks trek mulai. Baca/tulis int.

**Mengembalikan:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Mengembalikan atau mengatur indeks trek mulai. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Mengembalikan atau mengatur waktu trek mulai. Baca/tulis int.

**Mengembalikan:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Mengembalikan atau mengatur waktu trek mulai. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Mengembalikan atau mengatur indeks trek terakhir Baca/tulis int.

**Mengembalikan:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Mengembalikan atau mengatur indeks trek terakhir Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Mengembalikan atau mengatur waktu trek terakhir. Baca/tulis int.

**Mengembalikan:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Mengembalikan atau mengatur waktu trek terakhir. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Mengembalikan atau mengatur volume audio. Baca/tulis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Mengembalikan:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Mengembalikan atau mengatur volume audio. Baca/tulis [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Mengembalikan atau mengatur mode pemutaran audio. Baca/tulis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Mengembalikan:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Mengembalikan atau mengatur mode pemutaran audio. Baca/tulis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Menentukan apakah AudioFrame disembunyikan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Menentukan apakah AudioFrame disembunyikan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Menentukan apakah audio diputar berulang. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Menentukan apakah audio diputar berulang. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Menentukan apakah audio diputar di seluruh slide. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Tambahkan Frame Audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Atur Audio untuk diputar di seluruh slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Atur Audio untuk secara otomatis memutar ulang ke awal setelah diputar
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Mengembalikan:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Menentukan apakah audio diputar di seluruh slide. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Tambahkan Frame Audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Atur Audio untuk diputar di seluruh slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Atur Audio untuk secara otomatis memutar ulang ke awal setelah diputar
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Tambahkan Frame Audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Atur Audio untuk diputar di seluruh slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Atur Audio untuk secara otomatis memutar ulang ke awal setelah diputar
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Mengembalikan:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Tambahkan Frame Audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Atur Audio untuk diputar di seluruh slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Atur Audio untuk secara otomatis memutar ulang ke awal setelah diputar
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Menentukan apakah suara disematkan ke presentasi. Baca-saja boolean.

**Mengembalikan:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Mengembalikan atau mengatur nama file audio yang ditautkan ke AudioFrame. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Mengembalikan atau mengatur nama file audio yang ditautkan ke AudioFrame. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Mengembalikan atau mengatur objek audio yang disematkan. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Mengembalikan atau mengatur objek audio yang disematkan. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Menentukan durasi waktu untuk fade-in awal media dalam milidetik. Baca/tulis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur durasi fade awal selama 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Menentukan durasi waktu untuk fade-in awal media dalam milidetik. Baca/tulis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur durasi fade awal selama 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. Baca/tulis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur durasi fade akhir selama 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. Baca/tulis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur durasi fade akhir selama 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Mengembalikan atau mengatur volume audio dalam persen. Baca/tulis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur volume audio menjadi 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
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

Mengembalikan atau mengatur volume audio dalam persen. Baca/tulis float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur volume audio menjadi 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Baca/tulis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur waktu pemotongan awal 1,5 detik
>      audioFrame.setTrimFromStart(1500f);
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

Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Baca/tulis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur waktu pemotongan awal 1,5 detik
>      audioFrame.setTrimFromStart(1500f);
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

Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Baca/tulis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur waktu pemotongan akhir 2 detik
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Baca/tulis float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Atur waktu pemotongan akhir 2 detik
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Mendapatkan koleksi caption tertutup yang terkait dengan frame audio. Properti ini baca-saja dan mengembalikan sebuah [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) yang berisi semua trek caption.

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
>             // Simpan data biner trek caption sebagai file .vtt
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

**Mengembalikan:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)