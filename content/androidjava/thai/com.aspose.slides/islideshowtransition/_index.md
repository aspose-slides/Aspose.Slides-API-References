---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงถึงการเปลี่ยนสไลด์โชว์.
type: docs
url: /th/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

แสดงถึงการเปลี่ยนสไลด์โชว์.
## เมธอด

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่. |
| [getSoundMode()](#getSoundMode--) | กำหนดหรือรับโหมดเสียงสำหรับการเปลี่ยนสไลด์. |
| [setSoundMode(int value)](#setSoundMode-int-) | กำหนดหรือรับโหมดเสียงสำหรับการเปลี่ยนสไลด์. |
| [getSoundLoop()](#getSoundLoop--) | แอตทริบิวต์นี้ระบุว่าซาวด์จะวนซ้ำจนกว่าจะเกิดเหตุการณ์เสียงถัดไปในสไลด์โชว์. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | แอตทริบิวต์นี้ระบุว่าซาวด์จะวนซ้ำจนกว่าจะเกิดเหตุการณ์เสียงถัดไปในสไลด์โชว์. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | ระบุว่าการคลิกเมาส์จะทำให้สไลด์เลื่อนไปข้างหน้าหรือไม่. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | ระบุว่าการคลิกเมาส์จะทำให้สไลด์เลื่อนไปข้างหน้าหรือไม่. |
| [getAdvanceAfter()](#getAdvanceAfter--) | แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์โชว์จะย้ายไปยังสไลด์ถัดไปหลังจากเวลาที่กำหนด. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์โชว์จะย้ายไปยังสไลด์ถัดไปหลังจากเวลาที่กำหนด. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนภาพควรเริ่มต้น. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนภาพควรเริ่มต้น. |
| [getSpeed()](#getSpeed--) | ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป. |
| [setSpeed(int value)](#setSpeed-int-) | ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป. |
| [getValue()](#getValue--) | ค่าการเปลี่ยนสไลด์โชว์. |
| [getType()](#getType--) | ประเภทของการเปลี่ยน. |
| [setType(int value)](#setType-int-) | ประเภทของการเปลี่ยน. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่. |
| [getSoundName()](#getSoundName--) | ระบุชื่อที่อ่านง่ายสำหรับเสียงของการเปลี่ยนสไลด์. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | ระบุชื่อที่อ่านง่ายสำหรับเสียงของการเปลี่ยนสไลด์. |
| [getDuration()](#getDuration--) | รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. |
| [setDuration(int value)](#setDuration-int-) | รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่. อ่าน-เขียน [IAudio](../../com.aspose.slides/iaudio).

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่. อ่าน-เขียน [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```


กำหนดหรือรับโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน-เขียน [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**ผลลัพธ์:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```


กำหนดหรือรับโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน-เขียน [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```


แอตทริบิวต์นี้ระบุว่าซาวด์จะวนซ้ำจนกว่าจะเกิดเหตุการณ์เสียงถัดไปในสไลด์โชว์. อ่าน-เขียน boolean.

**ผลลัพธ์:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```


แอตทริบิวต์นี้ระบุว่าซาวด์จะวนซ้ำจนกว่าจะเกิดเหตุการณ์เสียงถัดไปในสไลด์โชว์. อ่าน-เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```


ระบุว่าการคลิกเมาส์จะทำให้สไลด์เลื่อนไปข้างหน้าหรือไม่. หากแอตทริบิวต์นี้ไม่ได้ระบุจะถือว่าค่าเป็น true. อ่าน-เขียน boolean.

**ผลลัพธ์:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```


ระบุว่าการคลิกเมาส์จะทำให้สไลด์เลื่อนไปข้างหน้าหรือไม่. หากแอตทริบิวต์นี้ไม่ได้ระบุจะถือว่าค่าเป็น true. อ่าน-เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```


แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์โชว์จะย้ายไปยังสไลด์ถัดไปหลังจากเวลาที่กำหนด. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // รับการเปลี่ยนสไลด์แรก
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // ตรวจสอบว่าแฟล็ก Advance Slide After ถูกตั้งค่าไว้หรือไม่
>      if (slideTransition.getAdvanceAfter())
>      {
>          // รับค่าเวลา Advance Slide After
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ผลลัพธ์:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```


แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์โชว์จะย้ายไปยังสไลด์ถัดไปหลังจากเวลาที่กำหนด. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // รับการเปลี่ยนสไลด์แรก
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // ตรวจสอบว่าแฟล็ก Advance Slide After ถูกตั้งค่าไว้หรือไม่
>      if (slideTransition.getAdvanceAfter())
>      {
>          // รับค่าเวลา Advance Slide After
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```


ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนภาพควรเริ่มต้น. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือว่ามีการเลื่อนอัตโนมัติไม่เกิดขึ้น. อ่าน-เขียน long.

**ผลลัพธ์:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```


ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนภาพควรเริ่มต้น. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือว่ามีการเลื่อนอัตโนมัติไม่เกิดขึ้น. อ่าน-เขียน long.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```


ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป. อ่าน-เขียน [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**ผลลัพธ์:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```


ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป. อ่าน-เขียน [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```


ค่าการเปลี่ยนสไลด์โชว์. อ่านอย่างเดียว [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**ผลลัพธ์:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```


ประเภทของการเปลี่ยน. อ่าน-เขียน [TransitionType](../../com.aspose.slides/transitiontype).

**ผลลัพธ์:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


ประเภทของการเปลี่ยน. อ่าน-เขียน [TransitionType](../../com.aspose.slides/transitiontype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```


ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่. หากแอตทริบิวต์นี้ตั้งค่าเป็น true โปรแกรมที่สร้างจะตรวจสอบแอตทริบิวต์ name ที่ระบุสำหรับเสียงนี้ในรายการเสียงในตัวและสามารถแสดงชื่อหรือ UI ที่กำหนดเองได้ตามต้องการ. อ่าน-เขียน boolean.

**ผลลัพธ์:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```


ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่. หากแอตทริบิวต์นี้ตั้งค่าเป็น true โปรแกรมที่สร้างจะตรวจสอบแอตทริบิวต์ name ที่ระบุสำหรับเสียงนี้ในรายการเสียงในตัวและสามารถแสดงชื่อหรือ UI ที่กำหนดเองได้ตามต้องการ. อ่าน-เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```


ระบุชื่อที่อ่านง่ายสำหรับเสียงของการเปลี่ยนสไลด์. คุณสมบัติ (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) ต้องถูกกำหนดเพื่อรับหรือกำหนดชื่อเสียง. อ่าน-เขียน String.

**ผลลัพธ์:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```


ระบุชื่อที่อ่านง่ายสำหรับเสียงของการเปลี่ยนสไลด์. คุณสมบัติ \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) ต้องถูกกำหนดเพื่อรับหรือกำหนดชื่อเสียง. อ่าน-เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```


รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. อ่าน/เขียน int.

--------------------

สอดคล้องกับแอตทริบิวต์ p14:dur ขององค์ประกอบ p:transition ในสคีม่า PresentationML. หากไม่ได้ตั้งค่า ระยะเวลาจะถูกกำหนดโดยอัตโนมัติตามคุณสมบัติ \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) และประเภทของการเปลี่ยน.

**ผลลัพธ์:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```


รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. อ่าน/เขียน int.

--------------------

สอดคล้องกับแอตทริบิวต์ p14:dur ขององค์ประกอบ p:transition ในสคีม่า PresentationML. หากไม่ได้ตั้งค่า ระยะเวลาจะถูกกำหนดโดยอัตโนมัติตามคุณสมบัติ \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) และประเภทของการเปลี่ยน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |