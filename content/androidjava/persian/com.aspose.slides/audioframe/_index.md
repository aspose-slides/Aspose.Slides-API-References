---
title: AudioFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک کلیپ صوتی بر روی اسلاید است.
type: docs
url: /fa/com.aspose.slides/audioframe/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)  
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

یک کلیپ صوتی را بر روی اسلاید نشان می‌دهد.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // دریافت شکل AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // تنظیم حالت پخش برای پخش با کلیک
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // تنظیم حجم صدا به کم
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // تنظیم پخش صدا در تمام اسلایدها
>      audioFrame.setPlayAcrossSlides(true);
>      // غیرفعال کردن حلقه برای صدا
>      audioFrame.setPlayLoopMode(false);
>      // مخفی کردن AudioFrame در طول نمایش اسلاید
>      audioFrame.setHideAtShowing(true);
>      // بازگرداندن صدا به شروع پس از پخش
>      audioFrame.setRewindAudio(true);
>      // ذخیره فایل PowerPoint روی دیسک
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | مقدار اندیس مسیر شروع را بر می‌گرداند یا تنظیم می‌کند. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | مقدار اندیس مسیر شروع را بر می‌گرداند یا تنظیم می‌کند. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | زمان مسیر شروع را بر می‌گرداند یا تنظیم می‌کند. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | زمان مسیر شروع را بر می‌گرداند یا تنظیم می‌کند. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | اندیس مسیر آخر را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | اندیس مسیر آخر را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | زمان مسیر آخر را بر می‌گرداند یا تنظیم می‌کند. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | زمان مسیر آخر را بر می‌گرداند یا تنظیم می‌کند. |
| [getVolume()](#getVolume--) | حجم صدا را بر می‌گرداند یا تنظیم می‌کند. |
| [setVolume(int value)](#setVolume-int-) | حجم صدا را بر می‌گرداند یا تنظیم می‌کند. |
| [getPlayMode()](#getPlayMode--) | حالت پخش صدا را بر می‌گرداند یا تنظیم می‌کند. |
| [setPlayMode(int value)](#setPlayMode-int-) | حالت پخش صدا را بر می‌گرداند یا تنظیم می‌کند. |
| [getHideAtShowing()](#getHideAtShowing--) | مشخص می‌کند که آیا یک AudioFrame مخفی است یا خیر. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | مشخص می‌کند که آیا یک AudioFrame مخفی است یا خیر. |
| [getPlayLoopMode()](#getPlayLoopMode--) | مشخص می‌کند که آیا صدا به‌صورت حلقه‌ای پخش می‌شود یا خیر. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | مشخص می‌کند که آیا صدا به‌صورت حلقه‌ای پخش می‌شود یا خیر. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | مشخص می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | مشخص می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. |
| [getRewindAudio()](#getRewindAudio--) | مشخص می‌کند که آیا صدا پس از پخش به‌صورت خودکار به شروع باز می‌گردد یا خیر. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | مشخص می‌کند که آیا صدا پس از پخش به‌صورت خودکار به شروع باز می‌گردد یا خیر. |
| [getEmbedded()](#getEmbedded--) | مشخص می‌کند که آیا صدا به ارائه جاسازی شده است یا خیر. |
| [getLinkPathLong()](#getLinkPathLong--) | نام فایل صوتی که به یک AudioFrame لینک شده است را بر می‌گرداند یا تنظیم می‌کند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | نام فایل صوتی که به یک AudioFrame لینک شده است را بر می‌گرداند یا تنظیم می‌کند. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | شیء صوتی جاسازی‌شده را بر می‌گرداند یا تنظیم می‌کند. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | شیء صوتی جاسازی‌شده را بر می‌گرداند یا تنظیم می‌کند. |
| [getFadeInDuration()](#getFadeInDuration--) | مدت زمان fade-in اولیه رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | مدت زمان fade-in اولیه رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [getFadeOutDuration()](#getFadeOutDuration--) | مدت زمان fade-out پایان رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | مدت زمان fade-out پایان رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [getVolumeValue()](#getVolumeValue--) | حجم صدا را به درصد بر می‌گرداند یا تنظیم می‌کند. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | حجم صدا را به درصد بر می‌گرداند یا تنظیم می‌کند. |
| [getTrimFromStart()](#getTrimFromStart--) | مدت زمانی که در زمان پخش از ابتدای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | مدت زمانی که در زمان پخش از ابتدای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [getTrimFromEnd()](#getTrimFromEnd--) | مدت زمانی که در زمان پخش از انتهای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | مدت زمانی که در زمان پخش از انتهای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [getCaptionTracks()](#getCaptionTracks--) | مجموعه‌ای از زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

اندیس مسیر شروع را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int .

**بازگرداندن:**  
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

اندیس مسیر شروع را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

زمان مسیر شروع را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int .

**بازگرداندن:**  
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

زمان مسیر شروع را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

اندیس مسیر آخر را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int .

**بازگرداندن:**  
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

اندیس مسیر آخر را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

زمان مسیر آخر را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int .

**بازگرداندن:**  
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

زمان مسیر آخر را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی  int .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

حجم صدا را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**بازگرداندن:**  
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

حجم صدا را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

حالت پخش صدا را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**بازگرداندن:**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

حالت پخش صدا را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

مشخص می‌کند که آیا یک AudioFrame مخفی است یا خیر خواندنی/نوشتنی  boolean .

**بازگرداندن:**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

مشخص می‌کند که آیا یک AudioFrame مخفی است یا خیر خواندنی/نوشتنی  boolean .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

مشخص می‌کند که آیا صدا به‌صورت حلقه‌ای پخش می‌شود یا خیر خواندنی/نوشتنی  boolean .

**بازگرداندن:**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

مشخص می‌کند که آیا صدا به‌صورت حلقه‌ای پخش می‌شود یا خیر خواندنی/نوشتنی  boolean .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

مشخص می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا خیر خواندنی/نوشتنی  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازگرداندن خودکار به شروع پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**بازگرداندن:**  
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

مشخص می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا خیر خواندنی/نوشتنی  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازگرداندن خودکار به شروع پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

مشخص می‌کند که آیا صدا پس از پخش به‌صورت خودکار به شروع باز می‌گردد یا خیر خواندنی/نوشتنی  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازگرداندن خودکار به شروع پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**بازگرداندن:**  
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

مشخص می‌کند که آیا صدا پس از پخش به‌صورت خودکار به شروع باز می‌گردد یا خیر خواندنی/نوشتنی  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازگرداندن خودکار به شروع پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

مشخص می‌کند که آیا صدا به ارائه جاسازی شده است یا خیر فقط-خواندنی  boolean .

**بازگرداندن:**  
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

نام فایل صوتی که به یک AudioFrame لینک شده است را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی String.

**بازگرداندن:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

نام فایل صوتی که به یک AudioFrame لینک شده است را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

شیء صوتی جاسازی‌شده را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [IAudio](../../com.aspose.slides/iaudio).

**بازگرداندن:**  
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

شیء صوتی جاسازی‌شده را بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [IAudio](../../com.aspose.slides/iaudio).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

مدت زمان fade-in اولیه رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // مدت زمان fade اولیه را برای 200 میلی‌ثانیه تنظیم کنید
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگرداندن:**  
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

مدت زمان fade-in اولیه رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // مدت زمان fade اولیه را برای 200 میلی‌ثانیه تنظیم کنید
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

مدت زمان fade-out پایان رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // مدت زمان fade انتهایی را برای 500 میلی‌ثانیه تنظیم کنید
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگرداندن:**  
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

مدت زمان fade-out پایان رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // مدت زمان fade انتهایی را برای 500 میلی‌ثانیه تنظیم کنید
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

حجم صدا را به درصد بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم حجم صدا برای 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگرداندن:**  
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

حجم صدا را به درصد بر می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم حجم صدا برای 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

مدت زمانی که در زمان پخش از ابتدای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش شروع به 1.5 ثانیه
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگرداندن:**  
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

مدت زمانی که در زمان پخش از ابتدای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش شروع به 1.5 ثانیه
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

مدت زمانی که در زمان پخش از انتهای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش انتها به 2 ثانیه
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگرداندن:**  
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

مدت زمانی که در زمان پخش از انتهای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش انتها به 2 ثانیه
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

مجموعه‌ای از زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) حاوی تمام مسیرهای زیرنویس را برمی‌گرداند.

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
>              // ذخیره داده‌های باینری مسیر زیرنویس به‌عنوان یک فایل .vtt
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


**بازگرداندن:**  
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)