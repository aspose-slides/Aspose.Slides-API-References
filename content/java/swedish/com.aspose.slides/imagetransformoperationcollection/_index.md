---
title: ImageTransformOperationCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av effekter som tillämpas på en bild.
type: docs
url: /sv/com.aspose.slides/imagetransformoperationcollection/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Representerar en samling av effekter som tillämpas på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Returnerar en [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) från samlingen efter dess index. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en bild-effekt från en samling på det angivna indexet. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Lägger till den nya Alpha Bi-Level-effekten i slutet av en samling. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Lägger till den nya Alpha Ceiling-effekten i slutet av en samling. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Lägger till den nya Alpha Floor-effekten i slutet av en samling. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Lägger till den nya Alpha Inverse-effekten i slutet av en samling. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Lägger till den nya Alpha Modulate-effekten i slutet av en samling. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Lägger till den nya Alpha Modulate Fixed-effekten i slutet av en samling. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Lägger till den nya Alpha Replace-effekten i slutet av en samling. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Lägger till den nya Bi-Level (svart/vitt)-effekten i slutet av en samling. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Lägger till den nya Blur-effekten i slutet av en samling. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Lägger till den nya Color Change-effekten i slutet av en samling. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Lägger till den nya Color Replacement-effekten i slutet av en samling. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Lägger till den nya Duotone-effekten i slutet av en samling. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Lägger till den nya Fill Overlay-effekten i slutet av en samling. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Lägger till den nya Gray Scale-effekten i slutet av en samling. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Lägger till den nya Hue/Saturation/Luminance-effekten i slutet av en samling. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Lägger till den nya Luminance-effekten i slutet av en samling. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Lägger till den nya Tint-effekten i slutet av en samling. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Lägger till den nya BrightnessContrast-effekten i slutet av en samling. |
| [size()](#size--) | Returnerar antalet bild-effekter i en samling. |
| [isReadOnly()](#isReadOnly--) | Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Lägger till den nya bild-effekten i slutet av en samling. |
| [clear()](#clear--) | Tar bort alla bild-effekter från en samling. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Avgör om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med början vid ett specifikt Array-index. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Tar bort den första förekomsten av ett specifikt objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Läs-endast long.

**Returnerar:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Returnerar en [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) från samlingen efter dess index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet. |

**Returnerar:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)-objektet.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort en bild-effekt från en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en bild-effekt som ska tas bort. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Lägger till den nya Alpha Bi-Level-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Tröskelvärdet för alpha bi-level-effekten. |

**Returnerar:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index för den nya bild-effekten i en samling.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Lägger till den nya Alpha Ceiling-effekten i slutet av en samling.

**Returnerar:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index för den nya bild-effekten i en samling.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Lägger till den nya Alpha Floor-effekten i slutet av en samling.

**Returnerar:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index för den nya bild-effekten i en samling.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Lägger till den nya Alpha Inverse-effekten i slutet av en samling.

**Returnerar:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index för den nya bild-effekten i en samling.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Lägger till den nya Alpha Modulate-effekten i slutet av en samling.

**Returnerar:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index för den nya bild-effekten i en samling.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Lägger till den nya Alpha Modulate Fixed-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| amount | float | Procentandelen för att skala alphan. |

**Returnerar:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index för den nya bild-effekten i en samling.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Lägger till den nya Alpha Replace-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | float | Det nya opacitetsvärdet. |

**Returnerar:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index för den nya bild-effekten i en samling.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Lägger till den nya Bi-Level (svart/vitt)-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Luminans-tröskeln för Bi-Level-effekten. Värden större än eller lika med tröskeln blir vita. Värden lägre än tröskeln blir svarta. |

**Returnerar:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index för den nya bild-effekten i en samling.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Lägger till den nya Blur-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radius | double | Radien för suddigheten. |
| grow | boolean | Anger om objektets gränser ska utökas som en följd av suddigheten. true betyder att gränserna utökas, false betyder att de inte gör det. |

**Returnerar:**
[IBlur](../../com.aspose.slides/iblur) - Index för den nya bild-effekten i en samling.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Lägger till den nya Color Change-effekten i slutet av en samling.

**Returnerar:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index för den nya bild-effekten i en samling.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Lägger till den nya Color Replacement-effekten i slutet av en samling.

**Returnerar:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index för den nya bild-effekten i en samling.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Lägger till den nya Duotone-effekten i slutet av en samling.

**Returnerar:**
[IDuotone](../../com.aspose.slides/iduotone) - Index för den nya bild-effekten i en samling.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Lägger till den nya Fill Overlay-effekten i slutet av en samling.

**Returnerar:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index för den nya bild-effekten i en samling.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Lägger till den nya Gray Scale-effekten i slutet av en samling.

**Returnerar:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index för den nya bild-effekten i en samling.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Lägger till den nya Hue/Saturation/Luminance-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hue | float | Antalet grader som färgtonen justeras med. |
| saturation | float | Procenten som mättnaden justeras med. |
| luminance | float | Procenten som luminansen justeras med. |

**Returnerar:**
[IHSL](../../com.aspose.slides/ihsl) - Index för den nya bild-effekten i en samling.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Lägger till den nya Luminance-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | float | Procenten för att ändra ljusstyrkan. |
| contrast | float | Procenten för att ändra kontrasten. |

**Returnerar:**
[ILuminance](../../com.aspose.slides/iluminance) - Index för den nya bild-effekten i en samling.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Lägger till den nya Tint-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hue | float | Färgtonen som ska färgas mot. |
| amount | float | Anger hur mycket färgvärdet ska förskjutas. |

**Returnerar:**
[ITint](../../com.aspose.slides/itint) - Index för den nya bild-effekten i en samling.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Lägger till den nya BrightnessContrast-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | float | Procenten för att ändra ljusstyrkan. |
| contrast | float | Procenten för att ändra kontrasten. |

**Returnerar:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index för den nya bild-effekten i en samling.

### size() {#size--}
```
public final int size()
```

Returnerar antalet bild-effekter i en samling. Läs-endast int.

**Returnerar:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. Läs-endast boolean.

**Returnerar:**
boolean - true om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad; annars false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Lägger till den nya bild-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Bild-effekten som ska läggas till i slutet av en samling. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla bild-effekter från en samling.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Avgör om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Objektet som ska sökas i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om objektet finns i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med början vid ett specifikt Array-index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Den endimensionella Array som är destinationen för elementen kopierade från [IGenericCollection](../../com.aspose.slides/igenericcollection). Array-en måste ha noll-baserad indexering. |
| arrayIndex | int | Det noll-baserade indexet i array där kopieringen börjar. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Tar bort den första förekomsten av ett specifikt objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Objektet som ska tas bort från [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om  item  togs bort framgångsrikt från [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false. Denna metod returnerar också false om item inte finns i den ursprungliga [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - En IGenericEnumerator som kan användas för att iterera genom samlingen.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - En java.util.Iterator för hela samlingen.