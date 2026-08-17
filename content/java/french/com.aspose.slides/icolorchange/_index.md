---
title: IColorChange
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet de changement de couleur.
type: docs
url: /fr/com.aspose.slides/icolorchange/
---
**Toutes les interfaces implémentées:**
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


Couleur qui sera remplacée. En lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Couleur qui remplacera. En lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne:**
[IColorFormat](../../com.aspose.slides/icolorformat)