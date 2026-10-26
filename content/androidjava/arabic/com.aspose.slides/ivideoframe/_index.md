---
title: IVideoFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API للجاڤا
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
| [getRewindVideo()](#getRewindVideo--) | يحدد ما إذا كان يتم إرجاع الفيديو تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | يحدد ما إذا كان يتم إرجاع الفيديو تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. |
| [getPlayLoopMode()](#getPlayLoopMode--) | يحدد ما إذا كان الفيديو يكرر التشغيل. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | يحدد ما إذا كان الفيديو يكرر التشغيل. |
| [getHideAtShowing()](#getHideAtShowing--) | يحدد ما إذا كان VideoFrame مخفيًا. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | يحدد ما إذا كان VideoFrame مخفيًا. |
| [getVolume()](#getVolume--) | إرجاع أو ضبط مستوى الصوت. |
| [setVolume(int value)](#setVolume-int-) | إرجاع أو ضبط مستوى الصوت. |
| [getPlayMode()](#getPlayMode--) | إرجاع أو ضبط وضع تشغيل الفيديو. |
| [setPlayMode(int value)](#setPlayMode-int-) | إرجاع أو ضبط وضع تشغيل الفيديو. |
| [getFullScreenMode()](#getFullScreenMode--) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو ضبط اسم ملف الفيديو المرتبط بـ VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو ضبط اسم ملف الفيديو المرتبط بـ VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | إرجاع أو ضبط كائن الفيديو المدمج. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | إرجاع أو ضبط كائن الفيديو المدمج. |
| [getTrimFromStart()](#getTrimFromStart--) | تقليم البداية [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | تقليم البداية [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | تقليم النهاية [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | تقليم النهاية [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | يحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

يحدد ما إذا كان يتم إرجاع الفيديو تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

يحدد ما إذا كان يتم إرجاع الفيديو تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

يحدد ما إذا كان الفيديو يكرر التشغيل. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

يحدد ما إذا كان الفيديو يكرر التشغيل. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

يحدد ما إذا كان VideoFrame مخفيًا. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

يحدد ما إذا كان VideoFrame مخفيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

يرجع أو يضبط مستوى الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**القيمة المرجعة:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

يرجع أو يضبط مستوى الصوت. قراءة/كتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

يرجع أو يضبط وضع تشغيل الفيديو. قراءة/كتابة [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**القيمة المرجعة:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

يرجع أو يضبط وضع تشغيل الفيديو. قراءة/كتابة [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

يرجع أو يضبط اسم ملف الفيديو المرتبط بـ VideoFrame. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

يرجع أو يضبط اسم ملف الفيديو المرتبط بـ VideoFrame. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

يرجع أو يضبط كائن الفيديو المضمن. قراءة/كتابة [IVideo](../../com.aspose.slides/ivideo).

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

يرجع أو يضبط كائن الفيديو المضمن. قراءة/كتابة [IVideo](../../com.aspose.slides/ivideo).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

تقليم البداية [ms]

--------------------

> ```markdown
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //تعيين زمن بدء القطع 1 ثانية
>      videoFrame.setTrimFromStart(1000f);
>      //تعيين زمن نهاية القطع 2 ثانية
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

تقليم البداية [ms]

--------------------

> ```markdown
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //تحديد زمن بدء القطع 1 ثانية
>      videoFrame.setTrimFromStart(1000f);
>      //تحديد زمن نهاية القطع 2 ثانية
>      videoFrame.setTrimFromEnd(2000f);
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

تقليم النهاية [ms]

**القيمة المرجعة:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

تقليم النهاية [ms]

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

يحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتُرجِع [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) يحتوي على جميع مسارات الترجمات.

--------------------

> ```markdown
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
>              // يستخرج البيانات الثنائية للتعليقات ويحفظها في الملف
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)