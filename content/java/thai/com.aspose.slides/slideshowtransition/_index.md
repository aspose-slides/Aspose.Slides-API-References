---
title: SlideShowTransition
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงการเปลี่ยนสไลด์โชว์.
type: docs
url: /th/com.aspose.slides/slideshowtransition/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ทุก Interface ที่ Implement:**  
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)  
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

เป็นตัวแทนของการเปลี่ยนสไลด์โชว์  
## วิธีการ

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่ |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่ |
| [getSoundMode()](#getSoundMode--) | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์ |
| [setSoundMode(int value)](#setSoundMode-int-) | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์ |
| [getSoundLoop()](#getSoundLoop--) | แอตทริบิวต์นี้กำหนดว่าการเล่นเสียงจะวนซ้ำจนกว่าจะมีเหตุการณ์เสียงต่อไปในสไลด์โชว์ |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | แอตทริบิวต์นี้กำหนดว่าการเล่นเสียงจะวนซ้ำจนกว่าจะมีเหตุการณ์เสียงต่อไปในสไลด์โชว์ |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | ระบุว่าจะกดเมาส์เพื่อเลื่อนสไลด์ต่อหรือไม่ |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | ระบุว่าจะกดเมาส์เพื่อเลื่อนสไลด์ต่อหรือไม่ |
| [getAdvanceAfter()](#getAdvanceAfter--) | แอตทริบิวต์นี้กำหนดว่าจะให้สไลด์โชว์ย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | แอตทริบิวต์นี้กำหนดว่าจะให้สไลด์โชว์ย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนสไลด์ควรเริ่ม |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนสไลด์ควรเริ่ม |
| [getSpeed()](#getSpeed--) | ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ถัดไป |
| [setSpeed(int value)](#setSpeed-int-) | ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ถัดไป |
| [getValue()](#getValue--) | ค่าการเปลี่ยนสไลด์โชว์ |
| [getType()](#getType--) | ประเภทของการเปลี่ยน |
| [setType(int value)](#setType-int-) | ประเภทของการเปลี่ยน |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่ |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่ |
| [getSoundName()](#getSoundName--) | ระบุชื่อที่คนอ่านได้สำหรับเสียงของการเปลี่ยนสไลด์ |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | ระบุชื่อที่คนอ่านได้สำหรับเสียงของการเปลี่ยนสไลด์ |
| [getDuration()](#getDuration--) | รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที |
| [setDuration(int value)](#setDuration-int-) | รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าตัวอย่าง SlideShowTransition สองตัวเท่ากันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทใดประเภทหนึ่ง ที่เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

คืนค่า หรือกำหนดข้อมูลเสียงที่ฝังอยู่. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน/เขียน [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**ผลลัพธ์:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน/เขียน [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

แอตทริบิวต์นี้ระบุว่าการเล่นเสียงจะวนซ้ำจนกว่าจะมีเหตุการณ์เสียงต่อไปในสไลด์โชว์. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

แอตทริบิวต์นี้ระบุว่าการเล่นเสียงจะวนซ้ำจนกว่าจะมีเหตุการณ์เสียงต่อไปในสไลด์โชว์. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

ระบุว่าจะกดเมาส์เพื่อเลื่อนสไลด์ต่อหรือไม่. หากไม่ได้ระบุค่าจะถือว่าเป็น true. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

ระบุว่าจะกดเมาส์เพื่อเลื่อนสไลด์ต่อหรือไม่. หากไม่ได้ระบุค่าจะถือว่าเป็น true. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

แอตทริบิวต์นี้กำหนดว่าจะให้สไลด์โชว์ย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // รับการเปลี่ยนสไลด์แรก
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // ตรวจสอบว่าธง Advance Slide After ถูกตั้งค่าหรือไม่
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
public final void setAdvanceAfter(boolean value)
```

แอตทริบิวต์นี้กำหนดว่าจะให้สไลด์โชว์ย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // รับการเปลี่ยนสไลด์แรก
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // ตรวจสอบว่าธง Advance Slide After ถูกตั้งค่าหรือไม่
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
public final long getAdvanceAfterTime()
```

ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนสไลด์ควรเริ่ม. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากไม่ได้ระบุค่าจะถือว่าไม่มีการเลื่อนอัตโนมัติ. อ่าน/เขียน long.

**ผลลัพธ์:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนสไลด์ควรเริ่ม. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากไม่ได้ระบุค่าจะถือว่าไม่มีการเลื่อนอัตโนมัติ. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ถัดไป. อ่าน/เขียน [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**ผลลัพธ์:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ถัดไป. อ่าน/เขียน [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

ค่าการเปลี่ยนสไลด์โชว์. อ่านอย่างเดียว [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**ผลลัพธ์:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

ประเภทของการเปลี่ยน. อ่าน/เขียน [TransitionType](../../com.aspose.slides/transitiontype).

**ผลลัพธ์:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

ประเภทของการเปลี่ยน. อ่าน/เขียน [TransitionType](../../com.aspose.slides/transitiontype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่. หากแอตทริบิวต์นี้ตั้งเป็น true แอปพลิเคชันที่สร้างจะตรวจสอบแอตทริบิวต์ name ของเสียงนี้ในรายการเสียงในตัวและอาจแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่. หากแอตทริบิวต์นี้ตั้งเป็น true แอปพลิเคชันที่สร้างจะตรวจสอบแอตทริบิวต์ name ของเสียงนี้ในรายการเสียงในตัวและอาจแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

ระบุชื่อที่คนอ่านได้สำหรับเสียงของการเปลี่ยนสไลด์. คุณสมบัติ Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) ต้องถูกกำหนดเพื่อรับหรือกำหนดชื่อเสียง. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

ระบุชื่อที่คนอ่านได้สำหรับเสียงของการเปลี่ยนสไลด์. คุณสมบัติ Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) ต้องถูกกำหนดเพื่อรับหรือกำหนดชื่อเสียง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. อ่าน/เขียน int.

--------------------

สอดคล้องกับแอตทริบิวต์ p14:dur ขององค์ประกอบ p:transition ในสคีม่า PresentationML. หากไม่ได้ตั้งค่า ระยะเวลาจะกำหนดอัตโนมัติตามคุณสมบัติ \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) และประเภทของการเปลี่ยน.

**ผลลัพธ์:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. อ่าน/เขียน int.

--------------------

สอดคล้องกับแอตทริบิวต์ p14:dur ขององค์ประกอบ p:transition ในสคีม่า PresentationML. หากไม่ได้ตั้งค่า ระยะเวลาจะกำหนดอัตโนมัติตามคุณสมบัติ \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) และประเภทของการเปลี่ยน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าตัวอย่าง SlideShowTransition สองตัวเท่ากันหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | SlideShowTransition ที่ต้องการเปรียบเทียบกับ SlideShowTransition ปัจจุบัน |

**ผลลัพธ์:**
boolean -  **true**  หาก SlideShowTransition ที่ระบุเท่ากับ SlideShowTransition ปัจจุบัน; มิฉะนั้น,  **false** .

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทใดประเภทหนึ่ง ที่เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช.

**ผลลัพธ์:**
int - 23454

--------------------

Overriden to make compiler happy. Always returns constant because object is mutable.