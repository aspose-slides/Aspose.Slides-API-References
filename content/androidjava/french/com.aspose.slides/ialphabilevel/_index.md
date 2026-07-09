---
title: IAlphaBiLevel
second_title: Référence API Java pour Aspose.Slides sous Android
description: Représente un effet binaire Alpha.
type: docs
url: /fr/com.aspose.slides/ialphabilevel/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Représente un effet binaire Alpha. Les valeurs Alpha (Opacité) inférieures au seuil sont remplacées par 0 (entièrement transparentes) et les valeurs Alpha supérieures ou égales au seuil sont remplacées par 100 % (entièrement opaques).

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