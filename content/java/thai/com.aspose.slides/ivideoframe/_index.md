---
title: IVideoFrame
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคลิปวิดีโอบนสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/ivideoframe/
---
**ทั้งหมดที่ทำไว้เป็นอินเทอร์เฟซ:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Represents a video clip on a slide.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติเพื่อเริ่มต้นใหม่เมื่อภาพยนตร์เล่นเสร็จแล้วหรือไม่. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติเพื่อเริ่มต้นใหม่เมื่อภาพยนตร์เล่นเสร็จแล้วหรือไม่. |
| [getPlayLoopMode()](#getPlayLoopMode--) | กำหนดว่าวิดีโอจะเล่นวนซ้ำหรือไม่. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | กำหนดว่าวิดีโอจะเล่นวนซ้ำหรือไม่. |
| [getHideAtShowing()](#getHideAtShowing--) | กำหนดว่า VideoFrame ถูกซ่อนหรือไม่. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | กำหนดว่า VideoFrame ถูกซ่อนหรือไม่. |
| [getVolume()](#getVolume--) | ส่งคืนหรือกำหนดระดับเสียงของออดิโอ. |
| [setVolume(int value)](#setVolume-int-) | ส่งคืนหรือกำหนดระดับเสียงของออดิโอ. |
| [getVolumeValue()](#getVolumeValue--) | ส่งคืนหรือกำหนดระดับเสียงวิดีโอที่แม่นยำเป็นเปอร์เซ็นต์. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | ส่งคืนหรือกำหนดระดับเสียงวิดีโอที่แม่นยำเป็นเปอร์เซ็นต์. |
| [getPlayMode()](#getPlayMode--) | ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ. |
| [setPlayMode(int value)](#setPlayMode-int-) | ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ. |
| [getFullScreenMode()](#getFullScreenMode--) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. |
| [getLinkPathLong()](#getLinkPathLong--) | ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | ส่งคืนหรือกำหนดออบเจกต์วิดีโอที่ฝังอยู่. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | ส่งคืนหรือกำหนดออบเจกต์วิดีโอที่ฝังอยู่. |
| [getTrimFromStart()](#getTrimFromStart--) | ตัดเริ่มต้น [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | ตัดเริ่มต้น [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | ตัดสิ้นสุด [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | ตัดสิ้นสุด [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | ดึงคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับเฟรมออดิโอ. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติเพื่อเริ่มต้นใหม่เมื่อภาพยนตร์เล่นเสร็จแล้วหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติเพื่อเริ่มต้นใหม่เมื่อภาพยนตร์เล่นเสร็จแล้วหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

กำหนดว่าวิดีโอจะเล่นวนซ้ำหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

กำหนดว่าวิดีโอจะเล่นวนซ้ำหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

กำหนดว่า VideoFrame ถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

กำหนดว่า VideoFrame ถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

ส่งคืนหรือกำหนดระดับเสียงของออดิโอ. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**ส่งคืน:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

ส่งคืนหรือกำหนดระดับเสียงของออดิโอ. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

ส่งคืนหรือกำหนดระดับเสียงวิดีโอที่แม่นยำเป็นเปอร์เซ็นต์ ค่าแสดงเป็นเปอร์เซ็นต์จาก 0 ถึง 100 ใช้คุณสมบัตินี้เพื่ออ่านหรือกำหนดค่าระดับเสียงที่ละเอียดกว่าระดับที่กำหนดไว้ล่วงหน้าผ่านคุณสมบัติ Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) อ่าน/เขียน float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // อ่านระดับเสียงที่แม่นยำในปัจจุบันและตั้งค่าเป็น 75.5 เปอร์เซ็นต์.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งคืน:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

ส่งคืนหรือกำหนดระดับเสียงวิดีโอที่แม่นยำเป็นเปอร์เซ็นต์ ค่าแสดงเป็นเปอร์เซ็นต์จาก 0 ถึง 100 ใช้คุณสมบัตินี้เพื่ออ่านหรือกำหนดค่าระดับเสียงที่ละเอียดกว่าระดับที่กำหนดไว้ล่วงหน้าผ่านคุณสมบัติ Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) อ่าน/เขียน float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // อ่านระดับเสียงที่แม่นยำในปัจจุบันและตั้งค่าเป็น 75.5 เปอร์เซ็นต์.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ. อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**ส่งคืน:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ. อ่าน/เขียน [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
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

ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

ส่งคืนหรือกำหนดออบเจกต์วิดีโอที่ฝังอยู่. อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo).

**ส่งคืน:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

ส่งคืนหรือกำหนดออบเจกต์วิดีโอที่ฝังอยู่. อ่าน/เขียน [IVideo](../../com.aspose.slides/ivideo).

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
>      //ตั้งค่าเวลาเริ่มการตัด 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งค่าเวลาสิ้นสุดการตัด 2 วินาที
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งคืน:**
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
>      //ตั้งเวลาเริ่มการตัด 1 วินาที
>      videoFrame.setTrimFromStart(1000f);
>      //ตั้งเวลาเส้นสิ้นสุดการตัด 2 วินาที
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

**ส่งคืน:**
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

ดึงคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับเฟรมออดิโอ. คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและส่งคืน [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด.

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

**ส่งคืน:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)