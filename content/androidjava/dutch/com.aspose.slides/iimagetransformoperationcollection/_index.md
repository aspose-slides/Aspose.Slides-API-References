---
title: IImageTransformOperationCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van effecten voor die op een afbeelding worden toegepast.
type: docs
url: /nl/com.aspose.slides/iimagetransformoperationcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Stelt een collectie van effecten voor die op een afbeelding worden toegepast.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert een [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) uit de collectie op basis van zijn index. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een afbeeldingseffect uit een collectie op de opgegeven index. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Voegt het nieuwe Alpha Bi-Level effect toe aan het einde van een collectie. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Voegt het nieuwe Alpha Ceiling effect toe aan het einde van een collectie. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Voegt het nieuwe Alpha Floor effect toe aan het einde van een collectie. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Voegt het nieuwe Alpha Inverse effect toe aan het einde van een collectie. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Voegt het nieuwe Alpha Modulate effect toe aan het einde van een collectie. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Voegt het nieuwe Alpha Modulate Fixed effect toe aan het einde van een collectie. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Voegt het nieuwe Alpha Replace effect toe aan het einde van een collectie. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Voegt het nieuwe Bi-Level (zwart/wit) effect toe aan het einde van een collectie. |
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
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```


Retourneert een [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) uit de collectie op basis van zijn index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het item. |

**Returns:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Het [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) object.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert een afbeeldingseffect uit een collectie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een afbeeldingseffect dat moet worden verwijderd. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```


Voegt het nieuwe Alpha Bi-Level effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | De drempelwaarde voor het Alpha Bi-Level effect. |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index van het nieuwe afbeeldingseffect in een collectie.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```


Voegt het nieuwe Alpha Ceiling effect toe aan het einde van een collectie.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index van het nieuwe afbeeldingseffect in een collectie.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```


Voegt het nieuwe Alpha Floor effect toe aan het einde van een collectie.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index van het nieuwe afbeeldingseffect in een collectie.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```


Voegt het nieuwe Alpha Inverse effect toe aan het einde van een collectie.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index van het nieuwe afbeeldingseffect in een collectie.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```


Voegt het nieuwe Alpha Modulate effect toe aan het einde van een collectie.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index van het nieuwe afbeeldingseffect in een collectie.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```


Voegt het nieuwe Alpha Modulate Fixed effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| amount | float | Het percentage waarmee de alpha wordt geschaald. |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index van het nieuwe afbeeldingseffect in een collectie.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```


Voegt het nieuwe Alpha Replace effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | float | De nieuwe opaciteitswaarde. |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index van het nieuwe afbeeldingseffect in een collectie.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```


Voegt het nieuwe Bi-Level (zwart/wit) effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | De luminantiedrempel voor het Bi-Level effect. Waarden groter dan of gelijk aan de drempel worden wit, waarden lager dan de drempel worden zwart. |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index van het nieuwe afbeeldingseffect in een collectie.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```


Voegt het nieuwe Blur effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | De radius van de vervaging. |
| grow | boolean | Specificeert of de grenzen van het object moeten worden vergroot als gevolg van het vervagen. True geeft aan dat de grenzen worden vergroot, terwijl false aangeeft dat ze niet worden vergroot. |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - Index van het nieuwe afbeeldingseffect in een collectie.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```


Voegt het nieuwe Color Change effect toe aan het einde van een collectie.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index van het nieuwe afbeeldingseffect in een collectie.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```


Voegt het nieuwe Color Replacement effect toe aan het einde van een collectie.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index van het nieuwe afbeeldingseffect in een collectie.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```


Voegt het nieuwe Duotone effect toe aan het einde van een collectie.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Index van het nieuwe afbeeldingseffect in een collectie.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```


Voegt het nieuwe Fill Overlay effect toe aan het einde van een collectie.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index van het nieuwe afbeeldingseffect in een collectie.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```


Voegt het nieuwe Gray Scale effect toe aan het einde van een collectie.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index van het nieuwe afbeeldingseffect in een collectie.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```


Voegt het nieuwe Hue/Saturation/Luminance effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | Het aantal graden waarmee de hue wordt aangepast. |
| saturation | float | Het percentage waarmee de verzadiging wordt aangepast. |
| luminance | float | Het percentage waarmee de luminantie wordt aangepast. |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - Index van het nieuwe afbeeldingseffect in een collectie.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```


Voegt het nieuwe Luminance effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightness | float | Het percentage waarmee de helderheid wordt aangepast. |
| contrast | float | Het percentage waarmee het contrast wordt aangepast. |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - Index van het nieuwe afbeeldingseffect in een collectie.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```


Voegt het nieuwe Tint effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | De hue waartoe getint moet worden. |
| amount | float | Geeft aan hoeveel de kleurwaarde wordt verschoven. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Index van het nieuwe afbeeldingseffect in een collectie.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```


Voegt het nieuwe BrightnessContrast effect toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightness | float | Het percentage waarmee de helderheid wordt aangepast. |
| contrast | float | Het percentage waarmee het contrast wordt aangepast. |

**Returns:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index van het nieuwe afbeeldingseffect in een collectie.