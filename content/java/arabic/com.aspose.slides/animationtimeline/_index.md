---
title: AnimationTimeLine
second_title: Aspose.Slides مرجع API لجافا
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

يمثل مخططًا زمنيًا للرسوم المتحركة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | يرجع مجموعة من التسلسلات التفاعلية. |
| [getMainSequence()](#getMainSequence--) | يرجع التسلسل الرئيسي الذي قد يحتوي فقط على مجموعة التأثيرات الرئيسية. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | يرجع مجموعة من الرسوم المتحركة للنص. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


يرجع مجموعة من التسلسلات التفاعلية. قد تحتوي هذه التسلسلات فقط على تأثيرات "click on shape" مع الشكل الهدف المحدد. للقراءة فقط [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**الإرجاع:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


يرجع التسلسل الرئيسي الذي قد يحتوي فقط على مجموعة التأثيرات الرئيسية. للقراءة فقط [ISequence](../../com.aspose.slides/isequence).

**الإرجاع:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


يرجع مجموعة من الرسوم المتحركة للنص. للقراءة فقط [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**الإرجاع:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)