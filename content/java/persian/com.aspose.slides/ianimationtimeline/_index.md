---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Represents timeline of animation.
type: docs
url: /fa/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

نمایانگر جدول زمانی انیمیشن.
## متدها

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | مجموعه‌ای از توالی‌های تعاملی را بر می‌گرداند. |
| [getMainSequence()](#getMainSequence--) | توالی اصلی را بر می‌گرداند که ممکن است فقط مجموعه‌ی اثرات اصلی را شامل شود. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | مجموعه‌ای از انیمیشن‌های متنی را بر می‌گرداند. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

مجموعه‌ای از توالی‌های تعاملی را بر می‌گرداند. این توالی‌ها ممکن است تنها اثرات «کلیک بر روی شکل» را داشته باشند که شکل هدف مشخص می‌شود. فقط‌خواندنی [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**بازگشت:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

توابع اصلی را بر می‌گرداند که ممکن است فقط مجموعه‌ اثرات اصلی را شامل شود. فقط‌خواندنی [ISequence](../../com.aspose.slides/isequence).

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

مجموعه‌ای از انیمیشن‌های متنی را بر می‌گرداند. فقط‌خواندنی [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**بازگشت:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)