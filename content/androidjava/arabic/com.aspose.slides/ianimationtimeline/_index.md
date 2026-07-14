---
title: IAnimationTimeLine
second_title: Aspose.Slides لنظام Android عبر Java API Reference
description: يمثل الخط الزمني للرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

يمثل الخط الزمني للرسوم المتحركة.
## الطرق

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | يعيد مجموعة من التسلسلات التفاعلية. |
| [getMainSequence()](#getMainSequence--) | يعيد التسلسل الرئيسي الذي قد يحتوي فقط على مجموعة التأثيرات الرئيسية. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | يعيد مجموعة من الرسوم المتحركة للنص. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

يعيد مجموعة من التسلسلات التفاعلية. قد تحتوي هذه التسلسلات فقط على تأثيرات عبر "click on shape" مع تحديد الشكل الهدف. قراءة فقط [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**القيمة المرجعة:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

يعيد التسلسل الرئيسي الذي قد يحتوي فقط على مجموعة التأثيرات الرئيسية. قراءة فقط [ISequence](../../com.aspose.slides/isequence).

**القيمة المرجعة:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

يعيد مجموعة من الرسوم المتحركة للنص. قراءة فقط [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**القيمة المرجعة:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)