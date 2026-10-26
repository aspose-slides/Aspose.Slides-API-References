---
title: IImageTransformOperationCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de efeitos aplicados a uma imagem.
type: docs
url: /pt/com.aspose.slides/iimagetransformoperationcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Representa uma coleção de efeitos aplicados a uma imagem.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna um [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) da coleção pelo seu índice. |
| [removeAt(int index)](#removeAt-int-) | Remove um efeito de imagem de uma coleção no índice especificado. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Adiciona o novo efeito Alpha Bi-Level ao final de uma coleção. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Adiciona o novo efeito Alpha Ceiling ao final de uma coleção. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Adiciona o novo efeito Alpha Floor ao final de uma coleção. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Adiciona o novo efeito Alpha Inverse ao final de uma coleção. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Adiciona o novo efeito Alpha Modulate ao final de uma coleção. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Adiciona o novo efeito Alpha Modulate Fixed ao final de uma coleção. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Adiciona o novo efeito Alpha Replace ao final de uma coleção. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Adiciona o novo efeito Bi-Level (preto/branco) ao final de uma coleção. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Adiciona o novo efeito Blur ao final de uma coleção. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Adiciona o novo efeito Color Change ao final de uma coleção. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Adiciona o novo efeito Color Replacement ao final de uma coleção. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Adiciona o novo efeito Duotone ao final de uma coleção. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Adiciona o novo efeito Fill Overlay ao final de uma coleção. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Adiciona o novo efeito Gray Scale ao final de uma coleção. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Adiciona o novo efeito Hue/Saturation/Luminance ao final de uma coleção. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Adiciona o novo efeito Luminance ao final de uma coleção. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Adiciona o novo efeito Tint ao final de uma coleção. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Adiciona o novo efeito BrightnessContrast ao final de uma coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Retorna um [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) da coleção pelo seu índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do item. |

**Retorna:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - O objeto [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove um efeito de imagem de uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um efeito de imagem que deve ser excluído. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Adiciona o novo efeito Alpha Bi-Level ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold | float | O valor de limiar para o efeito alpha bi-level. |

**Retorna:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Índice do novo efeito de imagem em uma coleção.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Adiciona o novo efeito Alpha Ceiling ao final de uma coleção.

**Retorna:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Índice do novo efeito de imagem em uma coleção.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Adiciona o novo efeito Alpha Floor ao final de uma coleção.

**Retorna:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Índice do novo efeito de imagem em uma coleção.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Adiciona o novo efeito Alpha Inverse ao final de uma coleção.

**Retorna:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Índice do novo efeito de imagem em uma coleção.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Adiciona o novo efeito Alpha Modulate ao final de uma coleção.

**Retorna:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Índice do novo efeito de imagem em uma coleção.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Adiciona o novo efeito Alpha Modulate Fixed ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| amount | float | A quantidade percentual para escalar o alpha. |

**Retorna:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Índice do novo efeito de imagem em uma coleção.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Adiciona o novo efeito Alpha Replace ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alpha | float | O novo valor de opacidade. |

**Retorna:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Índice do novo efeito de imagem em uma coleção.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Adiciona o novo efeito Bi-Level (preto/branco) ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold | float | O limiar de luminância para o efeito Bi-Level. Valores maiores ou iguais ao limiar são definidos como branco. Valores menores que o limiar são definidos como preto. |

**Retorna:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Índice do novo efeito de imagem em uma coleção.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Adiciona o novo efeito Blur ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| radius | double | O raio do desfoque. |
| grow | boolean | Especifica se os limites do objeto devem ser aumentados como resultado do desfoque. True indica que os limites são aumentados, enquanto false indica que não são. |

**Retorna:**
[IBlur](../../com.aspose.slides/iblur) - Índice do novo efeito de imagem em uma coleção.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Adiciona o novo efeito Color Change ao final de uma coleção.

**Retorna:**
[IColorChange](../../com.aspose.slides/icolorchange) - Índice do novo efeito de imagem em uma coleção.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Adiciona o novo efeito Color Replacement ao final de uma coleção.

**Retorna:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Índice do novo efeito de imagem em uma coleção.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Adiciona o novo efeito Duotone ao final de uma coleção.

**Retorna:**
[IDuotone](../../com.aspose.slides/iduotone) - Índice do novo efeito de imagem em uma coleção.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Adiciona o novo efeito Fill Overlay ao final de uma coleção.

**Retorna:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Índice do novo efeito de imagem em uma coleção.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Adiciona o novo efeito Gray Scale ao final de uma coleção.

**Retorna:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Índice do novo efeito de imagem em uma coleção.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Adiciona o novo efeito Hue/Saturation/Luminance ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hue | float | O número de graus pelos quais o matiz é ajustado. |
| saturation | float | A porcentagem pela qual a saturação é ajustada. |
| luminance | float | A porcentagem pela qual a luminância é ajustada. |

**Retorna:**
[IHSL](../../com.aspose.slides/ihsl) - Índice do novo efeito de imagem em uma coleção.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Adiciona o novo efeito Luminance ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brightness | float | A porcentagem para mudar o brilho. |
| contrast | float | A porcentagem para mudar o contraste. |

**Retorna:**
[ILuminance](../../com.aspose.slides/iluminance) - Índice do novo efeito de imagem em uma coleção.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Adiciona o novo efeito Tint ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hue | float | O matiz em direção ao qual tintar. |
| amount | float | Especifica o quanto o valor da cor é deslocado. |

**Retorna:**
[ITint](../../com.aspose.slides/itint) - Índice do novo efeito de imagem em uma coleção.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Adiciona o novo efeito BrightnessContrast ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brightness | float | A porcentagem para mudar o brilho. |
| contrast | float | A porcentagem para mudar o contraste. |

**Retorna:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Índice do novo efeito de imagem em uma coleção.