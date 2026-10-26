---
title: Timing
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API อ้างอิง
description: แสดงถึงการกำหนดเวลาแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/timing/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

แสดงถึงการกำหนดเวลาแอนิเมชัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | อธิบายเปอร์เซ็นต์ของพฤติกรรมเร่งความเร็วของระยะเวลา. |
| [setAccelerate(float value)](#setAccelerate-float-) | อธิบายเปอร์เซ็นต์ของพฤติกรรมเร่งความเร็วของระยะเวลา. |
| [getDecelerate()](#getDecelerate--) | อธิบายเปอร์เซ็นต์ของพฤติกรรมชะลอความเร็วของระยะเวลา. |
| [setDecelerate(float value)](#setDecelerate-float-) | อธิบายเปอร์เซ็นต์ของพฤติกรรมชะลอความเร็วของระยะเวลา. |
| [getAutoReverse()](#getAutoReverse--) | อธิบายว่าควรเล่นแอนิเมชันย้อนหลังจากเล่นไปข้างหน้าหรือไม่. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | อธิบายว่าควรเล่นแอนิเมชันย้อนหลังจากเล่นไปข้างหน้าหรือไม่. |
| [getDuration()](#getDuration--) | อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน. |
| [setDuration(float value)](#setDuration-float-) | อธิบายระยะเวลาของเอฟเฟกต์แอนิเมชัน. |
| [getRepeatCount()](#getRepeatCount--) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนถึงคลิกถัดไปหรือไม่. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนถึงคลิกถัดไปหรือไม่. |
| [getRepeatDuration()](#getRepeatDuration--) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | อธิบายจำนวนครั้งที่เอฟเฟกต์ควรทำซ้ำ. |
| [getRestart()](#getRestart--) | ระบุว่าเอฟเฟกต์ควรเริ่มใหม่หลังจากเสร็จสมบูรณ์หรือไม่. |
| [setRestart(int value)](#setRestart-int-) | ระบุว่าเอฟเฟกต์ควรเริ่มใหม่หลังจากเสร็จสมบูรณ์หรือไม่. |
| [getRewind()](#getRewind--) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะย้อนกลับเมื่อเล่นเสร็จหรือไม่. |
| [setRewind(boolean value)](#setRewind-boolean-) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะย้อนกลับเมื่อเล่นเสร็จหรือไม่. |
| [getSpeed()](#getSpeed--) | ระบุเปอร์เซ็นต์ที่จะเพิ่มความเร็ว (หรือชะลอ) ของการกำหนดเวลา. |
| [setSpeed(float value)](#setSpeed-float-) | ระบุเปอร์เซ็นต์ที่จะเพิ่มความเร็ว (หรือชะลอ) ของการกำหนดเวลา. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | อธิบายเวลาหน่วงหลังจากทริกเกอร์. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | อธิบายเวลาหน่วงหลังจากทริกเกอร์. |
| [getTriggerType()](#getTriggerType--) | อธิบายประเภทของทริกเกอร์. |
| [setTriggerType(int value)](#setTriggerType-int-) | อธิบายประเภทของทริกเกอร์. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

อธิบายเปอร์เซ็นต์ของพฤติกรรมเร่งความเร็วของระยะเวลา. อ่าน/เขียน float.

**คืนค่า:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

อธิบายเปอร์เซ็นต์ของพฤติกรรมเร่งความเร็วของระยะเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

อธิบายเปอร์เซ็นต์ของพฤติกรรมชะลอความเร็วของระยะเวลา. อ่าน/เขียน float.

**คืนค่า:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

อธิบายเปอร์เซ็นต์ของพฤติกรรมชะลอความเร็วของระยะเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

อธิบายว่าควรเล่นแอนิเมชันย้อนหลังจากเล่นไปข้างหน้าหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

อธิบายว่าควรเล่นแอนิเมชันย้อนหลังจากเล่นไปข้างหน้าหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่. อ่าน/เขียน boolean.

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
public final void setRepeatUntilEndSlide(boolean value)
```

คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนจบสไลด์หรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงลำดับเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // ดึงเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยน Timing/Repeat ของเอฟเฟกต์เป็น "จนกว่าจะถึงจบสไลด์"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนถึงคลิกถัดไปหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงลำดับเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // ดึงเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยน Timing/Repeat ของเอฟเฟกต์เป็น "Until Next Click"
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

คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนถึงคลิกถัดไปหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงลำดับเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // ดึงเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปลี่ยน Timing/Repeat ของเอฟเฟกต์เป็น "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

ระบุว่าเอฟเฟกต์ควรเริ่มใหม่หลังจากเสร็จสมบูรณ์หรือไม่. อ่าน/เขียน [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**คืนค่า:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

ระบุว่าเอฟเฟกต์ควรเริ่มใหม่หลังจากเสร็จสมบูรณ์หรือไม่. อ่าน/เขียน [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะย้อนกลับเมื่อเล่นเสร็จหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงลำดับเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // ดึงเอฟเฟกต์แรกของลำดับหลัก.
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

คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะย้อนกลับเมื่อเล่นเสร็จหรือไม่. อ่าน/เขียน boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงลำดับเอฟเฟกต์สำหรับสไลด์แรก
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // ดึงเอฟเฟกต์แรกของลำดับหลัก.
>      IEffect effect = effectsSequence.get_Item(0);
>      // เปิดใช้งาน Timing/Rewind ของเอฟเฟกต์.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

ระบุเปอร์เซ็นต์ที่จะเพิ่มความเร็ว (หรือชะลอ) ของการกำหนดเวลา. อ่าน/เขียน float.

**คืนค่า:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

ระบุเปอร์เซ็นต์ที่จะเพิ่มความเร็ว (หรือชะลอ) ของการกำหนดเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent_Immediate object. Read-only IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject