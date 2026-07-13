---
title: AnimationTimeLine
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta la linea temporale dell'animazione.
type: docs
url: /it/com.aspose.slides/animationtimeline/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Rappresenta la linea temporale dell'animazione.
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


Restituisce la collezione di sequenze interattive. Questa sequenza può contenere solo effetti da "clic sulla forma" con forma target specificata. Solo lettura [ISequenceCollection](../../com.aspose.slides/isequencecollection).

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