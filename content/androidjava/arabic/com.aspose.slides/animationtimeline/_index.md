---
title: AnimationTimeLine
second_title: Aspose.Slides لأندرويد عبر مرجع Java API
description: يمثل المخطط الزمني للرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/animationtimeline/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

يمثل المخطط الزمني للرسوم المتحركة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | يعيد مجموعة من التسلسلات التفاعلية. |
| [getMainSequence()](#getMainSequence--) | يعيد التسلسل الرئيسي الذي قد يحتوي فقط على مجموعة التأثيرات الرئيسية. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | يعيد مجموعة من الرسوم المتحركة للنص. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

يعيد مجموعة من التسلسلات التفاعلية. قد تحتوي هذه التسلسلات فقط على تأثيرات بواسطة "click on shape" مع الشكل الهدف المحدد. للقراءة فقط [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**القيمة المرجعة:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

يعيد التسلسل الرئيسي الذي قد يحتوي فقط على مجموعة التأثيرات الرئيسية. للقراءة فقط [ISequence](../../com.aspose.slides/isequence).

**القيمة المرجعة:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

يعيد مجموعة من الرسوم المتحركة للنص. للقراءة فقط [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**القيمة المرجعة:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)