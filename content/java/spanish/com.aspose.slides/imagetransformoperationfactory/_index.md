---
title: ImageTransformOperationFactory
second_title: Referencia de la API de Aspose.Slides para Java
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

Para compatibilidad con COM.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Crea efecto Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Crea efecto Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Crea efecto Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Crea efecto Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Crea efecto Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Crea efecto Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Crea efecto Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Crea efecto BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Crea efecto Blur. |
| [createColorChange()](#createColorChange--) | Crea efecto Color change. |
| [createColorReplace()](#createColorReplace--) | Crea efecto Color replace. |
| [createDuotone()](#createDuotone--) | Crea efecto Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Crea efecto Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Crea efecto Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Crea efecto Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Crea efecto Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Crea efecto Tint. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Crea efecto Alpha BiLevel.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | Umbral. |

**Devuelve:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Efecto Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Crea efecto Alpha Ceiling.

**Devuelve:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Efecto Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Crea efecto Alpha floor.

**Devuelve:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Efecto Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Crea efecto Alpha inverse.

**Devuelve:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Efecto Alpha inverse.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Crea efecto Alpha modulate.

**Devuelve:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Efecto Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Crea efecto Alpha modulate fixed.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| amount | float | Cantidad. |

**Devuelve:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Efecto Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Crea efecto Alpha replace.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | float | Alpha |

**Devuelve:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Efecto Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


Crea efecto BiLevel.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | Umbral. |

**Devuelve:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Efecto BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Crea efecto Blur.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radius | double | Radio. |
| grow | boolean | Crecer. |

**Devuelve:**
[IBlur](../../com.aspose.slides/iblur) - Efecto Blur.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Crea efecto Color change.

**Devuelve:**
[IColorChange](../../com.aspose.slides/icolorchange) - Efecto Color change.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Crea efecto Color replace.

**Devuelve:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Efecto Color replace.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Crea efecto Duotone.

**Devuelve:**
[IDuotone](../../com.aspose.slides/iduotone) - Efecto Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Crea efecto Fill overlay.

**Devuelve:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Efecto Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Crea efecto Gray scale.

**Devuelve:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Efecto Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Crea efecto Hue Saturation Luminance.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | Tono. |
| saturation | float | Saturación. |
| luminance | float | Luminancia. |

**Devuelve:**
[IHSL](../../com.aspose.slides/ihsl) - Efecto HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Crea efecto Luminance.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | float | Brillo. |
| contrast | float | Contraste. |

**Devuelve:**
[ILuminance](../../com.aspose.slides/iluminance) - Efecto Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Crea efecto Tint.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | Tono. |
| amount | float | Cantidad. |

**Devuelve:**
[ITint](../../com.aspose.slides/itint) - Efecto Tint.