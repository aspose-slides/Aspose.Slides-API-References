---
title: Behavior
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa el comportamiento de la clase base del efecto.
type: docs
url: /es/com.aspose.slides/behavior/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Representa el comportamiento de la clase base del efecto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Representa si los comportamientos de animación se acumulan. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Representa si los comportamientos de animación se acumulan. |
| [getAdditive()](#getAdditive--) | Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. |
| [setAdditive(int value)](#setAdditive-int-) | Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. |
| [getProperties()](#getProperties--) | Representa las propiedades del comportamiento. |
| [getTiming()](#getTiming--) | Representa las propiedades de temporización del comportamiento del efecto. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Representa las propiedades de temporización del comportamiento del efecto. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Representa si los comportamientos de animación se acumulan. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Representa si los comportamientos de animación se acumulan. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. Lectura/escritura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Devuelve:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. Lectura/escritura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Representa las propiedades del comportamiento. Solo lectura [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Devuelve:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Representa las propiedades de temporización del comportamiento del efecto. Lectura/escritura [ITiming](../../com.aspose.slides/itiming).

**Devuelve:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Representa las propiedades de temporización del comportamiento del efecto. Lectura/escritura [ITiming](../../com.aspose.slides/itiming).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |