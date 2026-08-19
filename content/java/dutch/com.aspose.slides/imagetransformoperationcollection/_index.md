---
title: ImageTransformOperationCollection
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een collectie van effecten voor die op een afbeelding zijn toegepast.
type: docs
url: /nl/com.aspose.slides/imagetransformoperationcollection/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle Gearbeikte Interfaces:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Stelt een collectie van effecten voor die op een afbeelding zijn toegepast.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Retourneert een [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) uit de collectie op basis van zijn index. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een afbeeldingseffect uit een collectie op de opgegeven index. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Voegt het nieuwe Alpha Bi-Level effect toe aan het einde van een collectie. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Voegt het nieuwe Alpha Ceiling effect toe aan het einde van een collectie. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Voegt het nieuwe Alpha Floor effect toe aan het einde van een collectie. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Voegt het nieuwe Alpha Inverse effect toe aan het einde van een collectie. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Voegt het nieuwe Alpha Modulate effect toe aan het einde van een collectie. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Voegt het nieuwe Alpha Modulate Fixed effect toe aan het einde van een collectie. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Voegt het nieuwe Alpha Replace effect toe aan het einde van een collectie. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Voegt het nieuwe Bi-Level (black/white) effect toe aan het einde van een collectie. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Voegt het nieuwe Blur effect toe aan het einde van een collectie. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Voegt het nieuwe Color Change effect toe aan het einde van een collectie. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Voegt het nieuwe Color Replacement effect toe aan het einde van een collectie. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Voegt het nieuwe Duotone effect toe aan het einde van een collectie. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Voegt het nieuwe Fill Overlay effect toe aan het einde van een collectie. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Voegt het nieuwe Gray Scale effect toe aan het einde van een collectie. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Voegt het nieuwe Hue/Saturation/Luminance effect toe aan het einde van een collectie. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Voegt het nieuwe Luminance effect toe aan het einde van een collectie. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Voegt het nieuwe Tint effect toe aan het einde van een collectie. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Voegt het nieuwe BrightnessContrast effect toe aan het einde van een collectie. |
| [size()](#size--) | Retourneert het aantal afbeeldingseffecten in een collectie. |
| [isReadOnly()](#isReadOnly--) | Krijgt een waarde die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Voegt het nieuwe afbeeldingseffect toe aan het einde van een collectie. |
| [clear()](#clear--) | Verwijdert alle afbeeldingseffecten uit een collectie. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend op een bepaalde Array-index. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Verwijdert het eerste voorkomen van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java iterator voor de volledige collectie. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retour:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Retourneert een [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) uit de collectie op basis van zijn index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element. |

**Retour:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Het [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) object.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert een afbeeldingseffect uit een collectie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een afbeeldingseffect dat verwijderd moet worden. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Voegt het nieuwe Alpha Bi-Level effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | De drempelwaarde voor het Alpha Bi-Level effect. |

**Retour:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index van het nieuwe afbeeldingseffect in een collectie.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Voegt het nieuwe Alpha Ceiling effect toe aan het einde van een collectie.

**Retour:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index van het nieuwe afbeeldingseffect in een collectie.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Voegt het nieuwe Alpha Floor effect toe aan het einde van een collectie.

**Retour:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index van het nieuwe afbeeldingseffect in een collectie.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
``` 
public final IAlphaInverse addAlphaInverseEffect()
```

Voegt het nieuwe Alpha Inverse effect toe aan het einde van een collectie.

**Retour:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index van het nieuwe afbeeldingseffect in een collectie.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Voegt het nieuwe Alpha Modulate effect toe aan het einde van een collectie.

**Retour:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index van het nieuwe afbeeldingseffect in een collectie.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Voegt het nieuwe Alpha Modulate Fixed effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| amount | float | Het percentage waarmee de alpha wordt geschaald. |

**Retour:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index van het nieuwe afbeeldingseffect in een collectie.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
``` 
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Voegt het nieuwe Alpha Replace effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | float | De nieuwe opaciteitswaarde. |

**Retour:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index van het nieuwe afbeeldingseffect in een collectie.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Voegt het nieuwe Bi-Level (black/white) effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | De luminantiedrempel voor het Bi-Level effect. Waarden groter dan of gelijk aan de drempel worden wit. Waarden kleiner dan de drempel worden zwart. |

**Retour:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index van het nieuwe afbeeldingseffect in een collectie.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Voegt het nieuwe Blur effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | De radius van de vervaging. |
| grow | boolean | Geeft aan of de grenzen van het object moeten worden uitgebreid als gevolg van de vervaging. True betekent dat de grenzen worden uitgebreid, false dat niet. |

**Retour:**
[IBlur](../../com.aspose.slides/iblur) - Index van het nieuwe afbeeldingseffect in een collectie.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Voegt het nieuwe Color Change effect toe aan het einde van een collectie.

**Retour:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index van het nieuwe afbeeldingseffect in een collectie.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Voegt het nieuwe Color Replacement effect toe aan het einde van een collectie.

**Retour:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index van het nieuwe afbeeldingseffect in een collectie.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Voegt het nieuwe Duotone effect toe aan het einde van een collectie.

**Retour:**
[IDuotone](../../com.aspose.slides/iduotone) - Index van het nieuwe afbeeldingseffect in een collectie.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Voegt het nieuwe Fill Overlay effect toe aan het einde van een collectie.

**Retour:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index van het nieuwe afbeeldingseffect in een collectie.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Voegt het nieuwe Gray Scale effect toe aan het einde van een collectie.

**Retour:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index van het nieuwe afbeeldingseffect in een collectie.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Voegt het nieuwe Hue/Saturation/Luminance effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | Het aantal graden waarmee de tint wordt aangepast. |
| saturation | float | Het percentage waarmee de verzadiging wordt aangepast. |
| luminance | float | Het percentage waarmee de luminantie wordt aangepast. |

**Retour:**
[IHSL](../../com.aspose.slides/ihsl) - Index van het nieuwe afbeeldingseffect in een collectie.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Voegt het nieuwe Luminance effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightness | float | Het percentage om de helderheid te wijzigen. |
| contrast | float | Het percentage om het contrast te wijzigen. |

**Retour:**
[ILuminance](../../com.aspose.slides/iluminance) - Index van het nieuwe afbeeldingseffect in een collectie.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Voegt het nieuwe Tint effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | De tint waartoe getint wordt. |
| amount | float | Geeft aan hoeveel de kleurwaarde wordt verschoven. |

**Retour:**
[ITint](../../com.aspose.slides/itint) - Index van het nieuwe afbeeldingseffect in een collectie.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Voegt het nieuwe BrightnessContrast effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightness | float | Het percentage om de helderheid te wijzigen. |
| contrast | float | Het percentage om het contrast te wijzigen. |

**Retour:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index van het nieuwe afbeeldingseffect in een collectie.

### size() {#size--}
```
public final int size()
```

Retourneert het aantal afbeeldingseffecten in een collectie. Alleen-lezen int.

**Retour:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Krijgt een waarde die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. Alleen-lezen boolean.

**Retour:**
boolean - true als de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is; anders, false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Voegt het nieuwe afbeeldingseffect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Het afbeeldingseffect dat aan het einde van een collectie moet worden toegevoegd. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle afbeeldingseffecten uit een collectie.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Het object dat moet worden gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**
boolean - true als item wordt gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders, false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend op een bepaalde Array-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | De eendimensionale Array die de bestemming is van de gekopieerde elementen van [IGenericCollection](../../com.aspose.slides/igenericcollection). De Array moet nulgebaseerde indexering hebben. |
| arrayIndex | int | De nulgebaseerde index in de array waarop het kopiëren begint. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Verwijdert het eerste voorkomen van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Het object dat uit de [IGenericCollection](../../com.aspose.slides/igenericcollection) moet worden verwijderd. |

**Retour:**
boolean - true als  item  succesvol is verwijderd uit de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders, false. Deze methode retourneert ook false als item niet wordt gevonden in de oorspronkelijke [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Retourneert een java iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Een java.util.Iterator voor de volledige collectie.