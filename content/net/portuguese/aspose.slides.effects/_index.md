---
title: Aspose.Slides.Effects
second_title: Referência da API Aspose.Sildes para .NET
description: Contém classes para trabalhar com vários efeitos em apresentações do Microsoft PowerPoint.
type: docs
weight: 60
url: /pt/aspose.slides.effects/
---
Contém classes para trabalhar com vários efeitos em apresentações do Microsoft PowerPoint.

## Classes

| Class | Description |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Representa um efeito Alpha Bi-Level. Valores Alpha (Opacity) menores que o limiar são alterados para 0 (totalmente transparente) e valores alpha maiores ou iguais ao limiar são alterados para 100% (totalmente opaco). |
| [AlphaCeiling](./alphaceiling) | Representa um efeito Alpha Ceiling. Valores Alpha (opacity) maiores que zero são alterados para 100%. Em outras palavras, tudo que é parcialmente opaco torna-se totalmente opaco. |
| [AlphaFloor](./alphafloor) | Representa um efeito Alpha Floor. Valores Alpha (opacity) menores que 100% são alterados para zero. Em outras palavras, tudo que é parcialmente transparente torna-se totalmente transparente. |
| [AlphaInverse](./alphainverse) | Representa um efeito Alpha Inverse. Valores Alpha (opacity) são invertidos subtraindo de 100%. |
| [AlphaModulate](./alphamodulate) | Representa um efeito Alpha Modulate. Valores alpha (opacity) do efeito são multiplicados por uma porcentagem fixa. O contêiner do efeito especifica um efeito que contém valores alpha a serem modulados. |
| [AlphaModulateFixed](./alphamodulatefixed) | Representa um efeito Alpha Modulate Fixed. Valores alpha (opacity) do efeito são multiplicados por uma porcentagem fixa. |
| [AlphaReplace](./alphareplace) | Representa um efeito Alpha Replace. Valores alpha (opacity) do efeito são substituídos por um alpha fixo. |
| [BiLevel](./bilevel) | Representa um efeito Bi-Level (preto/branco). Cores de entrada cuja luminância é menor que o valor de limiar especificado são alteradas para preto. Cores de entrada cuja luminância é maior ou igual ao valor especificado são definidas como branco. Os valores alpha do efeito não são afetados por este efeito. |
| [Blur](./blur) | Representa um efeito Blur que é aplicado a toda a forma, incluindo seu preenchimento. Todos os canais de cor, incluindo alpha, são afetados. |
| [BrightnessContrast](./brightnesscontrast) | Representa um efeito BrightnessContrast. Ajusta brilho e contraste. |
| [ColorChange](./colorchange) | Representa um efeito Color Change. Instâncias de FromColor são substituídas por instâncias de ToColor. |
| [ColorReplace](./colorreplace) | Representa um efeito Color Replacement. Todas as cores do efeito são alteradas para uma cor fixa. Valores Alpha não são afetados. |
| [Duotone](./duotone) | Representa um efeito Duotone. Para cada pixel, combina Color1 e Color2 por interpolação linear para determinar a nova cor desse pixel. |
| [EffectFactory](./effectfactory) | Permite criar efeitos. |
| [FillOverlay](./filloverlay) | Representa um efeito Fill Overlay. Um overlay de preenchimento pode ser usado para especificar um preenchimento adicional para um objeto e mesclar os dois preenchimentos. |
| [Glow](./glow) | Representa um efeito Glow, no qual um contorno desfocado de cor é adicionado fora das bordas do objeto. |
| [GrayScale](./grayscale) | Representa um efeito Gray Scale. Converte todos os valores de cor do efeito para um tom de cinza, correspondente à sua luminância. Valores alpha (opacity) do efeito não são afetados. |
| [HSL](./hsl) | Representa um efeito Hue/Saturation/Luminance. Matiz, saturação e luminância podem ser ajustados individualmente em relação ao seu valor atual. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Objeto imutável que representa uma coleção somente-leitura de efeitos efetivos de transformação de imagem. |
| [ImageTransformOperation](./imagetransformoperation) | Representa um efeito abstrato de transformação de imagem. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Representa uma coleção de efeitos aplicados a uma imagem. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Permite criar operações de transformação de imagem. |
| [InnerShadow](./innershadow) | Representa um efeito Inner Shadow. |
| [Luminance](./luminance) | Representa um efeito Luminance. Brilho desloca linearmente todas as cores mais próximas ao branco ou preto. Contraste aumenta a separação entre todas as cores. |
| [OuterShadow](./outershadow) | Representa um efeito Outer Shadow. |
| [PresetShadow](./presetshadow) | Representa um efeito Preset Shadow. |
| [Reflection](./reflection) | Representa um efeito Reflection. |
| [SoftEdge](./softedge) | Representa um efeito soft edge. As bordas da forma são desfocadas, enquanto o preenchimento não é afetado. |
| [Tint](./tint) | Representa um efeito Tint. Desloca os valores de cor do efeito em direção ou afastamento da matiz pelo valor especificado. |

## Interfaces

| Interface | Description |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Representa um efeito Alpha Bi-Level. Valores Alpha (Opacity) menores que o limiar são alterados para 0 (totalmente transparente) e valores alpha maiores ou iguais ao limiar são alterados para 100% (totalmente opaco). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Objeto imutável que representa um efeito Alpha Bi-Level. Valores Alpha (Opacity) menores que o limiar são alterados para 0 (totalmente transparente) e valores alpha maiores ou iguais ao limiar são alterados para 100% (totalmente opaco). |
| [IAlphaCeiling](./ialphaceiling) | Representa um efeito Alpha Ceiling. Valores Alpha (opacity) maiores que zero são alterados para 100%. Em outras palavras, tudo que é parcialmente opaco torna-se totalmente opaco. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Objeto imutável que representa um efeito Alpha Ceiling. Valores Alpha (opacity) maiores que zero são alterados para 100%. Em outras palavras, tudo que é parcialmente opaco torna-se totalmente opaco. |
| [IAlphaFloor](./ialphafloor) | Representa um efeito Alpha Floor. Valores Alpha (opacity) menores que 100% são alterados para zero. Em outras palavras, tudo que é parcialmente transparente torna-se totalmente transparente. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Objeto imutável que representa um efeito Alpha Floor. Valores Alpha (opacity) menores que 100% são alterados para zero. Em outras palavras, tudo que é parcialmente transparente torna-se totalmente transparente. |
| [IAlphaInverse](./ialphainverse) | Representa um efeito Alpha Inverse. Valores Alpha (opacity) são invertidos subtraindo de 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Objeto imutável que representa um efeito Alpha Inverse. Valores Alpha (opacity) são invertidos subtraindo de 100%. |
| [IAlphaModulate](./ialphamodulate) | Representa um efeito Alpha Modulate. Valores alpha (opacity) do efeito são multiplicados por uma porcentagem fixa. O contêiner do efeito especifica um efeito que contém valores alpha a serem modulados. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Objeto imutável que representa um efeito Alpha Modulate. Valores alpha (opacity) do efeito são multiplicados por uma porcentagem fixa. O contêiner do efeito especifica um efeito que contém valores alpha a serem modulados. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Representa um efeito Alpha Modulate Fixed. Valores alpha (opacity) do efeito são multiplicados por uma porcentagem fixa. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Objeto imutável que representa um efeito Alpha Modulate Fixed. Valores alpha (opacity) do efeito são multiplicados por uma porcentagem fixa. |
| [IAlphaReplace](./ialphareplace) | Representa a interface base IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Objeto imutável que representa um efeito Alpha Replace. Valores alpha (opacity) do efeito são substituídos por um alpha fixo. |
| [IBiLevel](./ibilevel) | Representa a interface base IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Objeto imutável que representa um efeito Bi-Level (preto/branco). Cores de entrada cuja luminância é menor que o valor de limiar especificado são alteradas para preto. Cores de entrada cuja luminância é maior ou igual ao valor especificado são definidas como branco. Os valores alpha do efeito não são afetados por este efeito. |
| [IBlur](./iblur) | Representa um efeito Blur que é aplicado a toda a forma, incluindo seu preenchimento. Todos os canais de cor, incluindo alpha, são afetados. |
| [IBlurEffectiveData](./iblureffectivedata) | Objeto imutável que representa um efeito Blur que é aplicado a toda a forma, incluindo seu preenchimento. Todos os canais de cor, incluindo alpha, são afetados. |
| [IBrightnessContrast](./ibrightnesscontrast) | Representa um efeito BrightnessContrast. Ajusta brilho e contraste. |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | Objeto imutável que representa um efeito BrightnessContrast. Ajusta brilho e contraste. |
| [IColorChange](./icolorchange) | Representa um efeito Color Change. Instâncias de FromColor são substituídas por instâncias de ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Objeto imutável que representa um efeito Color Change. Instâncias de FromColor são substituídas por instâncias de ToColor. |
| [IColorReplace](./icolorreplace) | Representa um efeito Color Replacement. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Objeto imutável que representa um efeito Color Replacement. Todas as cores do efeito são alteradas para uma cor fixa. Valores Alpha não são afetados. |
| [IDuotone](./iduotone) | Representa um efeito Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Objeto imutável que representa um efeito Duotone. Para cada pixel, combina clr1 e clr2 por interpolação linear para determinar a nova cor desse pixel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Classe base para objetos imutáveis, que representam efeitos. |
| [IEffectFactory](./ieffectfactory) | Permite criar instâncias de efeitos. |
| [IFillOverlay](./ifilloverlay) | Representa um efeito Fill Overlay. Um overlay de preenchimento pode ser usado para especificar um preenchimento adicional para um objeto e mesclar os dois preenchimentos. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Objeto imutável que representa um efeito Fill Overlay. Um overlay de preenchimento pode ser usado para especificar um preenchimento adicional para um objeto e mesclar os dois preenchimentos. |
| [IGlow](./iglow) | Representa um efeito Glow, no qual um contorno desfocado de cor é adicionado fora das bordas do objeto. |
| [IGlowEffectiveData](./igloweffectivedata) | Objeto imutável que representa um efeito Glow, no qual um contorno desfocado de cor é adicionado fora das bordas do objeto. |
| [IGrayScale](./igrayscale) | Representa a interface IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Objeto imutável que representa um efeito Gray Scale. Converte todos os valores de cor do efeito para um tom de cinza, correspondente à sua luminância. Valores alpha (opacity) do efeito não são afetados. |
| [IHSL](./ihsl) | Representa um efeito Hue/Saturation/Luminance. Matiz, saturação e luminância podem ser ajustados individualmente em relação ao seu valor atual. |
| [IHSLEffectiveData](./ihsleffectivedata) | Representa um efeito Hue/Saturation/Luminance. Matiz, saturação e luminância podem ser ajustados individualmente em relação ao seu valor atual. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Objeto imutável que representa uma coleção somente-leitura de efeitos efetivos de transformação de imagem. |
| [IImageTransformOperation](./iimagetransformoperation) | Representa um efeito abstrato de transformação de imagem. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Representa uma coleção de efeitos aplicados a uma imagem. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Permite criar instâncias de efeitos de imagem. |
| [IInnerShadow](./iinnershadow) | Representa um efeito inner shadow. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Objeto imutável que representa um efeito inner shadow. |
| [ILuminance](./iluminance) | Representa um efeito Luminance. Brilho desloca linearmente todas as cores mais próximas ao branco ou preto. Contraste aumenta a separação entre todas as cores. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Representa um efeito Luminance. Brilho desloca linearmente todas as cores mais próximas ao branco ou preto. Contraste aumenta a separação entre todas as cores. |
| [IOuterShadow](./ioutershadow) | Representa um efeito Outer Shadow. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Objeto imutável que representa um efeito Outer Shadow. |
| [IPresetShadow](./ipresetshadow) | Representa um efeito Preset Shadow. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Objeto imutável que representa um efeito Preset Shadow. |
| [IReflection](./ireflection) | Representa um efeito Reflection. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Objeto imutável que representa um efeito Reflection. |
| [ISoftEdge](./isoftedge) | Representa um efeito Soft Edge. As bordas da forma são desfocadas, enquanto o preenchimento não é afetado. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Objeto imutável que representa um efeito soft edge. As bordas da forma são desfocadas, enquanto o preenchimento não é afetado. |
| [ITint](./itint) | Representa um efeito Tint. Desloca os valores de cor do efeito em direção ou afastamento da matiz pelo valor especificado. |
| [ITintEffectiveData](./itinteffectivedata) | Objeto imutável que representa um efeito Tint. Desloca os valores de cor do efeito em direção ou afastamento da matiz pelo valor especificado. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->