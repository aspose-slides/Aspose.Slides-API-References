---
title: AudioFrame
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili klip audio pada slide.
type: docs
url: /id/com.aspose.slides/audioframe/
---
**Keturunan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Mewakili klip audio pada slide.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Mengambil bentuk AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Mengatur mode pemutaran menjadi bermain pada klik
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Mengatur volume menjadi Rendah
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Mengatur audio agar diputar lintas slide
>      audioFrame.setPlayAcrossSlides(true);
>      // Menonaktifkan loop untuk audio
>      audioFrame.setPlayLoopMode(false);
>      // Menyembunyikan AudioFrame selama pertunjukan slide
>      audioFrame.setHideAtShowing(true);
>      // Memutar ulang audio ke awal setelah diputar
>      audioFrame.setRewindAudio(true);
>      // Menyimpan file PowerPoint ke disk
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Mengembalikan atau mengatur indeks trek mulai. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Mengembalikan atau mengatur indeks trek mulai. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Mengembalikan atau mengatur waktu trek mulai. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Mengembalikan atau mengatur waktu trek mulai. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Mengembalikan atau mengatur indeks trek terakhir Baca/tulis  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Mengembalikan atau mengatur indeks trek terakhir Baca/tulis  int . |
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
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Menentukan apakah audio diputar lintas slide. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Menentukan apakah audio diputar lintas slide. |
| [getRewindAudio()](#getRewindAudio--) | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. |
| [getEmbedded()](#getEmbedded--) | Menentukan apakah suara tertanam dalam presentasi. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan atau mengatur nama file audio yang terhubung ke AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan atau mengatur nama file audio yang terhubung ke AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Mengembalikan atau mengatur objek audio yang tertanam. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Mengembalikan atau mengatur objek audio yang tertanam. |
| [getFadeInDuration()](#getFadeInDuration--) | Menentukan durasi waktu untuk fade-in awal media dalam milidetik. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Menentukan durasi waktu untuk fade-in awal media dalam milidetik. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. |
| [getVolumeValue()](#getVolumeValue--) | Mengembalikan atau mengatur volume audio dalam persen. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Mengembalikan atau mengatur volume audio dalam persen. |
| [getTrimFromStart()](#getTrimFromStart--) | Menentukan durasi waktu yang dihapus dari awal media selama pemutaran, dalam milidetik. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Menentukan durasi waktu yang dihapus dari awal media selama pemutaran, dalam milidetik. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Menentukan durasi waktu yang dihapus dari akhir media selama pemutaran, dalam milidetik. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Menentukan durasi waktu yang dihapus dari akhir media selama pemutaran, dalam milidetik. |
| [getCaptionTracks()](#getCaptionTracks--) | Mendapatkan koleksi caption tertutup yang terkait dengan audio frame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Mengembalikan atau mengatur indeks trek mulai. Baca/tulis  int .

**Mengembalikan:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Mengembalikan atau mengatur indeks trek mulai. Baca/tulis  int .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Mengembalikan atau mengatur waktu trek mulai. Baca/tulis  int .

**Mengembalikan:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Mengembalikan atau mengatur waktu trek mulai. Baca/tulis  int .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Mengembalikan atau mengatur indeks trek terakhir Baca/tulis  int .

**Mengembalikan:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Mengembalikan atau mengatur indeks trek terakhir Baca/tulis  int .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Mengembalikan atau mengatur waktu trek terakhir. Baca/tulis  int .

**Mengembalikan:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Mengembalikan atau mengatur waktu trek terakhir. Baca/tulis  int .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

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

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Mengembalikan atau mengatur mode pemutaran audio. Baca/tulis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Mengembalikan:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Mengembalikan atau mengatur mode pemutaran audio. Baca/tulis [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Menentukan apakah AudioFrame disembunyikan. Baca/tulis  boolean .

**Mengembalikan:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Menentukan apakah AudioFrame disembunyikan. Baca/tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Menentukan apakah audio diputar berulang. Baca/tulis  boolean .

**Mengembalikan:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Menentukan apakah audio diputar berulang. Baca/tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Menentukan apakah audio diputar lintas slide. Baca/tulis  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Tambahkan Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Atur Audio agar diputar lintas slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Atur Audio agar secara otomatis diputar ulang ke awal setelah diputar
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
public final void setPlayAcrossSlides(boolean value)
```

Menentukan apakah audio diputar lintas slide. Baca/tulis  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Tambahkan Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Atur Audio agar diputar lintas slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Atur Audio agar secara otomatis diputar ulang ke awal setelah diputar
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
public final boolean getRewindAudio()
```

Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Baca/tulis  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Tambahkan Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Atur Audio agar diputar lintas slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Atur Audio agar secara otomatis diputar ulang ke awal setelah diputar
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
public final void setRewindAudio(boolean value)
```

Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Baca/tulis  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Tambahkan Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Atur Audio agar diputar lintas slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Atur Audio agar secara otomatis diputar ulang ke awal setelah diputar
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
public final boolean getEmbedded()
```

Menentukan apakah suara tertanam dalam presentasi. Baca-saja  boolean .

**Mengembalikan:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Mengembalikan atau mengatur nama file audio yang terhubung ke AudioFrame. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Mengembalikan atau mengatur nama file audio yang terhubung ke AudioFrame. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Mengembalikan atau mengatur objek audio yang tertanam. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Mengembalikan atau mengatur objek audio yang tertanam. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
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
public final void setFadeInDuration(float value)
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
public final float getFadeOutDuration()
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
public final void setFadeOutDuration(float value)
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
public final float getVolumeValue()
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
public final void setVolumeValue(float value)
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
public final float getTrimFromStart()
```

Menentukan durasi waktu yang dihapus dari awal media selama pemutaran, dalam milidetik. Baca/tulis float.

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
public final void setTrimFromStart(float value)
```

Menentukan durasi waktu yang dihapus dari awal media selama pemutaran, dalam milidetik. Baca/tulis float.

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
public final float getTrimFromEnd()
```

Menentukan durasi waktu yang dihapus dari akhir media selama pemutaran, dalam milidetik. Baca/tulis float.

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
public final void setTrimFromEnd(float value)
```

Menentukan durasi waktu yang dihapus dari akhir media selama pemutaran, dalam milidetik. Baca/tulis float.

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
public final ICaptionsCollection getCaptionTracks()
```

Mendapatkan koleksi caption tertutup yang terkait dengan audio frame. Properti ini bersifat baca-saja dan mengembalikan sebuah [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) yang berisi semua trek caption.

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
>              // Simpan data biner trek caption sebagai file .vtt
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


**Mengembalikan:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)