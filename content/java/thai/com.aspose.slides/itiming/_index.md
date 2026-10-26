---
title: ITiming
second_title: Aspose.Slides for Java API Reference
description: แสดงถึงการกำหนดเวลาแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/itiming/
---```
public interface ITiming
```

แสดงถึงการกำหนดเวลาแอนิเมชัน.
## เมธอด

| Method | Description |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | อธิบายเปอร์เซ็นต์ของระยะเวลาในพฤติกรรมเร่ง |
| [setAccelerate(float value)](#setAccelerate-float-) | อธิบายเปอร์เซ็นต์ของระยะเวลาในพฤติกรรมเร่ง |
| [getDecelerate()](#getDecelerate--) | อธิบายเปอร์เซ็นต์ของระยะเวลาในพฤติกรรมชะลอ |
| [setDecelerate(float value)](#setDecelerate-float-) | อธิบายเปอร์เซ็นต์ของระยะเวลาในพฤติกรรมชะลอ |
| [getAutoReverse()](#getAutoReverse--) | อธิบายว่าควรเล่นแอนิเมชันแบบย้อนกลับโดยอัตโนมัติหลังจากเล่นในทิศทางไปข้างหน้าหรือไม่ |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | อธิบายว่าควรเล่นแอนิเมชันแบบย้อนกลับโดยอัตโนมัติหลังจากเล่นในทิศทางไปข้างหน้าหรือไม่ |
| [getDuration()](#getDuration--) | อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน |
| [setDuration(float value)](#setDuration-float-) | อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน |
| [getRepeatCount()](#getRepeatCount--) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ |
| [setRepeatCount(float value)](#setRepeatCount-float-) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่ |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่ |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนกว่าจะคลิกครั้งถัดไปหรือไม่ |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนกว่าจะคลิกครั้งถัดไปหรือไม่ |
| [getRepeatDuration()](#getRepeatDuration--) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ |
| [getRestart()](#getRestart--) | ระบุว่าเอฟเฟกต์จะเริ่มใหม่หลังจากเสร็จสมบูรณ์หรือไม่ |
| [setRestart(int value)](#setRestart-int-) | ระบุว่าเอฟเฟกต์จะเริ่มใหม่หลังจากเสร็จสมบูรณ์หรือไม่ |
| [getSpeed()](#getSpeed--) | ระบุเปอร์เซ็นต์ที่ต้องการเร่ง (หรือชะลอ) เวลา |
| [setSpeed(float value)](#setSpeed-float-) | ระบุเปอร์เซ็นต์ที่ต้องการเร่ง (หรือชะลอ) เวลา |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | อธิบายเวลาหน่วงหลังจากการกระตุ้น |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | อธิบายเวลาหน่วงหลังจากการกระตุ้น |
| [getTriggerType()](#getTriggerType--) | อธิบายประเภทของทริกเกอร์ |
| [setTriggerType(int value)](#setTriggerType-int-) | อธิบายประเภทของทริกเกอร์ |
| [getRewind()](#getRewind--) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะรีวินด์เมื่อเล่นเสร็จหรือไม่ |
| [setRewind(boolean value)](#setRewind-boolean-) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะรีวินด์เมื่อเล่นเสร็จหรือไม่ |

### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

อธิบายเปอร์เซ็นต์ของระยะเวลาในพฤติกรรมเร่ง. Read/write float.

**คืนค่า:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

อธิบายเปอร์เซ็นต์ของระยะเวลาในพฤติกรรมเร่ง. Read/write float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

อธิบายเปอร์เซ็นต์ของระยะเวลาในพฤติกรรมชะลอ. Read/write float.

**คืนค่า:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

อธิบายเปอร์เซ็นต์ของระยะเวลาในพฤติกรรมชะลอ. Read/write float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

อธิบายว่าควรเล่นแอนิเมชันแบบย้อนกลับโดยอัตโนมัติหลังจากเล่นในทิศทางไปข้างหน้าหรือไม่. Read/write boolean.

**คืนค่า:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

อธิบายว่าควรเล่นแอนิเมชันแบบย้อนกลับโดยอัตโนมัติหลังจากเล่นในทิศทางไปข้างหน้าหรือไม่. Read/write boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน. Read/write float.

**คืนค่า:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน. Read/write float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. Read/write float.

**คืนค่า:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. Read/write float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับผลกระทบสำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยนการตั้งค่า Timing/Repeat ของเอฟเฟกต์เป็น "Until End of Slide"
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

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับผลกระทบสำหรับสไลด์แรก
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนกว่าจะคลิกครั้งถัดไปหรือไม่. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับผลกระทบสำหรับสไลด์แรก
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
public abstract void setRepeatUntilNextClick(boolean value)
```

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนกว่าจะคลิกครั้งถัดไปหรือไม่. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับผลกระทบสำหรับสไลด์แรก
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. Read/write float.

**คืนค่า:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. Read/write float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

ระบุว่าเอฟเฟกต์จะเริ่มใหม่หลังจากเสร็จสมบูรณ์หรือไม่. Read/write [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**คืนค่า:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

ระบุว่าเอฟเฟกต์จะเริ่มใหม่หลังจากเสร็จสมบูรณ์หรือไม่. Read/write [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

ระบุเปอร์เซ็นต์ที่ต้องการเร่ง (หรือชะลอ) เวลา. Read/write float.

**คืนค่า:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

ระบุเปอร์เซ็นต์ที่ต้องการเร่ง (หรือชะลอ) เวลา. Read/write float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

อธิบายเวลาหน่วงหลังจากการกระตุ้น. Read/write float.

**คืนค่า:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

อธิบายเวลาหน่วงหลังจากการกระตุ้น. Read/write float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

อธิบายประเภทของทริกเกอร์. Read/write [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**คืนค่า:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

อธิบายประเภทของทริกเกอร์. Read/write [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะรีวินด์เมื่อเล่นเสร็จหรือไม่. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับผลกระทบสำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปิดการทำงานของ Timing/Rewind ของเอฟเฟกต์
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

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์จะรีวินด์เมื่อเล่นเสร็จหรือไม่. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับลำดับผลกระทบสำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // รับเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปิดการทำงานของ Timing/Rewind ของเอฟเฟกต์
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |