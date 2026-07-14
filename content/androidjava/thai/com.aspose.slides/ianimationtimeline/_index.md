---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงไทม์ไลน์ของแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

แสดงไทม์ไลน์ของแอนิเมชัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | คืนคอลเลกชันของลำดับเชิงโต้ตอบ. |
| [getMainSequence()](#getMainSequence--) | คืนค่าลำดับหลักซึ่งอาจมีเพียงคอลเลกชันของเอฟเฟ็กต์หลักเท่านั้น. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | คืนค่าคอลเลกชันของการแอนิเมชันข้อความ. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

คืนค่าคอลเลกชันของลำดับเชิงโต้ตอบ. ลำดับเหล่านี้อาจมีเอฟเฟ็กต์ที่ทำโดยการคลิกบนรูปทรงที่ระบุเป็นเป้าหมายเท่านั้น. อ่านอย่างเดียว [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**คืนค่า:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

คืนค่าลำดับหลักซึ่งอาจมีคอลเลกชันของเอฟเฟ็กต์หลักเท่านั้น. อ่านอย่างเดียว [ISequence](../../com.aspose.slides/isequence).

**คืนค่า:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

คืนค่าคอลเลกชันของการแอนิเมชันข้อความ. อ่านอย่างเดียว [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**คืนค่า:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)