---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Rappresenta il comportamento della classe base dell'effetto.
type: docs
url: /it/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Rappresenta il comportamento della classe base dell'effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Represents whether animation behaviors are accumulated. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Represents whether animation behaviors are accumulated. |
| [getAdditive()](#getAdditive--) | Represents whether the current animation behavior is combined with other running animations. |
| [setAdditive(int value)](#setAdditive-int-) | Represents whether the current animation behavior is combined with other running animations. |
| [getProperties()](#getProperties--) | Represents properties of behavior. |
| [getTiming()](#getTiming--) | Represents timing properties for the effect behavior. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Represents timing properties for the effect behavior. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Rappresenta se i comportamenti di animazione sono accumulati. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Rappresenta se i comportamenti di animazione sono accumulati. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. Lettura/scrittura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Restituisce:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. Lettura/scrittura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Rappresenta le proprietà del comportamento. Solo lettura [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Restituisce:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto. Lettura/scrittura [ITiming](../../com.aspose.slides/itiming).

**Restituisce:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto. Lettura/scrittura [ITiming](../../com.aspose.slides/itiming).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |