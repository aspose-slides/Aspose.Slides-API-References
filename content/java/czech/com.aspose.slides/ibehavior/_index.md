---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje chování základní třídy efektu.
type: docs
url: /cs/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Reprezentuje chování základní třídy efektu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Určuje, zda jsou animační chování akumulována. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Určuje, zda jsou animační chování akumulována. |
| [getAdditive()](#getAdditive--) | Určuje, zda je aktuální animační chování kombinováno s ostatními běžícími animacemi. |
| [setAdditive(int value)](#setAdditive-int-) | Určuje, zda je aktuální animační chování kombinováno s ostatními běžícími animacemi. |
| [getProperties()](#getProperties--) | Zobrazuje vlastnosti chování. |
| [getTiming()](#getTiming--) | Zobrazuje časové vlastnosti pro chování efektu. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Zobrazuje časové vlastnosti pro chování efektu. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Určuje, zda jsou animační chování akumulována. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Určuje, zda jsou animační chování akumulována. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Určuje, zda je aktuální animační chování kombinováno s ostatními běžícími animacemi. Čtení/zápis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Vrací:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Určuje, zda je aktuální animační chování kombinováno s ostatními běžícími animacemi. Čtení/zápis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Zobrazuje vlastnosti chování. Pouze pro čtení [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Vrací:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Zobrazuje časové vlastnosti pro chování efektu. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Vrací:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Zobrazuje časové vlastnosti pro chování efektu. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |