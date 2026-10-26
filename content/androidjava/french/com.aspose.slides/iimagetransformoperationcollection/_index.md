---
title: IImageTransformOperationCollection
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente une collection d'effets appliqués à une image.
type: docs
url: /fr/com.aspose.slides/iimagetransformoperationcollection/
---
**Toutes les interfaces implémentées :**  
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Représente une collection d'effets appliqués à une image.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie un [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) de la collection par son indice. |
| [removeAt(int index)](#removeAt-int-) | Supprime un effet d'image d'une collection à l'index spécifié. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Ajoute le nouvel effet Alpha Bi-Level à la fin d'une collection. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Ajoute le nouvel effet Alpha Ceiling à la fin d'une collection. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Ajoute le nouvel effet Alpha Floor à la fin d'une collection. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Ajoute le nouvel effet Alpha Inverse à la fin d'une collection. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Ajoute le nouvel effet Alpha Modulate à la fin d'une collection. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Ajoute le nouvel effet Alpha Modulate Fixed à la fin d'une collection. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Ajoute le nouvel effet Alpha Replace à la fin d'une collection. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Ajoute le nouvel effet Bi-Level (noir/blanc) à la fin d'une collection. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Ajoute le nouvel effet Blur à la fin d'une collection. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Ajoute le nouvel effet Color Change à la fin d'une collection. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Ajoute le nouvel effet Color Replacement à la fin d'une collection. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Ajoute le nouvel effet Duotone à la fin d'une collection. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Ajoute le nouvel effet Fill Overlay à la fin d'une collection. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Ajoute le nouvel effet Gray Scale à la fin d'une collection. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Ajoute le nouvel effet Hue/Saturation/Luminance à la fin d'une collection. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Ajoute le nouvel effet Luminance à la fin d'une collection. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Ajoute le nouvel effet Tint à la fin d'une collection. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Ajoute le nouvel effet BrightnessContrast à la fin d'une collection. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Renvoie un [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) de la collection par son indice.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de l'élément. |

**Retour :**  
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - L'objet [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime un effet d'image d'une collection à l'index spécifié.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de l'effet d'image à supprimer. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Ajoute le nouvel effet Alpha Bi-Level à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Valeur du seuil pour l'effet alpha bi-level. |

**Retour :**  
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Indice du nouvel effet d'image dans une collection.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Ajoute le nouvel effet Alpha Ceiling à la fin d'une collection.

**Retour :**  
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Indice du nouvel effet d'image dans une collection.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Ajoute le nouvel effet Alpha Floor à la fin d'une collection.

**Retour :**  
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Indice du nouvel effet d'image dans une collection.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Ajoute le nouvel effet Alpha Inverse à la fin d'une collection.

**Retour :**  
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Indice du nouvel effet d'image dans une collection.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Ajoute le nouvel effet Alpha Modulate à la fin d'une collection.

**Retour :**  
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Indice du nouvel effet d'image dans une collection.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Ajoute le nouvel effet Alpha Modulate Fixed à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| amount | float | Pourcentage de mise à l'échelle de l'alpha. |

**Retour :**  
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Indice du nouvel effet d'image dans une collection.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Ajoute le nouvel effet Alpha Replace à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | float | Nouvelle valeur d'opacité. |

**Retour :**  
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Indice du nouvel effet d'image dans une collection.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Ajoute le nouvel effet Bi-Level (noir/blanc) à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Le seuil de luminance pour l'effet Bi-Level. Les valeurs supérieures ou égales au seuil deviennent blanches, les valeurs inférieures deviennent noires. |

**Retour :**  
[IBiLevel](../../com.aspose.slides/ibilevel) - Indice du nouvel effet d'image dans une collection.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Ajoute le nouvel effet Blur à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| radius | double | Le rayon du flou. |
| grow | boolean | Indique si les limites de l'objet doivent être agrandies suite au flou. True = agrandies, false = non agrandies. |

**Retour :**  
[IBlur](../../com.aspose.slides/iblur) - Indice du nouvel effet d'image dans une collection.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Ajoute le nouvel effet Color Change à la fin d'une collection.

**Retour :**  
[IColorChange](../../com.aspose.slides/icolorchange) - Indice du nouvel effet d'image dans une collection.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Ajoute le nouvel effet Color Replacement à la fin d'une collection.

**Retour :**  
[IColorReplace](../../com.aspose.slides/icolorreplace) - Indice du nouvel effet d'image dans une collection.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Ajoute le nouvel effet Duotone à la fin d'une collection.

**Retour :**  
[IDuotone](../../com.aspose.slides/iduotone) - Indice du nouvel effet d'image dans une collection.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Ajoute le nouvel effet Fill Overlay à la fin d'une collection.

**Retour :**  
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Indice du nouvel effet d'image dans une collection.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Ajoute le nouvel effet Gray Scale à la fin d'une collection.

**Retour :**  
[IGrayScale](../../com.aspose.slides/igrayscale) - Indice du nouvel effet d'image dans une collection.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Ajoute le nouvel effet Hue/Saturation/Luminance à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | float | Nombre de degrés de réglage de la teinte. |
| saturation | float | Pourcentage de réglage de la saturation. |
| luminance | float | Pourcentage de réglage de la luminance. |

**Retour :**  
[IHSL](../../com.aspose.slides/ihsl) - Indice du nouvel effet d'image dans une collection.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Ajoute le nouvel effet Luminance à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | float | Pourcentage de modification de la luminosité. |
| contrast | float | Pourcentage de modification du contraste. |

**Retour :**  
[ILuminance](../../com.aspose.slides/iluminance) - Indice du nouvel effet d'image dans une collection.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Ajoute le nouvel effet Tint à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | float | Teinte vers laquelle appliquer la teinte. |
| amount | float | Spécifie de combien la valeur de couleur est décalée. |

**Retour :**  
[ITint](../../com.aspose.slides/itint) - Indice du nouvel effet d'image dans une collection.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Ajoute le nouvel effet BrightnessContrast à la fin d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | float | Pourcentage de modification de la luminosité. |
| contrast | float | Pourcentage de modification du contraste. |

**Retour :**  
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Indice du nouvel effet d'image dans une collection.