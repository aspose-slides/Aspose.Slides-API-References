---
title: IAnimationTimeLine
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta la linea temporale dell'animazione.
type: docs
url: /it/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Rappresenta la linea temporale dell'animazione.
## Metodi

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Restituisce la collezione di sequenze interattive. |
| [getMainSequence()](#getMainSequence--) | Restituisce la sequenza principale che può contenere solo la collezione di effetti principali. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Restituisce la collezione di animazioni di testo. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Restituisce la collezione di sequenze interattive. Queste sequenze possono contenere solo effetti mediante "click on shape" con forma di destinazione specificata. Solo lettura [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Restituisce:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Restituisce la sequenza principale che può contenere solo la collezione di effetti principali. Solo lettura [ISequence](../../com.aspose.slides/isequence).

**Restituisce:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Restituisce la collezione di animazioni di testo. Solo lettura [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Restituisce:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)