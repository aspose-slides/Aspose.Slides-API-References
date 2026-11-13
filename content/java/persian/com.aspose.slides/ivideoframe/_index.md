---
title: IVideoFrame
second_title: مرجع API Aspose.Slides برای جاوا
description: یک کلیپ ویدئویی را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ivideoframe/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

یک کلیپ ویدئویی را بر روی اسلاید نمایان می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | مشخص می‌کند که آیا ویدیو به‌صورت خودکار به ابتدای خود باز می‌گردد به محض اینکه فیلم به اتمام رسیده باشد. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | مشخص می‌کند که آیا ویدیو به‌صورت خودکار به ابتدای خود باز می‌گردد به محض اینکه فیلم به اتمام رسیده باشد. |
| [getPlayLoopMode()](#getPlayLoopMode--) | مشخص می‌کند که آیا ویدیو به صورت حلقه‌ای پخش می‌شود. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | مشخص می‌کند که آیا ویدیو به صورت حلقه‌ای پخش می‌شود. |
| [getHideAtShowing()](#getHideAtShowing--) | مشخص می‌کند که آیا VideoFrame مخفی است. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | مشخص می‌کند که آیا VideoFrame مخفی است. |
| [getVolume()](#getVolume--) | مقدار صدای صوتی را بازمی‌گرداند یا تنظیم می‌کند. |
| [setVolume(int value)](#setVolume-int-) | مقدار صدای صوتی را بازمی‌گرداند یا تنظیم می‌کند. |
| [getVolumeValue()](#getVolumeValue--) | حجم دقیق ویدیو را به‌صورت درصد بازمی‌گرداند یا تنظیم می‌کند. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | حجم دقیق ویدیو را به‌صورت درصد بازمی‌گرداند یا تنظیم می‌کند. |
| [getPlayMode()](#getPlayMode--) | حالت پخش ویدیو را بازمی‌گرداند یا تنظیم می‌کند. |
| [setPlayMode(int value)](#setPlayMode-int-) | حالت پخش ویدیو را بازمی‌گرداند یا تنظیم می‌کند. |
| [getFullScreenMode()](#getFullScreenMode--) | مشخص می‌کند که آیا ویدیو به صورت تمام‌صفحه نمایش داده می‌شود. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | مشخص می‌کند که آیا ویدیو به صورت تمام‌صفحه نمایش داده می‌شود. |
| [getLinkPathLong()](#getLinkPathLong--) | نام فایل ویدئویی که به VideoFrame لینک شده است را بازمی‌گرداند یا تنظیم می‌کند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | نام فایل ویدئویی که به VideoFrame لینک شده است را بازمی‌گرداند یا تنظیم می‌کند. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | شیء ویدئوی توکار را بازمی‌گرداند یا تنظیم می‌کند. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | شیء ویدئوی توکار را بازمی‌گرداند یا تنظیم می‌کند. |
| [getTrimFromStart()](#getTrimFromStart--) | شروع برش [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | شروع برش [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | پایان برش [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | پایان برش [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | مجموعه زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

مشخص می‌کند که آیا ویدیو به‌صورت خودکار به ابتدای خود باز می‌گردد به محض اینکه فیلم به اتمام رسیده باشد. قابل خواندن/نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

مشخص می‌کند که آیا ویدیو به‌صورت خودکار به ابتدای خود باز می‌گردد به محض اینکه فیلم به اتمام رسیده باشد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

مشخص می‌کند که آیا ویدیو به صورت حلقه‌ای پخش می‌شود. قابل خواندن/نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

مشخص می‌کند که آیا ویدیو به صورت حلقه‌ای پخش می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

مشخص می‌کند که آیا VideoFrame مخفی است. قابل خواندن/نوشتن boolean.

**بازمی‌گرداند:**
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

مقدار صدای صوتی را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**بازمی‌گرداند:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

مقدار صدای صوتی را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

حجم دقیق ویدیو را به‌صورت درصد بازمی‌گرداند یا تنظیم می‌کند. مقدار به‌صورت درصدی از 0 تا 100 بیان می‌شود. از این ویژگی برای خواندن یا تنظیم مقادیر حجمی دقیق‌تر نسبت به سطوح پیش‌تعریف‌شده موجود در ویژگی Volume استفاده کنید. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // خواندن حجم دقیق فعلی و تنظیم آن به 75.5 درصد.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

حجم دقیق ویدیو را به‌صورت درصد بازمی‌گرداند یا تنظیم می‌کند. مقدار به‌صورت درصدی از 0 تا 100 بیان می‌شود. از این ویژگی برای خواندن یا تنظیم مقادیر حجمی دقیق‌تر نسبت به سطوح پیش‌تعریف‌شده موجود در ویژگی Volume استفاده کنید. قابل خواندن/نوشتن float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // خواندن حجم دقیق فعلی و تنظیم آن به 75.5 درصد.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

حالت پخش ویدیو را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**بازمی‌گرداند:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

حالت پخش ویدیو را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

مشخص می‌کند که آیا ویدیو به صورت تمام‌صفحه نمایش داده می‌شود. قابل خواندن/نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

مشخص می‌کند که آیا ویدیو به صورت تمام‌صفحه نمایش داده می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

نام فایل ویدئویی که به VideoFrame لینک شده است را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازمی‌گرداند:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

نام فایل ویدئویی که به VideoFrame لینک شده است را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

شیء ویدئوی توکار را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IVideo](../../com.aspose.slides/ivideo).

**بازمی‌گرداند:**
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

شیء ویدئوی توکار را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IVideo](../../com.aspose.slides/ivideo).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

شروع برش [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      // تنظیم زمان شروع برش 1 ثانیه
>      videoFrame.setTrimFromStart(1000f);
>      // تنظیم زمان پایان برش 2 ثانیه
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

شروع برش [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      // تنظیم زمان شروع برش 1 ثانیه
>      videoFrame.setTrimFromStart(1000f);
>      // تنظیم زمان پایان برش 2 ثانیه
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

پایان برش [ms]

**بازمی‌گرداند:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

پایان برش [ms]

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

مجموعه زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) شامل تمام تراک‌های زیرنویس را برمی‌گرداند.

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
>              // داده‌های باینری زیرنویس را استخراج می‌کند و در فایل ذخیره می‌کند
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)