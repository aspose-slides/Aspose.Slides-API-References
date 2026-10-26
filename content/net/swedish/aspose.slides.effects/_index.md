---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes för .NET API-referens
description: Innehåller klasser för arbete med olika effekter i Microsoft PowerPoint-presentationer.
type: docs
weight: 60
url: /sv/aspose.slides.effects/
---
Innehåller klasser för arbete med olika effekter i Microsoft PowerPoint-presentationer.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Representerar en Alpha Bi-Level-effekt. Alpha (opacitet) värden mindre än tröskeln ändras till 0 (fullt transparent) och alpha värden större än eller lika med tröskeln ändras till 100% (fullt ogenomskinlig). |
| [AlphaCeiling](./alphaceiling) | Representerar en Alpha Ceiling-effekt. Alpha (opacitet) värden större än noll ändras till 100%. Med andra ord blir allt som är delvis ogenomskinligt helt ogenomskinligt. |
| [AlphaFloor](./alphafloor) | Representerar en Alpha Floor-effekt. Alpha (opacitet) värden mindre än 100% ändras till noll. Med andra ord blir allt som är delvis transparent helt transparent. |
| [AlphaInverse](./alphainverse) | Representerar en Alpha Inverse-effekt. Alpha (opacitet) värden inverteras genom att subtraheras från 100%. |
| [AlphaModulate](./alphamodulate) | Representerar en Alpha Modulate-effekt. Effektens alpha (opacitet) värden multipliceras med en fast procentsats. Effektbehållaren specificerar en effekt som innehåller alpha-värden att modulera. |
| [AlphaModulateFixed](./alphamodulatefixed) | Representerar en Alpha Modulate Fixed-effekt. Effektens alpha (opacitet) värden multipliceras med en fast procentsats. |
| [AlphaReplace](./alphareplace) | Representerar en Alpha Replace-effekt. Effektens alpha (opacitet) värden ersätts med ett fast alfa-värde. |
| [BiLevel](./bilevel) | Representerar en Bi-Level (svart/vitt)-effekt. Indatakulörer vars luminans är mindre än det angivna tröskelvärdet ändras till svart. Indatakulörer vars luminans är större än eller lika med det angivna värdet sätts till vitt. Alpha-effektvärden påverkas inte av denna effekt. |
| [Blur](./blur) | Representerar en Blur-effekt som tillämpas på hela formen, inklusive fyllningen. Alla färgkanaler, inklusive alfa, påverkas. |
| [BrightnessContrast](./brightnesscontrast) | Representerar en BrightnessContrast-effekt. Justerar ljusstyrka och kontrast |
| [ColorChange](./colorchange) | Representerar en Color Change-effekt. Instanser av FromColor ersätts med instanser av ToColor. |
| [ColorReplace](./colorreplace) | Representerar en Color Replacement-effekt. Alla effektfärger ändras till en fast färg. Alfa-värden påverkas inte. |
| [Duotone](./duotone) | Representerar en Duotone-effekt. För varje pixel kombineras Color1 och Color2 genom linjär interpolation för att bestämma den nya färgen för den pixeln. |
| [EffectFactory](./effectfactory) | Gör det möjligt att skapa effekter |
| [FillOverlay](./filloverlay) | Representerar en Fill Overlay-effekt. En fyllnadsöverlagring kan användas för att ange en extra fyllning för ett objekt och blanda de två fyllningarna tillsammans. |
| [Glow](./glow) | Representerar en Glow-effekt, där en färgblurrad kontur läggs till utanför objektets kanter. |
| [GrayScale](./grayscale) | Representerar en Gray Scale-effekt. Konverterar alla effektfärgvärden till en gråskala som motsvarar deras luminans. Effektens alpha (opacitet) värden påverkas inte. |
| [HSL](./hsl) | Representerar en Hue/Saturation/Luminance-effekt. Nyans, mättnad och luminans kan var och en justeras relativt sitt nuvarande värde. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Oföränderligt objekt som representerar en skrivskyddad samling av effektiva bildtransformeringseffekter. |
| [ImageTransformOperation](./imagetransformoperation) | Representerar en abstrakt bildtransformeringseffekt. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Representerar en samling av effekter som tillämpas på en bild. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Gör det möjligt att skapa bildtransformeringsoperationer |
| [InnerShadow](./innershadow) | Representerar en Inner Shadow-effekt. |
| [Luminance](./luminance) | Representerar en Luminance-effekt. Ljusstyrka skiftar linjärt alla färger närmare vitt eller svart. Kontrast skalar alla färger så att de blir antingen närmare eller längre ifrån varandra. |
| [OuterShadow](./outershadow) | Representerar en Outer Shadow-effekt. |
| [PresetShadow](./presetshadow) | Representerar en Preset Shadow-effekt. |
| [Reflection](./reflection) | Representerar en Reflection-effekt. |
| [SoftEdge](./softedge) | Representerar en Soft Edge-effekt. Formens kanter är suddade, medan fyllningen inte påverkas. |
| [Tint](./tint) | Representerar en Tint-effekt. Skiftar effektfärgvärden mot eller bort från nyans med den angivna mängden. |

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Representerar en Alpha Bi-Level-effekt. Alpha (opacitet) värden mindre än tröskeln ändras till 0 (fullt transparent) och alpha värden större än eller lika med tröskeln ändras till 100% (fullt ogenomskinlig). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Oföränderligt objekt som representerar en Alpha Bi-Level-effekt. Alpha (opacitet) värden mindre än tröskeln ändras till 0 (fullt transparent) och alpha värden större än eller lika med tröskeln ändras till 100% (fullt ogenomskinlig). |
| [IAlphaCeiling](./ialphaceiling) | Representerar en Alpha Ceiling-effekt. Alpha (opacitet) värden större än noll ändras till 100%. Med andra ord blir allt som är delvis ogenomskinligt helt ogenomskinligt. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Oföränderligt objekt som representerar en Alpha Ceiling-effekt. Alpha (opacitet) värden större än noll ändras till 100%. Med andra ord blir allt som är delvis ogenomskinligt helt ogenomskinligt. |
| [IAlphaFloor](./ialphafloor) | Representerar en Alpha Floor-effekt. Alpha (opacitet) värden mindre än 100% ändras till noll. Med andra ord blir allt som är delvis transparent helt transparent. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Oföränderligt objekt som representerar en Alpha Floor-effekt. Alpha (opacitet) värden mindre än 100% ändras till noll. Med andra ord blir allt som är delvis transparent helt transparent. |
| [IAlphaInverse](./ialphainverse) | Representerar en Alpha Inverse-effekt. Alpha (opacitet) värden inverteras genom att subtraheras från 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Oföränderligt objekt som representerar en Alpha Inverse-effekt. Alpha (opacitet) värden inverteras genom att subtraheras från 100%. |
| [IAlphaModulate](./ialphamodulate) | Representerar en Alpha Modulate-effekt. Effektens alpha (opacitet) värden multipliceras med en fast procentsats. Effektbehållaren specificerar en effekt som innehåller alpha-värden att modulera. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Oföränderligt objekt som representerar en Alpha Modulate-effekt. Effektens alpha (opacitet) värden multipliceras med en fast procentsats. Effektbehållaren specificerar en effekt som innehåller alpha-värden att modulera. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Representerar en Alpha Modulate Fixed-effekt. Effektens alpha (opacitet) värden multipliceras med en fast procentsats. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Oföränderligt objekt som representerar en Alpha Modulate Fixed-effekt. Effektens alpha (opacitet) värden multipliceras med en fast procentsats. |
| [IAlphaReplace](./ialphareplace) | Representerar bas-IImageTransformOperation-gränssnittet. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Oföränderligt objekt som representerar en Alpha Replace-effekt. Effektens alpha (opacitet) värden ersätts med ett fast alfa-värde. |
| [IBiLevel](./ibilevel) | Representerar bas-IImageTransformOperation-gränssnittet. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Oföränderligt objekt som representerar en Bi-Level (svart/vitt)-effekt. Indatakulörer vars luminans är mindre än det angivna tröskelvärdet ändras till svart. Indatakulörer vars luminans är större än eller lika med det angivna värdet sätts till vitt. Alpha-effektvärden påverkas inte av denna effekt. |
| [IBlur](./iblur) | Representerar en Blur-effekt som tillämpas på hela formen, inklusive fyllningen. Alla färgkanaler, inklusive alfa, påverkas. |
| [IBlurEffectiveData](./iblureffectivedata) | Oföränderligt objekt som representerar en Blur-effekt som tillämpas på hela formen, inklusive fyllningen. Alla färgkanaler, inklusive alfa, påverkas. |
| [IBrightnessContrast](./ibrightnesscontrast) | Representerar en BrightnessContrast-effekt. Justerar ljusstyrka och kontrast |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | Oföränderligt objekt som representerar en BrightnessContrast-effekt. Justerar ljusstyrka och kontrast |
| [IColorChange](./icolorchange) | Representerar en Color Change-effekt. Instanser av FromColor ersätts med instanser av ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Oföränderligt objekt som representerar en Color Change-effekt. Instanser av FromColor ersätts med instanser av ToColor. |
| [IColorReplace](./icolorreplace) | Representerar en Color Replacement-effekt. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Oföränderligt objekt som representerar en Color Replacement-effekt. Alla effektfärger ändras till en fast färg. Alfa-värden påverkas inte. |
| [IDuotone](./iduotone) | Representerar en Duotone-effekt. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Oföränderligt objekt som representerar en Duotone-effekt. För varje pixel kombineras clr1 och clr2 genom linjär interpolation för att bestämma den nya färgen för den pixeln. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Bas-klass för oföränderliga objekt som representerar en effekt. |
| [IEffectFactory](./ieffectfactory) | Gör det möjligt att skapa instanser av effekter |
| [IFillOverlay](./ifilloverlay) | Representerar en Fill Overlay-effekt. En fyllnadsöverlagring kan användas för att ange en extra fyllning för ett objekt och blanda de två fyllningarna tillsammans. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Oföränderligt objekt som representerar en Fill Overlay-effekt. En fyllnadsöverlagring kan användas för att ange en extra fyllning för ett objekt och blanda de två fyllningarna tillsammans. |
| [IGlow](./iglow) | Representerar en Glow-effekt, där en färgblurrad kontur läggs till utanför objektets kanter. |
| [IGlowEffectiveData](./igloweffectivedata) | Oföränderligt objekt som representerar en Glow-effekt, där en färgblurrad kontur läggs till utanför objektets kanter. |
| [IGrayScale](./igrayscale) | Representerar IImageTransformOperation-gränssnittet. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Oföränderligt objekt som representerar en Gray Scale-effekt. Konverterar alla effektfärgvärden till en gråskala som motsvarar deras luminans. Effektens alpha (opacitet) värden påverkas inte. |
| [IHSL](./ihsl) | Representerar en Hue/Saturation/Luminance-effekt. Nyans, mättnad och luminans kan var och en justeras relativt sitt nuvarande värde. |
| [IHSLEffectiveData](./ihsleffectivedata) | Representerar en Hue/Saturation/Luminance-effekt. Nyans, mättnad och luminans kan var och en justeras relativt sitt nuvarande värde. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Oföränderligt objekt som representerar en skrivskyddad samling av effektiva bildtransformeringseffekter. |
| [IImageTransformOperation](./iimagetransformoperation) | Representerar en abstrakt bildtransformeringseffekt. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Representerar en samling av effekter som tillämpas på en bild. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Gör det möjligt att skapa instanser av bildeffekter |
| [IInnerShadow](./iinnershadow) | Representerar en inner shadow-effekt. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Oföränderligt objekt som representerar en inner shadow-effekt. |
| [ILuminance](./iluminance) | Representerar en Luminance-effekt. Ljusstyrka skiftar linjärt alla färger närmare vitt eller svart. Kontrast skalar alla färger så att de blir antingen närmare eller längre ifrån varandra. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Representerar en Luminance-effekt. Ljusstyrka skiftar linjärt alla färger närmare vitt eller svart. Kontrast skalar alla färger så att de blir antingen närmare eller längre ifrån varandra. |
| [IOuterShadow](./ioutershadow) | Representerar en Outer Shadow-effekt. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Oföränderligt objekt som representerar en Outer Shadow-effekt. |
| [IPresetShadow](./ipresetshadow) | Representerar en Preset Shadow-effekt. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Oföränderligt objekt som representerar en Preset Shadow-effekt. |
| [IReflection](./ireflection) | Representerar en reflection-effekt. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Oföränderligt objekt som representerar en Reflection-effekt. |
| [ISoftEdge](./isoftedge) | Representerar en Soft Edge-effekt. Formens kanter är suddade, medan fyllningen inte påverkas. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Oföränderligt objekt som representerar en soft edge-effekt. Formens kanter är suddade, medan fyllningen inte påverkas. |
| [ITint](./itint) | Representerar en Tint-effekt. Skiftar effektfärgvärden mot eller bort från nyans med den angivna mängden. |
| [ITintEffectiveData](./itinteffectivedata) | Oföränderligt objekt som representerar en Tint-effekt. Skiftar effektfärgvärden mot eller bort från nyans med den angivna mängden. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->