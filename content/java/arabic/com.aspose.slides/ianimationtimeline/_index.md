---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: يمثل خط الزمن للرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

يمثل خط الزمن للرسوم المتحركة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | إرجاع مجموعة من السلاسل التفاعلية. |
| [getMainSequence()](#getMainSequence--) | إرجاع السلسلة الرئيسية التي قد تحتوي فقط على مجموعة التأثيرات الرئيسية. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | إرجاع مجموعة من الرسوم المتحركة للنص. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

إرجاع مجموعة من السلاسل التفاعلية. قد تحتوي هذه السلاسل فقط على تأثيرات بواسطة "النقر على الشكل" مع تحديد الشكل المستهدف. قراءة فقط [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**الإرجاع:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

إرجاع السلسلة الرئيسية التي قد تحتوي فقط على مجموعة التأثيرات الرئيسية. قراءة فقط [ISequence](../../com.aspose.slides/isequence).

**الإرجاع:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

إرجاع مجموعة من الرسوم المتحركة للنص. قراءة فقط [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**الإرجاع:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)