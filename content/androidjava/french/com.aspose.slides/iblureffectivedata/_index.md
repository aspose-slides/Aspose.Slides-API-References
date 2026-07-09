---
title: IBlurEffectiveData
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Objet immuable qui représente un effet de flou appliqué à toute la forme, y compris son remplissage.
type: docs
url: /fr/com.aspose.slides/iblureffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet de flou appliqué à toute la forme, y compris son remplissage. Tous les canaux de couleur, y compris l'alpha, sont affectés.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Renvoie ou définit le rayon du flou. |
| [getGrow()](#getGrow--) | Détermine si les limites de l’objet doivent être agrandies à cause du flou. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Renvoie ou définit le rayon du flou. Lecture seule double.

**Retourne :**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Détermine si les limites de l’objet doivent être agrandies à cause du flou. True indique que les limites sont agrandies, false indique le contraire. Lecture seule boolean.

**Retourne :**
boolean