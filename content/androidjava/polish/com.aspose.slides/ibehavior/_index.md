---
title: IBehavior
second_title: Aspose.Slides for Android za pośrednictwem referencji API Java
description: Reprezentuje zachowanie klasy bazowej efektu.
type: docs
url: /pl/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Reprezentuje zachowanie klasy bazowej efektu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Określa, czy zachowania animacji są kumulowane. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Określa, czy zachowania animacji są kumulowane. |
| [getAdditive()](#getAdditive--) | Określa, czy bieżące zachowanie animacji jest łączone z innymi uruchomionymi animacjami. |
| [setAdditive(int value)](#setAdditive-int-) | Określa, czy bieżące zachowanie animacji jest łączone z innymi uruchomionymi animacjami. |
| [getProperties()](#getProperties--) | Reprezentuje właściwości zachowania. |
| [getTiming()](#getTiming--) | Reprezentuje właściwości czasowe zachowania efektu. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Reprezentuje właściwości czasowe zachowania efektu. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Określa, czy zachowania animacji są kumulowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Określa, czy zachowania animacji są kumulowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Określa, czy bieżące zachowanie animacji jest łączone z innymi uruchomionymi animacjami. Odczyt/zapis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Zwraca:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Określa, czy bieżące zachowanie animacji jest łączone z innymi uruchomionymi animacjami. Odczyt/zapis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Reprezentuje właściwości zachowania. Tylko do odczytu [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Zwraca:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Reprezentuje właściwości czasowe zachowania efektu. Odczyt/zapis [ITiming](../../com.aspose.slides/itiming).

**Zwraca:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Reprezentuje właściwości czasowe zachowania efektu. Odczyt/zapis [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |