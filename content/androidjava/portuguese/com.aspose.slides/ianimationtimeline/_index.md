---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Represents timeline of animation.
type: docs
url: /pt/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Representa a linha do tempo da animação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Retorna a coleção de sequências interativas. |
| [getMainSequence()](#getMainSequence--) | Retorna a sequência principal que pode conter apenas a coleção de efeitos principais. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Retorna a coleção de animações de texto. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Retorna a coleção de sequências interativas. Essas sequências podem conter apenas efeitos de "clique na forma" com a forma de destino especificada. Somente leitura [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Retorna:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Retorna a sequência principal que pode conter apenas a coleção de efeitos principais. Somente leitura [ISequence](../../com.aspose.slides/isequence).

**Retorna:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Retorna a coleção de animações de texto. Somente leitura [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Retorna:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)