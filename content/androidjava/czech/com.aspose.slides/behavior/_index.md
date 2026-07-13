---
title: Behavior
second_title: Aspose.Slides pro Android přes referenci Java API
description: Reprezentuje chování základní třídy efektu.
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

Reprezentuje chování základní třídy efektu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Zobrazuje, zda jsou animace kumulovány. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Zobrazuje, zda jsou animace kumulovány. |
| [getAdditive()](#getAdditive--) | Zobrazuje, zda je aktuální chování animace kombinováno s dalšími běžícími animacemi. |
| [setAdditive(int value)](#setAdditive-int-) | Zobrazuje, zda je aktuální chování animace kombinováno s dalšími běžícími animacemi. |
| [getProperties()](#getProperties--) | Zobrazuje vlastnosti chování. |
| [getTiming()](#getTiming--) | Zobrazuje časové vlastnosti pro chování efektu. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Zobrazuje časové vlastnosti pro chování efektu. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent\_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Zobrazuje, zda jsou animace kumulovány. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Zobrazuje, zda jsou animace kumulovány. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Zobrazuje, zda je aktuální chování animace kombinováno s dalšími běžícími animacemi. Čtení/Zápis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Vrací:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Zobrazuje, zda je aktuální chování animace kombinováno s dalšími běžícími animacemi. Čtení/Zápis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Zobrazuje vlastnosti chování. Pouze pro čtení [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Vrací:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Zobrazuje časové vlastnosti pro chování efektu. Čtení/Zápis [ITiming](../../com.aspose.slides/itiming).

**Vrací:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Zobrazuje časové vlastnosti pro chování efektu. Čtení/Zápis [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |