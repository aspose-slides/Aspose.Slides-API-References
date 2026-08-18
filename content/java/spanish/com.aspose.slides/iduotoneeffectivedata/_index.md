---
title: IDuotoneEffectiveData
second_title: Referencia de la API de Aspose.Slides para Java
description: Objeto inmutable que representa un efecto Duotone.
type: docs
url: /es/com.aspose.slides/iduotoneeffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Objeto inmutable que representa un efecto Duotone. Para cada píxel, combina clr1 y clr2 mediante una interpolación lineal para determinar el nuevo color de ese píxel.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColor1()](#getColor1--) | Devuelve el formato de color objetivo para píxeles oscuros. |
| [getColor2()](#getColor2--) | Devuelve el formato de color objetivo para píxeles claros. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Devuelve el formato de color objetivo para píxeles oscuros. java.awt.Color de solo lectura.

**Devuelve:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Devuelve el formato de color objetivo para píxeles claros. java.awt.Color de solo lectura.

**Devuelve:**
java.awt.Color