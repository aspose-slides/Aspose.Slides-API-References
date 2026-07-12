---
title: IImageTransformOperationCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una colección de efectos aplicados a una imagen.
type: docs
url: /es/com.aspose.slides/iimagetransformoperationcollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Representa una colección de efectos aplicados a una imagen.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve un [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) de la colección por su índice. |
| [removeAt(int index)](#removeAt-int-) | Elimina un efecto de imagen de una colección en el índice especificado. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Agrega el nuevo efecto Alpha Bi-Level al final de una colección. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Agrega el nuevo efecto Alpha Ceiling al final de una colección. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Agrega el nuevo efecto Alpha Floor al final de una colección. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Agrega el nuevo efecto Alpha Inverse al final de una colección. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Agrega el nuevo efecto Alpha Modulate al final de una colección. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Agrega el nuevo efecto Alpha Modulate Fixed al final de una colección. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Agrega el nuevo efecto Alpha Replace al final de una colección. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Agrega el nuevo efecto Bi-Level (blanco/negro) al final de una colección. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Agrega el nuevo efecto Blur al final de una colección. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Agrega el nuevo efecto Color Change al final de una colección. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Agrega el nuevo efecto Color Replacement al final de una colección. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Agrega el nuevo efecto Duotone al final de una colección. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Agrega el nuevo efecto Fill Overlay al final de una colección. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Agrega el nuevo efecto Gray Scale al final de una colección. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Agrega el nuevo efecto Hue/Saturation/Luminance al final de una colección. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Agrega el nuevo efecto Luminance al final de una colección. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Agrega el nuevo efecto Tint al final de una colección. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Agrega el nuevo efecto BrightnessContrast al final de una colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Devuelve un [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) de la colección por su índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - El objeto [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina un efecto de imagen de una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del efecto de imagen que debe eliminarse. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Agrega el nuevo efecto Alpha Bi-Level al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | El valor del umbral para el efecto Alpha Bi-Level. |

**Devuelve:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Índice del nuevo efecto de imagen en una colección.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Agrega el nuevo efecto Alpha Ceiling al final de una colección.

**Devuelve:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Índice del nuevo efecto de imagen en una colección.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Agrega el nuevo efecto Alpha Floor al final de una colección.

**Devuelve:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Índice del nuevo efecto de imagen en una colección.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Agrega el nuevo efecto Alpha Inverse al final de una colección.

**Devuelve:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Índice del nuevo efecto de imagen en una colección.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Agrega el nuevo efecto Alpha Modulate al final de una colección.

**Devuelve:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Índice del nuevo efecto de imagen en una colección.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Agrega el nuevo efecto Alpha Modulate Fixed al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| amount | float | El valor porcentual para escalar el alpha. |

**Devuelve:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Índice del nuevo efecto de imagen en una colección.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Agrega el nuevo efecto Alpha Replace al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | float | El nuevo valor de opacidad. |

**Devuelve:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Índice del nuevo efecto de imagen en una colección.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Agrega el nuevo efecto Bi-Level (blanco/negro) al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | el umbral de luminancia para el efecto Bi-Level. Los valores mayores o iguales al umbral se establecen a blanco. Los valores menores que el umbral se establecen a negro. |

**Devuelve:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Índice del nuevo efecto de imagen en una colección.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Agrega el nuevo efecto Blur al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radius | double | El radio del desenfoque. |
| grow | boolean | Especifica si los límites del objeto deben ampliarse como resultado del desenfoque. True indica que los límites se amplían mientras que false indica que no lo hacen. |

**Devuelve:**
[IBlur](../../com.aspose.slides/iblur) - Índice del nuevo efecto de imagen en una colección.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Agrega el nuevo efecto Color Change al final de una colección.

**Devuelve:**
[IColorChange](../../com.aspose.slides/icolorchange) - Índice del nuevo efecto de imagen en una colección.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Agrega el nuevo efecto Color Replacement al final de una colección.

**Devuelve:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Índice del nuevo efecto de imagen en una colección.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Agrega el nuevo efecto Duotone al final de una colección.

**Devuelve:**
[IDuotone](../../com.aspose.slides/iduotone) - Índice del nuevo efecto de imagen en una colección.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Agrega el nuevo efecto Fill Overlay al final de una colección.

**Devuelve:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Índice del nuevo efecto de imagen en una colección.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Agrega el nuevo efecto Gray Scale al final de una colección.

**Devuelve:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Índice del nuevo efecto de imagen en una colección.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Agrega el nuevo efecto Hue/Saturation/Luminance al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | El número de grados en que se ajusta el hue. |
| saturation | float | El porcentaje en que se ajusta la saturation. |
| luminance | float | El porcentaje en que se ajusta la luminance. |

**Devuelve:**
[IHSL](../../com.aspose.slides/ihsl) - Índice del nuevo efecto de imagen en una colección.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Agrega el nuevo efecto Luminance al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | float | El porcentaje para cambiar el brillo. |
| contrast | float | El porcentaje para cambiar el contraste. |

**Devuelve:**
[ILuminance](../../com.aspose.slides/iluminance) - Índice del nuevo efecto de imagen en una colección.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Agrega el nuevo efecto Tint al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | El tono hacia el cual aplicar el tinte. |
| amount | float | Especifica cuánto se desplaza el valor del color. |

**Devuelve:**
[ITint](../../com.aspose.slides/itint) - Índice del nuevo efecto de imagen en una colección.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Agrega el nuevo efecto BrightnessContrast al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | float | El porcentaje para cambiar el brillo. |
| contrast | float | El porcentaje para cambiar el contraste. |

**Devuelve:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Índice del nuevo efecto de imagen en una colección.