---
title: IAnimationTimeLine
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa la línea de tiempo de la animación.
type: docs
url: /es/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
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
public abstract ISequenceCollection getInteractiveSequences()
```

Devuelve la colección de secuencias interactivas. Estas secuencias pueden contener solo efectos de "click on shape" con la forma objetivo especificada. Solo lectura [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Devuelve:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Devuelve la secuencia principal que puede contener solo la colección de efectos principales. Solo lectura [ISequence](../../com.aspose.slides/isequence).

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Devuelve la colección de animaciones de texto. Solo lectura [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Devuelve:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)