---
title: AnimationTimeLine
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر خط زمان انیمیشن.
type: docs
url: /fa/com.aspose.slides/animationtimeline/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

نمایانگر خط زمان انیمیشن.
## متدها

| متد | توضیح |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | مجموعه‌ای از دنباله‌های تعاملی را بر می‌گرداند. |
| [getMainSequence()](#getMainSequence--) | دنباله اصلی را که ممکن است فقط شامل مجموعه افکت‌های اصلی باشد بر می‌گرداند. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | مجموعه‌ای از انیمیشن‌های متن را بر می‌گرداند. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

مجموعه‌ای از دنباله‌های تعاملی را بر می‌گرداند. این دنباله‌ها ممکن است فقط افکت‌های "کلیک روی شکل" را داشته باشند که شکل هدف مشخصی دارد. فقط-خواندنی [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**بازگشت:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

دنباله اصلی را که ممکن است فقط شامل مجموعه افکت‌های اصلی باشد بر می‌گرداند. فقط-خواندنی [ISequence](../../com.aspose.slides/isequence).

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

مجموعه‌ای از انیمیشن‌های متن را بر می‌گرداند. فقط-خواندنی [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**بازگشت:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)