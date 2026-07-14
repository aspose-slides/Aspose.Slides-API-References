---
title: AnimationTimeLine
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر خط زمان انیمیشن.
type: docs
url: /fa/com.aspose.slides/animationtimeline/
---
**وراثت:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

نمایش‌گر خط زمان انیمیشن.
## متدها

| متد | توضیح |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | مجموعه‌ای از توالی‌های تعاملی را برمی‌گرداند. |
| [getMainSequence()](#getMainSequence--) | دنبالهٔ اصلی را برمی‌گرداند که ممکن است تنها شامل مجموعهٔ افکت‌های اصلی باشد. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | مجموعه‌ای از انیمیشن‌های متن را برمی‌گرداند. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


مجموعه‌ای از توالی‌های تعاملی را برمی‌گرداند. این توالی‌ها ممکن است فقط افکت‌های «کلیک بر روی شکل» با شکل هدف مشخص‌شده را شامل شوند. فقط‌خواندنی [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**بازگشت:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


دنبالهٔ اصلی را برمی‌گرداند که ممکن است تنها شامل مجموعهٔ افکت‌های اصلی باشد. فقط‌خواندنی [ISequence](../../com.aspose.slides/isequence).

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


مجموعه‌ای از انیمیشن‌های متن را برمی‌گرداند. فقط‌خواندنی [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**بازگشت:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)