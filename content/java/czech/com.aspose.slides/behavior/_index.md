---
title: Behavior
second_title: Aspose.Slides pro Java – referenční příručka API
description: Zastupuje chování základní třídy efektu.
type: docs
url: /cs/com.aspose.slides/behavior/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Zastupuje chování základní třídy efektu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Reprezentuje, zda jsou animační chování akumulována. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Reprezentuje, zda jsou animační chování akumulována. |
| [getAdditive()](#getAdditive--) | Reprezentuje, zda je aktuální animační chování kombinováno s ostatními probíhajícími animacemi. |
| [setAdditive(int value)](#setAdditive-int-) | Reprezentuje, zda je aktuální animační chování kombinováno s ostatními probíhajícími animacemi. |
| [getProperties()](#getProperties--) | Reprezentuje vlastnosti chování. |
| [getTiming()](#getTiming--) | Reprezentuje časové vlastnosti pro chování efektu. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Reprezentuje časové vlastnosti pro chování efektu. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Reprezentuje, zda jsou animační chování akumulována. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Reprezentuje, zda jsou animační chování akumulována. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Reprezentuje, zda je aktuální animační chování kombinováno s ostatními probíhajícími animacemi. Čtení/zápis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Vrací:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Reprezentuje, zda je aktuální animační chování kombinováno s ostatními probíhajícími animacemi. Čtení/zápis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Reprezentuje vlastnosti chování. Pouze pro čtení [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Vrací:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Reprezentuje časové vlastnosti pro chování efektu. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Vrací:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Reprezentuje časové vlastnosti pro chování efektu. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |