---
title: IImageTransformOperationCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet werden.
type: docs
url: /de/com.aspose.slides/iimagetransformoperationcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt ein [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) aus der Sammlung anhand seines Index zurück. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Bildeffekt aus einer Sammlung am angegebenen Index. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Fügt den neuen Alpha Bi-Level-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Fügt den neuen Alpha Ceiling-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Fügt den neuen Alpha Floor-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Fügt den neuen Alpha Inverse-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Fügt den neuen Alpha Modulate-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Fügt den neuen Alpha Modulate Fixed-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Fügt den neuen Alpha Replace-Effekt am Ende einer Sammlung hinzu. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Fügt den neuen Bi-Level (black/white)-Effekt am Ende einer Sammlung hinzu. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Fügt den neuen Blur-Effekt am Ende einer Sammlung hinzu. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Fügt den neuen Color Change-Effekt am Ende einer Sammlung hinzu. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Fügt den neuen Color Replacement-Effekt am Ende einer Sammlung hinzu. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Fügt den neuen Duotone-Effekt am Ende einer Sammlung hinzu. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Fügt den neuen Fill Overlay-Effekt am Ende einer Sammlung hinzu. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Fügt den neuen Gray Scale-Effekt am Ende einer Sammlung hinzu. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Fügt den neuen Hue/Saturation/Luminance-Effekt am Ende einer Sammlung hinzu. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Fügt den neuen Luminance-Effekt am Ende einer Sammlung hinzu. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Fügt den neuen Tint-Effekt am Ende einer Sammlung hinzu. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Fügt den neuen BrightnessContrast-Effekt am Ende einer Sammlung hinzu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Gibt ein [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) aus der Sammlung anhand seines Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabewert:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Das [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) Objekt.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt einen Bildeffekt aus einer Sammlung am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Bildeffekts, der gelöscht werden soll. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Fügt den neuen Alpha Bi-Level-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Der Schwellenwert für den Alpha Bi-Level-Effekt. |

**Rückgabewert:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index des neuen Bildeffekts in einer Sammlung.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Fügt den neuen Alpha Ceiling-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index des neuen Bildeffekts in einer Sammlung.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Fügt den neuen Alpha Floor-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index des neuen Bildeffekts in einer Sammlung.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Fügt den neuen Alpha Inverse-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index des neuen Bildeffekts in einer Sammlung.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Fügt den neuen Alpha Modulate-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index des neuen Bildeffekts in einer Sammlung.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Fügt den neuen Alpha Modulate Fixed-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| amount | float | Der prozentuale Betrag, um den das Alpha skaliert wird. |

**Rückgabewert:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index des neuen Bildeffekts in einer Sammlung.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Fügt den neuen Alpha Replace-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha | float | Der neue Deckungswert. |

**Rückgabewert:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index des neuen Bildeffekts in einer Sammlung.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Fügt den neuen Bi-Level (black/white)-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Der Luminanz-Schwellenwert für den Bi-Level-Effekt. Werte, die größer oder gleich dem Schwellenwert sind, werden auf Weiß gesetzt. Werte kleiner als der Schwellenwert werden auf Schwarz gesetzt. |

**Rückgabewert:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index des neuen Bildeffekts in einer Sammlung.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Fügt den neuen Blur-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| radius | double | Der Radius der Unschärfe. |
| grow | boolean | Gibt an, ob die Begrenzungen des Objekts durch das Weichzeichnen vergrößert werden sollen. True bedeutet, dass die Begrenzungen vergrößert werden, während false bedeutet, dass sie nicht vergrößert werden. |

**Rückgabewert:**
[IBlur](../../com.aspose.slides/iblur) - Index des neuen Bildeffekts in einer Sammlung.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Fügt den neuen Color Change-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index des neuen Bildeffekts in einer Sammlung.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Fügt den neuen Color Replacement-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index des neuen Bildeffekts in einer Sammlung.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Fügt den neuen Duotone-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IDuotone](../../com.aspose.slides/iduotone) - Index des neuen Bildeffekts in einer Sammlung.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Fügt den neuen Fill Overlay-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index des neuen Bildeffekts in einer Sammlung.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Fügt den neuen Gray Scale-Effekt am Ende einer Sammlung hinzu.

**Rückgabewert:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index des neuen Bildeffekts in einer Sammlung.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Fügt den neuen Hue/Saturation/Luminance-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hue | float | Die Anzahl der Grad, um die der Farbton angepasst wird. |
| saturation | float | Der Prozentsatz, um den die Sättigung angepasst wird. |
| luminance | float | Der Prozentsatz, um den die Luminanz angepasst wird. |

**Rückgabewert:**
[IHSL](../../com.aspose.slides/ihsl) - Index des neuen Bildeffekts in einer Sammlung.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Fügt den neuen Luminance-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | float | Der Prozentsatz, um den die Helligkeit geändert wird. |
| contrast | float | Der Prozentsatz, um den der Kontrast geändert wird. |

**Rückgabewert:**
[ILuminance](../../com.aspose.slides/iluminance) - Index des neuen Bildeffekts in einer Sammlung.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Fügt den neuen Tint-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hue | float | Der Farbton, zu dem getönt wird. |
| amount | float | Gibt an, um wie viel der Farbwert verschoben wird. |

**Rückgabewert:**
[ITint](../../com.aspose.slides/itint) - Index des neuen Bildeffekts in einer Sammlung.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Fügt den neuen BrightnessContrast-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | float | Der Prozentsatz, um den die Helligkeit geändert wird. |
| contrast | float | Der Prozentsatz, um den der Kontrast geändert wird. |

**Rückgabewert:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index des neuen Bildeffekts in einer Sammlung.