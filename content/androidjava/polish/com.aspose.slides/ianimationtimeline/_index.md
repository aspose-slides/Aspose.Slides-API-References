---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje oś czasu animacji.
type: docs
url: /pl/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Reprezentuje oś czasu animacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Zwraca kolekcję interaktywnych sekwencji. |
| [getMainSequence()](#getMainSequence--) | Zwraca główną sekwencję, która może zawierać tylko kolekcję głównych efektów. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Zwraca kolekcję animacji tekstu. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Zwraca kolekcję interaktywnych sekwencji. Te sekwencje mogą zawierać tylko efekty wywoływane kliknięciem na kształt, z określonym kształtem docelowym. Tylko do odczytu [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Zwraca:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Zwraca główną sekwencję, która może zawierać tylko kolekcję głównych efektów. Tylko do odczytu [ISequence](../../com.aspose.slides/isequence).

**Zwraca:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Zwraca kolekcję animacji tekstu. Tylko do odczytu [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Zwraca:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)