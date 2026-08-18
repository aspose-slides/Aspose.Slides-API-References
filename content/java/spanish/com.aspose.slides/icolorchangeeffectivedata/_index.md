---
title: IColorChangeEffectiveData
second_title: Referencia de la API de Aspose.Slides para Java
description: Objeto inmutable que representa un efecto de cambio de color.
type: docs
url: /es/com.aspose.slides/icolorchangeeffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Objeto inmutable que representa un efecto de cambio de color. Las instancias de FromColor se reemplazan con instancias de ToColor.
## Métodos

| Method | Descripción |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color que será reemplazado. |
| [getToColor()](#getToColor--) | Color que reemplazará. |
| [getUseAlpha()](#getUseAlpha--) | Devuelve un valor booleano que determina si se debe usar el componente alfa. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Color que será reemplazado. Solo de lectura java.awt.Color.

**Devuelve:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Color que reemplazará. Solo de lectura java.awt.Color.

**Devuelve:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Devuelve un valor booleano que determina si se debe usar el componente alfa. Solo de lectura boolean.

**Devuelve:**
boolean