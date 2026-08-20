---
title: Timing
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: แสดงถึงการตั้งเวลาแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/timing/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

แสดงถึงการตั้งเวลาแอนิเมชัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | อธิบายเปอร์เซ็นต์ของระยะเวลาของผลการทำงานแบบเร่ง |
| [setAccelerate(float value)](#setAccelerate-float-) | อธิบายเปอร์เซ็นต์ของระยะเวลาของผลการทำงานแบบเร่ง |
| [getDecelerate()](#getDecelerate--) | อธิบายเปอร์เซ็นต์ของระยะเวลาของผลการทำงานแบบเร่งช้า |
| [setDecelerate(float value)](#setDecelerate-float-) | อธิบายเปอร์เซ็นต์ของระยะเวลาของผลการทำงานแบบเร่งช้า |
| [getAutoReverse()](#getAutoReverse--) | อธิบายว่าจะเล่นแอนิเมชันย้อนกลับโดยอัตโนมัติหลังจากเล่นไปข้างหน้าแล้วหรือไม่ |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | อธิบายว่าจะเล่นแอนิเมชันย้อนกลับโดยอัตโนมัติหลังจากเล่นไปข้างหน้าแล้วหรือไม่ |
| [getDuration()](#getDuration--) | อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน |
| [setDuration(float value)](#setDuration-float-) | อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน |
| [getRepeatCount()](#getRepeatCount--) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ |
| [setRepeatCount(float value)](#setRepeatCount-float-) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่ |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่ |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะทำซ้ำจนคลิกถัดไปหรือไม่ |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะทำซ้ำจนคลิกถัดไปหรือไม่ |
| [getRepeatDuration()](#getRepeatDuration--) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ |
| [getRestart()](#getRestart--) | กำหนดว่าผลกระทบจะรีสตาร์ทหลังจากเสร็จหรือไม่ |
| [setRestart(int value)](#setRestart-int-) | กำหนดว่าผลกระทบจะรีสตาร์ทหลังจากเสร็จหรือไม่ |
| [getRewind()](#getRewind--) | แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะรีวินด์เมื่อเล่นเสร็จหรือไม่ |
| [setRewind(boolean value)](#setRewind-boolean-) | แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะรีวินด์เมื่อเล่นเสร็จหรือไม่ |
| [getSpeed()](#getSpeed--) | กำหนดเปอร์เซ็นต์ที่ต้องการเพิ่มความเร็ว (หรือชะลอ) ของเวลา |
| [setSpeed(float value)](#setSpeed-float-) | กำหนดเปอร์เซ็นต์ที่ต้องการเพิ่มความเร็ว (หรือชะลอ) ของเวลา |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | อธิบายเวลาหน่วงหลังจากทริกเกอร์ |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | อธิบายเวลาหน่วงหลังจากทริกเกอร์ |
| [getTriggerType()](#getTriggerType--) | อธิบายประเภทของทริกเกอร์ |
| [setTriggerType(int value)](#setTriggerType-int-) | อธิบายประเภทของทริกเกอร์ |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

อธิบายเปอร์เซ็นต์ของระยะเวลาของผลการทำงานแบบเร่ง. อ่าน/เขียน float.

**คืนค่า:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

อธิบายเปอร์เซ็นต์ของระยะเวลาของผลการทำงานแบบเร่ง. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

อธิบายเปอร์เซ็นต์ของระยะเวลาของผลการทำงานแบบเร่งช้า. อ่าน/เขียน float.

**คืนค่า:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

อธิบายเปอร์เซ็นต์ของระยะเวลาของผลการทำงานแบบเร่งช้า. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

อธิบายว่าจะเล่นแอนิเมชันย้อนกลับโดยอัตโนมัติหลังจากเล่นไปข้างหน้าแล้วหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

อธิบายว่าจะเล่นแอนิเมชันย้อนกลับโดยอัตโนมัติหลังจากเล่นไปข้างหน้าแล้วหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน. อ่าน/เขียน float.

**คืนค่า:**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. อ่าน/เขียน float.

**คืนค่า:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยนการตั้งค่า Timing/Repeat ของเอฟเฟกต์เป็น "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยนการตั้งค่า Timing/Repeat ของเอฟเฟกต์เป็น "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะทำซ้ำจนคลิกถัดไปหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยนการตั้งค่า Timing/Repeat ของเอฟเฟกต์เป็น "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะทำซ้ำจนคลิกถัดไปหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยนการตั้งค่า Timing/Repeat ของเอฟเฟกต์เป็น "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public final float getRepeatDuration()
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. อ่าน/เขียน float.

**คืนค่า:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

กำหนดว่าผลกระทบจะรีสตาร์ทหลังจากเสร็จหรือไม่. อ่าน/เขียน [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**คืนค่า:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

กำหนดว่าผลกระทบจะรีสตาร์ทหลังจากเสร็จหรือไม่. อ่าน/เขียน [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะรีวินด์เมื่อเล่นเสร็จหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปิดใช้งาน Timing/Rewind ของเอฟเฟกต์.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

แอตทริบิวต์นี้กำหนดว่าเอฟเฟกต์จะรีวินด์เมื่อเล่นเสร็จหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปิดใช้งาน Timing/Rewind ของเอฟเฟกต์.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

กำหนดเปอร์เซ็นต์ที่ต้องการเพิ่มความเร็ว (หรือชะลอ) ของเวลา. อ่าน/เขียน float.

**คืนค่า:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

กำหนดเปอร์เซ็นต์ที่ต้องการเพิ่มความเร็ว (หรือชะลอ) ของเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

อธิบายเวลาหน่วงหลังจากทริกเกอร์. อ่าน/เขียน float.

**คืนค่า:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

อธิบายเวลาหน่วงหลังจากทริกเกอร์. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

อธิบายประเภทของทริกเกอร์. อ่าน/เขียน [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**คืนค่า:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

อธิบายประเภทของทริกเกอร์. อ่าน/เขียน [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject