---
title: IImageTransformOperationFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar instâncias de efeitos de imagem
type: docs
url: /pt/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Permite criar instâncias de efeitos de imagem

--------------------

Para interface COM.
## Métodos

| Método | Descrição |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Cria efeito Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Cria efeito Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Cria efeito Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Cria efeito Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Cria efeito Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Cria efeito Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Cria efeito Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Cria efeito BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Cria efeito Blur. |
| [createColorChange()](#createColorChange--) | Cria efeito Color change. |
| [createColorReplace()](#createColorReplace--) | Cria efeito Color replace. |
| [createDuotone()](#createDuotone--) | Cria efeito Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Cria efeito Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Cria efeito Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Cria efeito Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Cria efeito Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Cria efeito Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Cria efeito Alpha BiLevel.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold | float | Limite. |

**Retorna:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - efeito Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Cria efeito Alpha Ceiling.

**Retorna:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - efeito Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Cria efeito Alpha floor.

**Retorna:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - efeito Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Cria efeito Alpha inverse.

**Retorna:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - efeito Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Cria efeito Alpha modulate.

**Retorna:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - efeito Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Cria efeito Alpha modulate fixed.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| amount | float | Quantidade. |

**Retorna:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - efeito Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Cria efeito Alpha replace.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alpha | float | Alpha |

**Retorna:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - efeito Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Cria efeito BiLevel.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold | float | Limite. |

**Retorna:**
[IBiLevel](../../com.aspose.slides/ibilevel) - efeito BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Cria efeito Blur.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| radius | double | Raio. |
| grow | boolean | Grow. |

**Retorna:**
[IBlur](../../com.aspose.slides/iblur) - efeito Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Cria efeito Color change.

**Retorna:**
[IColorChange](../../com.aspose.slides/icolorchange) - efeito Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Cria efeito Color replace.

**Retorna:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - efeito Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Cria efeito Duotone.

**Retorna:**
[IDuotone](../../com.aspose.slides/iduotone) - efeito Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Cria efeito Fill overlay.

**Retorna:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - efeito Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Cria efeito Gray scale.

**Retorna:**
[IGrayScale](../../com.aspose.slides/igrayscale) - efeito Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Cria efeito Hue Saturation Luminance.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Retorna:**
[IHSL](../../com.aspose.slides/ihsl) - efeito HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Cria efeito Luminance.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Retorna:**
[ILuminance](../../com.aspose.slides/iluminance) - efeito Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Cria efeito Tint.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Quantidade. |

**Retorna:**
[ITint](../../com.aspose.slides/itint) - efeito Tint.