---
title: IAlphaBiLevel
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet Alpha bi-niveau.
type: docs
url: /fr/com.aspose.slides/ialphabilevel/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Représente un effet Alpha bi-niveau. Les valeurs Alpha (opacité) inférieures au seuil sont changées à 0 (totalement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées à 100 % (totalement opaque).

--------------------

Utilisez ImageTransformOperationFactory pour créer des instances dans COM.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Renvoie le seuil d'effet. |
| [setThreshold(float value)](#setThreshold-float-) | Renvoie le seuil d'effet. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Renvoie le seuil d'effet. Lecture/écriture float.

**Renvoie :**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Renvoie le seuil d'effet. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |