---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
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
| [getAccumulate()](#getAccumulate--) | Udává, zda jsou animace akumulovány. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Udává, zda jsou animace akumulovány. |
| [getAdditive()](#getAdditive--) | Udává, zda je aktuální chování animace kombinováno s dalšími probíhajícími animacemi. |
| [setAdditive(int value)](#setAdditive-int-) | Udává, zda je aktuální chování animace kombinováno s dalšími probíhajícími animacemi. |
| [getProperties()](#getProperties--) | Udává vlastnosti chování. |
| [getTiming()](#getTiming--) | Udává časové vlastnosti chování efektu. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Udává časové vlastnosti chování efektu. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Udává, zda jsou animace akumulovány. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Udává, zda jsou animace akumulovány. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Udává, zda je aktuální chování animace kombinováno s dalšími probíhajícími animacemi. Čtení/zápis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returns:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Udává, zda je aktuální chování animace kombinováno s dalšími probíhajícími animacemi. Čtení/zápis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Udává vlastnosti chování. Pouze pro čtení [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returns:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Udává časové vlastnosti chování efektu. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Udává časové vlastnosti chování efektu. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |