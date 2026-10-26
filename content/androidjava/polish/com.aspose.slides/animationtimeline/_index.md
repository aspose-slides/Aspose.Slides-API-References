---
title: AnimationTimeLine
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje oś czasu animacji.
type: docs
url: /pl/com.aspose.slides/animationtimeline/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Reprezentuje oś czasu animacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Zwraca kolekcję interaktywnych sekwencji. |
| [getMainSequence()](#getMainSequence--) | Zwraca główną sekwencję, która może zawierać tylko kolekcję głównych efektów. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Zwraca kolekcję animacji tekstowych. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

Zwraca kolekcję interaktywnych sekwencji. Ta sekwencja może zawierać tylko efekty wywoływane przez „kliknięcie na kształt” z określonym docelowym kształtem. Tylko do odczytu [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Zwraca:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

Zwraca główną sekwencję, która może zawierać tylko kolekcję głównych efektów. Tylko do odczytu [ISequence](../../com.aspose.slides/isequence).

**Zwraca:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

Zwraca kolekcję animacji tekstowych. Tylko do odczytu [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Zwraca:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)