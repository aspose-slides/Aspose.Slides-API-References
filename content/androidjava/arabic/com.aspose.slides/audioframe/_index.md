---
title: AudioFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل مقطع صوتي على شريحة.
type: docs
url: /ar/com.aspose.slides/audioframe/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

يمثل مقطع صوتي على شريحة.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // يجلب شكل AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // يضبط وضع التشغيل ليعمل عند النقر
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // يضبط مستوى الصوت إلى منخفض
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // يضبط تشغيل الصوت عبر الشرائح
>      audioFrame.setPlayAcrossSlides(true);
>      // يعطل التكرار للصوت
>      audioFrame.setPlayLoopMode(false);
>      // يخفي AudioFrame أثناء عرض الشرائح
>      audioFrame.setHideAtShowing(true);
>      // يعيد تشغيل الصوت إلى البداية بعد الانتهاء
>      audioFrame.setRewindAudio(true);
>      // Saves the PowerPoint file to disk
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | إرجاع أو تعيين فهرس المسار البدائي. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | إرجاع أو تعيين فهرس المسار البدائي. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | إرجاع أو تعيين وقت مسار البدء. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | إرجاع أو تعيين وقت مسار البدء. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | إرجاع أو تعيين فهرس المسار الأخير قراءة/كتابة  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | إرجاع أو تعيين فهرس المسار الأخير قراءة/كتابة  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | إرجاع أو تعيين وقت المسار الأخير. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | إرجاع أو تعيين وقت المسار الأخير. |
| [getVolume()](#getVolume--) | إرجاع أو تعيين حجم الصوت. |
| [setVolume(int value)](#setVolume-int-) | إرجاع أو تعيين حجم الصوت. |
| [getPlayMode()](#getPlayMode--) | إرجاع أو تعيين وضع تشغيل الصوت. |
| [setPlayMode(int value)](#setPlayMode-int-) | إرجاع أو تعيين وضع تشغيل الصوت. |
| [getHideAtShowing()](#getHideAtShowing--) | تحديد ما إذا كان AudioFrame مخفيًا. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | تحديد ما إذا كان AudioFrame مخفيًا. |
| [getPlayLoopMode()](#getPlayLoopMode--) | تحديد ما إذا كان الصوت مكررًا. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | تحديد ما إذا كان الصوت مكررًا. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | تحديد ما إذا كان الصوت يُشغَّل عبر الشرائح. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | تحديد ما إذا كان الصوت يُشغَّل عبر الشرائح. |
| [getRewindAudio()](#getRewindAudio--) | تحديد ما إذا كان يتم إرجاع الصوت تلقائيًا إلى البداية بعد التشغيل. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | تحديد ما إذا كان يتم إرجاع الصوت تلقائيًا إلى البداية بعد التشغيل. |
| [getEmbedded()](#getEmbedded--) | تحديد ما إذا كان الصوت مضمّنًا في العرض التقديمي. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | إرجاع أو تعيين كائن الصوت المضمّن. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | إرجاع أو تعيين كائن الصوت المضمّن. |
| [getFadeInDuration()](#getFadeInDuration--) | تحديد مدة الوقت للانقضاء الأولي للوسائط بالملي ثانية. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | تحديد مدة الوقت للانقضاء الأولي للوسائط بالملي ثانية. |
| [getFadeOutDuration()](#getFadeOutDuration--) | تحديد مدة الوقت للانقضاء النهائي للوسائط بالملي ثانية. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | تحديد مدة الوقت للانقضاء النهائي للوسائط بالملي ثانية. |
| [getVolumeValue()](#getVolumeValue--) | إرجاع أو تعيين حجم الصوت بالنسبة المئوية. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | إرجاع أو تعيين حجم الصوت بالنسبة المئوية. |
| [getTrimFromStart()](#getTrimFromStart--) | تحديد مدة الوقت لإزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | تحديد مدة الوقت لإزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. |
| [getTrimFromEnd()](#getTrimFromEnd--) | تحديد مدة الوقت لإزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | تحديد مدة الوقت لإزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. |
| [getCaptionTracks()](#getCaptionTracks--) | الحصول على مجموعة التسميات التوضيحية المغلقة المرتبطة بإطار الصوت. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

إرجاع أو تعيين فهرس المسار البدائي. قراءة/كتابة  int .

**الإرجاع:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

إرجاع أو تعيين فهرس المسار البدائي. قراءة/كتابة  int .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

إرجاع أو تعيين وقت مسار البدء. قراءة/كتابة  int .

**الإرجاع:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

إرجاع أو تعيين وقت مسار البدء. قراءة/كتابة  int .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

إرجاع أو تعيين فهرس المسار الأخير قراءة/كتابة  int .

**الإرجاع:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

إرجاع أو تعيين فهرس المسار الأخير قراءة/كتابة  int .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

إرجاع أو تعيين وقت المسار الأخير. قراءة/كتابة  int .

**الإرجاع:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

إرجاع أو تعيين وقت المسار الأخير. قراءة/كتابة  int .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

إرجاع أو تعيين حجم الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**الإرجاع:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

إرجاع أو تعيين حجم الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

إرجاع أو تعيين وضع تشغيل الصوت. قراءة/كتابة [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**الإرجاع:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

إرجاع أو تعيين وضع تشغيل الصوت. قراءة/كتابة [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

تحديد ما إذا كان AudioFrame مخفيًا. قراءة/كتابة  boolean .

**الإرجاع:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

تحديد ما إذا كان AudioFrame مخفيًا. قراءة/كتابة  boolean .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

تحديد ما إذا كان الصوت مكررًا. قراءة/كتابة  boolean .

**الإرجاع:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

تحديد ما إذا كان الصوت مكررًا. قراءة/كتابة  boolean .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

تحديد ما إذا كان الصوت يُشغَّل عبر الشرائح. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت ليعمل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة التشغيل تلقائيًا إلى البداية بعد الانتهاء
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**الإرجاع:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

تحديد ما إذا كان الصوت يُشغَّل عبر الشرائح. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت ليعمل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة التشغيل تلقائيًا إلى البداية بعد الانتهاء
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

تحديد ما إذا كان يتم إرجاع الصوت تلقائيًا إلى البداية بعد التشغيل. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت ليعمل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة التشغيل تلقائيًا إلى البداية بعد الانتهاء
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**الإرجاع:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

تحديد ما إذا كان يتم إرجاع الصوت تلقائيًا إلى البداية بعد التشغيل. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت ليعمل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة التشغيل تلقائيًا إلى البداية بعد الانتهاء
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

تحديد ما إذا كان الصوت مضمّنًا في العرض التقديمي. قراءة-فقط  boolean .

**الإرجاع:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

إرجاع أو تعيين كائن الصوت المضمّن. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

إرجاع أو تعيين كائن الصوت المضمّن. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

تحديد مدة الوقت للانقضاء الأولي للوسائط بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين مدة التلاشي الأولي لمدة 200 مللي ثانية
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

تحديد مدة الوقت للانقضاء الأولي للوسائط بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين مدة التلاشي الأولي لمدة 200 مللي ثانية
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

تحديد مدة الوقت للانقضاء النهائي للوسائط بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين مدة التلاشي النهائي لمدة 500 مللي ثانية
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

تحديد مدة الوقت للانقضاء النهائي للوسائط بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تحديد مدة التلاشي النهائي لمدة 500 مللي ثانية
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

إرجاع أو تعيين حجم الصوت بالنسبة المئوية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين حجم الصوت إلى 85٪
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

إرجاع أو تعيين حجم الصوت بالنسبة المئوية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين حجم الصوت إلى 85٪
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

تحديد مدة الوقت لإزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت القص من البداية 1.5 ثانية
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

تحديد مدة الوقت لإزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت القص من البداية 1.5 ثانية
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

تحديد مدة الوقت لإزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت القص من النهاية 2 ثانية
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

تحديد مدة الوقت لإزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت القص من النهاية 2 ثانية
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

الحصول على مجموعة التسميات التوضيحية المغلقة المرتبطة بإطار الصوت. هذه الخاصية قراءة-فقط وتعيد [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) يحتوي على جميع مسارات التسمية.

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
>              // حفظ البيانات الثنائية لمسار التسمية كملف .vtt
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

**الإرجاع:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)