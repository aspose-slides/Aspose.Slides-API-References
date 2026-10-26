---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes pour PHP via référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/imagetransformoperationcollection/
---
## ImageTransformOperationCollection classe

 Représente une collection d'effets appliqués à une image.
 
### addAlphaBiLevelEffect {#addAlphaBiLevelEffect}

| Name | Description |
| --- | --- |
| addAlphaBiLevelEffect (float) | Ajoute le nouvel effet Alpha Bi-Level à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| threshold | float | La valeur du seuil pour l'effet Alpha Bi-Level. |

 **Renvoie:** 
[AlphaBiLevel](../alphabilevel)


---


### addAlphaCeilingEffect {#addAlphaCeilingEffect}

| Name | Description |
| --- | --- |
| addAlphaCeilingEffect () | Ajoute le nouvel effet Alpha Ceiling à la fin d'une collection. |

 **Renvoie:** 
[AlphaCeiling](../alphaceiling)


---


### addAlphaFloorEffect {#addAlphaFloorEffect}

| Name | Description |
| --- | --- |
| addAlphaFloorEffect () | Ajoute le nouvel effet Alpha Floor à la fin d'une collection. |

 **Renvoie:** 
[AlphaFloor](../alphafloor)


---


### addAlphaInverseEffect {#addAlphaInverseEffect}

| Name | Description |
| --- | --- |
| addAlphaInverseEffect () | Ajoute le nouvel effet Alpha Inverse à la fin d'une collection. |

 **Renvoie:** 
[AlphaInverse](../alphainverse)


---


### addAlphaModulateEffect {#addAlphaModulateEffect}

| Name | Description |
| --- | --- |
| addAlphaModulateEffect () | Ajoute le nouvel effet Alpha Modulate à la fin d'une collection. |

 **Renvoie:** 
[AlphaModulate](../alphamodulate)


---


### addAlphaModulateFixedEffect {#addAlphaModulateFixedEffect}

| Name | Description |
| --- | --- |
| addAlphaModulateFixedEffect (float) | Ajoute le nouvel effet Alpha Modulate Fixed à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| amount | float | Le pourcentage à appliquer à l'alpha. |

 **Renvoie:** 
[AlphaModulateFixed](../alphamodulatefixed)


---


### addAlphaReplaceEffect {#addAlphaReplaceEffect}

| Name | Description |
| --- | --- |
| addAlphaReplaceEffect (float) | Ajoute le nouvel effet Alpha Replace à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| alpha | float | La nouvelle valeur d'opacité. |

 **Renvoie:** 
[AlphaReplace](../alphareplace)


---


### addBiLevelEffect {#addBiLevelEffect}

| Name | Description |
| --- | --- |
| addBiLevelEffect (float) | Ajoute le nouvel effet Bi-Level (noir/blanc) à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| threshold | float | le seuil de luminance pour l'effet Bi-Level. Les valeurs supérieures ou égales au seuil sont définies sur blanc. Les valeurs inférieures au seuil sont définies sur noir. |

 **Renvoie:** 
[BiLevel](../bilevel)


---


### addBlurEffect {#addBlurEffect}

| Name | Description |
| --- | --- |
| addBlurEffect (double, boolean) | Ajoute le nouvel effet Blur à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| radius | double | Le rayon du flou. |
| grow | boolean | Indique si les limites de l'objet doivent être agrandies à la suite du flou. True indique que les limites sont agrandies, false indique le contraire. |

 **Renvoie:** 
[Blur](../blur)


---


### addBrightnessContrastEffect {#addBrightnessContrastEffect}

| Name | Description |
| --- | --- |
| addBrightnessContrastEffect (float, float) | Ajoute le nouvel effet BrightnessContrast à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| brightness | float | Le pourcentage pour modifier la luminosité. |
| contrast | float | Le pourcentage pour modifier le contraste. |

 **Renvoie:** 
[BrightnessContrast](../brightnesscontrast)


---


### addColorChangeEffect {#addColorChangeEffect}

| Name | Description |
| --- | --- |
| addColorChangeEffect () | Ajoute le nouvel effet Color Change à la fin d'une collection. |

 **Renvoie:** 
[ColorChange](../colorchange)


---


### addColorReplaceEffect {#addColorReplaceEffect}

| Name | Description |
| --- | --- |
| addColorReplaceEffect () | Ajoute le nouvel effet Color Replacement à la fin d'une collection. |

 **Renvoie:** 
[ColorReplace](../colorreplace)


---


### addDuotoneEffect {#addDuotoneEffect}

| Name | Description |
| --- | --- |
| addDuotoneEffect () | Ajoute le nouvel effet Duotone à la fin d'une collection. |

 **Renvoie:** 
[Duotone](../duotone)


---


### addFillOverlayEffect {#addFillOverlayEffect}

| Name | Description |
| --- | --- |
| addFillOverlayEffect () | Ajoute le nouvel effet Fill Overlay à la fin d'une collection. |

 **Renvoie:** 
[FillOverlay](../filloverlay)


---


### addGrayScaleEffect {#addGrayScaleEffect}

| Name | Description |
| --- | --- |
| addGrayScaleEffect () | Ajoute le nouvel effet Gray Scale à la fin d'une collection. |

 **Renvoie:** 
[GrayScale](../grayscale)


---


### addHSLEffect {#addHSLEffect}

| Name | Description |
| --- | --- |
| addHSLEffect (float, float, float) | Ajoute le nouvel effet Hue/Saturation/Luminance à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| hue | float | Le nombre de degrés de réglage de la teinte. |
| saturation | float | Le pourcentage de réglage de la saturation. |
| luminance | float | Le pourcentage de réglage de la luminance. |

 **Renvoie:** 
[HSL](../hsl)


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([SoftEdge](../softedge)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [SoftEdge](../softedge) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([ImageTransformOperation](../imagetransformoperation)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [ImageTransformOperation](../imagetransformoperation) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Glow](../glow)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [Glow](../glow) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaModulateFixed](../alphamodulatefixed)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaModulateFixed](../alphamodulatefixed) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaFloor](../alphafloor)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaFloor](../alphafloor) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([OuterShadow](../outershadow)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [OuterShadow](../outershadow) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Blur](../blur)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [Blur](../blur) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaReplace](../alphareplace)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaReplace](../alphareplace) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([FillOverlay](../filloverlay)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [FillOverlay](../filloverlay) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([HSL](../hsl)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [HSL](../hsl) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaBiLevel](../alphabilevel)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaBiLevel](../alphabilevel) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([BrightnessContrast](../brightnesscontrast)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [BrightnessContrast](../brightnesscontrast) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([ColorChange](../colorchange)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [ColorChange](../colorchange) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([InnerShadow](../innershadow)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [InnerShadow](../innershadow) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaModulate](../alphamodulate)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaModulate](../alphamodulate) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Reflection](../reflection)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [Reflection](../reflection) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([GrayScale](../grayscale)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [GrayScale](../grayscale) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Duotone](../duotone)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [Duotone](../duotone) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Luminance](../luminance)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [Luminance](../luminance) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaInverse](../alphainverse)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaInverse](../alphainverse) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaCeiling](../alphaceiling)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaCeiling](../alphaceiling) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([PresetShadow](../presetshadow)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

 **Paramètres:** 

| Name | Type | Description |
| --- | --- | --- |
| operation | [PresetShadow](../presetshadow) | L'effet d'image à ajouter à la fin d'une collection. |

 **Renvoie:** 
void

---
### addItem {#addItem}

| Nom | Description |
| --- | --- |
| addItem ([BiLevel](../bilevel)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| operation | [BiLevel](../bilevel) | L'effet d'image à ajouter à la fin d'une collection. |

**Renvoie :**
void


---


### addItem {#addItem}

| Nom | Description |
| --- | --- |
| addItem ([ColorReplace](../colorreplace)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| operation | [ColorReplace](../colorreplace) | L'effet d'image à ajouter à la fin d'une collection. |

**Renvoie :**
void


---


### addItem {#addItem}

| Nom | Description |
| --- | --- |
| addItem ([Tint](../tint)) | Ajoute le nouvel effet d'image à la fin d'une collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| operation | [Tint](../tint) | L'effet d'image à ajouter à la fin d'une collection. |

**Renvoie :**
void


---


### addLuminanceEffect {#addLuminanceEffect}

| Nom | Description |
| --- | --- |
| addLuminanceEffect (float, float) | Ajoute le nouvel effet Luminance à la fin d'une collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| brightness | float | Le pourcentage pour modifier la luminosité. |
| contrast | float | Le pourcentage pour modifier le contraste. |

**Renvoie :**
[Luminance](../luminance)


---


### addTintEffect {#addTintEffect}

| Nom | Description |
| --- | --- |
| addTintEffect (float, float) | Ajoute le nouvel effet Tint à la fin d'une collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| hue | float | La teinte vers laquelle appliquer la teinte. |
| amount | float | Spécifie de combien la valeur de couleur est décalée. |

**Renvoie :**
[Tint](../tint)


---


### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les effets d'image d'une collection. |

**Renvoie :**
void


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([SoftEdge](../softedge)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [SoftEdge](../softedge) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([ImageTransformOperation](../imagetransformoperation)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [ImageTransformOperation](../imagetransformoperation) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([Glow](../glow)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Glow](../glow) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([AlphaModulateFixed](../alphamodulatefixed)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed](../alphamodulatefixed) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([AlphaFloor](../alphafloor)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor](../alphafloor) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([OuterShadow](../outershadow)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [OuterShadow](../outershadow) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([Blur](../blur)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Blur](../blur) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([AlphaReplace](../alphareplace)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace](../alphareplace) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([FillOverlay](../filloverlay)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [FillOverlay](../filloverlay) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([HSL](../hsl)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [HSL](../hsl) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([AlphaBiLevel](../alphabilevel)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel](../alphabilevel) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([BrightnessContrast](../brightnesscontrast)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [BrightnessContrast](../brightnesscontrast) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([ColorChange](../colorchange)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [ColorChange](../colorchange) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([InnerShadow](../innershadow)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [InnerShadow](../innershadow) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([AlphaModulate](../alphamodulate)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate](../alphamodulate) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([Reflection](../reflection)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Reflection](../reflection) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([GrayScale](../grayscale)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [GrayScale](../grayscale) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([Duotone](../duotone)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Duotone](../duotone) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([Luminance](../luminance)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Luminance](../luminance) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([AlphaInverse](../alphainverse)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse](../alphainverse) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([AlphaCeiling](../alphaceiling)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling](../alphaceiling) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([PresetShadow](../presetshadow)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [PresetShadow](../presetshadow) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([BiLevel](../bilevel)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [BiLevel](../bilevel) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([ColorReplace](../colorreplace)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [ColorReplace](../colorreplace) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([Tint](../tint)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Tint](../tint) | L'objet à localiser dans IGenericCollection. |

**Renvoie :**
boolean


---


### copyToTArray {#copyToTArray}

| Nom | Description |
| --- | --- |
| copyToTArray (com.aspose.slides.IImageTransformOperation[], int) | Copie les éléments de IGenericCollection vers un tableau, en commençant à un indice de tableau particulier. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IImageTransformOperation[] | Le tableau unidimensionnel qui est la destination des éléments copiés depuis IGenericCollection. Le tableau doit être indexé à partir de zéro. |
| arrayIndex | int | L'indice de base zéro dans le tableau où commence la copie. |

**Renvoie :**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Le nombre d'éléments dans le IGenericCollection source est supérieur à l'espace disponible depuis arrayIndex jusqu'à la fin du tableau de destination. |


---


### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () |  |

**Renvoie :**
long


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Renvoie un ImageTransformOperation de la collection par son indice. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice de l'élément. |

**Renvoie :**
[SoftEdge](../softedge), [ImageTransformOperation](../imagetransformoperation), [Glow](../glow), [AlphaModulateFixed](../alphamodulatefixed), [AlphaFloor](../alphafloor), [OuterShadow](../outershadow), [Blur](../blur), [AlphaReplace](../alphareplace), [FillOverlay](../filloverlay), [HSL](../hsl), [AlphaBiLevel](../alphabilevel), [BrightnessContrast](../brightnesscontrast), [ColorChange](../colorchange), [InnerShadow](../innershadow), [AlphaModulate](../alphamodulate), [Reflection](../reflection), [GrayScale](../grayscale), [Duotone](../duotone), [Luminance](../luminance), [AlphaInverse](../alphainverse), [AlphaCeiling](../alphaceiling), [PresetShadow](../presetshadow), [BiLevel](../bilevel), [ColorReplace](../colorreplace), [Tint](../tint)


---


### isReadOnly {#isReadOnly}
| --- | --- |
| isReadOnly () | Obtient une valeur indiquant si IGenericCollection est en lecture seule. Booléen en lecture seule. |

**Retour :**
boolean


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

**Retour :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour la collection entière. |

**Retour :**



---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime un effet d'image d'une collection à l'index indiqué. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index d'un effet d'image qui doit être supprimé. |

**Retour :**
void


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([SoftEdge](../softedge)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [SoftEdge](../softedge) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([ImageTransformOperation](../imagetransformoperation)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [ImageTransformOperation](../imagetransformoperation) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([Glow](../glow)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Glow](../glow) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([AlphaModulateFixed](../alphamodulatefixed)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed](../alphamodulatefixed) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([AlphaFloor](../alphafloor)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor](../alphafloor) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([OuterShadow](../outershadow)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [OuterShadow](../outershadow) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([Blur](../blur)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Blur](../blur) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([AlphaReplace](../alphareplace)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace](../alphareplace) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([FillOverlay](../filloverlay)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [FillOverlay](../filloverlay) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([HSL](../hsl)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [HSL](../hsl) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([AlphaBiLevel](../alphabilevel)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel](../alphabilevel) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([BrightnessContrast](../brightnesscontrast)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [BrightnessContrast](../brightnesscontrast) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([ColorChange](../colorchange)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [ColorChange](../colorchange) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([InnerShadow](../innershadow)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [InnerShadow](../innershadow) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([AlphaModulate](../alphamodulate)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate](../alphamodulate) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([Reflection](../reflection)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Reflection](../reflection) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([GrayScale](../grayscale)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [GrayScale](../grayscale) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([Duotone](../duotone)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Duotone](../duotone) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([Luminance](../luminance)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Luminance](../luminance) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([AlphaInverse](../alphainverse)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse](../alphainverse) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([AlphaCeiling](../alphaceiling)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling](../alphaceiling) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([PresetShadow](../presetshadow)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [PresetShadow](../presetshadow) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([BiLevel](../bilevel)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [BiLevel](../bilevel) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([ColorReplace](../colorreplace)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [ColorReplace](../colorreplace) | L'objet à supprimer de l'IGenericCollection. |

**Retour :**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | L'IGenericCollection est en lecture seule. |
---
### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([Tint](../tint)) | Supprime la première occurrence d'un objet spécifique de l'IGenericCollection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Tint](../tint) | L'objet à supprimer de l'IGenericCollection. |

**Valeur de retour:**  
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
 | NotSupportedException | L'IGenericCollection est en lecture seule. |
---
### size {#size}

| Nom | Description |
| --- | --- |
| size () | Renvoie le nombre d'effets d'image dans une collection. int en lecture seule. |

**Valeur de retour:**  
int
---