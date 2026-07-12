---
title: ImageTransformOperationCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet werden.
type: docs
url: /de/com.aspose.slides/imagetransformoperationcollection/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Gibt ein [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) aus der Sammlung anhand seines Index zurück. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Bildeffekt aus einer Sammlung am angegebenen Index. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Fügt den neuen Alpha-Bi-Level-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Fügt den neuen Alpha-Ceiling-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Fügt den neuen Alpha-Floor-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Fügt den neuen Alpha-Inverse-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Fügt den neuen Alpha-Modulate-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Fügt den neuen Alpha-Modulate-Fixed-Effekt am Ende einer Sammlung hinzu. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Fügt den neuen Alpha-Replace-Effekt am Ende einer Sammlung hinzu. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Fügt den neuen Bi-Level-(schwarz/weiß)-Effekt am Ende einer Sammlung hinzu. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Fügt den neuen Unschärfe-Effekt am Ende einer Sammlung hinzu. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Fügt den neuen Farbwechsel-Effekt am Ende einer Sammlung hinzu. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Fügt den neuen Farb-Ersetzungs-Effekt am Ende einer Sammlung hinzu. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Fügt den neuen Duotone-Effekt am Ende einer Sammlung hinzu. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Fügt den neuen Fill-Overlay-Effekt am Ende einer Sammlung hinzu. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Fügt den neuen Graustufen-Effekt am Ende einer Sammlung hinzu. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Fügt den neuen Hue/Saturation/Luminance-Effekt am Ende einer Sammlung hinzu. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Fügt den neuen Luminanz-Effekt am Ende einer Sammlung hinzu. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Fügt den neuen Farbton-Effekt am Ende einer Sammlung hinzu. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Fügt den neuen BrightnessContrast-Effekt am Ende einer Sammlung hinzu. |
| [size()](#size--) | Gibt die Anzahl der Bildeffekte in einer Sammlung zurück. |
| [isReadOnly()](#isReadOnly--) | Liefert einen Wert, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) nur lesbar ist. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Fügt den neuen Bildeffekt am Ende einer Sammlung hinzu. |
| [clear()](#clear--) | Entfernt alle Bildeffekte aus einer Sammlung. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbarer long.

**Rückgabe:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Gibt ein [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) aus der Sammlung anhand seines Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabe:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Das [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)-Objekt.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt einen Bildeffekt aus einer Sammlung am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu löschenden Bildeffekts. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Fügt den neuen Alpha-Bi-Level-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Der Schwellenwert für den Alpha-Bi-Level-Effekt. |

**Rückgabe:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index des neuen Bildeffekts in der Sammlung.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Fügt den neuen Alpha-Ceiling-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index des neuen Bildeffekts in der Sammlung.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Fügt den neuen Alpha-Floor-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index des neuen Bildeffekts in der Sammlung.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Fügt den neuen Alpha-Inverse-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index des neuen Bildeffekts in der Sammlung.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Fügt den neuen Alpha-Modulate-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index des neuen Bildeffekts in der Sammlung.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Fügt den neuen Alpha-Modulate-Fixed-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| amount | float | Der prozentuale Betrag, um den das Alpha skaliert wird. |

**Rückgabe:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index des neuen Bildeffekts in der Sammlung.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Fügt den neuen Alpha-Replace-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha | float | Der neue Transparenzwert. |

**Rückgabe:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index des neuen Bildeffekts in der Sammlung.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Fügt den neuen Bi-Level-(schwarz/weiß)-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Der Luminanz-Schwellenwert für den Bi-Level-Effekt. Werte ≥ Schwellenwert werden zu Weiß, Werte < Schwellenwert zu Schwarz. |

**Rückgabe:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index des neuen Bildeffekts in der Sammlung.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Fügt den neuen Unschärfe-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| radius | double | Der Radius der Unschärfe. |
| grow | boolean | Gibt an, ob die Begrenzungen des Objekts durch das Weichzeichnen vergrößert werden sollen. True bedeutet Vergrößerung, false keine. |

**Rückgabe:**
[IBlur](../../com.aspose.slides/iblur) - Index des neuen Bildeffekts in der Sammlung.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Fügt den neuen Farbwechsel-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index des neuen Bildeffekts in der Sammlung.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Fügt den neuen Farb-Ersetzungs-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index des neuen Bildeffekts in der Sammlung.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Fügt den neuen Duotone-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IDuotone](../../com.aspose.slides/iduotone) - Index des neuen Bildeffekts in der Sammlung.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Fügt den neuen Fill-Overlay-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index des neuen Bildeffekts in der Sammlung.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Fügt den neuen Graustufen-Effekt am Ende einer Sammlung hinzu.

**Rückgabe:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index des neuen Bildeffekts in der Sammlung.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Fügt den neuen Hue/Saturation/Luminance-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hue | float | Die Anzahl der Grad, um die der Farbton angepasst wird. |
| saturation | float | Der Prozentsatz, um den die Sättigung angepasst wird. |
| luminance | float | Der Prozentsatz, um den die Luminanz angepasst wird. |

**Rückgabe:**
[IHSL](../../com.aspose.slides/ihsl) - Index des neuen Bildeffekts in der Sammlung.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Fügt den neuen Luminanz-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | float | Der Prozentsatz zur Änderung der Helligkeit. |
| contrast | float | Der Prozentsatz zur Änderung des Kontrasts. |

**Rückgabe:**
[ILuminance](../../com.aspose.slides/iluminance) - Index des neuen Bildeffekts in der Sammlung.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Fügt den neuen Farbton-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hue | float | Der Farbton, zu dem getönt werden soll. |
| amount | float | Gibt an, um wie viel der Farbwert verschoben wird. |

**Rückgabe:**
[ITint](../../com.aspose.slides/itint) - Index des neuen Bildeffekts in der Sammlung.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Fügt den neuen BrightnessContrast-Effekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | float | Der Prozentsatz zur Änderung der Helligkeit. |
| contrast | float | Der Prozentsatz zur Änderung des Kontrasts. |

**Rückgabe:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index des neuen Bildeffekts in der Sammlung.

### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Bildeffekte in einer Sammlung zurück. Nur lesbarer int.

**Rückgabe:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Liefert einen Wert, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) nur lesbar ist. Nur lesbar boolean.

**Rückgabe:**
boolean – true, wenn [IGenericCollection](../../com.aspose.slides/igenericcollection) nur lesbar ist; andernfalls false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Fügt den neuen Bildeffekt am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Der hinzuzufügende Bildeffekt. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Bildeffekte aus einer Sammlung.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Das zu findende Objekt in [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabe:**
boolean – true, wenn das Element in [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wurde; andernfalls false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Das eindimensionale Array, das die kopierten Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) erhält. Das Array muss nullbasierte Indizierung besitzen. |
| arrayIndex | int | Der nullbasierte Index im Array, an dem das Kopieren beginnt. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Das zu entfernende Objekt aus [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabe:**
boolean – true, wenn das Element erfolgreich aus [IGenericCollection](../../com.aspose.slides/igenericcollection) entfernt wurde; andernfalls false. Diese Methode liefert ebenfalls false, wenn das Element im ursprünglichen [IGenericCollection](../../com.aspose.slides/igenericcollection) nicht gefunden wird.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> – Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> – Ein java.util.Iterator für die gesamte Sammlung.