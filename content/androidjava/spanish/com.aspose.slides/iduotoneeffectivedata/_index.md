---
title: IDuotoneEffectiveData
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Objeto inmutable que representa un efecto Duotono.
type: docs
url: /es/com.aspose.slides/iduotoneeffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Objeto inmutable que representa un efecto Duotono. Para cada píxel, combina clr1 y clr2 mediante una interpolación lineal para determinar el nuevo color de ese píxel.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColor1()](#getColor1--) | Devuelve el formato de color objetivo para píxeles oscuros. |
| [getColor2()](#getColor2--) | Devuelve el formato de color objetivo para píxeles claros. |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```


Devuelve el formato de color objetivo para píxeles oscuros. Solo lectura java.lang.Integer.

**Devuelve:**
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```


Devuelve el formato de color objetivo para píxeles claros. Solo lectura java.lang.Integer.

**Devuelve:**
java.lang.Integer