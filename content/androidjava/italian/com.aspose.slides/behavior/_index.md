---
title: Behavior
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta il comportamento della classe base dell'effetto.
type: docs
url: /it/com.aspose.slides/behavior/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Rappresenta il comportamento della classe base dell'effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Rappresenta se i comportamenti di animazione sono accumulati. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Rappresenta se i comportamenti di animazione sono accumulati. |
| [getAdditive()](#getAdditive--) | Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. |
| [setAdditive(int value)](#setAdditive-int-) | Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. |
| [getProperties()](#getProperties--) | Rappresenta le proprietà del comportamento. |
| [getTiming()](#getTiming--) | Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Rappresenta se i comportamenti di animazione sono accumulati. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Rappresenta se i comportamenti di animazione sono accumulati. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. Lettura/scrittura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Restituisce:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. Lettura/scrittura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Rappresenta le proprietà del comportamento. Solo lettura [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Restituisce:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto. Lettura/scrittura [ITiming](../../com.aspose.slides/itiming).

**Restituisce:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto. Lettura/scrittura [ITiming](../../com.aspose.slides/itiming).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |