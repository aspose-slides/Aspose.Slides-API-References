---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Represents slide show transition.
type: docs
url: /th/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

แสดงการเปลี่ยนสไลด์โชว์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSound()](#getSound--) | คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่ |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่ |
| [getSoundMode()](#getSoundMode--) | ตั้งค่า หรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์ |
| [setSoundMode(int value)](#setSoundMode-int-) | ตั้งค่า หรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์ |
| [getSoundLoop()](#getSoundLoop--) | แอตทริบิวต์นี้ระบุว่าซาวด์จะทำซ้ำจนกว่าจะมีเหตุการณ์เสียงถัดไปเกิดขึ้นในสไลด์โชว์ |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | แอตทริบิวต์นี้ระบุว่าซาวด์จะทำซ้ำจนกว่าจะมีเหตุการณ์เสียงถัดไปเกิดขึ้นในสไลด์โชว์ |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | ระบุว่าการคลิกเมาส์จะทำให้สไลด์ก้าวหน้า หรือไม่ |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | ระบุว่าการคลิกเมาส์จะทำให้สไลด์ก้าวหน้า หรือไม่ |
| [getAdvanceAfter()](#getAdvanceAfter--) | แอตทริบิวต์นี้ระบุว่าการพรีเซนเทชันจะย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | แอตทริบิวต์นี้ระบุว่าการพรีเซนเทชันจะย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | ระบุเวลาที่หน่วยเป็นมิลลิวินาที ซึ่งหลังจากนั้นการเปลี่ยนจะเริ่มต้น |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | ระบุเวลาที่หน่วยเป็นมิลลิวินาที ซึ่งหลังจากนั้นการเปลี่ยนจะเริ่มต้น |
| [getSpeed()](#getSpeed--) | ระบุความเร็วของการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป |
| [setSpeed(int value)](#setSpeed-int-) | ระบุความเร็วของการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป |
| [getValue()](#getValue--) | ค่าการเปลี่ยนสไลด์โชว์ |
| [getType()](#getType--) | ประเภทของการเปลี่ยน |
| [setType(int value)](#setType-int-) | ประเภทของการเปลี่ยน |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | ระบุว่านี้เป็นเสียงที่มาพร้อมในระบบหรือไม่ |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | ระบุว่านี้เป็นเสียงที่มาพร้อมในระบบหรือไม่ |
| [getSoundName()](#getSoundName--) | ระบุชื่อที่อ่านเข้าใจได้สำหรับเสียงของการเปลี่ยน |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | ระบุชื่อที่อ่านเข้าใจได้สำหรับเสียงของการเปลี่ยน |
| [getDuration()](#getDuration--) | รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์ในหน่วยมิลลิวินาที |
| [setDuration(int value)](#setDuration-int-) | รับหรือกำหนดระยะเวลของเอฟเฟกต์การเปลี่ยนสไลด์ในหน่วยมิลลิวินาที |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่. อ่าน-เขียน [IAudio](../../com.aspose.slides/iaudio).

**คืนค่า:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่. อ่าน-เขียน [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

ตั้งค่า หรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน-เขียน [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**คืนค่า:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

ตั้งค่า หรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน-เขียน [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

แอตทริบิวต์นี้ระบุว่าซาวด์จะทำซ้ำจนกว่าจะมีเหตุการณ์เสียงถัดไปเกิดขึ้นในสไลด์โชว์. อ่าน-เขียน boolean.

**คืนค่า:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

แอตทริบิวต์นี้ระบุว่าซาวด์จะทำซ้ำจนกว่าจะมีเหตุการณ์เสียงถัดไปเกิดขึ้นในสไลด์โชว์. อ่าน-เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

ระบุว่าการคลิกเมาส์จะทำให้สไลด์ก้าวหน้า หรือไม่. หากไม่ได้ระบุค่า จะถือว่าเป็น true. อ่าน-เขียน boolean.

**คืนค่า:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

ระบุว่าการคลิกเมาส์จะทำให้สไลด์ก้าวหน้า หรือไม่. หากไม่ได้ระบุค่า จะถือว่าเป็น true. อ่าน-เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

แอตทริบิวต์นี้ระบุว่าการพรีเซนเทชันจะย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่. อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // รับการเปลี่ยนสไลด์แรก
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // ตรวจสอบว่าแฟล็ก Advance Slide After ถูกเลือกหรือไม่
>      if (slideTransition.getAdvanceAfter())
>      {
>          // รับค่าเวลา Advance Slide After
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

แอตทริบิวต์นี้ระบุว่าการพรีเซนเทชันจะย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่. อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // รับการเปลี่ยนสไลด์แรก
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // ตรวจสอบว่าแฟล็ก Advance Slide After ถูกเลือกหรือไม่
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

ระบุเวลาที่หน่วยเป็นมิลลิวินาที ซึ่งหลังจากนั้นการเปลี่ยนจะเริ่มต้น. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากไม่ได้ระบุค่า จะถือว่าไม่มีการเปลี่ยนอัตโนมัติ. อ่าน-เขียน long.

**คืนค่า:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

ระบุเวลาที่หน่วยเป็นมิลลิวินาที ซึ่งหลังจากนั้นการเปลี่ยนจะเริ่มต้น. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากไม่ได้ระบุค่า จะถือว่าไม่มีการเปลี่ยนอัตโนมัติ. อ่าน-เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

ระบุความเร็วของการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป. อ่าน-เขียน [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**คืนค่า:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

ระบุความเร็วของการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป. อ่าน-เขียน [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

ค่าการเปลี่ยนสไลด์โชว์. อ่านอย่างเดียว [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**คืนค่า:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

ประเภทของการเปลี่ยน. อ่าน-เขียน [TransitionType](../../com.aspose.slides/transitiontype).

**คืนค่า:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

ประเภทของการเปลี่ยน. อ่าน-เขียน [TransitionType](../../com.aspose.slides/transitiontype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

ระบุว่านี้เป็นเสียงที่มาพร้อมในระบบหรือไม่. หากแอตทริบิวต์นี้ตั้งค่าเป็น true ระบบสร้างสรรค์จะตรวจสอบแอตทริบิวต์ name ที่ระบุสำหรับเสียงนี้ในรายการเสียงที่มาพร้อมและอาจแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ. อ่าน-เขียน boolean.

**คืนค่า:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

ระบุว่านี้เป็นเสียงที่มาพร้อมในระบบหรือไม่. หากแอตทริบิวต์นี้ตั้งค่าเป็น true ระบบสร้างสรรค์จะตรวจสอบแอตทริบิวต์ name ที่ระบุสำหรับเสียงนี้ในรายการเสียงที่มาพร้อมและอาจแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ. อ่าน-เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

ระบุชื่อที่อ่านเข้าใจได้สำหรับเสียงของการเปลี่ยน. คุณสมบัติ \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) ต้องกำหนดค่าเพื่อรับหรือกำหนดชื่อเสียง. อ่าน-เขียน String.

**คืนค่า:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

ระบุชื่อที่อ่านเข้าใจได้สำหรับเสียงของการเปลี่ยน. คุณสมบัติ \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) ต้องกำหนดค่าเพื่อรับหรือกำหนดชื่อเสียง. อ่าน-เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์ในหน่วยมิลลิวินาที. อ่าน/เขียน int.

--------------------

ตรงกับแอตทริบิวต์ p14:dur ขององค์ประกอบ p:transition ในสคีม่า PresentationML หากไม่ได้ตั้งค่า ระยะเวลาจะถูกกำหนดโดยอัตโนมัติตามคุณสมบัติ \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) และประเภทของการเปลี่ยน.

**คืนค่า:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์ในหน่วยมิลลิวินาที. อ่าน/เขียน int.

--------------------

ตรงกับแอตทริบิวต์ p14:dur ขององค์ประกอบ p:transition ในสคีม่า PresentationML หากไม่ได้ตั้งค่า ระยะเวลาจะถูกกำหนดโดยอัตโนมัติตามคุณสมบัติ \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) และประเภทของการเปลี่ยน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |