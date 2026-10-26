---
title: IAnimationTimeLine
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر جدول زمانی انیمیشن.
type: docs
url: /fa/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

نمایانگر جدول زمانی انیمیشن.
## متدها

| متد | توضیح |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Returns collection of interactive sequences. |
| [getMainSequence()](#getMainSequence--) | Returns main sequence which may contain only main effects collection. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Returns collection of text animations. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

مجموعه‌ای از توالی‌های تعاملی را برمی‌گرداند. این توالی‌ها ممکن است فقط افکت‌های "click on shape" با هدف شکل مشخص شده را شامل شوند. فقط خواندنی [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**بازگشت:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

توالی اصلی را برمی‌گرداند که ممکن است فقط مجموعه افکت‌های اصلی را شامل شود. فقط خواندنی [ISequence](../../com.aspose.slides/isequence).

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

مجموعه‌ای از انیمیشن‌های متن را برمی‌گرداند. فقط خواندنی [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**بازگشت:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)