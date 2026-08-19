---
title: AnimationTimeLine
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta la timeline dell'animazione.
type: docs
url: /it/com.aspose.slides/animationtimeline/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Rappresenta la timeline dell'animazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Restituisce la collezione di sequenze interattive. |
| [getMainSequence()](#getMainSequence--) | Restituisce la sequenza principale che può contenere solo la collezione di effetti principali. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Restituisce la collezione di animazioni di testo. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Restituisce la collezione di sequenze interattive. Questa sequenza può contenere solo effetti tramite "clic sulla forma" con la forma target specificata. Solo lettura [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Restituisce:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Restituisce la sequenza principale che può contenere solo la collezione di effetti principali. Solo lettura [ISequence](../../com.aspose.slides/isequence).

**Restituisce:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Restituisce la collezione di animazioni di testo. Solo lettura [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Restituisce:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)