---
title: IDuotoneEffectiveData
second_title: Référence de l'API Aspose.Slides pour Java
description: Objet immuable qui représente un effet Duotone.
type: docs
url: /fr/com.aspose.slides/iduotoneeffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet Duotone. Pour chaque pixel, combine clr1 et clr2 via une interpolation linéaire afin de déterminer la nouvelle couleur de ce pixel.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor1()](#getColor1--) | Renvoie le format de couleur cible pour les pixels sombres. |
| [getColor2()](#getColor2--) | Renvoie le format de couleur cible pour les pixels clairs. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Renvoie le format de couleur cible pour les pixels sombres. Lecture seule java.awt.Color.

**Renvoie :**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Renvoie le format de couleur cible pour les pixels clairs. Lecture seule java.awt.Color.

**Renvoie :**
java.awt.Color