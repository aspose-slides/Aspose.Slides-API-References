---
title: IVideoFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นคลิปวิดีโอที่แสดงบนสไลด์
type: docs
url: /th/com.aspose.slides/ivideoframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

เป็นคลิปวิดีโอบนสไลด์
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | ระบุว่า วิดีโอจะถูกรีวายด์โดยอัตโนมัติไปที่จุดเริ่มต้นทันทีที่ภาพยนตร์เล่นจบหรือไม่ |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | ระบุว่า วิดีโอจะถูกรีวายด์โดยอัตโนมัติไปที่จุดเริ่มต้นทันทีที่ภาพยนตร์เล่นจบหรือไม่ |
| [getPlayLoopMode()](#getPlayLoopMode--) | ระบุว่า วิดีโอจะเล่นวนลูปหรือไม่ |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | ระบุว่า วิดีโอจะเล่นวนลูปหรือไม่ |
| [getHideAtShowing()](#getHideAtShowing--) | ระบุว่า VideoFrame ถูกซ่อนหรือไม่ |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | ระบุว่า VideoFrame ถูกซ่อนหรือไม่ |
| [getVolume()](#getVolume--) | ส่งคืนหรือกำหนดระดับเสียง |
| [setVolume(int value)](#setVolume-int-) | ส่งคืนหรือกำหนดระดับเสียง |
| [getPlayMode()](#getPlayMode--) | ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ |
| [setPlayMode(int value)](#setPlayMode-int-) | ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ |
| [getFullScreenMode()](#getFullScreenMode--) | ระบุว่า วิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | ระบุว่า วิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ |
| [getLinkPathLong()](#getLinkPathLong--) | ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | ส่งคืนหรือกำหนดวัตถุวิดีโอที่ฝังอยู่ |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | ส่งคืนหรือกำหนดวัตถุวิดีโอที่ฝังอยู่ |
| [getTrimFromStart()](#getTrimFromStart--) | ตัดเริ่มต้น [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | ตัดเริ่มต้น [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | ตัดท้าย [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | ตัดท้าย [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | รับคอลเลกชันของคำบรรยายแบบปิดที่เกี่ยวข้องกับเฟรมเสียง |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

ระบุว่า วิดีโอจะถูกรีวายด์โดยอัตโนมัติไปที่จุดเริ่มต้นทันทีที่ภาพยนตร์เล่นจบหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

ระบุว่า วิดีโอจะถูกรีวายด์โดยอัตโนมัติไปที่จุดเริ่มต้นทันทีที่ภาพยนตร์เล่นจบหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

ระบุว่า วิดีโอจะเล่นวนลูปหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

ระบุว่า วิดีโอจะเล่นวนลูปเช่นกัน อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

ระบุว่า VideoFrame ถูกซ่อนหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

ระบุว่า VideoFrame ถูกซ่อนหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

ส่งคืนหรือกำหนดระดับเสียง อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**คืนค่า:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

ส่งคืนหรือกำหนดระดับเสียง อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**คืนค่า:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

ระบุว่า วิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

ระบุว่า วิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

ส่งคืนหรือกำหนดวัตถุวิดีโอที่ฝังอยู่ อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo).

**คืนค่า:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

ส่งคืนหรือกำหนดวัตถุวิดีโอที่ฝังอยู่ อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo).

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
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ตั้งเวลาเริ่มต้นการตัด 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งเวลา สิ้นสุดการตัด 2 วินาที
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
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ตั้งเวลาเริ่มต้นการตัด 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งเวลา สิ้นสุดการตัด 2 วินาที
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

ตัดท้าย [ms]

**คืนค่า:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

ตัดท้าย [ms]

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

รับคอลเลกชันของคำบรรยายแบบปิดที่เกี่ยวข้องกับเฟรมเสียง คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและส่งคืน [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด

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