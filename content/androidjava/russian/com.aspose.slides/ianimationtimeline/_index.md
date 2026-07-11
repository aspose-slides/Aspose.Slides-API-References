---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет временную шкалу анимации.
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
| [getMainSequence()](#getMainSequence--) | Возвращает основную последовательность, которая может содержать только коллекцию основных эффектов. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Возвращает коллекцию анимаций текста. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Возвращает коллекцию интерактивных последовательностей. Эти последовательности могут содержать только эффекты по «click on shape», указанные целевой фигурой. Толькo для чтения [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Возвращает:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Возвращает основную последовательность, которая может содержать только коллекцию основных эффектов. Толькo для чтения [ISequence](../../com.aspose.slides/isequence).

**Возвращает:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Возвращает коллекцию анимаций текста. Толькo для чтения [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Возвращает:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)