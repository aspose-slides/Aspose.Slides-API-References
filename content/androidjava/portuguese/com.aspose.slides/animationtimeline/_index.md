---
title: AnimationTimeLine
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a linha do tempo da animação.
type: docs
url: /pt/com.aspose.slides/animationtimeline/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Representa a linha do tempo da animação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Retorna coleção de sequências interativas. |
| [getMainSequence()](#getMainSequence--) | Retorna a sequência principal que pode conter apenas a coleção de efeitos principais. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Retorna coleção de animações de texto. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Retorna coleção de sequências interativas. Estas sequências podem conter apenas efeitos por "clique na forma" com forma-alvo especificada. Somente leitura [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Retorna:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Retorna a sequência principal que pode conter apenas a coleção de efeitos principais. Somente leitura [ISequence](../../com.aspose.slides/isequence).

**Retorna:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Retorna coleção de animações de texto. Somente leitura [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Retorna:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)