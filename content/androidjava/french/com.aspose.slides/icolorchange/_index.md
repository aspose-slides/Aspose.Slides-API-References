---
title: IColorChange
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un effet de changement de couleur.
type: docs
url: /fr/com.aspose.slides/icolorchange/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Couleur qui sera remplacée. |
| [getToColor()](#getToColor--) | Couleur qui remplacera. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Couleur qui sera remplacée. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Couleur qui remplacera. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)