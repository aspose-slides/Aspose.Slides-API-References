---
title: ITiming
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงการกำหนดเวลาการเคลื่อนไหว.
type: docs
url: /th/com.aspose.slides/itiming/
---```
public interface ITiming
```

แสดงถึงการกำหนดเวลาการเคลื่อนไหว.
## วิธีการ

| Method | Description |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | อธิบายเปอร์เซ็นต์ของพฤติกรรมเร่งความเร็วของระยะเวลา. |
| [setAccelerate(float value)](#setAccelerate-float-) | อธิบายเปอร์เซ็นต์ของพฤติกรรมเร่งความเร็วของระยะเวลา. |
| [getDecelerate()](#getDecelerate--) | อธิบายเปอร์เซ็นต์ของพฤติกรรมลดความเร็วของระยะเวลา. |
| [setDecelerate(float value)](#setDecelerate-float-) | อธิบายเปอร์เซ็นต์ของพฤติกรรมลดความเร็วของระยะเวลา. |
| [getAutoReverse()](#getAutoReverse--) | อธิบายว่าการเคลื่อนไหวจะเล่นย้อนกลับโดยอัตโนมัติหลังจากที่เล่นในทิศทางไปข้างหน้าหรือไม่. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | อธิบายว่าการเคลื่อนไหวจะเล่นย้อนกลับโดยอัตโนมัติหลังจากที่เล่นในทิศทางไปข้างหน้าหรือไม่. |
| [getDuration()](#getDuration--) | อธิบายระยะเวลาของเอฟเฟกต์การเคลื่อนไหว. |
| [setDuration(float value)](#setDuration-float-) | อธิบายระยะเวลาของเอฟเฟกต์การเคลื่อนไหว. |
| [getRepeatCount()](#getRepeatCount--) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | แอตทริบิวต์นี้ระบุว่เอฟเฟกต์จะทำซ้ำจนถึงตอนจบของสไลด์หรือไม่. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | แอตทริบิวต์นี้ระบุว่เอฟเฟกต์จะทำซ้ำจนถึงตอนจบของสไลด์หรือไม่. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | แอตทริบิวต์นี้ระบุว่เอฟเฟกต์จะทำซ้ำจนกว่าจะคลิกต่อไปหรือไม่. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | แอตทริบิวต์นี้ระบุว่เอฟเฟกต์จะทำซ้ำจนกว่าจะคลิกต่อไปหรือไม่. |
| [getRepeatDuration()](#getRepeatDuration--) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. |
| [getRestart()](#getRestart--) | ระบุว่าเอฟเฟกต์ควรรีสตาร์ทหลังจากเสร็จสิ้นหรือไม่. |
| [setRestart(int value)](#setRestart-int-) | ระบุว่าเอฟเฟกต์ควรรีสตาร์ทหลังจากเสร็จสิ้นหรือไม่. |
| [getSpeed()](#getSpeed--) | ระบุเปอร์เซ็นต์ที่ต้องเร่ง (หรือชะลอ) การกำหนดเวลา. |
| [setSpeed(float value)](#setSpeed-float-) | ระบุเปอร์เซ็นต์ที่ต้องเร่ง (หรือชะลอ) การกำหนดเวลา. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | อธิบายเวลาหน่วงหลังจากทริกเกอร์. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | อธิบายเวลาหน่วงหลังจากทริกเกอร์. |
| [getTriggerType()](#getTriggerType--) | อธิบายประเภทของทริกเกอร์. |
| [setTriggerType(int value)](#setTriggerType-int-) | อธิบายประเภทของทริกเกอร์. |
| [getRewind()](#getRewind--) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะย้อนกลับเมื่อเล่นเสร็จหรือไม่. |
| [setRewind(boolean value)](#setRewind-boolean-) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะย้อนกลับเมื่อเล่นเสร็จหรือไม่. |

### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

อธิบายเปอร์เซ็นต์ของพฤติกรรมเร่งความเร็วของระยะเวลา. อ่าน/เขียน float.

**คืนค่า:**
float

### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

อธิบายเปอร์เซ็นต์ของพฤติกรรมเร่งความเร็วของระยะเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

อธิบายเปอร์เซ็นต์ของพฤติกรรมลดความเร็วของระยะเวลา. อ่าน/เขียน float.

**คืนค่า:**
float

### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

อธิบายเปอร์เซ็นต์ของพฤติกรรมลดความเร็วของระยะเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

อธิบายว่าการเคลื่อนไหวจะเล่นย้อนกลับโดยอัตโนมัติหลังจากที่เล่นในทิศทางไปข้างหน้าหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

อธิบายว่าการเคลื่อนไหวจะเล่นย้อนกลับโดยอัตโนมัติหลังจากที่เล่นในทิศทางไปข้างหน้าหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

อธิบายระยะเวลาของเอฟเฟกต์การเคลื่อนไหว. อ่าน/เขียน float.

**คืนค่า:**
float

### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

อธิบายระยะเวลาของเอฟเฟกต์การเคลื่อนไหว. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. อ่าน/เขียน float.

**คืนค่า:**
float

### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

แอตทริบิวต์นี้ระบุว่เอฟเฟกต์จะทำซ้ำจนถึงตอนจบของสไลด์หรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
boolean

### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

แอตทริบิวต์นี้ระบุว่เอฟเฟกต์จะทำซ้ำจนถึงตอนจบของสไลด์หรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

แอตทริบิวต์นี้ระบุว่เอฟเฟกต์จะทำซ้ำจนกว่าจะคลิกต่อไปหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยนการกำหนดเวลา/การทำซ้ำของเอฟเฟกต์เป็น "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**
boolean

### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

แอตทริบิวต์นี้ระบุว่เอฟเฟกต์จะทำซ้ำจนกว่าจะคลิกต่อไปหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยนการกำหนดเวลา/การทำซ้ำของเอฟเฟกต์เป็น "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. อ่าน/เขียน float.

**คืนค่า:**
float

### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

ระบุว่าเอฟเฟกต์ควรรีสตาร์ทหลังจากเสร็จสิ้นหรือไม่. อ่าน/เขียน [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**คืนค่า:**
int

### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

ระบุว่าเอฟเฟกต์ควรรีสตาร์ทหลังจากเสร็จสิ้นหรือไม่. อ่าน/เขียน [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

ระบุเปอร์เซ็นต์ที่ต้องเร่ง (หรือชะลอ) การกำหนดเวลา. อ่าน/เขียน float.

**คืนค่า:**
float

### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

ระบุเปอร์เซ็นต์ที่ต้องเร่ง (หรือชะลอ) การกำหนดเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

อธิบายเวลาหน่วงหลังจากทริกเกอร์. อ่าน/เขียน float.

**คืนค่า:**
float

### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

อธิบายเวลาหน่วงหลังจากทริกเกอร์. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

อธิบายประเภทของทริกเกอร์. อ่าน/เขียน [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**คืนค่า:**
int

### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

อธิบายประเภทของทริกเกอร์. อ่าน/เขียน [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะย้อนกลับเมื่อเล่นเสร็จหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปิดการทำงานของ Timing/Rewind ของเอฟเฟกต์.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**
boolean

### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะย้อนกลับเมื่อเล่นเสร็จหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปิดการทำงานของ Timing/Rewind ของเอฟเฟกต์.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |