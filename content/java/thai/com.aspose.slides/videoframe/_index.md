---
title: VideoFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคลิปวิดีโอบนสไลด์.
type: docs
url: /th/com.aspose.slides/videoframe/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**  
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)  
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Represents a video clip on a slide.

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติเพื่อเริ่มต้นใหม่ทันทีที่ภาพยนตร์เล่นจบหรือไม่. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติเพื่อเริ่มต้นใหม่ทันทีที่ภาพยนตร์เล่นจบหรือไม่. |
| [getPlayLoopMode()](#getPlayLoopMode--) | กำหนดว่าวิดีโอจะทำการวนซ้ำหรือไม่. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | กำหนดว่าวิดีโอจะทำการวนซ้ำหรือไม่. |
| [getHideAtShowing()](#getHideAtShowing--) | กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่. |
| [getVolume()](#getVolume--) | คืนค่า หรือ ตั้งค่าปริมาณเสียง. |
| [setVolume(int value)](#setVolume-int-) | คืนค่า หรือ ตั้งค่าปริมาณเสียง. |
| [getPlayMode()](#getPlayMode--) | คืนค่า หรือ ตั้งค่าโหมดการเล่นวิดีโอ. |
| [setPlayMode(int value)](#setPlayMode-int-) | คืนค่า หรือ ตั้งค่าโหมดการเล่นวิดีโอ. |
| [getFullScreenMode()](#getFullScreenMode--) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า หรือ ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่า หรือ ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | คืนค่า หรือ ตั้งค่าออบเจ็กต์วิดีโอที่ฝังไว้. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | คืนค่า หรือ ตั้งค่าออบเจ็กต์วิดีโอที่ฝังไว้. |
| [getTrimFromStart()](#getTrimFromStart--) | ตัดเริ่มต้น [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | ตัดเริ่มต้น [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | ตัดสิ้นสุด [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | ตัดสิ้นสุด [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | รับคอลเลกชันของคำบรรยายปิดที่เกี่ยวข้องกับเฟรมวิดีโอ. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติเพื่อเริ่มต้นใหม่ทันทีที่ภาพยนตร์เล่นจบหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติเพื่อเริ่มต้นใหม่ทันทีที่ภาพยนตร์เล่นจบหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

กำหนดว่าวิดีโอจะทำการวนซ้ำหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

กำหนดว่าวิดีโอจะทำการวนซ้ำหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

คืนค่า หรือ ตั้งค่าปริมาณเสียง. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**คืนค่า:**  
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

คืนค่า หรือ ตั้งค่าปริมาณเสียง. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

คืนค่า หรือ ตั้งค่าโหมดการเล่นวิดีโอ. อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**คืนค่า:**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

คืนค่า หรือ ตั้งค่าโหมดการเล่นวิดีโอ. อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

คืนค่า หรือ ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

คืนค่า หรือ ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

คืนค่า หรือ ตั้งค่าออบเจ็กต์วิดีโอที่ฝังไว้. อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo).

**คืนค่า:**  
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

คืนค่า หรือ ตั้งค่าออบเจ็กต์วิดีโอที่ฝังไว้. อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ตั้งค่าเวลาเริ่มการตัด 1 วินาที
>      //ตั้งค่าเวลาให้การตัดสิ้นสุด 2 วินาที
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
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
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ตั้งค่าเวลาเริ่มการตัด 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งค่าเวลาให้การตัดสิ้นสุด 2 วินาที
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
public final float getTrimFromEnd()
```

ตัดสิ้นสุด [ms]

**คืนค่า:**  
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

ตัดสิ้นสุด [ms]

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

รับคอลเลกชันของคำบรรยายปิดที่เกี่ยวข้องกับเฟรมวิดีโอ. คุณสมบัตินี้เป็นอ่านอย่างเดียวและคืนค่าเป็น [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด.

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