---
title: Effect
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นตัวแทนของเอฟเฟกต์การเคลื่อนไหว.
type: docs
url: /th/com.aspose.slides/effect/
---
**การสืบทอด:**  
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject  
```
public class Effect implements IEffect, IDOMObject
```

อธิบายถึงเอฟเฟกต์การเคลื่อนไหว.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSequence()](#getSequence--) | ส่งคืนลำดับสำหรับเอฟเฟกต์ |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation อ่านอย่างเดียว [ITextAnimation](../../com.aspose.slides/itextanimation) |
| [getPresetClassType()](#getPresetClassType--) | กำหนดคลาสของเอฟเฟกต์ |
| [setPresetClassType(int value)](#setPresetClassType-int-) | กำหนดคลาสของเอฟเฟกต์ |
| [getType()](#getType--) | กำหนดประเภทของเอฟเฟกต์ |
| [setType(int value)](#setType-int-) | กำหนดประเภทของเอฟเฟกต์ |
| [getSubtype()](#getSubtype--) | กำหนดชนิดย่อยของเอฟเฟกต์ |
| [setSubtype(int value)](#setSubtype-int-) | กำหนดชนิดย่อยของเอฟเฟกต์ |
| [getBehaviors()](#getBehaviors--) | ส่งคืนคอลเลกชันของพฤติกรรมสำหรับเอฟเฟ็กต์ |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | ส่งคืนคอลเลกชันของพฤติกรรมสำหรับเอฟเฟ็กต์ |
| [getTiming()](#getTiming--) | กำหนดค่าเวลา สำหรับเอฟเฟ็กต์ |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | กำหนดค่าเวลา สำหรับเอฟเฟ็กต์ |
| [getTargetShape()](#getTargetShape--) | ส่งคืนรูปร่างเป้าหมายสำหรับเอฟเฟ็กต์ |
| [getSound()](#getSound--) | กำหนดเสียงฝังสำหรับเอฟเฟ็กต์ |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | กำหนดเสียงฝังสำหรับเอฟเฟ็กต์ |
| [getStopPreviousSound()](#getStopPreviousSound--) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์การเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์การเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ |
| [getAfterAnimationType()](#getAfterAnimationType--) | กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | กำหนดสีการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | กำหนดสีการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ |
| [getAnimateTextType()](#getAnimateTextType--) | กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟ็กต์ |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟ็กต์ |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | กำหนดค่าหน่วงระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักษร) |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | กำหนดค่าหน่วงระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักษร) |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

ส่งคืนลำดับสำหรับเอฟเฟกต์ อ่านอย่างเดียว [ISequence](../../com.aspose.slides/isequence).

**คืนค่า:**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation อ่านอย่างเดียว [ITextAnimation](../../com.aspose.slides/itextanimation).

**คืนค่า:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

กำหนดคลาสของเอฟเฟกต์ อ่าน/เขียน [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**คืนค่า:**  
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

กำหนดคลาสของเอฟเฟกต์ อ่าน/เขียน [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

กำหนดประเภทของเอฟเฟกต์ อ่าน/เขียน [EffectType](../../com.aspose.slides/effecttype).

**คืนค่า:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

กำหนดประเภทของเอฟเฟกต์ อ่าน/เขียน [EffectType](../../com.aspose.slides/effecttype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

กำหนดชนิดย่อยของเอฟเฟกต์ อ่าน/เขียน [EffectSubtype](../../com.aspose.slides/effectsubtype).

**คืนค่า:**  
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

กำหนดชนิดย่อยของเอฟเฟกต์ อ่าน/เขียน [EffectSubtype](../../com.aspose.slides/effectsubtype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

ส่งคืนคอลเลกชันของพฤติกรรมสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**คืนค่า:**  
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

ส่งคืนคอลเลกชันของพฤติกรรมสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

กำหนดค่าเวลา สำหรับเอฟเฟ็กต์ อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**คืนค่า:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

กำหนดค่าเวลา สำหรับเอฟเฟ็กต์ อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

ส่งคืนรูปร่างเป้าหมายสำหรับเอฟเฟ็กต์ อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**  
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

กำหนดเสียงฝังสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // ดึงเสียงเอฟเฟกต์เป็นอาร์เรย์ไบต์
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

กำหนดเสียงฝังสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // รับลำดับของเอฟเฟกต์สำหรับสไลด์
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // ดึงเสียงเอฟเฟกต์เป็นอาร์เรย์ไบต์
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

คุณลักษณะนี้ระบุว่าเอฟเฟกต์การเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // รับเอฟเฟกต์แรกของสไลด์ที่สอง.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // เปลี่ยน Enhancements/Sound ของเอฟเฟกต์ที่สองเป็น "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**  
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

คุณลักษณะนี้ระบุว่าเอฟเฟกต์การเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // รับเอฟเฟกต์แรกของสไลด์ที่สอง.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // เปลี่ยน Enhancements/Sound ของเอฟเฟกต์ที่สองเป็น "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ อ่าน/เขียน [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนการเคลื่อนไหวหลังของเอฟเฟกต์เป็น "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**  
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ อ่าน/เขียน [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนการเคลื่อนไหวหลังของเอฟเฟกต์เป็น "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

กำหนดสีการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภทการเคลื่อนไหวหลังของเอฟเฟกต์เป็น "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // ตั้งค่าสีการเคลื่อนไหวหลังของเอฟเฟกต์.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

กำหนดสีการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภทการเคลื่อนไหวหลังของเอฟเฟกต์เป็น "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // ตั้งค่าสีการเคลื่อนไหวนหลังของเอฟเฟกต์.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิ터:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟ็กต์ รูปแบบข้อความสามารถเคลื่อนไหวโดยอักษร, คำ หรือทั้งหมดพร้อมกัน อ่าน/เขียน  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภทการเคลื่อนไหวข้อความของเอฟเฟกต์เป็น "โดยอักษร"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**  
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟ็กต์ รูปแบบข้อความสามารถเคลื่อนไหวโดยอักษร, คำ หรือทั้งหมดพร้อมกัน อ่าน/เขียน  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภทการเคลื่อนไหวข้อความของเอฟเฟกต์เป็น "โดยอักษร"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

กำหนดค่าหน่วงระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักษร) ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์ ค่าลบระบุค่าหน่วงเป็นวินาที อ่าน/เขียน  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภทการเคลื่อนไหวข้อความของเอฟเฟกต์เป็น "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // ตั้งค่าความหน่วงระหว่างส่วนของข้อความที่เคลื่อนไหวเป็น 20% ของระยะเวลาเอฟเฟ็กต์.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**  
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

กำหนดค่าหน่วงระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักษร) ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์ ค่าลบระบุค่าหน่วงเป็นวินาที อ่าน/เขียน  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภทการเคลื่อนไหวข้อความของเอฟเฟกต์เป็น "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // ตั้งค่าความหน่วงระหว่างส่วนของข้อความที่เคลื่อนไหวเป็น 20% ของระยะเวลาเอฟเฟ็กต์.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject