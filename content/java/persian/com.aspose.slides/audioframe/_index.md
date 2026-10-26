---
title: AudioFrame
second_title: مرجع API Aspose.Slides برای جاوا
description: یک کلیپ صوتی را در اسلاید نشان می‌دهد.
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

یک کلیپ صوتی را در اسلاید نشان می‌دهد.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // شکل AudioFrame را دریافت می‌کند
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // حالت پخش را به پخش با کلیک تنظیم می‌کند
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // حجم را به کم تنظیم می‌کند
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // پخش صدا را در تمام اسلایدها تنظیم می‌کند
>      audioFrame.setPlayAcrossSlides(true);
>      // حلقه پخش صدا را غیرفعال می‌کند
>      audioFrame.setPlayLoopMode(false);
>      // AudioFrame را در حین نمایش اسلاید مخفی می‌کند
>      audioFrame.setHideAtShowing(true);
>      // پس از پخش صدا را به ابتدای خود باز می‌گرداند
>      audioFrame.setRewindAudio(true);
>      // فایل PowerPoint را روی دیسک ذخیره می‌کند
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | شاخص ترک شروع را برمی‌گرداند یا تنظیم می‌کند. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | شاخص ترک شروع را برمی‌گرداند یا تنظیم می‌کند. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | زمان ترک شروع را برمی‌گرداند یا تنظیم می‌کند. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | زمان ترک شروع را برمی‌گرداند یا تنظیم می‌کند. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | شاخص ترک آخر را برمی‌گرداند یا تنظیم می‌کند خواندن/نوشتن  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | شاخص ترک آخر را برمی‌گرداند یا تنظیم می‌کند خواندن/نوشتن  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | زمان ترک آخر را برمی‌گرداند یا تنظیم می‌کند. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | زمان ترک آخر را برمی‌گرداند یا تنظیم می‌کند. |
| [getVolume()](#getVolume--) | حجم صدا را برمی‌گرداند یا تنظیم می‌کند. |
| [setVolume(int value)](#setVolume-int-) | حجم صدا را برمی‌گرداند یا تنظیم می‌کند. |
| [getPlayMode()](#getPlayMode--) | حالت پخش صدا را برمی‌گرداند یا تنظیم می‌کند. |
| [setPlayMode(int value)](#setPlayMode-int-) | حالت پخش صدا را برمی‌گرداند یا تنظیم می‌کند. |
| [getHideAtShowing()](#getHideAtShowing--) | تعیین می‌کند آیا AudioFrame مخفی است یا خیر. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | تعیین می‌کند آیا AudioFrame مخفی است یا خیر. |
| [getPlayLoopMode()](#getPlayLoopMode--) | تعیین می‌کند آیا صدا به‌صورت حلقه‌ای پخش می‌شود یا خیر. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | تعیین می‌کند آیا صدا به‌صورت حلقه‌ای پخش می‌شود یا خیر. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | تعیین می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | تعیین می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. |
| [getRewindAudio()](#getRewindAudio--) | تعیین می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدای خود باز می‌گردد یا خیر. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | تعیین می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدای خود باز می‌گردد یا خیر. |
| [getEmbedded()](#getEmbedded--) | تعیین می‌کند آیا صدا به‌صورت جاسازی‌شده در ارائه موجود است یا خیر. |
| [getLinkPathLong()](#getLinkPathLong--) | نام فایل صوتی که به AudioFrame لینک شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | نام فایل صوتی که به AudioFrame لینک شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | شیء صوتی جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | شیء صوتی جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [getFadeInDuration()](#getFadeInDuration--) | مدت زمان محو شدن اولیه‌ی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | مدت زمان محو شدن اولیه‌ی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [getFadeOutDuration()](#getFadeOutDuration--) | مدت زمان محو شدن انتهایی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | مدت زمان محو شدن انتهایی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [getVolumeValue()](#getVolumeValue--) | حجم صدا را به درصد برمی‌گرداند یا تنظیم می‌کند. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | حجم صدا را به درصد برمی‌گرداند یا تنظیم می‌کند. |
| [getTrimFromStart()](#getTrimFromStart--) | مدت زمانی که باید از ابتدای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | مدت زمانی که باید از ابتدای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [getTrimFromEnd()](#getTrimFromEnd--) | مدت زمانی که باید از انتهای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | مدت زمانی که باید از انتهای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. |
| [getCaptionTracks()](#getCaptionTracks--) | مجموعه‌ای از زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

شاخص ترک شروع را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  int .

**بازگشت:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

شاخص ترک شروع را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  int .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

زمان ترک شروع را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  int .

**بازگشت:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

زمان ترک شروع را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  int .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

شاخص ترک آخر را برمی‌گرداند یا تنظیم می‌کند خواندن/نوشتن  int .

**بازگشت:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

شاخص ترک آخر را برمی‌گرداند یا تنظیم می‌کند خواندن/نوشتن  int .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

زمان ترک آخر را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  int .

**بازگشت:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

زمان ترک آخر را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  int .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

حجم صدا را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**بازگشت:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

حجم صدا را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

حالت پخش صدا را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**بازگشت:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

حالت پخش صدا را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

تعیین می‌کند آیا AudioFrame مخفی است یا خیر. خواندن/نوشتن  boolean .

**بازگشت:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

تعیین می‌کند آیا AudioFrame مخفی است یا خیر. خواندن/نوشتن  boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

تعیین می‌کند آیا صدا به‌صورت حلقه‌ای پخش می‌شود یا خیر. خواندن/نوشتن  boolean .

**بازگشت:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

تعیین می‌کند آیا صدا به‌صورت حلقه‌ای پخش می‌شود یا خیر. خواندن/نوشتن  boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

تعیین می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. خواندن/نوشتن  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
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

**بازگشت:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

تعیین می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. خواندن/نوشتن  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // افزودن Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تنظیم Audio برای پخش در تمام اسلایدها
>       audioFrame.setPlayAcrossSlides(true);
>       // تنظیم Audio برای بازگرداندن خودکار به ابتدا پس از پخش
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

تعیین می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدای خود باز می‌گردد یا خیر. خواندن/نوشتن  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
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

**بازگشت:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

تعیین می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدای خود باز می‌گردد یا خیر. خواندن/نوشتن  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
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
public final boolean getEmbedded()
```

تعیین می‌کند آیا صدایی به‌صورت جاسازی‌شده در ارائه موجود است یا خیر. فقط-خواندنی  boolean .

**بازگشت:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

نام فایل صوتی که به AudioFrame لینک شده است را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

نام فایل صوتی که به AudioFrame لینک شده است را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

شیء صوتی جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IAudio](../../com.aspose.slides/iaudio).

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

شیء صوتی جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IAudio](../../com.aspose.slides/iaudio).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

مدت زمان محو شدن اولیه‌ی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندن/نوشتن float.

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
public final void setFadeInDuration(float value)
```

مدت زمان محو شدن اولیه‌ی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندن/نوشتن float.

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
public final float getFadeOutDuration()
```

مدت زمان محو شدن انتهایی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندن/نوشتن float.

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

**بازگشت:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

مدت زمان محو شدن انتهایی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // مدت زمان محو شدن انتهایی را به 500 میلی‌ثانیه تنظیم کنید
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

حجم صدا را به درصد برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // حجم صدا را به 85٪ تنظیم کنید
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
public final void setVolumeValue(float value)
```

حجم صدا را به درصد برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // حجم صدا را به 85٪ تنظیم کنید
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

مدت زمانی که باید از ابتدای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. خواندن/نوشتن float.

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

**بازگشت:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

مدت زمانی که باید از ابتدای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. خواندن/نوشتن float.

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

مدت زمانی که باید از انتهای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. خواندن/نوشتن float.

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

**بازگشت:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

مدت زمانی که باید از انتهای رسانه هنگام پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. خواندن/نوشتن float.

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
>              // داده‌های باینری مسیر زیرنویس را به عنوان فایل .vtt ذخیره کنید
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

**بازگشت:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)