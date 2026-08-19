---
title: IVideoFrame
second_title: Aspose.Slides برای مرجع API جاوا
description: یک کلیپ ویدئویی را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ivideoframe/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

یک کلیپ ویدئویی را بر روی اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | تعیین می‌کند آیا ویدئو به‌صورت خودکار پس از اتمام فیلم به شروع برمی‌گردد. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | تعیین می‌کند آیا ویدئو به‌صورت خودکار پس از اتمام فیلم به شروع برمی‌گردد. |
| [getPlayLoopMode()](#getPlayLoopMode--) | تعیین می‌کند آیا ویدئو حلقه‌ای است. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | تعیین می‌کند آیا ویدئو حلقه‌ای است. |
| [getHideAtShowing()](#getHideAtShowing--) | تعیین می‌کند آیا VideoFrame مخفی است. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | تعیین می‌کند آیا VideoFrame مخفی است. |
| [getVolume()](#getVolume--) | بازمی‌گردد یا تنظیم می‌شود حجم صدا. |
| [setVolume(int value)](#setVolume-int-) | بازمی‌گردد یا تنظیم می‌شود حجم صدا. |
| [getPlayMode()](#getPlayMode--) | بازمی‌گردد یا تنظیم می‌شود حالت پخش ویدئو. |
| [setPlayMode(int value)](#setPlayMode-int-) | بازمی‌گردد یا تنظیم می‌شود حالت پخش ویدئو. |
| [getFullScreenMode()](#getFullScreenMode--) | تعیین می‌کند آیا ویدئو در حالت تمام‌صفحه نشان داده می‌شود. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | تعیین می‌کند آیا ویدئو در حالت تمام‌صفحه نشان داده می‌شود. |
| [getLinkPathLong()](#getLinkPathLong--) | بازمی‌گردد یا تنظیم می‌شود نام فایل ویدئویی که به VideoFrame پیوند خورده است. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | بازمی‌گردد یا تنظیم می‌شود نام فایل ویدئویی که به VideoFrame پیوند خورده است. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | بازمی‌گردد یا تنظیم می‌شود شیء ویدئوی توکار. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | بازمی‌گردد یا تنظیم می‌شود شیء ویدئوی توکار. |
| [getTrimFromStart()](#getTrimFromStart--) | برش شروع [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | برش شروع [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | برش پایان [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | برش پایان [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | مجموعه زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

تعیین می‌کند آیا ویدئو به‌صورت خودکار پس از اتمام فیلم به شروع برمی‌گردد. قابل خواندن/نوشتن boolean.

**بازمی‌گردد:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

تعیین می‌کند آیا ویدئو به‌صورت خودکار پس از اتمام فیلم به شروع برمی‌گردد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

تعیین می‌کند آیا ویدئو حلقه‌ای است. قابل خواندن/نوشتن boolean.

**بازمی‌گردد:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

تعیین می‌کند آیا ویدئو حلقه‌ای است. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

ت تعیین می‌کند آیا VideoFrame مخفی است. قابل خواندن/نوشتن boolean.

**بازمی‌گردد:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

ت تعیین می‌کند آیا VideoFrame مخفی است. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

بازمی‌گردد یا تنظیم می‌شود حجم صدا. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**بازمی‌گردد:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

بازمی‌گردد یا تنظیم می‌شود حجم صدا. قابل خواندن/نوشتن [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

بازمی‌گردد یا تنظیم می‌شود حالت پخش ویدئو. قابل خواندن/نوشتن [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**بازمی‌گردد:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

بازمی‌گردد یا تنظیم می‌شود حالت پخش ویدئو. قابل خواندن/نوشتن [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

تعیین می‌کند آیا ویدئو در حالت تمام‌صفحه نشان داده می‌شود. قابل خواندن/نوشتن boolean.

**بازمی‌گردد:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

تعیین می‌کند آیا ویدئو در حالت تمام‌صفحه نشان داده می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

بازمی‌گردد یا تنظیم می‌شود نام یک فایل ویدئویی که به VideoFrame پیوند خورده است. قابل خواندن/نوشتن String.

**بازمی‌گردد:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

بازمی‌گردد یا تنظیم می‌شود نام یک فایل ویدئویی که به VideoFrame پیوند خورده است. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

بازمی‌گردد یا تنظیم می‌شود شیء ویدئوی توکار. قابل خواندن/نوشتن [IVideo](../../com.aspose.slides/ivideo).

**بازمی‌گردد:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

بازمی‌گردد یا تنظیم می‌شود شیء ویدئوی توکار. قابل خواندن/نوشتن [IVideo](../../com.aspose.slides/ivideo).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

برش شروع [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //تنظیم زمان شروع برش 1 ثانیه
>      videoFrame.setTrimFromStart(1000f);
>      //تنظیم زمان پایان برش 2 ثانیه
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گردد:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

برش شروع [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
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

برش پایان [ms]

**بازمی‌گردد:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

برش پایان [ms]

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

کلکسیونی از زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) حاوی تمام مسیرهای زیرنویس را بازمی‌گرداند.

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
>              // داده‌های باینری زیرنویس‌ها را استخراج می‌کند و در فایل ذخیره می‌نماید
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گردد:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)