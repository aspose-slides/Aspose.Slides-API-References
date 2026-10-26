---
title: IImageTransformOperationCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av effekter som tillämpas på en bild.
type: docs
url: /sv/com.aspose.slides/iimagetransformoperationcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Representerar en samling av effekter som tillämpas på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar ett [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) från samlingen enligt dess index. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en bild-effekt från en samling på angivet index. |
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
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Returnerar ett [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) från samlingen enligt dess index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för objektet. |

**Returnerar:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) – [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)-objektet.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort en bild-effekt från en samling på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den bild-effekt som ska tas bort. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Lägger till den nya Alpha Bi-Level-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Tröskelvärdet för Alpha Bi-Level-effekten. |

**Returnerar:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) – Index för den nya bild-effekten i samlingen.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Lägger till den nya Alpha Ceiling-effekten i slutet av en samling.

**Returnerar:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) – Index för den nya bild-effekten i samlingen.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Lägger till den nya Alpha Floor-effekten i slutet av en samling.

**Returnerar:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) – Index för den nya bild-effekten i samlingen.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Lägger till den nya Alpha Inverse-effekten i slutet av en samling.

**Returnerar:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) – Index för den nya bild-effekten i samlingen.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Lägger till den nya Alpha Modulate-effekten i slutet av en samling.

**Returnerar:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) – Index för den nya bild-effekten i samlingen.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Lägger till den nya Alpha Modulate Fixed-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| amount | float | Procentandelen för att skala alphan. |

**Returnerar:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) – Index för den nya bild-effekten i samlingen.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Lägger till den nya Alpha Replace-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | float | Det nya opacitetsvärdet. |

**Returnerar:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) – Index för den nya bild-effekten i samlingen.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Lägger till den nya Bi-Level (svart/vitt)-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Luminanströskeln för Bi-Level-effekten. Värden som är större än eller lika med tröskeln sätts till vitt. Värden som är mindre än tröskeln sätts till svart. |

**Returnerar:**
[IBiLevel](../../com.aspose.slides/ibilevel) – Index för den nya bild-effekten i samlingen.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Lägger till den nya Blur-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radius | double | Blur-radien. |
| grow | boolean | Anger om objektets begränsningar ska växa som ett resultat av suddigheten. Sant betyder att begränsningarna växer, falskt betyder att de inte gör det. |

**Returnerar:**
[IBlur](../../com.aspose.slides/iblur) – Index för den nya bild-effekten i samlingen.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Lägger till den nya Color Change-effekten i slutet av en samling.

**Returnerar:**
[IColorChange](../../com.aspose.slides/icolorchange) – Index för den nya bild-effekten i samlingen.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Lägger till den nya Color Replacement-effekten i slutet av en samling.

**Returnerar:**
[IColorReplace](../../com.aspose.slides/icolorreplace) – Index för den nya bild-effekten i samlingen.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Lägger till den nya Duotone-effekten i slutet av en samling.

**Returnerar:**
[IDuotone](../../com.aspose.slides/iduotone) – Index för den nya bild-effekten i samlingen.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Lägger till den nya Fill Overlay-effekten i slutet av en samling.

**Returnerar:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) – Index för den nya bild-effekten i samlingen.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Lägger till den nya Gray Scale-effekten i slutet av en samling.

**Returnerar:**
[IGrayScale](../../com.aspose.slides/igrayscale) – Index för den nya bild-effekten i samlingen.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Lägger till den nya Hue/Saturation/Luminance-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hue | float | Antalet grader som nyansen justeras. |
| saturation | float | Procentandelen som mättnaden justeras. |
| luminance | float | Procentandelen som luminansen justeras. |

**Returnerar:**
[IHSL](../../com.aspose.slides/ihsl) – Index för den nya bild-effekten i samlingen.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Lägger till den nya Luminance-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | float | Procenten för att ändra ljusstyrkan. |
| contrast | float | Procenten för att ändra kontrasten. |

**Returnerar:**
[ILuminance](../../com.aspose.slides/iluminance) – Index för den nya bild-effekten i samlingen.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Lägger till den nya Tint-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hue | float | Den nyans som färgen ska tonas mot. |
| amount | float | Anger hur mycket färgvärdet ska förskjutas. |

**Returnerar:**
[ITint](../../com.aspose.slides/itint) – Index för den nya bild-effekten i samlingen.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Lägger till den nya BrightnessContrast-effekten i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | float | Procenten för att ändra ljusstyrkan. |
| contrast | float | Procenten för att ändra kontrasten. |

**Returnerar:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) – Index för den nya bild-effekten i samlingen.