---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Animasyonun zaman çizelgesini temsil eder.
type: docs
url: /tr/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Animasyonun zaman çizelgesini temsil eder.
## Metotlar

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Etkileşimli dizilerin koleksiyonunu döndürür. |
| [getMainSequence()](#getMainSequence--) | Yalnızca ana efektler koleksiyonunu içerebilen ana diziyi döndürür. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Metin animasyonlarının koleksiyonunu döndürür. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Etkileşimli dizilerin koleksiyonunu döndürür. Bu diziler, yalnızca belirli hedef şekil ile "click on shape" etkisi içerebilir. Salt okunur [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Döndürür:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Yalnızca ana efektler koleksiyonunu içerebilen ana diziyi döndürür. Salt okunur [ISequence](../../com.aspose.slides/isequence).

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Metin animasyonlarının koleksiyonunu döndürür. Salt okunur [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Döndürür:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)