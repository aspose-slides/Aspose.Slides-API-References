---
title: IVideoFrame
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นคลิปวิดีโอบนสไลด์.
type: docs
url: /th/com.aspose.slides/ivideoframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Represents a video clip on a slide.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | กำหนดว่าวิดีโอจะทำการย้อนกลับอัตโนมัติเพื่อเริ่มใหม่ทันทีที่ภาพยนตร์จบการเล่นหรือไม่ |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | กำหนดว่าวิดีโอจะทำการย้อนกลับอัตโนมัติเพื่อเริ่มใหม่ทันทีที่ภาพยนตร์จบการเล่นหรือไม่ |
| [getPlayLoopMode()](#getPlayLoopMode--) | กำหนดว่าวิดีโอจะทำซ้ำหรือไม่ |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | กำหนดว่าวิดีโอจะทำซ้ำหรือไม่ |
| [getHideAtShowing()](#getHideAtShowing--) | กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่ |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่ |
| [getVolume()](#getVolume--) | คืนค่า หรือกำหนดปริมาณเสียง |
| [setVolume(int value)](#setVolume-int-) | คืนค่า หรือกำหนดปริมาณเสียง |
| [getPlayMode()](#getPlayMode--) | คืนค่า หรือกำหนดโหมดการเล่นวิดีโอ |
| [setPlayMode(int value)](#setPlayMode-int-) | คืนค่า หรือกำหนดโหมดการเล่นวิดีโอ |
| [getFullScreenMode()](#getFullScreenMode--) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า หรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่า หรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | คืนค่า หรือกำหนดอ็อบเจ็กต์วิดีโอที่ฝังอยู่ |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | คืนค่า หรือกำหนดอ็อบเจ็กต์วิดีโอที่ฝังอยู่ |
| [getTrimFromStart()](#getTrimFromStart--) | ตัดเริ่มต้น [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | ตัดเริ่มต้น [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | ตัดสิ้นสุด [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | ตัดสิ้นสุด [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | รับชุดของคำบรรยายปิดที่เชื่อมโยงกับเฟรมเสียง |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

กำหนดว่าวิดีโอจะทำการย้อนกลับอัตโนมัติเพื่อเริ่มใหม่ทันทีที่ภาพยนตร์จบการเล่นหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

กำหนดว่าวิดีโอจะทำการย้อนกลับอัตโนมัติเพื่อเริ่มใหม่ทันทีที่ภาพยนตร์จบการเล่นหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

กำหนดว่าวิดีโอจะทำซ้ำหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

กำหนดว่าวิดีโอจะทำซ้ำโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

คืนค่า หรือกำหนดปริมาณเสียง. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**คืนค่า:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

คืนค่า หรือกำหนดปริมาณเสียง. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

คืนค่า หรือกำหนดโหมดการเล่นวิดีโอ. อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**คืนค่า:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

คืนค่า หรือกำหนดโหมดการเล่นวิดีโอ. อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

คืนค่า หรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

คืนค่า หรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

คืนค่า หรือกำหนดอ็อบเจ็กต์วิดีโอที่ฝังอยู่. อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo).

**คืนค่า:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

คืนค่า หรือกำหนดอ็อบเจ็กต์วิดีโอที่ฝังอยู่. อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
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
>      //ตั้งค่าเวลาเริ่มต้นการตัด 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งค่าเวลาในการตัดสิ้นสุด 2 วินาที
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
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
>      //ตั้งค่าเวลาเริ่มต้นการตัด 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งค่าเวลาในการตัดสิ้นสุด 2 วินาที
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

ตัดสิ้นสุด [ms]

**คืนค่า:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

ตัดสิ้นสุด [ms]

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

รับชุดของคำบรรยายปิดที่เชื่อมโยงกับเฟรมเสียง. คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด.

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

**คืนค่า:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)