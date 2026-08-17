---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Referansı
description: Animasyon zaman çizelgesini temsil eder.
type: docs
url: /tr/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Animasyon zaman çizelgesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Returns collection of interactive sequences. |
| [getMainSequence()](#getMainSequence--) | Returns main sequence which may contain only main effects collection. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Returns collection of text animations. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Koleksiyon şeklinde etkileşimli sıraları döndürür. Bu sıralar yalnızca hedef şekli belirten “şekle tıkla” etkileri içerebilir. Yalnızca okuma [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Döndürür:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Ana etki koleksiyonunu içerebilen ana sıralamayı döndürür. Yalnızca okuma [ISequence](../../com.aspose.slides/isequence).

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Metin animasyonları koleksiyonunu döndürür. Yalnızca okuma [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Döndürür:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)