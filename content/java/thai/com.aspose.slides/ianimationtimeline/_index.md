---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: แสดงไทม์ไลน์ของแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

แสดงไทม์ไลน์ของแอนิเมชัน.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | ส่งคืนคอลเลกชันของลำดับเชิงโต้ตอบ |
| [getMainSequence()](#getMainSequence--) | ส่งคืนลำดับหลักซึ่งอาจมีเฉพาะคอลเลกชันของเอฟเฟกต์หลัก |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | ส่งคืนคอลเลกชันของแอนิเมชันข้อความ |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

ส่งคืนคอลเลกชันของลำดับเชิงโต้ตอบ ลำดับเหล่านี้อาจมีเอฟเฟกต์ที่เกิดจาก "click on shape" โดยระบุรูปร่างเป้าหมายเท่านั้น อ่านอย่างเดียว [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**ส่งคืน:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

ส่งคืนลำดับหลักซึ่งอาจมีเฉพาะคอลเลกชันของเอฟเฟกต์หลัก อ่านอย่างเดียว [ISequence](../../com.aspose.slides/isequence).

**ส่งคืน:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

ส่งคืนคอลเลกชันของแอนิเมชันข้อความ อ่านอย่างเดียว [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**ส่งคืน:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)