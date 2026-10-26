---
title: IAudioFrame
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يمثل مقطعًا صوتيًا على شريحة.
type: docs
url: /ar/com.aspose.slides/iaudioframe/
---
**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

يمثل مقطع صوتي على شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | إرجاع أو تعيين فهرس مسار البداية. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | إرجاع أو تعيين فهرس مسار البداية. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | إرجاع أو تعيين وقت مسار البدء. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | إرجاع أو تعيين وقت مسار البدء. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | إرجاع أو تعيين فهرس المسار الأخير قراءة/كتابة int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | إرجاع أو تعيين فهرس المسار الأخير قراءة/كتابة int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | إرجاع أو تعيين وقت المسار الأخير. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | إرجاع أو تعيين وقت المسار الأخير. |
| [getVolume()](#getVolume--) | إرجاع أو تعيين مستوى الصوت. |
| [setVolume(int value)](#setVolume-int-) | إرجاع أو تعيين مستوى الصوت. |
| [getPlayMode()](#getPlayMode--) | إرجاع أو تعيين وضع تشغيل الصوت. |
| [setPlayMode(int value)](#setPlayMode-int-) | إرجاع أو تعيين وضع تشغيل الصوت. |
| [getHideAtShowing()](#getHideAtShowing--) | تحديد ما إذا كان AudioFrame مخفيًا. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | تحديد ما إذا كان AudioFrame مخفيًا. |
| [getPlayLoopMode()](#getPlayLoopMode--) | تحديد ما إذا كان الصوت يتكرر. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | تحديد ما إذا كان الصوت يتكرر. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | تحديد ما إذا كان الصوت يتم تشغيله عبر الشرائح. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | تحديد ما إذا كان الصوت يتم تشغيله عبر الشرائح. |
| [getRewindAudio()](#getRewindAudio--) | تحديد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | تحديد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. |
| [getEmbedded()](#getEmbedded--) | تحديد ما إذا كان الصوت مدمجًا في العرض التقديمي. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو تعيين اسم ملف الصوت المرتبط بـ AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو تعيين اسم ملف الصوت المرتبط بـ AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | إرجاع أو تعيين كائن الصوت المضمّن. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | إرجاع أو تعيين كائن الصوت المضمّن. |
| [getFadeInDuration()](#getFadeInDuration--) | تحديد مدة الوقت للظهور التدريجي الأولي للوسائط بالملي ثانية. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | تحديد مدة الوقت للظهور التدريجي الأولي للوسائط بالملي ثانية. |
| [getFadeOutDuration()](#getFadeOutDuration--) | تحديد مدة الوقت للانخفاض التدريجي النهائي للوسائط بالملي ثانية. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | تحديد مدة الوقت للانخفاض التدريجي النهائي للوسائط بالملي ثانية. |
| [getVolumeValue()](#getVolumeValue--) | إرجاع أو تعيين مستوى الصوت بالنسبة المئوية. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | إرجاع أو تعيين مستوى الصوت بالنسبة المئوية. |
| [getTrimFromStart()](#getTrimFromStart--) | تحديد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | تحديد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. |
| [getTrimFromEnd()](#getTrimFromEnd--) | تحديد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | تحديد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. |
| [getCaptionTracks()](#getCaptionTracks--) | جلب مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

إرجاع أو تعيين فهرس مسار البدء. قراءة/كتابة int.

**الإرجاع:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

إرجاع أو تعيين فهرس مسار البدء. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

إرجاع أو تعيين وقت مسار البدء. قراءة/كتابة int.

**الإرجاع:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

إرجاع أو تعيين وقت مسار البدء. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

إرجاع أو تعيين فهرس المسار الأخير قراءة/كتابة int.

**الإرجاع:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

إرجاع أو تعيين فهرس المسار الأخير قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

إرجاع أو تعيين وقت المسار الأخير. قراءة/كتابة int.

**الإرجاع:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

إرجاع أو تعيين وقت المسار الأخير. قراءة/كتابة int.

**المعاملات:**
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

إرجاع أو تعيين وضع تشغيل الصوت. قراءة/كتابة [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**الإرجاع:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

إرجاع أو تعيين وضع تشغيل الصوت. قراءة/كتابة [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**المعاملات:**
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

تحديد ما إذا كان الصوت يتكرر. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

تحديد ما إذا كان الصوت يتكرر. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

تحديد ما إذا كان الصوت يتم تشغيله عبر الشرائح. قراءة/كتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت للتشغيل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة تشغيل تلقائيًا إلى البداية بعد التشغيل
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

تحديد ما إذا كان الصوت يتم تشغيله عبر الشرائح. قراءة/كتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت للتشغيل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة تشغيل تلقائيًا إلى البداية بعد التشغيل
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

تحديد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. قراءة/كتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت للتشغيل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة تشغيل تلقائيًا إلى البداية بعد التشغيل
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

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط الصوت للتشغيل عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط الصوت لإعادة تشغيل تلقائيًا إلى البداية بعد التشغيل
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

تحديد ما إذا كان الصوت مدمجًا في العرض التقديمي. للقراءة فقط boolean.

**الإرجاع:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

إرجاع أو تعيين اسم ملف الصوت المرتبط بـ AudioFrame. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

إرجاع أو تعيين اسم ملف الصوت المرتبط بـ AudioFrame. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

إرجاع أو تعيين كائن الصوت المضمّن. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

إرجاع أو تعيين كائن الصوت المضمّن. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

تحديد مدة الوقت للظهور التدريجي الأولي للوسائط بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تحديد مدة الظهور التدريجي الابتدائي لـ 200 مللي ثانية
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

تحديد مدة الوقت للظهور التدريجي الأولي للوسائط بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تحديد مدة الظهور التدريجي الابتدائي لـ 200 مللي ثانية
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

تحديد مدة الوقت للانخفاض التدريجي النهائي للوسائط بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تحديد مدة الانخفاض التدريجي النهائي لـ 500 مللي ثانية
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

تحديد مدة الوقت للانخفاض التدريجي النهائي للوسائط بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تحديد مدة الانخفاض التدريجي النهائي لـ 500 مللي ثانية
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

إرجاع أو تعيين مستوى الصوت بالنسبة المئوية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ضبط مستوى الصوت على 85%
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

إرجاع أو تعيين مستوى الصوت بالنسبة المئوية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ضبط مستوى الصوت إلى 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

تحديد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت البدء للقص 1.5 ثانية
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

تحديد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت القص الابتدائي 1.5 ثانية
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

تحديد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت القص النهائي 2 ثانية
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

تحديد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // تعيين وقت القص النهائي 2 ثانية
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

جلب مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) يحتوي جميع مسارات الترجمات.

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
>             // حفظ البيانات الثنائية لمسار التسمية كملف .vtt
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