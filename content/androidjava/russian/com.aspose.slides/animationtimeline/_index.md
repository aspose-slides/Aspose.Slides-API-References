---
title: AnimationTimeLine
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет временную шкалу анимации.
type: docs
url: /ru/com.aspose.slides/animationtimeline/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
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
public final ISequenceCollection getInteractiveSequences()
```


Возвращает коллекцию интерактивных последовательностей. Эти последовательности могут содержать только эффекты «щелчок по фигуре» с указанной целевой фигурой. Только для чтения [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Возвращаемое значение:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Возвращает основную последовательность, которая может содержать только коллекцию основных эффектов. Только для чтения [ISequence](../../com.aspose.slides/isequence).

**Возвращаемое значение:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Возвращает коллекцию анимаций текста. Только для чтения [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Возвращаемое значение:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)