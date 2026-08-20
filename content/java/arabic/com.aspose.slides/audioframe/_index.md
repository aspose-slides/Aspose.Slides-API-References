---
title: AudioFrame
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مقطعًا صوتيًا على شريحة.
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

يمثِل مقطع صوتي على الشريحة.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // يحصل على شكل AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // يحدد وضع التشغيل لتشغيل عند النقر
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // يحدد مستوى الصوت إلى منخفض
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // يحدد تشغيل الصوت عبر الشرائح
>      audioFrame.setPlayAcrossSlides(true);
>      // يعطل تكرار الصوت
>      audioFrame.setPlayLoopMode(false);
>      // يخفي AudioFrame أثناء عرض الشرائح
>      audioFrame.setHideAtShowing(true);
>      // يرجع الصوت إلى البداية بعد التشغيل
>      audioFrame.setRewindAudio(true);
>      // يحفظ ملف PowerPoint إلى القرص
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methods

| الطريقة | الوصف |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | يرجع أو يضبط فهرس مسار البدء. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | يرجع أو يضبط فهرس مسار البدء. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | يرجع أو يضبط زمن مسار البدء. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | يرجع أو يضبط زمن مسار البدء. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | يرجع أو يضبط فهرس المسار الأخير قراءة/كتابة  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | يرجع أو يضبط فهرس المسار الأخير قراءة/كتابة  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | يرجع أو يضبط زمن المسار الأخير. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | يرجع أو يضبط زمن المسار الأخير. |
| [getVolume()](#getVolume--) | يرجع أو يضبط مستوى صوت الصوت. |
| [setVolume(int value)](#setVolume-int-) | يرجع أو يضبط مستوى صوت الصوت. |
| [getPlayMode()](#getPlayMode--) | يرجع أو يضبط وضع تشغيل الصوت. |
| [setPlayMode(int value)](#setPlayMode-int-) | يرجع أو يضبط وضع تشغيل الصوت. |
| [getHideAtShowing()](#getHideAtShowing--) | يحدد ما إذا كان AudioFrame مخفيًا. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | يحدد ما إذا كان AudioFrame مخفيًا. |
| [getPlayLoopMode()](#getPlayLoopMode--) | يحدد ما إذا كان الصوت معادًا. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | يحدد ما إذا كان الصوت معادًا. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | يحدد ما إذا كان الصوت يُشَغَّل عبر الشرائح. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | يحدد ما إذا كان الصوت يُشَغَّل عبر الشرائح. |
| [getRewindAudio()](#getRewindAudio--) | يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. |
| [getEmbedded()](#getEmbedded--) | يحدد ما إذا كان الصوت مدمجًا في العرض التقديمي. |
| [getLinkPathLong()](#getLinkPathLong--) | يرجع أو يضبط اسم ملف صوتي مرتبط بـ AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | يرجع أو يضبط اسم ملف صوتي مرتبط بـ AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | يرجع أو يضبط كائن الصوت المدمج. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | يرجع أو يضبط كائن الصوت المدمج. |
| [getFadeInDuration()](#getFadeInDuration--) | يحدد مدة الوقت للاندماج الأولي للوسائط بالمللي ثانية. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | يحدد مدة الوقت للاندماج الأولي للوسائط بالمللي ثانية. |
| [getFadeOutDuration()](#getFadeOutDuration--) | يحدد مدة الوقت للاندماج النهائي للوسائط بالمللي ثانية. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | يحدد مدة الوقت للاندماج النهائي للوسائط بالمللي ثانية. |
| [getVolumeValue()](#getVolumeValue--) | يرجع أو يضبط مستوى صوت الصوت بالنسبة المئوية. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | يرجع أو يضبط مستوى صوت الصوت بالنسبة المئوية. |
| [getTrimFromStart()](#getTrimFromStart--) | يحدد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالمللي ثانية. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | يحدد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالمللي ثانية. |
| [getTrimFromEnd()](#getTrimFromEnd--) | يحدد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | يحدد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. |
| [getCaptionTracks()](#getCaptionTracks--) | يحصل على مجموعة العناوين المغلقة المرتبطة بإطار الصوت. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

يرجع أو يضبط فهرس مسار البدء. قراءة/كتابة  int .

**الإرجاع:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

يرجع أو يضبط فهرس مسار البدء. قراءة/كتابة  int .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

يرجع أو يضبط زمن مسار البدء. قراءة/كتابة  int .

**الإرجاع:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

يرجع أو يضبط زمن مسار البدء. قراءة/كتابة  int .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

يرجع أو يضبط فهرس المسار الأخير قراءة/كتابة  int .

**الإرجاع:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

يرجع أو يضبط فهرس المسار الأخير قراءة/كتابة  int .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

يرجع أو يضبط زمن المسار الأخير. قراءة/كتابة  int .

**الإرجاع:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

يرجع أو يضبط زمن المسار الأخير. قراءة/كتابة  int .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

يرجع أو يضبط مستوى صوت الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**الإرجاع:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

يرجع أو يضبط مستوى صوت الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

يرجع أو يضبط وضع تشغيل الصوت. قراءة/كتابة [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**الإرجاع:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

يرجع أو يضبط وضع تشغيل الصوت. قراءة/كتابة [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

يحدد ما إذا كان AudioFrame مخفيًا. قراءة/كتابة  boolean .

**الإرجاع:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

يحدد ما إذا كان AudioFrame مخفيًا. قراءة/كتابة  boolean .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

يحدد ما إذا كان الصوت معادًا. قراءة/كتابة  boolean .

**الإرجاع:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

يحدد ما إذا كان الصوت معادًا. قراءة/كتابة  boolean .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

يحدد ما إذا كان الصوت يُشَغَّل عبر الشرائح. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تحديد تشغيل الصوت عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // تحديد إعادة تشغيل الصوت تلقائيًا إلى البداية بعد التشغيل
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

يحدد ما إذا كان الصوت يُشَغَّل عبر الشرائح. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تحديد تشغيل الصوت عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // تحديد إعادة تشغيل الصوت تلقائيًا إلى البداية بعد التشغيل
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

يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // تحديد تشغيل الصوت عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // تحديد إعادة تشغيل الصوت تلقائيًا إلى البداية بعد التشغيل
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

يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // إضافة إطار صوتي
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ضبط تشغيل الصوت عبر الشرائح
>       audioFrame.setPlayAcrossSlides(true);
>       // ضبط إعادة تشغيل الصوت تلقائيًا إلى البداية بعد التشغيل
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

يحدد ما إذا كان الصوت مدمجًا في العرض التقديمي. قراءة فقط  boolean .

**الإرجاع:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

يرجع أو يضبط اسم ملف صوتي مرتبط بـ AudioFrame. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

يرجع أو يضبط اسم ملف صوتي مرتبط بـ AudioFrame. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

يرجع أو يضبط كائن الصوت المدمج. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

يرجع أو يضبط كائن الصوت المدمج. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

يحدد مدة الوقت للاندماج الأولي للوسائط بالمللي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // اضبط مدة الاندماج الأولي إلى 200 مللي ثانية
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

يحدد مدة الوقت للاندماج الأولي للوسائط بالمللي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // اضبط مدة الاندماج الأولي إلى 200 مللي ثانية
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

يحدد مدة الوقت للاندماج النهائي للوسائط بالمللي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // اضبط مدة الاندماج النهائي إلى 500 مللي ثانية
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

يحدد مدة الوقت للاندماج النهائي للوسائط بالمللي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // اضبط مدة الاندماج النهائي إلى 500 مللي ثانية
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

يرجع أو يضبط مستوى صوت الصوت بالنسبة المئوية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // اضبط مستوى صوت الصوت إلى 85%
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

يرجع أو يضبط مستوى صوت الصوت بالنسبة المئوية. قراءة/كتابة float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // اضبط مستوى صوت الصوت إلى 85%
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

يحدد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // حدد وقت القص من البداية 1.5 ثانية
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

يحدد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // حدد وقت القص من البداية 1.5 ثانية
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

يحدد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // حدد وقت القص من النهاية 2 ثانية
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

يحدد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة/كتابة float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // حدد وقت القص من النهاية 2 ثانية
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

يحصل على مجموعة العناوين المغلقة المرتبطة بإطار الصوت. هذه الخاصية قراءة فقط وتُرجِع [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) يحتوي جميع مسارات العناوين.

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
>              // احفظ البيانات الثنائية لمسار التسميات التوضيحية كملف .vtt
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