---
title: Effect
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงเอฟเฟกต์แอนิเมชัน
type: docs
url: /th/com.aspose.slides/effect/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

แสดงเอฟเฟกต์แอนิเมชัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSequence()](#getSequence--) | คืนค่าลำดับสำหรับเอฟเฟกต์ |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation อ่านอย่างเดียว [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | กำหนดคลาสของเอฟเฟกต์ |
| [setPresetClassType(int value)](#setPresetClassType-int-) | กำหนดคลาสของเอฟเฟกต์ |
| [getType()](#getType--) | กำหนดประเภทของเอฟเฟกต์ |
| [setType(int value)](#setType-int-) | กำหนดประเภทของเอฟเฟกต์ |
| [getSubtype()](#getSubtype--) | กำหนดประเภทย่อยของเอฟเฟกต์ |
| [setSubtype(int value)](#setSubtype-int-) | กำหนดประเภทย่อยของเอฟเฟกต์ |
| [getBehaviors()](#getBehaviors--) | คืนค่าคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์ |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | คืนค่าคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์ |
| [getTiming()](#getTiming--) | กำหนดค่าเวลาให้กับเอฟเฟกต์ |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | กำหนดค่าเวลาให้กับเอฟเฟกต์ |
| [getTargetShape()](#getTargetShape--) | คืนค่า shape เป้าหมายสำหรับเอฟเฟกต์ |
| [getSound()](#getSound--) | กำหนดเสียงฝังอยู่สำหรับเอฟเฟกต์ |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | กำหนดเสียงฝังอยู่สำหรับเอฟเฟกต์ |
| [getStopPreviousSound()](#getStopPreviousSound--) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์แอนิเมชันหยุดเสียงก่อนหน้าหรือไม่ |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์แอนิเมชันหยุดเสียงก่อนหน้าหรือไม่ |
| [getAfterAnimationType()](#getAfterAnimationType--) | กำหนดประเภทแอนิเมชันหลังสำหรับเอฟเฟกต์ |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | กำหนดประเภทแอนิเมชันหลังสำหรับเอฟเฟกต์ |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | กำหนดสีแอนิเมชันหลังสำหรับเอฟเฟกต์ |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | กำหนดสีแอนิเมชันหลังสำหรับเอฟเฟกต์ |
| [getAnimateTextType()](#getAnimateTextType--) | กำหนดประเภทการแอนิเมทข้อความสำหรับเอฟเฟกต์ |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | กำหนดประเภทการแอนิเมทข้อความสำหรับเอฟเฟกต์ |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | กำหนดการหน่วงเวลาระหว่างส่วนของข้อความที่แอนิเมท (คำหรืออักษร) |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | กำหนดการหน่วงเวลาระหว่างส่วนของข้อความที่แอนิเมท (คำหรืออักษร) |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

คืนค่าลำดับสำหรับเอฟเฟกต์. อ่านอย่างเดียว [ISequence](../../com.aspose.slides/isequence).

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

กำหนดคลาสของเอฟเฟกต์. อ่าน/เขียน [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**คืนค่า:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

กำหนดคลาสของเอฟเฟกต์. อ่าน/เขียน [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public final int getType()
```

กำหนดประเภทของเอฟเฟกต์. อ่าน/เขียน [EffectType](../../com.aspose.slides/effecttype).

**คืนค่า:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

กำหนดประเภทของเอฟเฟกต์. อ่าน/เขียน [EffectType](../../com.aspose.slides/effecttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

กำหนดประเภทย่อยของเอฟเฟกต์. อ่าน/เขียน [EffectSubtype](../../com.aspose.slides/effectsubtype).

**คืนค่า:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

กำหนดประเภทย่อยของเอฟเฟกต์. อ่าน/เขียน [EffectSubtype](../../com.aspose.slides/effectsubtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

คืนค่าคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์. อ่าน/เขียน [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**คืนค่า:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

คืนค่าคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์. อ่าน/เขียน [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

กำหนดค่าเวลาให้กับเอฟเฟกต์. อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**คืนค่า:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

กำหนดค่าเวลาให้กับเอฟเฟกต์. อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

คืนค่า shape เป้าหมายสำหรับเอฟเฟกต์. อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```

กำหนดเสียงฝังอยู่สำหรับเอฟเฟกต์. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // รับลำดับเอฟเฟกต์สำหรับสไลด์
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // ดึงเสียงของเอฟเฟกต์เป็นอาร์เรย์ของไบต์
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

กำหนดเสียงฝังอยู่สำหรับเอฟเฟกต์. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // รับลำดับเอฟเฟกต์สำหรับสไลด์
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // ดึงเสียงของเอฟเฟกต์เป็นอาร์เรย์ของไบต์
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

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์แอนิเมชันหยุดเสียงก่อนหน้าหรือไม่. อ่าน/เขียน  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // รับเอฟเฟกต์แรกของสไลด์ที่สอง
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // เปลี่ยนการปรับปรุง/เสียงของเอฟเฟกต์ที่สองเป็น "Stop Previous Sound"
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

แอตทริบิวต์นี้ระบุว่าเอฟเฟกต์แอนิเมชันหยุดเสียงก่อนหน้าหรือไม่. อ่าน/เขียน  boolean .

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
>          // เปลี่ยนการปรับปรุง/เสียงของเอฟเฟกต์ที่สองเป็น "Stop Previous Sound"
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

กำหนดประเภทแอนิเมชันหลังสำหรับเอฟเฟกต์. อ่าน/เขียน [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนเอฟเฟกต์ After animation เป็น "Hide on Next Mouse Click"
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

กำหนดประเภทแอนิเมชันหลังสำหรับเอฟเฟกต์. อ่าน/เขียน [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // เปลี่ยนเอฟเฟกต์ After animation เป็น "Hide on Next Mouse Click"
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

กำหนดสีแอนิเมชันหลังสำหรับเอฟเฟกต์. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      // ตั้งค่าสี After animation ของเอฟเฟกต์.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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

กำหนดสีแอนิเมชันหลังสำหรับเอฟเฟกต์. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      // ตั้งค่าสี After animation ของเอฟเฟกต์.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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
public final int getAnimateTextType()
```

กำหนดประเภทการแอนิเมทข้อความสำหรับเอฟเฟกต์. ข้อความใน shape สามารถแอนิเมทเป็นอักษร, คำ หรือทั้งหมดพร้อมกัน. อ่าน/เขียน  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
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
public final void setAnimateTextType(int value)
```

กำหนดประเภทการแอนิเมทข้อความสำหรับเอฟเฟกต์. ข้อความใน shape สามารถแอนิเมทเป็นอักษร, คำ หรือทั้งหมดพร้อมกัน. อ่าน/เขียน  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // รับเอฟเฟกต์แรกของสไลด์แรก.
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
public final float getDelayBetweenTextParts()
```

กำหนดการหน่วงเวลาระหว่างส่วนของข้อความที่แอนิเมท (คำหรืออักษร). ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์. ค่าลบระบุเวลาหน่วงเป็นวินาที. อ่าน/เขียน  float .

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
>      // ตั้งค่าการหน่วงเวลาระหว่างส่วนของข้อความที่แอนิเมตเป็น 20% ของระยะเวลาเอฟเฟกต์.
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

กำหนดการหน่วงเวลาระหว่างส่วนของข้อความที่แอนิเมท (คำหรืออักษร). ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์. ค่าลบระบุเวลาหน่วงเป็นวินาที. อ่าน/เขียน  float .

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
>      // ตั้งค่าการหน่วงเวลาระหว่างส่วนของข้อความที่แอนิเมตเป็น 20% ของระยะเวลาเอฟเฟกต์.
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

คืนค่าออบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject