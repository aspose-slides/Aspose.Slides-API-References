---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Représente le comportement de classe de base de l'effet.
type: docs
url: /fr/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Représente le comportement de classe de base de l'effet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Représente si les comportements d'animation sont accumulés. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Représente si les comportements d'animation sont accumulés. |
| [getAdditive()](#getAdditive--) | Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. |
| [setAdditive(int value)](#setAdditive-int-) | Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. |
| [getProperties()](#getProperties--) | Représente les propriétés du comportement. |
| [getTiming()](#getTiming--) | Représente les propriétés de synchronisation pour le comportement d'effet. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Représente les propriétés de synchronisation pour le comportement d'effet. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Représente si les comportements d'animation sont accumulés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retourne**:
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Représente si les comportements d'animation sont accumulés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. Lecture/écriture [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Retourne**:
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. Lecture/écriture [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Représente les propriétés du comportement. Lecture seule [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Retourne**:
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Représente les propriétés de synchronisation pour le comportement d'effet. Lecture/écriture [ITiming](../../com.aspose.slides/itiming).

**Retourne**:
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Représente les propriétés de synchronisation pour le comportement d'effet. Lecture/écriture [ITiming](../../com.aspose.slides/itiming).

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |