---
title: IDuotoneEffectiveData
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Objet immuable qui représente un effet Duo-ton.
type: docs
url: /fr/com.aspose.slides/iduotoneeffectivedata/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet Duo-ton. Pour chaque pixel, combine clr1 et clr2 par interpolation linéaire afin de déterminer la nouvelle couleur de ce pixel.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor1()](#getColor1--) | Renvoie le format de couleur cible pour les pixels sombres. |
| [getColor2()](#getColor2--) | Renvoie le format de couleur cible pour les pixels clairs. |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```

Renvoie le format de couleur cible pour les pixels sombres. Lecture seule java.lang.Integer.

**Renvoie:**  
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```

Renvoie le format de couleur cible pour les pixels clairs. Lecture seule java.lang.Integer.

**Renvoie:**  
java.lang.Integer