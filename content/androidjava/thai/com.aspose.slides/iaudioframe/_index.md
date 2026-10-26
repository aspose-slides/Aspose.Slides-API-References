---
title: IAudioFrame
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคลิปเสียงบนสไลด์.
type: docs
url: /th/com.aspose.slides/iaudioframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

แสดงคลิปเสียงบนสไลด์
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | คืนค่า หรือกำหนดเวลาเริ่มต้นของแทร็ก |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | คืนค่า หรือกำหนดเวลาเริ่มต้นของแทร็ก |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน int |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน int |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | คืนค่า หรือกำหนดเวลาสิ้นสุดของแทร็ก |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | คืนค่า หรือกำหนดเวลาสิ้นสุดของแทร็ก |
| [getVolume()](#getVolume--) | คืนค่า หรือกำหนดระดับเสียง |
| [setVolume(int value)](#setVolume-int-) | คืนค่า หรือกำหนดระดับเสียง |
| [getPlayMode()](#getPlayMode--) | คืนค่า หรือกำหนดโหมดการเล่นเสียง |
| [setPlayMode(int value)](#setPlayMode-int-) | คืนค่า หรือกำหนดโหมดการเล่นเสียง |
| [getHideAtShowing()](#getHideAtShowing--) | ตรวจสอบว่า AudioFrame ถูกซ่อนหรือไม่ |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | ตรวจสอบว่า AudioFrame ถูกซ่อนหรือไม่ |
| [getPlayLoopMode()](#getPlayLoopMode--) | ตรวจสอบว่าเสียงทำซ้ำหรือไม่ |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | ตรวจสอบว่าเสียงทำซ้ำหรือไม่ |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | ตรวจสอบว่าเสียงเล่นต่อเนื่องระหว่างสไลด์หรือไม่ |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | ตรวจสอบว่าเสียงเล่นต่อเนื่องระหว่างสไลด์หรือไม่ |
| [getRewindAudio()](#getRewindAudio--) | ตรวจสอบว่าเสียงจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จหรือไม่ |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | ตรวจสอบว่าเสียงจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จหรือไม่ |
| [getEmbedded()](#getEmbedded--) | ตรวจสอบว่าเสียงถูกฝังในพรีเซนเทชันหรือไม่ |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | คืนค่า หรือกำหนดออบเจ็กต์เสียงที่ฝังอยู่ |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | คืนค่า หรือกำหนดออบเจ็กต์เสียงที่ฝังอยู่ |
| [getFadeInDuration()](#getFadeInDuration--) | ระบุระยะเวลา (มิลลิวินาที) ของการเฟด-อินเริ่มต้นของสื่อ |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | ระบุระยะเวลา (มิลลิวินาที) ของการเฟด-อินเริ่มต้นของสื่อ |
| [getFadeOutDuration()](#getFadeOutDuration--) | ระบุระยะเวลา (มิลลิวินาที) ของการเฟด-เอาต์สุดท้ายของสื่อ |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | ระบุระยะเวลา (มิลลิวินาที) ของการเฟด-เอาต์สุดท้ายของสื่อ |
| [getVolumeValue()](#getVolumeValue--) | คืนค่า หรือกำหนดระดับเสียงเป็นเปอร์เซ็นต์ |
| [setVolumeValue(float value)](#setVolumeValue-float-) | คืนค่า หรือกำหนดระดับเสียงเป็นเปอร์เซ็นต์ |
| [getTrimFromStart()](#getTrimFromStart--) | ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น |
| [getTrimFromEnd()](#getTrimFromEnd--) | ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากสุดท้ายของสื่อระหว่างการเล่น |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากสุดท้ายของสื่อระหว่างการเล่น |
| [getCaptionTracks()](#getCaptionTracks--) | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ AudioFrame |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

คืนค่า หรือกำหนดเวลาเริ่มต้นของแทร็ก อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

คืนค่า หรือกำหนดเวลาเริ่มต้นของแทร็ก อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

คืนค่า หรือกำหนดเวลาสิ้นสุดของแทร็ก อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

คืนค่า หรือกำหนดเวลาสิ้นสุดของแทร็ก อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

คืนค่า หรือกำหนดระดับเสียง อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**ผลลัพธ์:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

คืนค่า หรือกำหนดระดับเสียง อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

คืนค่า หรือกำหนดโหมดการเล่นเสียง อ่าน/เขียน [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**ผลลัพธ์:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

คืนค่า หรือกำหนดโหมดการเล่นเสียง อ่าน/เขียน [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

ตรวจสอบว่า AudioFrame ถูกซ่อนหรือไม่ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

ตรวจสอบว่า AudioFrame ถูกซ่อนหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

ตรวจสอบว่าเสียงทำซ้ำหรือไม่ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

ตรวจสอบว่าเสียงทำซ้ำหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

ตรวจสอบว่าเสียงเล่นต่อเนื่องระหว่างสไลด์หรือไม่ อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องระหว่างสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จ
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**ผลลัพธ์:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

ตรวจสอบว่าเสียงเล่นต่อเนื่องระหว่างสไลด์หรือไม่ อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องระหว่างสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จ
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

ตรวจสอบว่าเสียงจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จหรือไม่ อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องระหว่างสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จ
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**ผลลัพธ์:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

ตรวจสอบว่าเสียงจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จหรือไม่ อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องระหว่างสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จ
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

ตรวจสอบว่าเสียงถูกฝังในพรีเซนเทชันหรือไม่ อ่าน-อย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

คืนค่า หรือกำหนดออบเจ็กต์เสียงที่ฝังอยู่ อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

คืนค่า หรือกำหนดออบเจ็กต์เสียงที่ฝังอยู่ อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

ระบุระยะเวลา (มิลลิวินาที) ของการเฟด-อินเริ่มต้นของสื่อ อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระยะเวลาเฟดเริ่มต้นเป็น 200 มิลลิวินาที
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

ระบุระยะเวลา (มิลลิวินาที) ของการเฟด-อินเริ่มต้นของสื่อ อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระยะเวลาเฟดเริ่มต้นเป็น 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

ระบุระยะเวลา (มิลลิวินาที) ของการเฟด-เอาต์สุดท้ายของสื่อ อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระยะเวลาเฟดจบเป็น 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

ระบุระยะเวลา (มิลลิวินาที) ของการเฟด-เอาต์สุดท้ายของสื่อ อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระยะเวลาเฟดจบเป็น 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

คืนค่า หรือกำหนดระดับเสียงเป็นเปอร์เซ็นต์ อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระดับเสียงเป็น 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

คืนค่า หรือกำหนดระดับเสียงเป็นเปอร์เซ็นต์ อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระดับเสียงเป็น 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าการตัดเริ่มต้นเป็น 1.5 วินาที
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าการตัดเริ่มต้นเป็น 1.5 วินาที
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากส่วนท้ายของสื่อระหว่างการเล่น อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าการตัดส่วนสุดท้ายเป็น 2 วินาที
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากส่วนท้ายของสื่อระหว่างการเล่น อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าการตัดส่วนสุดท้ายเป็น 2 วินาที
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ AudioFrame คุณสมบัตินี้เป็นอ่าน-อย่างเดียวและคืนค่า [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>     for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>     {
>         if (shape instanceof IAudioFrame)
>         {
>             IAudioFrame audioFrame = (IAudioFrame) shape;
>             // บันทึกข้อมูลไบนารีของแทร็กคำบรรยายเป็นไฟล์ .vtt
>             for (ICaptions captionTrack : audioFrame.getCaptionTracks())
>             {
>                 FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                 fos.write(captionTrack.getBinaryData());
>                 fos.close();
>             }
>         }
>     }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)