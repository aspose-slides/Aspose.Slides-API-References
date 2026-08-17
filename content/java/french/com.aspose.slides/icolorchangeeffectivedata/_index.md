---
title: IColorChangeEffectiveData
second_title: Référence de l'API Aspose.Slides pour Java
description: Objet immuable qui représente un effet de changement de couleur.
type: docs
url: /fr/com.aspose.slides/icolorchangeeffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Couleur qui sera remplacée. |
| [getToColor()](#getToColor--) | Couleur qui remplacera. |
| [getUseAlpha()](#getUseAlpha--) | Renvoie une valeur booléenne qui détermine si le composant alpha doit être utilisé. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Couleur qui sera remplacée. Lecture seule java.awt.Color.

**Renvoie :**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Couleur qui remplacera. Lecture seule java.awt.Color.

**Renvoie :**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Renvoie une valeur booléenne qui détermine si le composant alpha doit être utilisé. Lecture seule booléen.

**Renvoie :**
boolean