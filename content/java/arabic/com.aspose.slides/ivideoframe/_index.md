---
title: IVideoFrame
second_title: مرجع API Aspose.Slides للغة Java
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
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | يحدد ما إذا كان الفيديو يُعاد إلى البداية تلقائيًا بمجرد انتهاء تشغيل الفيلم. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | يحدد ما إذا كان الفيديو يُعاد إلى البداية تلقائيًا بمجرد انتهاء تشغيل الفيلم. |
| [getPlayLoopMode()](#getPlayLoopMode--) | يحدد ما إذا كان الفيديو يتكرر. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | يحدد ما إذا كان الفيديو يتكرر. |
| [getHideAtShowing()](#getHideAtShowing--) | يحدد ما إذا كان VideoFrame مخفيًا. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | يحدد ما إذا كان VideoFrame مخفيًا. |
| [getVolume()](#getVolume--) | إرجاع أو تعيين حجم الصوت. |
| [setVolume(int value)](#setVolume-int-) | إرجاع أو تعيين حجم الصوت. |
| [getPlayMode()](#getPlayMode--) | إرجاع أو تعيين وضع تشغيل الفيديو. |
| [setPlayMode(int value)](#setPlayMode-int-) | إرجاع أو تعيين وضع تشغيل الفيديو. |
| [getFullScreenMode()](#getFullScreenMode--) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو تعيين اسم ملف فيديو مرتبط بـ VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو تعيين اسم ملف فيديو مرتبط بـ VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | إرجاع أو تعيين كائن الفيديو المدمج. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | إرجاع أو تعيين كائن الفيديو المدمج. |
| [getTrimFromStart()](#getTrimFromStart--) | بدء التقليم [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | بدء التقليم [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | نهاية التقليم [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | نهاية التقليم [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | يحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

يحدد ما إذا كان الفيديو يُعاد إلى البداية تلقائيًا بمجرد انتهاء تشغيل الفيلم. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

يحدد ما إذا كان الفيديو يُعاد إلى البداية تلقائيًا بمجرد انتهاء تشغيل الفيلم. قراءة/كتابة boolean.

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

إرجاع أو تعيين كائن الفيديو المدمج. قراءة/كتابة [IVideo](../../com.aspose.slides/ivideo).

**الإرجاع:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

إرجاع أو تعيين كائن الفيديو المدمج. قراءة/كتابة [IVideo](../../com.aspose.slides/ivideo).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

بدء التقليم [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //تعيين وقت بدء القطع 1 ثانية
>      videoFrame.setTrimFromStart(1000f);
>      //تعيين وقت انتهاء القطع 2 ثانية
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

بدء التقليم [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //تعيين وقت بدء القطع 1 ثانية
>      videoFrame.setTrimFromStart(1000f);
>      //تعيين وقت انتهاء القطع 2 ثانية
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

نهاية التقليل [ms]

**الإرجاع:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

نهاية التقليل [ms]

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

يحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتُعيد [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) يحتوي على جميع مسارات الترجمة.

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
>              // يستخرج البيانات الثنائية للترجمات ويحفظها في الملف
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