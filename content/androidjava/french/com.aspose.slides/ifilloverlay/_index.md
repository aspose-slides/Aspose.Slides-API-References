---
title: IFillOverlay
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un effet de superposition de remplissage.
type: docs
url: /fr/com.aspose.slides/ifilloverlay/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Représente un effet de superposition de remplissage. Une superposition de remplissage peut être utilisée pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Format de remplissage. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Lecture/écriture [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Renvoie :** 
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. Lecture/écriture [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Format de remplissage. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)