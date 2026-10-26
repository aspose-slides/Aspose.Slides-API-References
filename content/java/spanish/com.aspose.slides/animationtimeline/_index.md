---
title: AnimationTimeLine
second_title: Referencia de API de Aspose.Slides para Java
description: Representa la línea de tiempo de la animación.
type: docs
url: /es/com.aspose.slides/animationtimeline/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Representa la línea de tiempo de la animación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Devuelve la colección de secuencias interactivas. |
| [getMainSequence()](#getMainSequence--) | Devuelve la secuencia principal que puede contener solo la colección de efectos principales. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Devuelve la colección de animaciones de texto. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Devuelve la colección de secuencias interactivas. Estas secuencias pueden contener solo efectos por "clic en la forma" con la forma objetivo especificada. Solo lectura [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Devuelve:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Devuelve la secuencia principal que puede contener solo la colección de efectos principales. Solo lectura [ISequence](../../com.aspose.slides/isequence).

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Devuelve la colección de animaciones de texto. Solo lectura [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Devuelve:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)