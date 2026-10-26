---
title: ImageTransformOperationFactory
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Permite crear operaciones de transformación de imágenes
type: docs
url: /es/com.aspose.slides/imagetransformoperationfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Permite crear operaciones de transformación de imágenes

--------------------

Para compatibilidad COM.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Crea el efecto Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Crea el efecto Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Crea el efecto Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Crea el efecto Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Crea el efecto Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Crea el efecto Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Crea el efecto Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Crea el efecto BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Crea el efecto Blur. |
| [createColorChange()](#createColorChange--) | Crea el efecto Color change. |
| [createColorReplace()](#createColorReplace--) | Crea el efecto Color replace. |
| [createDuotone()](#createDuotone--) | Crea el efecto Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Crea el efecto Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Crea el efecto Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Crea el efecto Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Crea el efecto Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Crea el efecto Tint. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Crea el efecto Alpha BiLevel.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | Umbral. |

**Devuelve:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - efecto Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Crea el efecto Alpha Ceiling.

**Devuelve:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - efecto Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Crea el efecto Alpha floor.

**Devuelve:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - efecto Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Crea el efecto Alpha inverse.

**Devuelve:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - efecto Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Crea el efecto Alpha modulate.

**Devuelve:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - efecto Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Crea el efecto Alpha modulate fixed.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| amount | float | Cantidad. |

**Devuelve:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - efecto Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Crea el efecto Alpha replace.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | float | Alfa |

**Devuelve:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - efecto Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


Crea el efecto BiLevel.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | Umbral. |

**Devuelve:**
[IBiLevel](../../com.aspose.slides/ibilevel) - efecto BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Crea el efecto Blur.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radius | double | Radio. |
| grow | boolean | Crecer. |

**Devuelve:**
[IBlur](../../com.aspose.slides/iblur) - efecto Blur.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Crea el efecto Color change.

**Devuelve:**
[IColorChange](../../com.aspose.slides/icolorchange) - efecto Color change.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Crea el efecto Color replace.

**Devuelve:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - efecto Color replace.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Crea el efecto Duotone.

**Devuelve:**
[IDuotone](../../com.aspose.slides/iduotone) - efecto Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Crea el efecto Fill overlay.

**Devuelve:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - efecto Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Crea el efecto Gray scale.

**Devuelve:**
[IGrayScale](../../com.aspose.slides/igrayscale) - efecto Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Crea el efecto Hue Saturation Luminance.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | Matiz. |
| saturation | float | Saturación. |
| luminance | float | Luminancia. |

**Devuelve:**
[IHSL](../../com.aspose.slides/ihsl) - efecto HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Crea el efecto Luminance.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | float | Brillo. |
| contrast | float | Contraste. |

**Devuelve:**
[ILuminance](../../com.aspose.slides/iluminance) - efecto Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Crea el efecto Tint.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | Matiz. |
| amount | float | Cantidad. |

**Devuelve:**
[ITint](../../com.aspose.slides/itint) - efecto Tint.