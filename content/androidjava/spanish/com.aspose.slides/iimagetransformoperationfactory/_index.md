---
title: IImageTransformOperationFactory
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Permite crear instancias de efectos de imagen
type: docs
url: /es/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Permite crear instancias de efectos de imagen

--------------------

Para la interfaz COM.
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
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
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
public abstract IAlphaCeiling createAlphCeiling()
```

Crea el efecto Alpha Ceiling.

**Devuelve:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - efecto Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Crea el efecto Alpha floor.

**Devuelve:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - efecto Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Crea el efecto Alpha inverse.

**Devuelve:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - efecto Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Crea el efecto Alpha modulate.

**Devuelve:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - efecto Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
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
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Crea el efecto Alpha replace.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | float | Alpha |

**Devuelve:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - efecto Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
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
public abstract IBlur createBlur(double radius, boolean grow)
```

Crea el efecto Blur.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radius | double | Radio. |
| grow | boolean | Crecimiento. |

**Devuelve:**
[IBlur](../../com.aspose.slides/iblur) - efecto Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Crea el efecto Color change.

**Devuelve:**
[IColorChange](../../com.aspose.slides/icolorchange) - efecto Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Crea el efecto Color replace.

**Devuelve:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - efecto Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Crea el efecto Duotone.

**Devuelve:**
[IDuotone](../../com.aspose.slides/iduotone) - efecto Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Crea el efecto Fill overlay.

**Devuelve:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - efecto Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Crea el efecto Gray scale.

**Devuelve:**
[IGrayScale](../../com.aspose.slides/igrayscale) - devuelve el efecto Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Crea el efecto Hue Saturation Luminance.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Devuelve:**
[IHSL](../../com.aspose.slides/ihsl) - efecto HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
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
public abstract ITint createTint(float hue, float amount)
```

Crea el efecto Tint.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Cantidad. |

**Devuelve:**
[ITint](../../com.aspose.slides/itint) - efecto Tint.