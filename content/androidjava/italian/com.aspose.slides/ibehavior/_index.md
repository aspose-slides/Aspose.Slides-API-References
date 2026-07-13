---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Represent base class behavior of effect.
type: docs
url: /it/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Rappresenta il comportamento di base della classe dell'effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Rappresenta se i comportamenti di animazione sono accumulati. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Rappresenta se i comportamenti di animazione sono accumulati. |
| [getAdditive()](#getAdditive--) | Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. |
| [setAdditive(int value)](#setAdditive-int-) | Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. |
| [getProperties()](#getProperties--) | Rappresenta le proprietà del comportamento. |
| [getTiming()](#getTiming--) | Rappresenta le proprietà temporali per il comportamento dell'effetto. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Rappresenta le proprietà temporali per il comportamento dell'effetto. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```


Rappresenta se i comportamenti di animazione sono accumulati. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```


Rappresenta se i comportamenti di animazione sono accumulati. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```


Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. Lettura/Scrittura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Restituisce:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```


Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. Lettura/Scrittura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

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


Rappresenta le proprietà temporali per il comportamento dell'effetto. Lettura/Scrittura [ITiming](../../com.aspose.slides/itiming).

**Restituisce:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITTiming-}
```
public abstract void setTiming(ITiming value)
```


Rappresenta le proprietà temporali per il comportamento dell'effetto. Lettura/Scrittura [ITiming](../../com.aspose.slides/itiming).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |