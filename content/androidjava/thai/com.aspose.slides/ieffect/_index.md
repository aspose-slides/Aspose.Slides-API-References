---
title: IEffect
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงเอฟเฟกต์แอนิเมชัน
type: docs
url: /th/com.aspose.slides/ieffect/
---```
public interface IEffect
```

แสดงถึงเอฟเฟกต์แอนิเมชัน.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSequence()](#getSequence--) | คืนลำดับสำหรับเอฟเฟกต์. |
| [getTextAnimation()](#getTextAnimation--) | คืนค่าแอนิเมชันข้อความ. |
| [getPresetClassType()](#getPresetClassType--) | กำหนดคลาสของเอฟเฟกต์. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | กำหนดคลาสของเอฟเฟกต์. |
| [getType()](#getType--) | กำหนดประเภทของเอฟเฟกต์. |
| [setType(int value)](#setType-int-) | กำหนดประเภทของเอฟเฟกต์. |
| [getSubtype()](#getSubtype--) | กำหนดประเภทย่อยของเอฟเฟกต์. |
| [setSubtype(int value)](#setSubtype-int-) | กำหนดประเภทย่อยของเอฟเฟกต์. |
| [getBehaviors()](#getBehaviors--) | คืนคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | คืนคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์. |
| [getTiming()](#getTiming--) | กำหนดค่าเวลาให้กับเอฟเฟกต์. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | กำหนดค่าเวลาให้กับเอฟเฟกต์. |
| [getTargetShape()](#getTargetShape--) | คืนรูปทรงเป้าหมายสำหรับเอฟเฟกต์. |
| [getSound()](#getSound--) | กำหนดเสียงฝังในเอฟเฟกต์. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | กำหนดเสียงฝังในเอฟเฟกต์. |
| [getStopPreviousSound()](#getStopPreviousSound--) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์แอนิเมชันจะหยุดเสียงก่อนหน้าหรือไม่. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์แอนิเมชันจะหยุดเสียงก่อนหน้าหรือไม่. |
| [getAfterAnimationType()](#getAfterAnimationType--) | กำหนดชนิดแอนิเมชันหลังจากทำเสร็จสำหรับเอฟเฟกต์. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | กำหนดชนิดแอนิเมชันหลังจากทำเสร็จสำหรับเอฟเฟกต์. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | กำหนดสีแอนิเมชันหลังจากทำเสร็จสำหรับเอฟเฟกต์. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | กำหนดสีแอนิเมชันหลังจากทำเสร็จสำหรับเอฟเฟกต์. |
| [getAnimateTextType()](#getAnimateTextType--) | กำหนดประเภทการแอนิเมชันข้อความสำหรับเอฟเฟกต์. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | กำหนดประเภทการแอนิเมชันข้อความสำหรับเอฟเฟกต์. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | กำหนดความล่าช้าระหว่างส่วนข้อความที่แอนิเมชัน (คำหรืออักษร). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | กำหนดความล่าช้าระหว่างส่วนข้อความที่แอนิเมชัน (คำหรืออักษร). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

คืนลำดับสำหรับเอฟเฟกต์. **อ่านอย่างเดียว** [ISequence](../../com.aspose.slides/isequence).

**ผลลัพธ์:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

คืนค่าแอนิเมชันข้อความ. **อ่านอย่างเดียว** [ITextAnimation](../../com.aspose.slides/itextanimation).

**ผลลัพธ์:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

กำหนดคลาสของเอฟเฟกต์. **อ่าน/เขียน** [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**ผลลัพธ์:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

กำหนดคลาสของเอฟเฟกต์. **อ่าน/เขียน** [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

กำหนดประเภทของเอฟเฟกต์. **อ่าน/เขียน** [EffectType](../../com.aspose.slides/effecttype).

**ผลลัพธ์:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

กำหนดประเภทของเอฟเฟกต์. **อ่าน/เขียน** [EffectType](../../com.aspose.slides/effecttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

กำหนดประเภทย่อยของเอฟเฟกต์. **อ่าน/เขียน** [EffectSubtype](../../com.aspose.slides/effectsubtype).

**ผลลัพธ์:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

กำหนดประเภทย่อยของเอฟเฟกต์. **อ่าน/เขียน** [EffectSubtype](../../com.aspose.slides/effectsubtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

คืนคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์. **อ่าน/เขียน** [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**ผลลัพธ์:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

คืนคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์. **อ่าน/เขียน** [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

กำหนดค่าเวลาให้กับเอฟเฟกต์. **อ่าน/เขียน** [ITiming](../../com.aspose.slides/itiming).

**ผลลัพธ์:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

กำหนดค่าเวลาให้กับเอฟเฟกต์. **อ่าน/เขียน** [ITiming](../../com.aspose.slides/itiming).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

คืนรูปทรงเป้าหมายสำหรับเอฟเฟกต์. **อ่านอย่างเดียว** [IShape](../../com.aspose.slides/ishape).

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

กำหนดเสียงฝังในเอฟเฟกต์. **อ่าน/เขียน** [IAudio](../../com.aspose.slides/iaudio).

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

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

กำหนดเสียงฝังในเอฟเฟกต์. **อ่าน/เขียน** [IAudio](../../com.aspose.slides/iaudio).

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์แอนิเมชันจะหยุดเสียงก่อนหน้าหรือไม่. **อ่าน/เขียน**  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // ดึงเอฟเฟกต์แรกของสไลด์ที่สอง.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // เปลี่ยนการเสริม/เสียงของเอฟเฟกต์ที่สองเป็น "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**ผลลัพธ์:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์แอนิเมชันจะหยุดเสียงก่อนหน้าหรือไม่. **อ่าน/เขียน**  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // ดึงเอฟเฟกต์แรกของสไลด์ที่สอง.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // เปลี่ยนการเสริม/เสียงของเอฟเฟกต์ที่สองเป็น "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

กำหนดชนิดแอนิเมชันหลังจากทำเสร็จสำหรับเอฟเฟกต์. **อ่าน/เขียน**  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยน After animation ของเอฟเฟกต์เป็น "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**ผลลัพธ์:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

กำหนดชนิดแอนิเมชันหลังจากทำเสร็จสำหรับเอฟเฟกต์. **อ่าน/เขียน**  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยน After animation ของเอฟเฟกต์เป็น "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

กำหนดสีแอนิเมชันหลังจากทำเสร็จสำหรับเอฟเฟกต์. **อ่าน/เขียน** [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท After animation ของเอฟเฟกต์เป็น "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // ตั้งค่าสี After animation ของเอฟเฟกต์.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**ผลลัพธ์:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

กำหนดสีแอนิเมชันหลังจากทำเสร็จสำหรับเอฟเฟกต์. **อ่าน/เขียน** [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท After animation ของเอฟเฟกต์เป็น "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // ตั้งค่าสี After animation ของเอฟเฟกต์.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

กำหนดประเภทการแอนิเมชันข้อความสำหรับเอฟเฟกต์. ข้อความของรูปทรงสามารถแอนิเมชันโดยตัวอักษร, โดยคำ หรือทั้งหมดพร้อมกัน. **อ่าน/เขียน**  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท Animate text ของเอฟเฟกต์เป็น "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**ผลลัพธ์:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

กำหนดประเภทการแอนิเมชันข้อความสำหรับเอฟเฟกต์. ข้อความของรูปทรงสามารถแอนิเมชันโดยตัวอักษร, โดยคำ หรือทั้งหมดพร้อมกัน. **อ่าน/เขียน**  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท Animate text ของเอฟเฟกต์เป็น "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

กำหนดความล่าช้าระหว่างส่วนข้อความที่แอนิเมชัน (คำหรืออักษร). ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์. ค่าลบระบุความล่าช้าเป็นวินาที. **อ่าน/เขียน**  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท Animate text ของเอฟเฟกต์เป็น "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // ตั้งค่าความล่าช้าระหว่างส่วนข้อความที่แอนิเมชันเป็น 20% ของระยะเวลาเอฟเฟกต์.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**ผลลัพธ์:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

กำหนดความล่าช้าระหว่างส่วนข้อความที่แอนิเมชัน (คำหรืออักษร). ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์. ค่าลบระบุความล่าช้าเป็นวินาที. **อ่าน/เขียน**  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // ดึงเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนประเภท Animate text ของเอฟเฟกต์เป็น "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // ตั้งค่าความล่าช้าระหว่างส่วนข้อความที่แอนิเมชันเป็น 20% ของระยะเวลาเอฟเฟกต์.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |