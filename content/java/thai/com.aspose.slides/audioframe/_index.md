---
title: AudioFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคลิปเสียงบนสไลด์.
type: docs
url: /th/com.aspose.slides/audioframe/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

แสดงคลิปเสียงบนสไลด์.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // รับ AudioFrame shape
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // ตั้งค่าโหมดการเล่นให้เล่นเมื่อคลิก
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // ตั้งระดับเสียงเป็น Low
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // ตั้งค่าให้เสียงเล่นต่อเนื่องข้ามสไลด์
>      audioFrame.setPlayAcrossSlides(true);
>      // ปิดการวนซ้ำสำหรับเสียง
>      audioFrame.setPlayLoopMode(false);
>      // ซ่อน AudioFrame ระหว่างการแสดงสไลด์
>      audioFrame.setHideAtShowing(true);
>      // รีวินด์เสียงกลับไปเริ่มต้นหลังการเล่น
>      audioFrame.setRewindAudio(true);
>      // บันทึกไฟล์ PowerPoint ลงดิสก์
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | คืนค่า หรือกำหนดเวลาของแทร็กเริ่มต้น. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | คืนค่า หรือกำหนดเวลาของแทร็กเริ่มต้น. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | คืนค่า หรือกำหนดเวลาของแทร็กสุดท้าย. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | คืนค่า หรือกำหนดเวลาของแทร็กสุดท้าย. |
| [getVolume()](#getVolume--) | คืนค่า หรือกำหนดระดับเสียงของออดิโอ. |
| [setVolume(int value)](#setVolume-int-) | คืนค่า หรือกำหนดระดับเสียงของออดิโอ. |
| [getPlayMode()](#getPlayMode--) | คืนค่า หรือกำหนดโหมดการเล่นออดิโอ. |
| [setPlayMode(int value)](#setPlayMode-int-) | คืนค่า หรือกำหนดโหมดการเล่นออดิโอ. |
| [getHideAtShowing()](#getHideAtShowing--) | กำหนดว่า AudioFrame ถูกซ่อนหรือไม่. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | กำหนดว่า AudioFrame ถูกซ่อนหรือไม่. |
| [getPlayLoopMode()](#getPlayLoopMode--) | กำหนดว่าเสียงถูกวนซ้ำหรือไม่. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | กำหนดว่าเสียงถูกวนซ้ำหรือไม่. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | กำหนดว่าเสียงกำลังเล่นต่อเนื่องข้ามสไลด์หรือไม่. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | กำหนดว่าเสียงกำลังเล่นต่อเนื่องข้ามสไลด์หรือไม่. |
| [getRewindAudio()](#getRewindAudio--) | กำหนดว่าเสียงจะถูกรีวินด์โดยอัตโนมัติไปยังจุดเริ่มต้นหลังการเล่นหรือไม่. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | กำหนดว่าเสียงจะถูกรีวินด์โดยอัตโนมัติไปยังจุดเริ่มต้นหลังการเล่นหรือไม่. |
| [getEmbedded()](#getEmbedded--) | กำหนดว่าเสียงถูกฝังไว้ในงานนำเสนอหรือไม่. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | คืนค่า หรือกำหนดออบเจกต์เสียงที่ฝังอยู่. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | คืนค่า หรือกำหนดออบเจกต์เสียงที่ฝังอยู่. |
| [getFadeInDuration()](#getFadeInDuration--) | ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที. |
| [getFadeOutDuration()](#getFadeOutDuration--) | ระบุระยะเวลาการเฟดเอาต์ของสื่อเป็นมิลลิวินาที. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | ระบุระยะเวลาการเฟดเอาต์ของสื่อเป็นมิลลิวินาที. |
| [getVolumeValue()](#getVolumeValue--) | คืนค่า หรือกำหนดระดับเสียงของออดิโอเป็นเปอร์เซ็นต์. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | คืนค่า หรือกำหนดระดับเสียงของออดิโอเป็นเปอร์เซ็นต์. |
| [getTrimFromStart()](#getTrimFromStart--) | ระบุระยะเวลาที่จะถูกลบจากจุดเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | ระบุระยะเวลาที่จะถูกลบจากจุดเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที. |
| [getTrimFromEnd()](#getTrimFromEnd--) | ระบุระยะเวลาที่จะถูกลบจากส่วนท้ายของสื่อระหว่างการเล่นเป็นมิลลิวินาที. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | ระบุระยะเวลาที่จะถูกลบจากส่วนท้ายของสื่อระหว่างการเล่นเป็นมิลลิวินาที. |
| [getCaptionTracks()](#getCaptionTracks--) | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ audio frame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น. อ่าน/เขียน  int .

**คืนค่า:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น. อ่าน/เขียน  int .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

คืนค่า หรือกำหนดเวลาของแทร็กเริ่มต้น. อ่าน/เขียน  int .

**คืนค่า:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

คืนค่า หรือกำหนดเวลาของแทร็กเริ่มต้น. อ่าน/เขียน  int .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน  int .

**คืนค่า:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน  int .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

คืนค่า หรือกำหนดเวลาของแทร็กสุดท้าย. อ่าน/เขียน  int .

**คืนค่า:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

คืนค่า หรือกำหนดเวลาของแทร็กสุดท้าย. อ่าน/เขียน  int .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

คืนค่า หรือกำหนดระดับเสียงของออดิโอ. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**คืนค่า:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

คืนค่า หรือกำหนดระดับเสียงของออดิโอ. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

คืนค่า หรือกำหนดโหมดการเล่นออดิโอ. อ่าน/เขียน [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**คืนค่า:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

คืนค่า หรือกำหนดโหมดการเล่นออดิโอ. อ่าน/เขียน [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

กำหนดว่า AudioFrame ถูกซ่อนหรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

กำหนดว่า AudioFrame ถูกซ่อนหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

กำหนดว่าเสียงถูกวนซ้ำหรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

กำหนดว่าเสียงถูกวนซ้ำหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

กำหนดว่าเสียงกำลังเล่นต่อเนื่องข้ามสไลด์หรือไม่. อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปจุดเริ่มต้นหลังการเล่น
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**คืนค่า:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

กำหนดว่าเสียงกำลังเล่นต่อเนื่องข้ามสไลด์หรือไม่. อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปจุดเริ่มต้นหลังการเล่น
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

กำหนดว่าเสียงจะถูกรีวินด์โดยอัตโนมัติไปยังจุดเริ่มต้นหลังการเล่นหรือไม่. อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปจุดเริ่มต้นหลังการเล่น
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**คืนค่า:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

กำหนดว่าเสียงจะถูกรีวินด์โดยอัตโนมัติไปยังจุดเริ่มต้นหลังการเล่นหรือไม่. อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปจุดเริ่มต้นหลังการเล่น
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

กำหนดว่าเสียงถูกฝังไว้ในงานนำเสนอหรือไม่. อ่านอย่างเดียว  boolean .

**คืนค่า:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

คืนค่า หรือกำหนดออบเจกต์เสียงที่ฝังอยู่. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**คืนค่า:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

คืนค่า หรือกำหนดออบเจกต์เสียงที่ฝังอยู่. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // กำหนดระยะเวลาการเฟดเริ่มต้นเป็น 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // กำหนดระยะเวลาการเฟดเริ่มต้นเป็น 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

ระบุระยะเวลาการเฟดเอาต์ของสื่อเป็นมิลลิวินาที. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // กำหนดระยะเวลาการเฟดเอาต์สุดท้ายเป็น 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

ระบุระยะเวลาการเฟดเอาต์ของสื่อเป็นมิลลิวินาที. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // กำหนดระยะเวลาการเฟดเอาต์สุดท้ายเป็น 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

คืนค่า หรือกำหนดระดับเสียงของออดิโอเป็นเปอร์เซ็นต์. อ่าน/เขียน float.

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

**คืนค่า:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

คืนค่า หรือกำหนดระดับเสียงของออดิโอเป็นเปอร์เซ็นต์. อ่าน/เขียน float.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

ระบุระยะเวลาที่จะถูกลบจากจุดเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที. อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าการตัดช่วงเริ่มต้นที่ 1.5 วินาที
>      audioFrame.setTrimFromStart(1500f);
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

ระบุระยะเวลาที่จะถูกลบจากจุดเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที. อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าการตัดช่วงเริ่มต้นที่ 1.5 วินาที
>      audioFrame.setTrimFromStart(1500f);
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

ระบุระยะเวลาที่จะถูกลบจากส่วนท้ายของสื่อระหว่างการเล่นเป็นมิลลิวินาที. อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าการตัดช่วงสุดท้ายเป็น 2 วินาที
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

ระบุระยะเวลาที่จะถูกลบจากส่วนท้ายของสื่อระหว่างการเล่นเป็นมิลลิวินาที. อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าการตัดช่วงสุดท้ายเป็น 2 วินาที
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ audio frame. คุณสมบัตินี้อ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) ที่มีทุกแทร็กคำบรรยาย.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (shape instanceof IAudioFrame)
>          {
>              IAudioFrame audioFrame = (IAudioFrame) shape;
>              // บันทึกข้อมูลไบนารีของแทร็กคำบรรยายเป็นไฟล์ .vtt
>              for (ICaptions captionTrack : audioFrame.getCaptionTracks()) {
>                  FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                  fos.write(captionTrack.getBinaryData());
>                  fos.close();
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)