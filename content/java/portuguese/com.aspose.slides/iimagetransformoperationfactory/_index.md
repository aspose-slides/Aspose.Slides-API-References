---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
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
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Cria Alpha BiLevel efeito. |
| [createAlphCeiling()](#createAlphCeiling--) | Cria Alpha Ceiling efeito. |
| [createAlphaFloor()](#createAlphaFloor--) | Cria Alpha floor efeito. |
| [createAlphaInverse()](#createAlphaInverse--) | Cria Alpha inverse efeito. |
| [createAlphaModulate()](#createAlphaModulate--) | Cria Alpha modulate efeito. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Cria Alpha modulate fixed efeito. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Cria Alpha replace efeito. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Cria BiLevel efeito. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Cria Blur efeito. |
| [createColorChange()](#createColorChange--) | Cria Color change efeito. |
| [createColorReplace()](#createColorReplace--) | Cria Color replace efeito. |
| [createDuotone()](#createDuotone--) | Cria Duotone efeito. |
| [createFillOverlay()](#createFillOverlay--) | Cria Fill overlay efeito. |
| [createGrayScale()](#createGrayScale--) | Cria Gray scale efeito. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Cria Hue Saturation Luminance efeito. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Cria Luminance efeito. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Cria Tint efeito. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Cria Alpha BiLevel efeito.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold | float | Limite. |

**Retorna:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel efeito.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Cria Alpha Ceiling efeito.

**Retorna:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling efeito.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Cria Alpha floor efeito.

**Retorna:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor efeito.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Cria Alpha inverse efeito.

**Retorna:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverse efeito.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Cria Alpha modulate efeito.

**Retorna:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate efeito.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Cria Alpha modulate fixed efeito.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| amount | float | Quantidade. |

**Retorna:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed efeito.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Cria Alpha replace efeito.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alpha | float | Alpha |

**Retorna:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace efeito.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Cria BiLevel efeito.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold | float | Limite. |

**Retorna:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel efeito.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Cria Blur efeito.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| radius | double | Raio. |
| grow | boolean | Crescer. |

**Retorna:**
[IBlur](../../com.aspose.slides/iblur) - Blur efeito.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Cria Color change efeito.

**Retorna:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change efeito.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Cria Color replace efeito.

**Retorna:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace efeito.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Cria Duotone efeito.

**Retorna:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone efeito.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Cria Fill overlay efeito.

**Retorna:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay efeito.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Cria Gray scale efeito.

**Retorna:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Retorna gray scale efeito.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Cria Hue Saturation Luminance efeito.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hue | float | Matiz. |
| saturation | float | Saturação. |
| luminance | float | Luminância. |

**Retorna:**
[IHSL](../../com.aspose.slides/ihsl) - HSL efeito.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Cria Luminance efeito.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brightness | float | Brilho. |
| contrast | float | Contraste. |

**Retorna:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance efeito.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Cria Tint efeito.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hue | float | Matiz. |
| amount | float | Quantidade. |

**Retorna:**
[ITint](../../com.aspose.slides/itint) - Tint efeito.