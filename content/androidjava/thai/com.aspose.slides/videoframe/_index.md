---
title: VideoFrame
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคลิปวิดีโอบนสไลด์
type: docs
url: /th/com.aspose.slides/videoframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

แสดงคลิปวิดีโอบนสไลด์
## Methods

| Method | Description |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | กำหนดว่าวิดีโอจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นทันทีเมื่อภาพยนตร์เล่นจบหรือไม่ |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | กำหนดว่าวิดีโอจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นทันทีเมื่อภาพยนตร์เล่นจบหรือไม่ |
| [getPlayLoopMode()](#getPlayLoopMode--) | กำหนดว่าวิดีโอจะวนซ้ำหรือไม่ |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | กำหนดว่าวิดีโอจะวนซ้ำหรือไม่ |
| [getHideAtShowing()](#getHideAtShowing--) | กำหนดว่า VideoFrame จะถูกซ่อนไว้หรือไม่ |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | กำหนดว่า VideoFrame จะถูกซ่อนไว้หรือไม่ |
| [getVolume()](#getVolume--) | คืนค่า หรือ ตั้งค่าปริมาณเสียง |
| [setVolume(int value)](#setVolume-int-) | คืนค่า หรือ ตั้งค่าปริมาณเสียง |
| [getPlayMode()](#getPlayMode--) | คืนค่า หรือ ตั้งค่าโหมดการเล่นวิดีโอ |
| [setPlayMode(int value)](#setPlayMode-int-) | คืนค่า หรือ ตั้งค่าโหมดการเล่นวิดีโอ |
| [getFullScreenMode()](#getFullScreenMode--) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า หรือ ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่า หรือ ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | คืนค่า หรือ ตั้งค่าอ็อบเจกต์วิดีโอที่ฝังไว้ |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | คืนค่า หรือ ตั้งค่าอ็อบเจกต์วิดีโอที่ฝังไว้ |
| [getTrimFromStart()](#getTrimFromStart--) | ตัดเริ่มต้น [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | ตัดเริ่มต้น [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | ตัดจบ [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | ตัดจบ [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | รับคอลเลกชันของคำบรรยายปิดที่สัมพันธ์กับ VideoFrame |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

กำหนดว่าวิดีโอจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นทันทีเมื่อภาพยนตร์เล่นจบหรือไม่ อ่าน/เขียน boolean

**Returns:**
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

กำหนดว่าวิดีโอจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นทันทีเมื่อภาพยนตร์เล่นจบหรือไม่ อ่าน/เขียน boolean

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

กำหนดว่าวิดีโอจะวนซ้ำหรือไม่ อ่าน/เขียน boolean

**Returns:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

กำหนดว่าวิดีโอจะวนซ้ำหรือไม่ อ่าน/เขียน boolean

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

กำหนดว่า VideoFrame จะถูกซ่อนไว้หรือไม่ อ่าน/เขียน boolean

**Returns:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
``` 
public final void setHideAtShowing(boolean value)
```

กำหนดว่า VideoFrame จะถูกซ่อนไว้หรือไม่ อ่าน/เขียน boolean

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

คืนค่า หรือ ตั้งค่าปริมาณเสียง อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)

**Returns:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

คืนค่า หรือ ตั้งค่าปริมาณเสียง อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

คืนค่า หรือ ตั้งค่าโหมดการเล่นวิดีโอ อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)

**Returns:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

คืนค่า หรือ ตั้งค่าโหมดการเล่นวิดีโอ อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ อ่าน/เขียน boolean

**Returns:**
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ อ่าน/เขียน boolean

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

คืนค่า หรือ ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame อ่าน/เขียน String

**Returns:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

คืนค่า หรือ ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame อ่าน/เขียน String

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

คืนค่า หรือ ตั้งค่าอ็อบเจกต์วิดีโอที่ฝังไว้ อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo)

**Returns:**
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

คืนค่า หรือ ตั้งค่าอ็อบเจกต์วิดีโอที่ฝังไว้ อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

ตัดเริ่มต้น [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ตั้งค่าการตัดเวลาเริ่มต้น 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งค่าการตัดเวลาในตอนจบ 2 วินาที
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

ตัดเริ่มต้น [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ตั้งค่าการตัดเวลาเริ่มต้น 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งค่าการตัดเวลาในตอนจบ 2 วินาที
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

ตัดจบ [ms]

**Returns:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

ตัดจบ [ms]

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

รับคอลเลกชันของคำบรรยายปิดที่สัมพันธ์กับ VideoFrame คุณสมบัตินี้เป็นอ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) ที่ประกอบด้วยแทร็กคำบรรยายทั้งหมด

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
>              // ดึงข้อมูลไบนารีของคำบรรยายและบันทึกลงไฟล์
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)