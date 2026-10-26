---
title: IColorChangeEffectiveData
second_title: Aspose.Slides Java API referenciája
description: Megváltoztathatatlan objektum, amely egy Color Change hatást képvisel.
type: docs
url: /hu/com.aspose.slides/icolorchangeeffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Megváltoztathatatlan objektum, amely egy Color Change hatást képvisel. FromColor példányok ToColor példányokkal lesznek helyettesítve.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFromColor()](#getFromColor--) | A helyettesítendő Color. |
| [getToColor()](#getToColor--) | A helyettesítő Color. |
| [getUseAlpha()](#getUseAlpha--) | Boolean értéket ad vissza, amely meghatározza, hogy az alpha komponens használva legyen-e. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


A helyettesítendő Color. Csak olvasható java.awt.Color.

**Visszatér:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


A helyettesítő Color. Csak olvasható java.awt.Color.

**Visszatér:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Boolean értéket ad vissza, amely meghatározza, hogy az alpha komponens használva legyen-e. Csak olvasható boolean.

**Visszatér:**
boolean