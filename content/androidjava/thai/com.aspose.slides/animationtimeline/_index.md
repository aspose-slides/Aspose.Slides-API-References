---
title: AnimationTimeLine
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นไทม์ไลน์ของแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/animationtimeline/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

เป็นไทม์ไลน์ของแอนิเมชัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | คืนค่าคอลเลกชันของลำดับเชิงโต้ตอบ. |
| [getMainSequence()](#getMainSequence--) | คืนค่าลำดับหลักที่อาจมีเพียงคอลเลกชันของเอฟเฟกต์หลักเท่านั้น. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | คืนค่าคอลเลกชันของแอนิเมชันข้อความ. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


คืนค่าคอลเลกชันของลำดับเชิงโต้ตอบ. ลำดับนี้อาจมีเพียงเอฟเฟกต์โดย "click on shape" ที่ระบุรูปร่างเป้าหมาย. อ่านได้อย่างเดียว [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**คืนค่า:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


คืนค่าลำดับหลักที่อาจมีเพียงคอลเลกชันของเอฟเฟกต์หลักเท่านั้น. อ่านได้อย่างเดียว [ISequence](../../com.aspose.slides/isequence).

**คืนค่า:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


คืนค่าคอลเลกชันของแอนิเมชันข้อความ. อ่านได้อย่างเดียว [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**คืนค่า:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)