---
title: Behavior
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le comportement de classe de base de l'effet.
type: docs
url: /fr/com.aspose.slides/behavior/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Représente le comportement de classe de base de l'effet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Représente si les comportements d'animation sont accumulés. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Représente si les comportements d'animation sont accumulés. |
| [getAdditive()](#getAdditive--) | Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. |
| [setAdditive(int value)](#setAdditive-int-) | Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. |
| [getProperties()](#getProperties--) | Représente les propriétés du comportement. |
| [getTiming()](#getTiming--) | Représente les propriétés de synchronisation pour le comportement d'effet. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Représente les propriétés de synchronisation pour le comportement d'effet. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Représente si les comportements d'animation sont accumulés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Représente si les comportements d'animation sont accumulés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. Lecture/écriture [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Renvoie :**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. Lecture/écriture [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Représente les propriétés du comportement. Lecture seule [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Renvoie :**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Représente les propriétés de synchronisation pour le comportement d'effet. Lecture/écriture [ITiming](../../com.aspose.slides/itiming).

**Renvoie :**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Représente les propriétés de synchronisation pour le comportement d'effet. Lecture/écriture [ITiming](../../com.aspose.slides/itiming).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |