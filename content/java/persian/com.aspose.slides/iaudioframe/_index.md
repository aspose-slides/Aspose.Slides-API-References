---
title: IAudioFrame
second_title: Aspose.Slides برای Java مرجع API
description: یک کلیپ صوتی را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/iaudioframe/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

یک کلیپ صوتی را بر روی اسلاید نشان می‌دهد.

## متدها

| Method | Description |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | یک ایندکس مسیر شروع را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | یک ایندکس مسیر شروع را بازمی‌گرداند یا تنظیم می‌کند. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | یک زمان مسیر شروع را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | یک زمان مسیر شروع را بازمی‌گرداند یا تنظیم می‌کند. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | یک ایندکس مسیر آخر را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | یک ایندکس مسیر آخر را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | یک زمان مسیر آخر را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | یک زمان مسیر آخر را بازمی‌گرداند یا تنظیم می‌کند. |
| [getVolume()](#getVolume--) | حجم صدا را بازمی‌گرداند یا تنظیم می‌کند. |
| [setVolume(int value)](#setVolume-int-) | حجم صدا را بازمی‌گرداند یا تنظیم می‌کند. |
| [getPlayMode()](#getPlayMode--) | حالت پخش صدا را بازمی‌گرداند یا تنظیم می‌کند. |
| [setPlayMode(int value)](#setPlayMode-int-) | حالت پخش صدا را بازمی‌گرداند یا تنظیم می‌کند. |
| [getHideAtShowing()](#getHideAtShowing--) | مشخص می‌کند آیا یک AudioFrame مخفی است یا نه. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | مشخص می‌کند آیا یک AudioFrame مخفی است یا نه. |
| [getPlayLoopMode()](#getPlayLoopMode--) | مشخص می‌کند آیا صدا به صورت حلقه‌ای پخش می‌شود یا نه. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | مشخص می‌کند آیا صدا به صورت حلقه‌ای پخش می‌شود یا نه. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | مشخص می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا نه. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | مشخص می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا نه. |
| [getRewindAudio()](#getRewindAudio--) | مشخص می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدا بازمی‌گردد یا نه. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | مشخص می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدا بازمی‌گردد یا نه. |
| [getEmbedded()](#getEmbedded--) | مشخص می‌کند آیا یک صدا به ارائه جاسازی شده است یا نه. |
| [getLinkPathLong()](#getLinkPathLong--) | نام فایل صوتی مرتبط با یک AudioFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | نام فایل صوتی مرتبط با یک AudioFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | شیء صوتی جاسازی‌شده را بازمی‌گرداند یا تنظیم می‌کند. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | شیء صوتی جاسازی‌شده را بازمی‌گرداند یا تنظیم می‌کند. |
| [getFadeInDuration()](#getFadeInDuration--) | مدت زمان محو‌ شدن اولیه رسانه را بر حسب میلی‌ثانیه تعیین می‌کند. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | مدت زمان محو‌ شدن اولیه رسانه را بر حسب میلی‌ثانیه تعیین می‌کند. |
| [getFadeOutDuration()](#getFadeOutDuration--) | مدت زمان محو‌ شدن نهایی رسانه را بر حسب میلی‌ثانیه تعیین می‌کند. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | مدت زمان محو‌ شدن نهایی رسانه را بر حسب میلی‌ثانیه تعیین می‌کند. |
| [getVolumeValue()](#getVolumeValue--) | حجم صدا را بر حسب درصد بازمی‌گرداند یا تنظیم می‌کند. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | حجم صدا را بر حسب درصد بازمی‌گرداند یا تنظیم می‌کند. |
| [getTrimFromStart()](#getTrimFromStart--) | مدت زمانی که باید از ابتدای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه تعیین می‌کند. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | مدت زمانی که باید از ابتدای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه تعیین می‌کند. |
| [getTrimFromEnd()](#getTrimFromEnd--) | مدت زمانی که باید از انتهای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه تعیین می‌کند. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | مدت زمانی که باید از انتهای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه تعیین می‌کند. |
| [getCaptionTracks()](#getCaptionTracks--) | مجموعه‌ای از زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

یک ایندکس مسیر شروع را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**بازمی‌گردد:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

یک ایندکس مسیر شروع را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

یک زمان مسیر شروع را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**بازمی‌گردد:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

یک زمان مسیر شروع را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

یک ایندکس مسیر آخر را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**بازمی‌گردد:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

یک ایندکس مسیر آخر را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

یک زمان مسیر آخر را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**بازمی‌گردد:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

یک زمان مسیر آخر را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

حجم صدا را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**بازمی‌گردد:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

حجم صدا را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

حالت پخش صدا را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**بازمی‌گردد:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

حالت پخش صدا را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

مشخص می‌کند آیا یک AudioFrame مخفی است یا نه. قابل خواندن/نوشتن boolean.

**بازمی‌گردد:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

مشخص می‌کند آیا یک AudioFrame مخفی است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

مشخص می‌کند آیا صدا به صورت حلقه‌ای پخش می‌شود یا نه. قابل خواندن/نوشتن boolean.

**بازمی‌گردد:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

مشخص می‌کند آیا صدا به صورت حلقه‌ای پخش می‌شود یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

مشخص می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا نه. قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازگرداندن خودکار به ابتدا پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**بازمی‌گردد:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

مشخص می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا نه. قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازگرداندن خودکار به ابتدا پس از پخش
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
public abstract boolean getRewindAudio()
```

مشخص می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدا بازمی‌گردد یا نه. قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازگرداندن خودکار به ابتدا پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**بازمی‌گردد:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

مشخص می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدا بازمی‌گردد یا نه. قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازگرداندن خودکار به ابتدا پس از پخش
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
public abstract boolean getEmbedded()
```

مشخص می‌کند آیا یک صدا به ارائه جاسازی شده است یا نه. فقط خواندنی boolean.

**بازمی‌گردد:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

نام فایل صوتی مرتبط با یک AudioFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازمی‌گردد:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

نام فایل صوتی مرتبط با یک AudioFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

شیء صوتی جاسازی‌شده را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IAudio](../../com.aspose.slides/iaudio).

**بازمی‌گردد:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

شیء صوتی جاسازی‌شده را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IAudio](../../com.aspose.slides/iaudio).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

مدت زمان محو‌ شدن اولیه رسانه را بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم مدت زمان محو شدن اولیه به 200 میلی‌ثانیه
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گردد:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

مدت زمان محو‌ شدن اولیه رسانه را بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم مدت زمان محو شدن اولیه به 200 میلی‌ثانیه
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
public abstract float getFadeOutDuration()
```

مدت زمان محو‌ شدن نهایی رسانه را بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم مدت زمان محو شدن انتهایی به 500 میلی‌ثانیه
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گردد:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

مدت زمان محو‌ شدن نهایی رسانه را بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم مدت زمان محو شدن انتهایی به 500 میلی‌ثانیه
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
public abstract float getVolumeValue()
```

حجم صدا را بر حسب درصد بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم حجم صدا به 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گردد:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

حجم صدا را بر حسب درصد بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم حجم صدا به 85%
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
public abstract float getTrimFromStart()
```

مدت زمانی که باید از ابتدای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن/نوشتن float.

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


**بازمی‌گردد:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

مدت زمانی که باید از ابتدای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن/نوشتن float.

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
public abstract float getTrimFromEnd()
```

مدت زمانی که باید از انتهای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش انتهایی به 2 ثانیه
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گردد:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

مدت زمانی که باید از انتهای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش انتهایی به 2 ثانیه
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
public abstract ICaptionsCollection getCaptionTracks()
```

مجموعه‌ای از زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این ویژگی فقط خواندنی است و یک [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) شامل همه ترک‌های زیرنویس را بازمی‌گرداند.

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
>             // ذخیره داده‌های باینری زیرنویس به عنوان فایل .vtt
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

**بازمی‌گردد:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)