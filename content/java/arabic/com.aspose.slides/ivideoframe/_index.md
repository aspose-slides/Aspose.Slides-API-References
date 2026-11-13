---
title: IVideoFrame
second_title: مرجع API ل Aspose.Slides لـ Java
description: يمثل مقطع فيديو على شريحة.
type: docs
url: /ar/com.aspose.slides/ivideoframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

يمثل مقطع فيديو على شريحة.
## طرق

| الطريقة | الوصف |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | يحدد ما إذا كان الفيديو يُعاد تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | يحدد ما إذا كان الفيديو يُعاد تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. |
| [getPlayLoopMode()](#getPlayLoopMode--) | يحدد ما إذا كان الفيديو يتكرر. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | يحدد ما إذا كان الفيديو يتكرر. |
| [getHideAtShowing()](#getHideAtShowing--) | يحدد ما إذا كان VideoFrame مخفيًا. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | يحدد ما إذا كان VideoFrame مخفيًا. |
| [getVolume()](#getVolume--) | إرجاع أو تعيين حجم الصوت. |
| [setVolume(int value)](#setVolume-int-) | إرجاع أو تعيين حجم الصوت. |
| [getVolumeValue()](#getVolumeValue--) | إرجاع أو تعيين حجم الفيديو بدقة كنسبة مئوية. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | إرجاع أو تعيين حجم الفيديو بدقة كنسبة مئوية. |
| [getPlayMode()](#getPlayMode--) | إرجاع أو تعيين وضع تشغيل الفيديو. |
| [setPlayMode(int value)](#setPlayMode-int-) | إرجاع أو تعيين وضع تشغيل الفيديو. |
| [getFullScreenMode()](#getFullScreenMode--) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو تعيين اسم ملف فيديو مرتبط بـ VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو تعيين اسم ملف فيديو مرتبط بـ VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | إرجاع أو تعيين كائن فيديو مضمن. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | إرجاع أو تعيين كائن فيديو مضمن. |
| [getTrimFromStart()](#getTrimFromStart--) | بدء القص [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | بدء القص [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | انتهاء القص [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | انتهاء القص [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | يحصل على مجموعة التسميات التوضيحية المغلقة المرتبطة بإطار الصوت. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```


يحدد ما إذا كان الفيديو يُعاد تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```


يحدد ما إذا كان الفيديو يُعاد تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```


يحدد ما إذا كان الفيديو يتكرر. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```


يحدد ما إذا كان الفيديو يتكرر. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```


يحدد ما إذا كان VideoFrame مخفيًا. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```


يحدد ما إذا كان VideoFrame مخفيًا. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```


إرجاع أو تعيين حجم الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**الإرجاع:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```


إرجاع أو تعيين حجم الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```


إرجاع أو تعيين حجم الفيديو الدقيق كنسبة مئوية. القيم تُعبر كنسبة مئوية من 0 إلى 100. استخدم هذه الخاصية لقراءة أو تعيين قيم حجم أكثر دقة من المستويات المحددة مسبقًا المتاحة عبر خاصية Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). قراءة/كتابة float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // قراءة الحجم الدقيق الحالي وتعيينه إلى 75.5 بالمئة.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
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


إرجاع أو تعيين حجم الفيديو الدقيق كنسبة مئوية. القيم تُعبر كنسبة مئوية من 0 إلى 100. استخدم هذه الخاصية لقراءة أو تعيين قيم حجم أكثر دقة من المستويات المحددة مسبقًا المتاحة عبر خاصية Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). قراءة/كتابة float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // قراءة الحجم الدقيق الحالي وتعيينه إلى 75.5 بالمئة.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```


إرجاع أو تعيين وضع تشغيل الفيديو. قراءة/كتابة [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**الإرجاع:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```


إرجاع أو تعيين وضع تشغيل الفيديو. قراءة/كتابة [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```


يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```


يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


إرجاع أو تعيين اسم ملف فيديو مرتبط بـ VideoFrame. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


إرجاع أو تعيين اسم ملف فيديو مرتبط بـ VideoFrame. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```


إرجاع أو تعيين كائن فيديو مضمن. قراءة/كتابة [IVideo](../../com.aspose.slides/ivideo).

**الإرجاع:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```


إرجاع أو تعيين كائن فيديو مضمن. قراءة/كتابة [IVideo](../../com.aspose.slides/ivideo).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```


بدء القص [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ضبط وقت بدء القص 1 ثانية
>      videoFrame.setTrimFromStart(1000f);
>      //ضبط وقت انتهاء القص 2 ثانية
>      videoFrame.setTrimFromEnd(2000f);
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


بدء القص [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ضبط وقت بدء القص 1 ثانية
>      videoFrame.setTrimFromStart(1000f);
>      //ضبط وقت انتهاء القص 2 ثانية
>      videoFrame.setTrimFromEnd(2000f);
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


انتهاء القص [ms]

**الإرجاع:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```


انتهاء القص [ms]

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```


يحصل على مجموعة التسميات التوضيحية المغلقة المرتبطة بإطار الصوت. هذه الخاصية قراءة فقط وتُرجع [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) يحتوي على جميع مسارات التسمية.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (!(shape instanceof IVideoFrame))
>              continue;
>          IVideoFrame videoFrame = (IVideoFrame) shape;
>          for (ICaptions captionTrack : videoFrame.getCaptionTracks())
>          {
>              // يستخرج البيانات الثنائية للتسميات ويحفظها إلى الملف
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)