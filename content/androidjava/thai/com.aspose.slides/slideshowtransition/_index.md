---
title: SlideShowTransition
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงการเปลี่ยนสไลด์โชว์.
type: docs
url: /th/com.aspose.slides/slideshowtransition/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**ส่วนต่อประสานที่ทำงานทั้งหมด:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

แสดงการเปลี่ยนสไลด์โชว์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSound()](#getSound--) | คืนค่าหรือกำหนดข้อมูลเสียงที่ฝังอยู่. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | คืนค่าหรือกำหนดข้อมูลเสียงที่ฝังอยู่. |
| [getSoundMode()](#getSoundMode--) | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. |
| [setSoundMode(int value)](#setSoundMode-int-) | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. |
| [getSoundLoop()](#getSoundLoop--) | แอตทริบิวต์นี้ระบุว่าความเสียงจะวนซ้ำจนกระทั่งเหตุการณ์เสียงต่อไปเกิดขึ้นในสไลด์โชว์. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | แอตทริบิวต์นี้ระบุว่าความเสียงจะวนซ้ำจนกระทั่งเหตุการณ์เสียงต่อไปเกิดขึ้นในสไลด์โชว์. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | ระบุว่าการคลิกเมาส์จะเลื่อนสไลด์ต่อหรือไม่. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | ระบุว่าการคลิกเมาส์จะเลื่อนสไลด์ต่อหรือไม่. |
| [getAdvanceAfter()](#getAdvanceAfter--) | แอตทริบิวต์นี้ระบุว่าการสไลด์โชว์จะย้ายไปสไลด์ถัดไปหลังจากเวลาหนึ่ง. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | แอตทริบิวต์นี้ระบุว่าการสไลด์โชว์จะย้ายไปสไลด์ถัดไปหลังจากเวลาหนึ่ง. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนแปลงจะเริ่มต้น. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนแปลงจะเริ่มต้น. |
| [getSpeed()](#getSpeed--) | ระบุความเร็วการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปสไลด์ต่อไป. |
| [setSpeed(int value)](#setSpeed-int-) | ระบุความเร็วการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปสไลด์ต่อไป. |
| [getValue()](#getValue--) | ค่าการเปลี่ยนสไลด์โชว์. |
| [getType()](#getType--) | ประเภทของการเปลี่ยน. |
| [setType(int value)](#setType-int-) | ประเภทของการเปลี่ยน. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | ระบุว่าเสียงนี้เป็นเสียงที่มาพร้อมกับโปรแกรมหรือไม่. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | ระบุว่าเสียงนี้เป็นเสียงที่มาพร้อมกับโปรแกรมหรือไม่. |
| [getSoundName()](#getSoundName--) | ระบุชื่อที่อ่านง่ายสำหรับเสียงของการเปลี่ยน. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | ระบุชื่อที่อ่านง่ายสำหรับเสียงของการเปลี่ยน. |
| [getDuration()](#getDuration--) | รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. |
| [setDuration(int value)](#setDuration-int-) | รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าตัวอย่าง SlideShowTransition สองอันเท่าเทียมกันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะที่เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

คืนค่าหรือกำหนดข้อมูลเสียงที่ฝังอยู่. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**คืนค่า:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

คืนค่าหรือกำหนดข้อมูลเสียงที่ฝังอยู่. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน/เขียน [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**คืนค่า:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน/เขียน [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

แอตทริบิวต์นี้ระบุว่าความเสียงจะวนซ้ำจนกว่าจะเหตุการณ์เสียงต่อไปเกิดขึ้นในสไลด์โชว์. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

แอตทริบิวต์นี้ระบุว่าความเสียงจะวนซ้ำจนกว่าจะเหตุการณ์เสียงต่อไปเกิดขึ้นในสไลด์โชว์. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

ระบุว่าการคลิกเมาส์จะเลื่อนสไลด์ต่อหรือไม่. หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือค่าจริงเป็นค่าเริ่มต้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

ระบุว่าการคลิกเมาส์จะเลื่อนสไลด์ต่อหรือไม่. หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือค่าจริงเป็นค่าเริ่มต้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

แอตทริบิวต์นี้ระบุว่าการสไลด์โชว์จะย้ายไปสไลด์ต่อหลังจากเวลาหนึ่ง. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // รับการเปลี่ยนสไลด์แรก
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // ตรวจสอบว่าแฟลก Advance Slide After ถูกตั้งค่า
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
public final void setAdvanceAfter(boolean value)
```

แอตทริบิวต์นี้ระบุว่าการสไลด์โชว์จะย้ายไปสไลด์ต่อหลังจากเวลาหนึ่ง. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // รับการเปลี่ยนสไลด์แรก
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // ตรวจสอบว่าแฟลก Advance Slide After ถูกตั้งค่า
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

ระบุเวลาเป็นมิลลิวินาที หลังจากนั้นการเปลี่ยนแปลงจะเริ่มต้น. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือว่าไม่มีการเลื่อนอัตโนมัติ. อ่าน/เขียน long.

**คืนค่า:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

ระบุเวลาเป็นมิลลิวินาที หลังจากนั้นการเปลี่ยนแปลงจะเริ่มต้น. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือว่าไม่มีการเลื่อนอัตโนมัติ. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

ระบุความเร็วการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปสไลด์ต่อไป. อ่าน/เขียน [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**คืนค่า:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

ระบุความเร็วการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปสไลด์ต่อไป. อ่าน/เขียน [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

ค่าการเปลี่ยนสไลด์โชว์. อ่านอย่างเดียว [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**คืนค่า:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

ประเภทของการเปลี่ยน. อ่าน/เขียน [TransitionType](../../com.aspose.slides/transitiontype).

**คืนค่า:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

ประเภทของการเปลี่ยน. อ่าน/เขียน [TransitionType](../../com.aspose.slides/transitiontype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

ระบุว่าเสียงนี้เป็นเสียงที่มาพร้อมกับโปรแกรมหรือไม่. หากแอตทริบิวต์นี้ตั้งเป็น true โปรแกรมที่สร้างจะได้รับการแจ้งให้ตรวจสอบแอตทริบิวต์ name ที่ระบุสำหรับเสียงนี้ในรายการเสียงที่มาพร้อมและสามารถแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

ระบุว่าเสียงนี้เป็นเสียงที่มาพร้อมกับโปรแกรมหรือไม่. หากแอตทริบิวต์นี้ตั้งเป็น true โปรแกรมที่สร้างจะได้รับการแจ้งให้ตรวจสอบแอตทริบิวต์ name ที่ระบุสำหรับเสียงนี้ในรายการเสียงที่มาพร้อมและสามารถแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

ระบุชื่อที่อ่านง่ายสำหรับเสียงของการเปลี่ยน. คุณสมบัติ Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) ต้องถูกกำหนดเพื่อรับหรือกำหนดชื่อเสียง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

ระบุชื่อที่อ่านง่ายสำหรับเสียงของการเปลี่ยน. คุณสมบัติ Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) ต้องถูกกำหนดเพื่อรับหรือกำหนดชื่อเสียง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. อ่าน/เขียน int.

--------------------

สอดคล้องกับแอตทริบิวต์ p14:dur ขององค์ประกอบ p:transition ในสคีม่า PresentationML. หากไม่ได้ตั้งค่า ระยะเวลาจะกำหนดอัตโนมัติตามคุณสมบัติ \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) และประเภทการเปลี่ยน.

**คืนค่า:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. อ่าน/เขียน int.

--------------------

สอดคล้องกับแอตทริบิวต์ p14:dur ขององค์ประกอบ p:transition ในสคีม่า PresentationML. หากไม่ได้ตั้งค่า ระยะเวลาจะกำหนดอัตโนมัติตามคุณสมบัติ \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) และประเภทการเปลี่ยน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าตัวอย่าง SlideShowTransition สองอันเท่าเทียมกันหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | SlideShowTransition ที่จะเปรียบเทียบกับ SlideShowTransition ปัจจุบัน. |

**คืนค่า:**
boolean -  **true**  หาก SlideShowTransition ที่ระบุเท่ากับ SlideShowTransition ปัจจุบัน; มิฉะนั้น  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะที่เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช.

**คืนค่า:**
int - 23454

--------------------

ถูกเขียนทับเพื่อทำให้คอมไพเลอร์พอใจ. เสมอคืนค่าคงที่เนื่องจากวัตถุสามารถเปลี่ยนแปลงได้.