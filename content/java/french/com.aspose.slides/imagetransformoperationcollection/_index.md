---
title: ImageTransformOperationCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection d'effets appliqués à une image.
type: docs
url: /fr/com.aspose.slides/imagetransformoperationcollection/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Représente une collection d'effets appliqués à une image.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Renvoie un [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) de la collection par son index. |
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
| [size()](#size--) | Renvoie le nombre d'effets d'image dans une collection. |
| [isReadOnly()](#isReadOnly--) | Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Ajoute le nouvel effet d'image à la fin d'une collection. |
| [clear()](#clear--) | Supprime tous les effets d'image d'une collection. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un tableau, en commençant à un indice de tableau particulier. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Supprime la première occurrence d'un objet spécifique du [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Renvoie un [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) de la collection par son index.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Renvoie :**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - L'objet [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime un effet d'image d'une collection à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'un effet d'image qui doit être supprimé. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Ajoute le nouvel effet Alpha Bi-Level à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | La valeur de seuil pour l'effet Alpha Bi-Level. |

**Renvoie :**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index du nouvel effet d'image dans la collection.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Ajoute le nouvel effet Alpha Ceiling à la fin d'une collection.

**Renvoie :**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index du nouvel effet d'image dans la collection.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Ajoute le nouvel effet Alpha Floor à la fin d'une collection.

**Renvoie :**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index du nouvel effet d'image dans la collection.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Ajoute le nouvel effet Alpha Inverse à la fin d'une collection.

**Renvoie :**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index du nouvel effet d'image dans la collection.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Ajoute le nouvel effet Alpha Modulate à la fin d'une collection.

**Renvoie :**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index du nouvel effet d'image dans la collection.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Ajoute le nouvel effet Alpha Modulate Fixed à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| amount | float | Le pourcentage à appliquer à l'alpha. |

**Renvoie :**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index du nouvel effet d'image dans la collection.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Ajoute le nouvel effet Alpha Replace à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | float | La nouvelle valeur d'opacité. |

**Renvoie :**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index du nouvel effet d'image dans la collection.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Ajoute le nouvel effet Bi-Level (noir/blanc) à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Le seuil de luminance pour l'effet Bi-Level. Les valeurs supérieures ou égales au seuil sont définies sur blanc. Les valeurs inférieures au seuil sont définies sur noir. |

**Renvoie :**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index du nouvel effet d'image dans la collection.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Ajoute le nouvel effet Blur à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| radius | double | Le rayon du flou. |
| grow | boolean | Indique si les limites de l'objet doivent être agrandies suite au flou. True indique que les limites sont agrandies, false indique le contraire. |

**Renvoie :**
[IBlur](../../com.aspose.slides/iblur) - Index du nouvel effet d'image dans la collection.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Ajoute le nouvel effet Color Change à la fin d'une collection.

**Renvoie :**
[IColorChange](../../com.aspose.slides/icolorchange) - Index du nouvel effet d'image dans la collection.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Ajoute le nouvel effet Color Replacement à la fin d'une collection.

**Renvoie :**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index du nouvel effet d'image dans la collection.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Ajoute le nouvel effet Duotone à la fin d'une collection.

**Renvoie :**
[IDuotone](../../com.aspose.slides/iduotone) - Index du nouvel effet d'image dans la collection.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Ajoute le nouvel effet Fill Overlay à la fin d'une collection.

**Renvoie :**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index du nouvel effet d'image dans la collection.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Ajoute le nouvel effet Gray Scale à la fin d'une collection.

**Renvoie :**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index du nouvel effet d'image dans la collection.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Ajoute le nouvel effet Hue/Saturation/Luminance à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | float | Le nombre de degrés de réglage de la teinte. |
| saturation | float | Le pourcentage de réglage de la saturation. |
| luminance | float | Le pourcentage de réglage de la luminance. |

**Renvoie :**
[IHSL](../../com.aspose.slides/ihsl) - Index du nouvel effet d'image dans la collection.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Ajoute le nouvel effet Luminance à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | float | Le pourcentage de modification de la luminosité. |
| contrast | float | Le pourcentage de modification du contraste. |

**Renvoie :**
[ILuminance](../../com.aspose.slides/iluminance) - Index du nouvel effet d'image dans la collection.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Ajoute le nouvel effet Tint à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | float | La teinte vers laquelle appliquer la teinte. |
| amount | float | Indique de combien la valeur de couleur est décalée. |

**Renvoie :**
[ITint](../../com.aspose.slides/itint) - Index du nouvel effet d'image dans la collection.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Ajoute le nouvel effet BrightnessContrast à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | float | Le pourcentage de modification de la luminosité. |
| contrast | float | Le pourcentage de modification du contraste. |

**Renvoie :**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index du nouvel effet d'image dans la collection.

### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'effets d'image dans une collection. Lecture seule int.

**Renvoie :**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. Lecture seule boolean.

**Renvoie :**
boolean - true si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule ; sinon, false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Ajoute le nouvel effet d'image à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | L'effet d'image à ajouter à la fin d'une collection. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les effets d'image d'une collection.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | L'objet à rechercher dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Renvoie :**
boolean - true si l'item est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un tableau, en commençant à un indice de tableau particulier.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Le tableau unidimensionnel qui est la destination des éléments copiés depuis [IGenericCollection](../../com.aspose.slides/igenericcollection). Le tableau doit être indexé à partir de zéro. |
| arrayIndex | int | L'indice de base zéro dans le tableau où la copie commence. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Supprime la première occurrence d'un objet spécifique du [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | L'objet à supprimer du [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Renvoie :**
boolean - true si  item  a été supprimé avec succès du [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false. Cette méthode renvoie également false si l'item n'est pas trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) original.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Un java.util.Iterator pour l'ensemble de la collection.