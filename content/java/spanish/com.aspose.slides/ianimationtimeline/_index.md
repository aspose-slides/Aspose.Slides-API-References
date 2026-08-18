---
title: IAnimationTimeLine
second_title: Aspose.Slides para Java Referencia de API
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
| [getInteractiveSequences()](#getInteractiveSequences--) | Returns collection of interactive sequences. |
| [getMainSequence()](#getMainSequence--) | Returns main sequence which may contain only main effects collection. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Returns collection of text animations. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Devuelve la colección de secuencias interactivas. Estas secuencias pueden contener sólo efectos mediante “clic en la forma” con la forma objetivo especificada. Solo lectura [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Devuelve:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Devuelve la secuencia principal que puede contener sólo la colección de efectos principales. Solo lectura [ISequence](../../com.aspose.slides/isequence).

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Devuelve la colección de animaciones de texto. Solo lectura [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Devuelve:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)