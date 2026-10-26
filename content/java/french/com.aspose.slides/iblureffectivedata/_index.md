---
title: IBlurEffectiveData
second_title: Référence API Aspose.Slides pour Java
description: Objet immuable qui représente un effet de flou appliqué à l'ensemble de la forme, y compris son remplissage.
type: docs
url: /fr/com.aspose.slides/iblureffectivedata/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet de flou appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris l'alpha, sont affectés.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Renvoie ou définit le rayon de flou. |
| [getGrow()](#getGrow--) | Détermine si les limites de l'objet doivent être agrandies suite au flou. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Renvoie ou définit le rayon de flou. Lecture seule double.

**Renvoie:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Détermine si les limites de l'objet doivent être agrandies suite au flou. True indique que les limites sont agrandies tandis que false indique le contraire. Lecture seule boolean.

**Renvoie:**
boolean