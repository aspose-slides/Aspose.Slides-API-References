---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Represents timeline of animation.
type: docs
url: /ru/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Представляет временную шкалу анимации.

## Методы

| Метод | Описание |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Возвращает коллекцию интерактивных последовательностей. |
| [getMainSequence()](#getMainSequence--) | Возвращает главную последовательность, которая может содержать только коллекцию основных эффектов. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Возвращает коллекцию текстовых анимаций. |

### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Возвращает коллекцию интерактивных последовательностей. Эти последовательности могут содержать только эффекты по "click on shape" с указанной целевой фигурой. Только для чтения [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Возвращает:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)

### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Возвращает главную последовательность, которая может содержать только коллекцию основных эффектов. Только для чтения [ISequence](../../com.aspose.slides/isequence).

**Возвращает:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Возвращает коллекцию текстовых анимаций. Только для чтения [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Возвращает:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)