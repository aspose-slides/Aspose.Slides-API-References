---
title: IAudioFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک کلیپ صوتی بر روی اسلاید.
type: docs
url: /fa/com.aspose.slides/iaudioframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

یک کلیپ صوتی را در یک اسلاید نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | بازگرداندن یا تنظیم یک ایندکس مسیر شروع. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | بازگرداندن یا تنظیم یک ایندکس مسیر شروع. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | بازگرداندن یا تنظیم زمان مسیر شروع. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | بازگرداندن یا تنظیم زمان مسیر شروع. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | بازگرداندن یا تنظیم یک ایندکس مسیر آخر. قابل خواندن/نوشتن int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | بازگرداندن یا تنظیم یک ایندکس مسیر آخر. قابل خواندن/نوشتن int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | بازگرداندن یا تنظیم زمان مسیر آخر. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | بازگرداندن یا تنظیم زمان مسیر آخر. |
| [getVolume()](#getVolume--) | بازگرداندن یا تنظیم حجم صدا. |
| [setVolume(int value)](#setVolume-int-) | بازگرداندن یا تنظیم حجم صدا. |
| [getPlayMode()](#getPlayMode--) | بازگرداندن یا تنظیم حالت پخش صدا. |
| [setPlayMode(int value)](#setPlayMode-int-) | بازگرداندن یا تنظیم حالت پخش صدا. |
| [getHideAtShowing()](#getHideAtShowing--) | تشخیص اینکه آیا یک AudioFrame مخفی است یا نه. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | تشخیص اینکه آیا یک AudioFrame مخفی است یا نه. |
| [getPlayLoopMode()](#getPlayLoopMode--) | تشخیص اینکه آیا صدا حلقه‌ای است یا نه. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | تشخیص اینکه آیا صدا حلقه‌ای است یا نه. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | تشخیص اینکه آیا صدا در سراسر اسلایدها پخش می‌شود یا نه. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | تشخیص اینکه آیا صدا در سراسر اسلایدها پخش می‌شود یا نه. |
| [getRewindAudio()](#getRewindAudio--) | تشخیص اینکه آیا صدا پس از پخش به طور خودکار به ابتدا باز می‌گردد یا نه. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | تشخیص اینکه آیا صدا پس از پخش به طور خودکار به ابتدا باز می‌گردد یا نه. |
| [getEmbedded()](#getEmbedded--) | تشخیص اینکه آیا صدا در ارائه جاسازی شده است یا نه. |
| [getLinkPathLong()](#getLinkPathLong--) | بازگرداندن یا تنظیم نام فایل صوتی که به یک AudioFrame لینک شده است. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | بازگرداندن یا تنظیم نام فایل صوتی که به یک AudioFrame لینک شده است. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | بازگرداندن یا تنظیم شیء صوتی جاسازی شده. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | بازگرداندن یا تنظیم شیء صوتی جاسازی شده. |
| [getFadeInDuration()](#getFadeInDuration--) | مشخص می‌کند مدت زمان محو‌کردن اولیه رسانه را به میلی‌ثانیه. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | مشخص می‌کند مدت زمان محو‌کردن اولیه رسانه را به میلی‌ثانیه. |
| [getFadeOutDuration()](#getFadeOutDuration--) | مشخص می‌کند مدت زمان محو‌کردن انتهایی رسانه را به میلی‌ثانیه. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | مشخص می‌کند مدت زمان محو‌کردن انتهایی رسانه را به میلی‌ثانیه. |
| [getVolumeValue()](#getVolumeValue--) | بازگرداندن یا تنظیم حجم صدا به درصد. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | بازگرداندن یا تنظیم حجم صدا به درصد. |
| [getTrimFromStart()](#getTrimFromStart--) | مشخص می‌کند مدت زمان حذف شده از ابتدای رسانه در هنگام پخش، به میلی‌ثانیه. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | مشخص می‌کند مدت زمان حذف شده از ابتدای رسانه در هنگام پخش، به میلی‌ثانیه. |
| [getTrimFromEnd()](#getTrimFromEnd--) | مشخص می‌کند مدت زمان حذف شده از انتهای رسانه در هنگام پخش، به میلی‌ثانیه. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | مشخص می‌کند مدت زمان حذف شده از انتهای رسانه در هنگام پخش، به میلی‌ثانیه. |
| [getCaptionTracks()](#getCaptionTracks--) | دریافت مجموعه‌ی زیرنویس‌های بسته مرتبط با قاب صوتی. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

بازگرداندن یا تنظیم یک ایندکس مسیر شروع. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

بازگرداندن یا تنظیم یک ایندکس مسیر شروع. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

بازگرداندن یا تنظیم زمان مسیر شروع. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

بازگرداندن یا تنظیم زمان مسیر شروع. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

بازگرداندن یا تنظیم یک ایندکس مسیر آخر. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

بازگرداندن یا تنظیم یک ایندکس مسیر آخر. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

بازگرداندن یا تنظیم زمان مسیر آخر. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

بازگرداندن یا تنظیم زمان مسیر آخر. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

بازگرداندن یا تنظیم حجم صدا. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**بازگشت:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

بازگرداندن یا تنظیم حجم صدا. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

بازگرداندن یا تنظیم حالت پخش صدا. قابل خواندن/نوشتن [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**بازگشت:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

بازگرداندن یا تنظیم حالت پخش صدا. قابل خواندن/نوشتن [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

تشخیص اینکه آیا یک AudioFrame مخفی است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

تشخیص اینکه آیا یک AudioFrame مخفی است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

تشخیص اینکه آیا صدا حلقه‌ای است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

تشخیص اینکه آیا صدا حلقه‌ای است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

تشخیص اینکه آیا صدا در سراسر اسلایدها پخش می‌شود یا نه. قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در سراسر اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازپخش خودکار به ابتدا پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**بازگشت:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

تشخیص اینکه آیا صدا در سراسر اسلایدها پخش می‌شود یا نه. قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در سراسر اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازپخش خودکار به ابتدا پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

تشخیص اینکه آیا صدا پس از پخش به طور خودکار به ابتدا باز می‌گردد یا نه. قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در سراسر اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازپخش خودکار به ابتدا پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**بازگشت:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

تشخیص اینکه آیا صدا پس از پخش به طور خودکار به ابتدا باز می‌گردد یا نه. قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن فریم صوتی
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم صدا برای پخش در سراسر اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم صدا برای بازپخش خودکار به ابتدا پس از پخش
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

تشخیص اینکه آیا صدا در ارائه جاسازی شده است یا نه. فقط-خواندنی boolean.

**بازگشت:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

بازگرداندن یا تنظیم نام فایل صوتی که به یک AudioFrame لینک شده است. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

بازگرداندن یا تنظیم نام فایل صوتی که به یک AudioFrame لینک شده است. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

بازگرداندن یا تنظیم شیء صوتی جاسازی شده. قابل خواندن/نوشتن [IAudio](../../com.aspose.slides/iaudio).

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

بازگرداندن یا تنظیم شیء صوتی جاسازی شده. قابل خواندن/نوشتن [IAudio](../../com.aspose.slides/iaudio).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

مشخص می‌کند مدت زمان محو‌کردن اولیه رسانه را به میلی‌ثانیه. قابل خواندن/نوشتن float.

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

**بازگشت:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

مشخص می‌کند مدت زمان محو‌کردن اولیه رسانه را به میلی‌ثانیه. قابل خواندن/نوشتن float.

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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

مشخص می‌کند مدت زمان محو‌کردن انتهایی رسانه را به میلی‌ثانیه. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم مدت زمان محو شدن انتهایی برای 500 میلی‌ثانیه
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

مشخص می‌کند مدت زمان محو‌کردن انتهایی رسانه را به میلی‌ثانیه. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم مدت زمان محو شدن انتهایی برای 500 میلی‌ثانیه
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

بازگرداندن یا تنظیم حجم صدا به درصد. قابل خواندن/نوشتن float.

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

**بازگشت:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

بازگرداندن یا تنظیم حجم صدا به درصد. قابل خواندن/نوشتن float.

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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

مشخص می‌کند مدت زمان حذف شده از ابتدای رسانه در هنگام پخش، به میلی‌ثانیه. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش ابتدایی 1.5 ثانیه
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

مشخص می‌کند مدت زمان حذف شده از ابتدای رسانه در هنگام پخش، به میلی‌ثانیه. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش ابتدایی 1.5 ثانیه
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

مشخص می‌کند مدت زمان حذف شده از انتهای رسانه در هنگام پخش، به میلی‌ثانیه. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش انتهایی 2 ثانیه
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

مشخص می‌کند مدت زمان حذف شده از انتهای رسانه در هنگام پخش، به میلی‌ثانیه. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تنظیم زمان برش انتهایی 2 ثانیه
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

دریافت مجموعه‌ی زیرنویس‌های بسته مرتبط با قاب صوتی. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) شامل تمام مسیرهای زیرنویس برمی‌گرداند.

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
>             // ذخیره‌ی داده‌های باینری زیرنویس به‌صورت فایل .vtt
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

**بازگشت:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)