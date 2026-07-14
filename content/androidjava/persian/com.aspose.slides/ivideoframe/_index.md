---
title: IVideoFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک کلیپ ویدئویی را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ivideoframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

یک کلیپ ویدئویی را بر روی اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | مشخص می‌کند که آیا یک ویدئو به‌صورت خودکار پس از اتمام فیلم به شروع باز می‌گردد. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | مشخص می‌کند که آیا یک ویدئو به‌صورت خودکار پس از اتمام فیلم به شروع باز می‌گردد. |
| [getPlayLoopMode()](#getPlayLoopMode--) | مشخص می‌کند که آیا یک ویدئو به صورت حلقه‌ای پخش می‌شود. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | مشخص می‌کند که آیا یک ویدئو به صورت حلقه‌ای پخش می‌شود. |
| [getHideAtShowing()](#getHideAtShowing--) | مشخص می‌کند که آیا VideoFrame مخفی است. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | مشخص می‌کند که آیا VideoFrame مخفی است. |
| [getVolume()](#getVolume--) | حجم صدا را باز می‌گرداند یا تنظیم می‌کند. |
| [setVolume(int value)](#setVolume-int-) | حجم صدا را باز می‌گرداند یا تنظیم می‌کند. |
| [getPlayMode()](#getPlayMode--) | حالت پخش ویدئو را باز می‌گرداند یا تنظیم می‌کند. |
| [setPlayMode(int value)](#setPlayMode-int-) | حالت پخش ویدئو را باز می‌گرداند یا تنظیم می‌کند. |
| [getFullScreenMode()](#getFullScreenMode--) | مشخص می‌کند که آیا ویدئو در حالت تمام‌صفحه نمایش داده می‌شود. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | مشخص می‌کند که آیا ویدئو در حالت تمام‌صفحه نمایش داده می‌شود. |
| [getLinkPathLong()](#getLinkPathLong--) | نام فایل ویدئویی که به VideoFrame پیوند داده شده است را باز می‌گرداند یا تنظیم می‌کند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | نام فایل ویدئویی که به VideoFrame پیوند داده شده است را باز می‌گرداند یا تنظیم می‌کند. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | شی ویدئوی جاسازی‌شده را باز می‌گرداند یا تنظیم می‌کند. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | شی ویدئوی جاسازی‌شده را باز می‌گرداند یا تنظیم می‌کند. |
| [getTrimFromStart()](#getTrimFromStart--) | برش از ابتدا [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | برش از ابتدا [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | برش از انتها [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | برش از انتها [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | مجموعه زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

مشخص می‌کند که آیا یک ویدئو به‌صورت خودکار پس از اتمام فیلم به شروع باز می‌گردد. قابل خواندن/نوشتن boolean.

**باز می‌گردد:**
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

مشخص می‌کند که آیا یک ویدئو به‌صورت خودکار پس از اتمام فیلم به شروع باز می‌گردد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

مشخص می‌کند که آیا یک ویدئو به صورت حلقه‌ای پخش می‌شود. قابل خواندن/نوشتن boolean.

**باز می‌گردد:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

مشخص می‌کند که آیا یک ویدئو به صورت حلقه‌ای پخش می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

مشخص می‌کند که آیا VideoFrame مخفی است. قابل خواندن/نوشتن boolean.

**باز می‌گردد:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

مشخص می‌کند که آیا VideoFrame مخفی است. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

حجم صدا را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**باز می‌گردد:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

حجم صدا را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

حالت پخش ویدئو را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**باز می‌گردد:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

حالت پخش ویدئو را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

مشخص می‌کند که آیا ویدئو در حالت تمام‌صفحه نمایش داده می‌شود. قابل خواندن/نوشتن boolean.

**باز می‌گردد:**
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

مشخص می‌کند که آیا ویدئو در حالت تمام‌صفحه نمایش داده می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

نام فایل ویدئویی که به VideoFrame پیوند داده شده است را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**باز می‌گردد:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

نام فایل ویدئویی که به VideoFrame پیوند داده شده است را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

شی ویدئوی جاسازی‌شده را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IVideo](../../com.aspose.slides/ivideo).

**باز می‌گردد:**
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

شی ویدئوی جاسازی‌شده را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IVideo](../../com.aspose.slides/ivideo).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

برش از ابتدا [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**باز می‌گردد:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

برش از ابتدا [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //تنظیم زمان شروع برش 1 ثانیه
>      videoFrame.setTrimFromStart(1000f);
>      //تنظیم زمان پایان برش 2 ثانیه
>      videoFrame.setTrimFromEnd(2000f);
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
public abstract float getTrimFromEnd()
```

برش از انتها [ms]

**باز می‌گردد:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

برش از انتها [ms]

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

مجموعه زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این ویژگی فقط‌خواندنی است و یک [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) حاوی تمام مسیرهای زیرنویس را برمی‌گرداند.

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
>              // داده‌های دودویی زیرنویس را استخراج می‌کند و در فایل ذخیره می‌کند
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گردد:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)