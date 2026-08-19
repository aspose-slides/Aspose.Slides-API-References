---
title: IImageTransformOperationCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di effetti applicati a un'immagine.
type: docs
url: /it/com.aspose.slides/iimagetransformoperationcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Rappresenta una collezione di effetti applicati a un'immagine.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce un [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) dalla collezione per il suo indice. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un effetto immagine da una collezione all'indice specificato. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Aggiunge il nuovo effetto Alpha Bi-Level alla fine di una collezione. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Aggiunge il nuovo effetto Alpha Ceiling alla fine di una collezione. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Aggiunge il nuovo effetto Alpha Floor alla fine di una collezione. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Aggiunge il nuovo effetto Alpha Inverse alla fine di una collezione. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Aggiunge il nuovo effetto Alpha Modulate alla fine di una collezione. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Aggiunge il nuovo effetto Alpha Modulate Fixed alla fine di una collezione. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Aggiunge il nuovo effetto Alpha Replace alla fine di una collezione. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Aggiunge il nuovo effetto Bi-Level (bianco/nero) alla fine di una collezione. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Aggiunge il nuovo effetto Blur alla fine di una collezione. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Aggiunge il nuovo effetto Color Change alla fine di una collezione. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Aggiunge il nuovo effetto Color Replacement alla fine di una collezione. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Aggiunge il nuovo effetto Duotone alla fine di una collezione. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Aggiunge il nuovo effetto Fill Overlay alla fine di una collezione. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Aggiunge il nuovo effetto Gray Scale alla fine di una collezione. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Aggiunge il nuovo effetto Hue/Saturation/Luminance alla fine di una collezione. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Aggiunge il nuovo effetto Luminance alla fine di una collezione. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Aggiunge il nuovo effetto Tint alla fine di una collezione. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Aggiunge il nuovo effetto BrightnessContrast alla fine di una collezione. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Restituisce un [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) dalla collezione per il suo indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - L'oggetto [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove un effetto immagine da una collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un effetto immagine da eliminare. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Aggiunge il nuovo effetto Alpha Bi-Level alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | Il valore di soglia per l'effetto Alpha Bi-Level. |

**Restituisce:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Indice del nuovo effetto immagine nella collezione.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Aggiunge il nuovo effetto Alpha Ceiling alla fine di una collezione.

**Restituisce:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Indice del nuovo effetto immagine nella collezione.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Aggiunge il nuovo effetto Alpha Floor alla fine di una collezione.

**Restituisce:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Indice del nuovo effetto immagine nella collezione.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Aggiunge il nuovo effetto Alpha Inverse alla fine di una collezione.

**Restituisce:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Indice del nuovo effetto immagine nella collezione.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Aggiunge il nuovo effetto Alpha Modulate alla fine di una collezione.

**Restituisce:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Indice del nuovo effetto immagine nella collezione.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Aggiunge il nuovo effetto Alpha Modulate Fixed alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| amount | float | La percentuale di scala per l'alpha. |

**Restituisce:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Indice del nuovo effetto immagine nella collezione.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Aggiunge il nuovo effetto Alpha Replace alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | float | Il nuovo valore di opacità. |

**Restituisce:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Indice del nuovo effetto immagine nella collezione.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Aggiunge il nuovo effetto Bi-Level (bianco/nero) alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | La soglia di luminanza per l'effetto Bi-Level. I valori maggiori o uguali alla soglia sono impostati a bianco. I valori minori della soglia sono impostati a nero. |

**Restituisce:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Indice del nuovo effetto immagine nella collezione.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Aggiunge il nuovo effetto Blur alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radius | double | Il raggio della sfocatura. |
| grow | boolean | Specifica se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. True indica che i limiti sono ampliati, false indica che non lo sono. |

**Restituisce:**
[IBlur](../../com.aspose.slides/iblur) - Indice del nuovo effetto immagine nella collezione.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Aggiunge il nuovo effetto Color Change alla fine di una collezione.

**Restituisce:**
[IColorChange](../../com.aspose.slides/icolorchange) - Indice del nuovo effetto immagine nella collezione.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Aggiunge il nuovo effetto Color Replacement alla fine di una collezione.

**Restituisce:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Indice del nuovo effetto immagine nella collezione.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Aggiunge il nuovo effetto Duotone alla fine di una collezione.

**Restituisce:**
[IDuotone](../../com.aspose.slides/iduotone) - Indice del nuovo effetto immagine nella collezione.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Aggiunge il nuovo effetto Fill Overlay alla fine di una collezione.

**Restituisce:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Indice del nuovo effetto immagine nella collezione.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Aggiunge il nuovo effetto Gray Scale alla fine di una collezione.

**Restituisce:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Indice del nuovo effetto immagine nella collezione.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Aggiunge il nuovo effetto Hue/Saturation/Luminance alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Il numero di gradi di cui è regolato il tono. |
| saturation | float | La percentuale di cui è regolata la saturazione. |
| luminance | float | La percentuale di cui è regolata la luminanza. |

**Restituisce:**
[IHSL](../../com.aspose.slides/ihsl) - Indice del nuovo effetto immagine nella collezione.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Aggiunge il nuovo effetto Luminance alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | float | La percentuale di variazione della luminosità. |
| contrast | float | La percentuale di variazione del contrasto. |

**Restituisce:**
[ILuminance](../../com.aspose.slides/iluminance) - Indice del nuovo effetto immagine nella collezione.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Aggiunge il nuovo effetto Tint alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Il tono verso cui tinteggiare. |
| amount | float | Specifica di quanto il valore del colore è spostato. |

**Restituisce:**
[ITint](../../com.aspose.slides/itint) - Indice del nuovo effetto immagine nella collezione.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Aggiunge il nuovo effetto BrightnessContrast alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | float | La percentuale di variazione della luminosità. |
| contrast | float | La percentuale di variazione del contrasto. |

**Restituisce:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Indice del nuovo effetto immagine nella collezione.