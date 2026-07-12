---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Represent base class behavior of effect.
type: docs
url: /es/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Representa el comportamiento de la clase base del efecto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Representa si los comportamientos de animación se acumulan. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Representa si los comportamientos de animación se acumulan. |
| [getAdditive()](#getAdditive--) | Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. |
| [setAdditive(int value)](#setAdditive-int-) | Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. |
| [getProperties()](#getProperties--) | Representa las propiedades del comportamiento. |
| [getTiming()](#getTiming--) | Representa las propiedades de temporización para el comportamiento del efecto. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Representa las propiedades de temporización para el comportamiento del efecto. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Representa si los comportamientos de animación se acumulan. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Representa si los comportamientos de animación se acumulan. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. Lectura/escritura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Devuelve:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. Lectura/escritura [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Representa las propiedades del comportamiento. Solo lectura [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Devuelve:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Representa las propiedades de temporización para el comportamiento del efecto. Lectura/escritura [ITiming](../../com.aspose.slides/itiming).

**Devuelve:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Representa las propiedades de temporización para el comportamiento del efecto. Lectura/escritura [ITiming](../../com.aspose.slides/itiming).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |