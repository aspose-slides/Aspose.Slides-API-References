---
title: IColorChangeEffectiveData
second_title: Aspose.Slides pro Java – reference API
description: Neměnný objekt, který představuje efekt změny barvy.
type: docs
url: /cs/com.aspose.slides/icolorchangeeffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Neměnný objekt, který představuje efekt změny barvy. Instance FromColor jsou nahrazeny instancemi ToColor.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFromColor()](#getFromColor--) | Barva, která bude nahrazena. |
| [getToColor()](#getToColor--) | Barva, která nahradí. |
| [getUseAlpha()](#getUseAlpha--) | Vrací boolean hodnotu, která určuje, zda se má použít alfa komponenta. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Barva, která bude nahrazena. Pouze pro čtení java.awt.Color.

**Vrátí:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Barva, která nahradí. Pouze pro čtení java.awt.Color.

**Vrátí:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Vrací boolean hodnotu, která určuje, zda se má použít alfa komponenta. Pouze pro čtení boolean.

**Vrátí:**
boolean