---
title: IAudioFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคลิปเสียงบนสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/iaudioframe/
---
**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

แสดงคลิปเสียงบนสไลด์หนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | คืนค่าหรือกำหนดดัชนีแทร็กเริ่มต้น. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | คืนค่าหรือกำหนดดัชนีแทร็กเริ่มต้น. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | คืนค่าหรือกำหนดเวลาเริ่มต้นของแทร็ก. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | คืนค่าหรือกำหนดเวลาเริ่มต้นของแทร็ก. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | คืนค่า或กำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | คืนค่า或กำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | คืนค่า或กำหนดเวลาสุดท้ายของแทร็ก. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | คืนค่า或กำหนดเวลาสุดท้ายของแทร็ก. |
| [getVolume()](#getVolume--) | คืนค่า或กำหนดระดับเสียงของออดิโอ. |
| [setVolume(int value)](#setVolume-int-) | คืนค่า或กำหนดระดับเสียงของออดิโอ. |
| [getPlayMode()](#getPlayMode--) | คืนค่า或กำหนดโหมดการเล่นออดิโอ. |
| [setPlayMode(int value)](#setPlayMode-int-) | คืนค่า或กำหนดโหมดการเล่นออดิโอ. |
| [getHideAtShowing()](#getHideAtShowing--) | กำหนดว่า AudioFrame จะซ่อนอยู่หรือไม่. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | กำหนดว่า AudioFrame จะซ่อนอยู่หรือไม่. |
| [getPlayLoopMode()](#getPlayLoopMode--) | กำหนดว่าเสียงจะเล่นวนซ้ำหรือไม่. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | กำหนดว่าเสียงจะเล่นวนซ้ำหรือไม่. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | กำหนดว่าเสียงจะเล่นต่อเนื่องข้ามสไลด์หรือไม่. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | กำหนดว่าเสียงจะเล่นต่อเนื่องข้ามสไลด์หรือไม่. |
| [getRewindAudio()](#getRewindAudio--) | กำหนดว่าเสียงจะถูกรีวินด์อัตโนมัติไปเริ่มต้นหลังเล่นเสร็จหรือไม่. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | กำหนดว่าเสียงจะถูกรีวินด์อัตโนมัติไปเริ่มต้นหลังเล่นเสร็จหรือไม่. |
| [getEmbedded()](#getEmbedded--) | กำหนดว่าเสียงจะฝังอยู่ในงานนำเสนอหรือไม่. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า或กำหนดชื่อไฟล์ออดิโอที่เชื่อมโยงกับ AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่า或กำหนดชื่อไฟล์ออดิโอที่เชื่อมโยงกับ AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | คืนค่า或กำหนดออบเจกต์ออดิโอที่ฝังไว้. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | คืนค่า或กำหนดออบเจกต์ออดิโอที่ฝังไว้. |
| [getFadeInDuration()](#getFadeInDuration--) | ระบุตัวเวลาเป็นมิลลิวินาทีสำหรับการเฟดอินเริ่มต้นของสื่อ. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | ระบุตัวเวลาเป็นมิลลิวินาทีสำหรับการเฟดอินเริ่มต้นของสื่อ. |
| [getFadeOutDuration()](#getFadeOutDuration--) | ระบุตัวเวลาเป็นมิลลิวินาทีสำหรับการเฟดเอาต์สุดท้ายของสื่อ. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | ระบุตัวเวลาเป็นมิลลิวินาทีสำหรับการเฟดเอาต์สุดท้ายของสื่อ. |
| [getVolumeValue()](#getVolumeValue--) | คืนค่า或กำหนดระดับเสียงออดิโอเป็นเปอร์เซ็นต์. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | คืนค่า或กำหนดระดับเสียงออดิโอเป็นเปอร์เซ็นต์. |
| [getTrimFromStart()](#getTrimFromStart--) | ระบุตัวเวลาเป็นมิลลิวินาทีที่จะตัดออกจากต้นสื่อระหว่างการเล่น. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | ระบุตัวเวลาเป็นมิลลิวินาทีที่จะตัดออกจากต้นสื่อระหว่างการเล่น. |
| [getTrimFromEnd()](#getTrimFromEnd--) | ระบุตัวเวลาเป็นมิลลิวินาทีที่จะตัดออกจากท้ายสื่อระหว่างการเล่น. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | ระบุตัวเวลาเป็นมิลลิวินาทีที่จะตัดออกจากท้ายสื่อระหว่างการเล่น. |
| [getCaptionTracks()](#getCaptionTracks--) | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ AudioFrame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

คืนค่า或กำหนดดัชนีแทร็กเริ่มต้น. อ่าน/เขียน int.

**คืนค่า:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

คืนค่า或กำหนดดัชนีแทร็กเริ่มต้น. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

คืนค่า或กำหนดเวลาเริ่มต้นของแทร็ก. อ่าน/เขียน int.

**คืนค่า:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

คืนค่า或กำหนดเวลาเริ่มต้นของแทร็ก. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

คืนค่า或กำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน int.

**คืนค่า:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

คืนค่า或กำหนดดัชนีแทร็กสุดท้าย อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

คืนค่า或กำหนดเวลาสุดท้ายของแทร็ก. อ่าน/เขียน int.

**คืนค่า:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

คืนค่า或กำหนดเวลาสุดท้ายของแทร็ก. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

คืนค่า或กำหนดระดับเสียงออดิโอ. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**คืนค่า:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

คืนค่า或กำหนดระดับเสียงออดิโอ. อ่าน/เขียน [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

คืนค่า或กำหนดโหมดการเล่นออดิโอ. อ่าน/เขียน [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**คืนค่า:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

คืนค่า或กำหนดโหมดการเล่นออดิโอ. อ่าน/เขียน [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

กำหนดว่า AudioFrame จะซ่อนอยู่หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

กำหนดว่า AudioFrame จะซ่อนอยู่หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

กำหนดว่าเสียงจะเล่นวนซ้ำหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

กำหนดว่าเสียงจะเล่นวนซ้ำหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

กำหนดว่าเสียงจะเล่นต่อเนื่องข้ามสไลด์หรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จ
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
public abstract void setPlayAcrossSlides(boolean value)
```

กำหนดว่าเสียงจะเล่นต่อเนื่องข้ามสไลด์หรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
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

กำหนดว่าเสียงจะรีวินด์อัตโนมัติไปเริ่มต้นหลังเล่นเสร็จหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
>       audioFrame.setPlayAcrossSlides(true);
>       // ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่นเสร็จ
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
public abstract void setRewindAudio(boolean value)
```

กำหนดว่าเสียงจะรีวินด์อัตโนมัติไปเริ่มต้นหลังเล่นเสร็จหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // เพิ่ม Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
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

กำหนดว่าเสียงจะฝังอยู่ในงานนำเสนอหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

คืนค่า或กำหนดชื่อไฟล์ออดิโอที่เชื่อมโยงกับ AudioFrame. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

คืนค่า或กำหนดชื่อไฟล์ออดิโอที่เชื่อมโยงกับ AudioFrame. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

คืนค่า或กำหนดออบเจกต์ออดิโอที่ฝังไว้. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**คืนค่า:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

คืนค่า或กำหนดออบเจกต์ออดิโอที่ฝังไว้. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

ระบุตัวเวลาเป็นมิลลิวินาทีสำหรับการเฟดอินเริ่มต้นของสื่อ. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระยะเวลาเฟดอินเริ่มต้นเป็น 200 มิลลิวินาที
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
public abstract void setFadeInDuration(float value)
```

ระบุตัวเวลาเป็นมิลลิวินาทีสำหรับการเฟดอินเริ่มต้นของสื่อ. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระยะเวลาเฟดอินเริ่มต้นเป็น 200 มิลลิวินาที
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

ระบุตัวเวลาเป็นมิลลิวินาทีสำหรับการเฟดเอาต์สุดท้ายของสื่อ. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระยะเวลาเฟดเอาต์สุดท้ายเป็น 500 มิลลิวินาที
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
public abstract void setFadeOutDuration(float value)
```

ระบุตัวเวลาเป็นมิลลิวินาทีสำหรับการเฟดเอาต์สุดท้ายของสื่อ. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระยะเวลาเฟดเอาต์สุดท้ายเป็น 500 มิลลิวินาที
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเทร | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

คืนค่า或กำหนดระดับเสียงออดิโอเป็นเปอร์เซ็นต์. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระดับเสียงออดิโอเป็น 85%
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
public abstract void setVolumeValue(float value)
```

คืนค่า或กำหนดระดับเสียงออดิโอเป็นเปอร์เซ็นต์. อ่าน/เขียน float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าระดับเสียงออดิโอเป็น 85%
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

ระบุตัวเวลาเป็นมิลลิวินาทีที่จะตัดออกจากต้นสื่อระหว่างการเล่น. อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าช่วงตัดเริ่มต้น 1.5 วินาที
>      audioFrame.setTrimFromStart(1500f);
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

ระบุตัวเวลาเป็นมิลลิวินาทีที่จะตัดออกจากต้นสื่อระหว่างการเล่น. อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าช่วงตัดเวลาต้น 1.5 วินาที
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

ระบุตัวเวลาเป็นมิลลิวินาทีที่จะตัดออกจากท้ายสื่อระหว่างการเล่น. อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าช่วงตัดเวลาสิ้นสุด 2 วินาที
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

ระบุตัวเวลาเป็นมิลลิวินาทีที่จะตัดออกจากท้ายสื่อระหว่างการเล่น. อ่าน/เขียน float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // ตั้งค่าช่วงตัดเวลาสิ้นสุด 2 วินาที
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

รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ AudioFrame. คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด.

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

**คืนค่า:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)