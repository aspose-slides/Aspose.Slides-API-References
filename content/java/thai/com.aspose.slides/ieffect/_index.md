---
title: IEffect
second_title: Aspose.Slides for Java API Reference
description: Represents animation effect.
type: docs
url: /th/com.aspose.slides/ieffect/
---```
public interface IEffect
```

แสดงเอฟเฟ็กต์การเคลื่อนไหว
## วิธีการ

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | คืนค่าลำดับสำหรับเอฟเฟกต์ |
| [getTextAnimation()](#getTextAnimation--) | คืนค่าการเคลื่อนไหวข้อความ |
| [getPresetClassType()](#getPresetClassType--) | กำหนดคลาสของเอฟเฟ็กต์ |
| [setPresetClassType(int value)](#setPresetClassType-int-) | กำหนดคลาสของเอฟเฟ็กต์ |
| [getType()](#getType--) | กำหนดประเภทของเอฟเฟ็กต์ |
| [setType(int value)](#setType-int-) | กำหนดประเภทของเอฟเฟ็กต์ |
| [getSubtype()](#getSubtype--) | กำหนดชนิดย่อยของเอฟเฟ็กต์ |
| [setSubtype(int value)](#setSubtype-int-) | กำหนดชนิดย่อยของเอฟเฟ็กต์ |
| [getBehaviors()](#getBehaviors--) | คืนค่าชุดของพฤติกรรมสำหรับเอฟเฟ็กต์ |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | คืนค่าชุดของพฤติกรรมสำหรับเอฟเฟ็กต์ |
| [getTiming()](#getTiming--) | กำหนดค่าการเวลาสำหรับเอฟเฟ็กต์ |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | กำหนดค่าการเวลาสำหรับเอฟเฟ็กต์ |
| [getTargetShape()](#getTargetShape--) | คืนค่า shape เป้าหมายสำหรับเอฟเฟ็กต์ |
| [getSound()](#getSound--) | กำหนดเสียงฝังตัวสำหรับเอฟเฟ็กต์ |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | กำหนดเสียงฝังตัวสำหรับเอฟเฟ็กต์ |
| [getStopPreviousSound()](#getStopPreviousSound--) | คุณลักษณะนี้กำหนดว่าการเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | คุณลักษณะนี้กำหนดว่าการเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ |
| [getAfterAnimationType()](#getAfterAnimationType--) | กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | กำหนดสีการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | กำหนดสีการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ |
| [getAnimateTextType()](#getAnimateTextType--) | กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟ็กต์ |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟ็กต์ |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | กำหนดการหน่วงเวลาระหว่างส่วนข้อความที่เคลื่อนไหว (คำหรืออักขระ) |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | กำหนดการหน่วงเวลาระหว่างส่วนข้อความที่เคลื่อนไหว (คำหรืออักขระ) |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


คืนค่าลำดับสำหรับเอฟเฟ็กต์ อ่านอย่างเดียว [ISequence](../../com.aspose.slides/isequence).

**คืนค่า:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


คืนค่าการเคลื่อนไหวข้อความ อ่านอย่างเดียว [ITextAnimation](../../com.aspose.slides/itextanimation).

**คืนค่า:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


กำหนดคลาสของเอฟเฟ็กต์ อ่าน/เขียน [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**คืนค่า:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


กำหนดคลาสของเอฟเฟ็กต์ อ่าน/เขียน [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


กำหนดประเภทของเอฟเฟ็กต์ อ่าน/เขียน [EffectType](../../com.aspose.slides/effecttype).

**คืนค่า:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


กำหนดประเภทของเอฟเฟ็กต์ อ่าน/เขียน [EffectType](../../com.aspose.slides/effecttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


กำหนดชนิดย่อยของเอฟเฟ็กต์ อ่าน/เขียน [EffectSubtype](../../com.aspose.slides/effectsubtype).

**คืนค่า:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


กำหนดชนิดย่อยของเอฟเฟ็กต์ อ่าน/เขียน [EffectSubtype](../../com.aspose.slides/effectsubtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


คืนค่าชุดของพฤติกรรมสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**คืนค่า:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


คืนค่าชุดของพฤติกรรมสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


กำหนดค่าการเวลาสำหรับเอฟเฟ็กต์ อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**คืนค่า:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


กำหนดค่าการเวลาสำหรับเอฟเฟ็กต์ อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


คืนค่า shape เป้าหมายสำหรับเอฟเฟ็กต์ อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


กำหนดเสียงฝังตัวสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // ดึงลำดับเอฟเฟกต์สำหรับสไลด์
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
public abstract void setSound(IAudio value)
```


กำหนดเสียงฝังตัวสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // ดึงลำดับเอฟเฟกต์สำหรับสไลด์
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
public abstract boolean getStopPreviousSound()
```


คุณลักษณะนี้ระบุว่าการเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ อ่าน/เขียน boolean .

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
public abstract void setStopPreviousSound(boolean value)
```


คุณลักษณะนี้ระบุว่าการเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ อ่าน/เขียน boolean .

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
public abstract int getAfterAnimationType()
```


กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ อ่าน/เขียน AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยน After animation ของเอฟเฟกต์เป็น "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ อ่าน/เขียน AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยน After animation ของเอฟเฟกต์เป็น "Hide on Next Mouse Click"
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
public abstract IColorFormat getAfterAnimationColor()
```


กำหนดสีการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท After animation ของเอฟเฟกต์เป็น "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // กำหนดสี After animation ของเอฟเฟกต์.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


กำหนดสีการเคลื่อนไหวหลังสำหรับเอฟเฟ็กต์ อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท After animation ของเอฟเฟกต์เป็น "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // กำหนดสี After animation ของเอฟเฟกต์.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟ็กต์ ข้อความใน shape สามารถเคลื่อนไหวเป็นอักขระ คำ หรือทั้งหมดพร้อมกัน อ่าน/เขียน AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท Animate text ของเอฟเฟกต์เป็น "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟ็กต์ ข้อความใน shape สามารถเคลื่อนไหวเป็นอักขระ คำ หรือทั้งหมดพร้อมกัน อ่าน/เขียน AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท Animate text ของเอฟเฟกต์เป็น "By letter"
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
public abstract float getDelayBetweenTextParts()
```


กำหนดการหน่วงเวลาระหว่างส่วนข้อความที่เคลื่อนไหว (คำหรืออักขระ) ค่าเป็นบวกระบุเป็นเปอร์เซ็นต์ของระยะเวลาเอฟเฟ็กต์ ค่าเป็นลบระบุเป็นวินาที อ่าน/เขียน float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท Animate text ของเอฟเฟกต์เป็น "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // กำหนดการหน่วงเวลาระหว่างส่วนข้อความที่เคลื่อนไหวเป็น 20% ของระยะเวลาเอฟเฟ็กต์.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


กำหนดการหน่วงเวลาระหว่างส่วนข้อความที่เคลื่อนไหว (คำหรืออักขระ) ค่าเป็นบวกระบุเป็นเปอร์เซ็นต์ของระยะเวลาเอฟเฟ็กต์ ค่าเป็นลบระบุเป็นวินาที อ่าน/เขียน float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท Animate text ของเอฟเฟกต์เป็น "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // กำหนดการหน่วงเวลาระหว่างส่วนข้อความที่เคลื่อนไหวเป็น 20% ของระยะเวลาเอฟเฟ็กต์.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |