---
title: AnimationTimeLine
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Animasyon zaman çizelgesini temsil eder.
type: docs
url: /tr/com.aspose.slides/animationtimeline/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Animasyon zaman çizelgesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Etkileşimli dizilerin koleksiyonunu döndürür. |
| [getMainSequence()](#getMainSequence--) | Yalnızca ana efekt koleksiyonunu içerebilen ana diziyi döndürür. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Metin animasyonlarının koleksiyonunu döndürür. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Etkileşimli dizilerin koleksiyonunu döndürür. Bu diziler yalnızca hedef şekli belirten "şekle tıkla" ile etkileri içerebilir. Salt-okunur [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Döndürür:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Yalnızca ana efekt koleksiyonunu içerebilen ana diziyi döndürür. Salt-okunur [ISequence](../../com.aspose.slides/isequence).

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Metin animasyonlarının koleksiyonunu döndürür. Salt-okunur [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Döndürür:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)