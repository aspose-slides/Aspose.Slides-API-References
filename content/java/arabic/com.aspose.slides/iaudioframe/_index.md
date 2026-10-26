---
title: IAudioFrame
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مقطعًا صوتيًا على الشريحة.
type: docs
url: /ar/com.aspose.slides/iaudioframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

يمثل مقطع صوتي على الشريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | إرجاع أو تعيين فهرس المسار البادئ. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | إرجاع أو تعيين فهرس المسار البادئ. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | إرجاع أو تعيين وقت بداية المسار. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | إرجاع أو تعيين وقت بداية المسار. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | إرجاع أو تعيين فهرس آخر مسار. قراءة/كتابة int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | إرجاع أو تعيين فهرس آخر مسار. قراءة/كتابة int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | إرجاع أو تعيين وقت آخر مسار. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | إرجاع أو تعيين وقت آخر مسار. |
| [getVolume()](#getVolume--) | إرجاع أو تعيين مستوى الصوت. |
| [setVolume(int value)](#setVolume-int-) | إرجاع أو تعيين مستوى الصوت. |
| [getPlayMode()](#getPlayMode--) | إرجاع أو تعيين نمط تشغيل الصوت. |
| [setPlayMode(int value)](#setPlayMode-int-) | إرجاع أو تعيين نمط تشغيل الصوت. |
| [getHideAtShowing()](#getHideAtShowing--) | تحديد ما إذا كان AudioFrame مخفيًا. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | تحديد ما إذا كان AudioFrame مخفيًا. |
| [getPlayLoopMode()](#getPlayLoopMode--) | تحديد ما إذا كان الصوت مكرّرًا. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | تحديد ما إذا كان الصوت مكرّرًا. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | تحديد ما إذا كان الصوت يُشغَل عبر الشرائح. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | تحديد ما إذا كان الصوت يُشغَل عبر الشرائح. |
| [getRewindAudio()](#getRewindAudio--) | تحديد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | تحديد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. |
| [getEmbedded()](#getEmbedded--) | تحديد ما إذا كان الصوت مدمجًا في العرض التقديمي. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | إرجاع أو تعيين كائن صوت مدمج. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | إرجاع أو تعيين كائن صوت مدمج. |
| [getFadeInDuration()](#getFadeInDuration--) | تحديد مدة الزمن للظهور التدريجي الأولي للوسائط بالملي ثانية. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | تحديد مدة الزمن للظهور التدريجي الأولي للوسائط بالملي ثانية. |
| [getFadeOutDuration()](#getFadeOutDuration--) | تحديد مدة الزمن للانخفاض التدريجي النهائي للوسائط بالملي ثانية. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | تحديد مدة الزمن للانخفاض التدريجي النهائي للوسائط بالملي ثانية. |
| [getVolumeValue()](#getVolumeValue--) | إرجاع أو تعيين مستوى الصوت بالنسب المئوية. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | إرجاع أو تعيين مستوى الصوت بالنسب المئوية. |
| [getTrimFromStart()](#getTrimFromStart--) | تحديد مدة الزمن التي يجب إزالتها من بداية الوسائط أثناء التشغيل بالملي ثانية. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | تحديد مدة الزمن التي يجب إزالتها من بداية الوسائط أثناء التشغيل بالملي ثانية. |
| [getTrimFromEnd()](#getTrimFromEnd--) | تحديد مدة الزمن التي يجب إزالتها من نهاية الوسائط أثناء التشغيل بالملي ثانية. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | تحديد مدة الزمن التي يجب إزالتها من نهاية الوسائط أثناء التشغيل بالملي ثانية. |
| [getCaptionTracks()](#getCaptionTracks--) | يحصل على مجموعة الترميزات المغلقة المرتبطة بإطار الصوت. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

إرجاع أو تعيين فهرس المسار البادئ. قراءة/كتابة int.

**الإرجاع:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

إرجاع أو تعيين فهرس المسار البادئ. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

إرجاع أو تعيين وقت بداية المسار. قراءة/كتابة int.

**الإرجاع:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

إرجاع أو تعيين وقت بداية المسار. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

إرجاع أو تعيين فهرس آخر مسار. قراءة/كتابة int.

**الإرجاع:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

إرجاع أو تعيين فهرس آخر مسار. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

إرجاع أو تعيين وقت آخر مسار. قراءة/كتابة int.

**الإرجاع:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

إرجاع أو تعيين وقت آخر مسار. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

إرجاع أو تعيين مستوى الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**الإرجاع:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

إرجاع أو تعيين مستوى الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

إرجاع أو تعيين نمط تشغيل الصوت. قراءة/كتابة [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**الإرجاع:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

إرجاع أو تعيين نمط تشغيل الصوت. قراءة/كتابة [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

تحديد ما إذا كان AudioFrame مخفيًا. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

تحديد ما إذا كان AudioFrame مخفيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

تحديد ما إذا كان الصوت مكرّرًا. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

تحديد ما إذا كان الصوت مكرّرًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

تحديد ما إذا كان الصوت يُشغَل عبر الشرائح. قراءة/كتابة boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوت
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت ليُشغل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة التشغيل تلقائيًا إلى البداية بعد التشغيل
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
public abstract void setPlayAcrossSlides(boolean value)
```

تحديد ما إذا كان الصوت يُشغَل عبر الشرائح. قراءة/كتابة boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوت
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت ليُشغل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة تشغيله تلقائيًا إلى البداية بعد التشغيل
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
public abstract boolean getRewindAudio()
```

تحديد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. قراءة/كتابة boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوت
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت ليُشغل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة تشغيله تلقائيًا إلى البداية بعد التشغيل
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
public abstract void setRewindAudio(boolean value)
```

تحديد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. قراءة/كتابة boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوت
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت ليُشغل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة تشغيله تلقائيًا إلى البداية بعد التشغيل
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
public abstract boolean getEmbedded()
```

تحديد ما إذا كان الصوت مدمجًا في العرض التقديمي. قراءة فقط boolean.

**الإرجاع:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

إرجاع أو تعيين كائن صوت مدمج. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

إرجاع أو تعيين كائن صوت مدمج. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

تحديد مدة الزمن للظهور التدريجي الأولي للوسائط بالملي ثانية. قراءة/كتابة float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين مدة التلاشي الأولية إلى 200 مللي ثانية
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
public abstract void setFadeInDuration(float value)
```

تحديد مدة الزمن للظهور التدريجي الأولي للوسائط بالملي ثانية. قراءة/كتابة float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين مدة التلاشي الأولية إلى 200 مللي ثانية
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
public abstract float getFadeOutDuration()
```

تحديد مدة الزمن للانخفاض التدريجي النهائي للوسائط بالملي ثانية. قراءة/كتابة float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين مدة التلاشي النهائي إلى 500 مللي ثانية
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
public abstract void setFadeOutDuration(float value)
```

تحديد مدة الزمن للانخفاض التدريجي النهائي للوسائط بالملي ثانية. قراءة/كتابة float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين مدة التلاشي النهائي إلى 500 مللي ثانية
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
public abstract float getVolumeValue()
```

إرجاع أو تعيين مستوى الصوت بالنسب المئوية. قراءة/كتابة float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ضبط مستوى صوت الإطار إلى 85٪
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
public abstract void setVolumeValue(float value)
```

إرجاع أو تعيين مستوى الصوت بالنسب المئوية. قراءة/كتابة float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ضبط مستوى صوت الإطار إلى 85٪
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
public abstract float getTrimFromStart()
```

تحديد مدة الزمن التي يجب إزالتها من بداية الوسائط أثناء التشغيل بالملي ثانية. قراءة/كتابة float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت قص البداية 1.5 ثانية
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

تحديد مدة الزمن التي يجب إزالتها من بداية الوسائط أثناء التشغيل بالملي ثانية. قراءة/كتابة float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت قص البداية 1.5 ثانية
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
public abstract float getTrimFromEnd()
```

تحديد مدة الزمن التي يجب إزالتها من نهاية الوسائط أثناء التشغيل بالملي ثانية. قراءة/كتابة float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ضبط وقت القص النهائي إلى 2 ثانية
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

تحديد مدة الزمن التي يجب إزالتها من نهاية الوسائط أثناء التشغيل بالملي ثانية. قراءة/كتابة float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ضبط وقت القص النهائي إلى 2 ثانية
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
public abstract ICaptionsCollection getCaptionTracks()
```

يحصل على مجموعة الترميزات المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) يحتوي على جميع مسارات الترميز.

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
>             // حفظ البيانات الثنائية لمسار التسمية التوضيحية كملف .vtt
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

**الإرجاع:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)