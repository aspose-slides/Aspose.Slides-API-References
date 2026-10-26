---
title: VideoFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل مقطع فيديو على شريحة.
type: docs
url: /ar/com.aspose.slides/videoframe/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

يمثل مقطع فيديو على شريحة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | يحدد ما إذا كان يتم إعادة تشغيل الفيديو تلقائيًا إلى البداية بمجرد انتهاء الفيلم من التشغيل. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | يحدد ما إذا كان يتم إعادة تشغيل الفيديو تلقائيًا إلى البداية بمجرد انتهاء الفيلم من التشغيل. |
| [getPlayLoopMode()](#getPlayLoopMode--) | يحدد ما إذا كان الفيديو يتم تشغيله بشكل متكرر. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | يحدد ما إذا كان الفيديو يتم تشغيله بشكل متكرر. |
| [getHideAtShowing()](#getHideAtShowing--) | يحدد ما إذا كان VideoFrame مخفيًا. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | يحدد ما إذا كان VideoFrame مخفيًا. |
| [getVolume()](#getVolume--) | إرجاع أو تعيين حجم الصوت. |
| [setVolume(int value)](#setVolume-int-) | إرجاع أو تعيين حجم الصوت. |
| [getPlayMode()](#getPlayMode--) | إرجاع أو تعيين وضع تشغيل الفيديو. |
| [setPlayMode(int value)](#setPlayMode-int-) | إرجاع أو تعيين وضع تشغيل الفيديو. |
| [getFullScreenMode()](#getFullScreenMode--) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو تعيين اسم ملف الفيديو المرتبط بـ VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو تعيين اسم ملف الفيديو المرتبط بـ VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | إرجاع أو تعيين كائن الفيديو المضمّن. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | إرجاع أو تعيين كائن الفيديو المضمّن. |
| [getTrimFromStart()](#getTrimFromStart--) | بداية القص [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | بداية القص [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | نهاية القص [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | نهاية القص [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | الحصول على مجموعة الترجمة المغلقة المرتبطة بإطار الفيديو. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

يحدد ما إذا كان يتم إعادة تشغيل الفيديو تلقائيًا إلى البداية بمجرد انتهاء الفيلم من التشغيل. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

يحدد ما إذا كان يتم إعادة تشغيل الفيديو تلقائيًا إلى البداية بمجرد انتهاء الفيلم من التشغيل. قابل للقراءة والكتابة boolean.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

يحدد ما إذا كان الفيديو يتم تشغيله بشكل متكرر. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

يحدد ما إذا كان الفيديو يتم تشغيله بشكل متكرر. قابل للقراءة والكتابة boolean.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

يحدد ما إذا كان VideoFrame مخفيًا. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

يحدد ما إذا كان VideoFrame مخفيًا. قابل للقراءة والكتابة boolean.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

إرجاع أو تعيين حجم الصوت. قابل للقراءة والكتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**القيمة المرجعة:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

إرجاع أو تعيين حجم الصوت. قابل للقراءة والكتابة [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

إرجاع أو تعيين وضع تشغيل الفيديو. قابل للقراءة والكتابة [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**القيمة المرجعة:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

إرجاع أو تعيين وضع تشغيل الفيديو. قابل للقراءة والكتابة [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. قابل للقراءة والكتابة boolean.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

إرجاع أو تعيين اسم ملف الفيديو المرتبط بـ VideoFrame. قابل للقراءة والكتابة String.

**القيمة المرجعة:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

إرجاع أو تعيين اسم ملف الفيديو المرتبط بـ VideoFrame. قابل للقراءة والكتابة String.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

إرجاع أو تعيين كائن الفيديو المضمّن. قابل للقراءة والكتابة [IVideo](../../com.aspose.slides/ivideo).

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

إرجاع أو تعيين كائن الفيديو المضمّن. قابل للقراءة والكتابة [IVideo](../../com.aspose.slides/ivideo).

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

بداية القص [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //تعيين وقت بدء القطع 1 ثانية
>      videoFrame.setTrimFromStart(1000f);
>      //تعيين وقت نهاية القطع 2 ثانية
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

بداية القص [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //تعيين وقت بدء القطع 1 ثانية
>      videoFrame.setTrimFromStart(1000f);
>      //تعيين وقت نهاية القطع 2 ثانية
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

نهاية القص [ms]

**القيمة المرجعة:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

نهاية القص [ms]

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

الحصول على مجموعة الترجمة المغلقة المرتبطة بإطار الفيديو. هذه الخاصية للقراءة فقط وتُرجع [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) يحتوي على جميع مسارات الترجمة.

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
>              // يستخرج البيانات الثنائية للترجمات ويحفظها إلى الملف
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