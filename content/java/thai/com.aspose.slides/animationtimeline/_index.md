---
title: AnimationTimeLine
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงไทม์ไลน์ของการเคลื่อนไหว.
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

เป็นไทม์ไลน์ของการเคลื่อนไหว.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | ส่งคืนคอลเลกชันของลำดับเชิงโต้ตอบ |
| [getMainSequence()](#getMainSequence--) | ส่งคืนลำดับหลักซึ่งอาจมีเพียงคอลเลกชันของเอฟเฟ็กต์หลัก |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | ส่งคืนคอลเลกชันของการเคลื่อนไหวข้อความ |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


ส่งคืนคอลเลกชันของลำดับเชิงโต้ตอบ ลำดับเหล่านี้อาจมีเพียงเอฟเฟ็กต์โดย “คลิกบนรูปร่าง” พร้อมระบุกำหนดรูปร่างเป้าหมาย. อ่านอย่างเดียว [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**ส่งคืน:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


ส่งคืนลำดับหลักซึ่งอาจมีเพียงคอลเลกชันของเอฟเฟ็กต์หลัก. อ่านอย่างเดียว [ISequence](../../com.aspose.slides/isequence).

**ส่งคืน:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


ส่งคืนคอลเลกชันของการเคลื่อนไหวข้อความ. อ่านอย่างเดียว [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**ส่งคืน:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)