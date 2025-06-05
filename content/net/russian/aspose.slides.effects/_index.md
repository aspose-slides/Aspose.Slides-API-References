---
title: Aspose.Slides.Effects
second_title: Aspose.Slides для .NET API Справочник
description: Содержит классы для работы с различными эффектами в презентациях Microsoft PowerPoint.
type: docs
weight: 50
url: /ru/aspose.slides.effects/
---

Содержит классы для работы с различными эффектами в презентациях Microsoft PowerPoint.

## Классы

| Класс | Описание |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Представляет эффект Alpha Bi-Level. Значения Alpha (непрозрачности), менее чем порог, изменяются на 0 (полностью прозрачный), а значения alpha, равные или превышающие порог, изменяются на 100% (полностью непрозрачный). |
| [AlphaCeiling](./alphaceiling) | Представляет эффект Alpha Ceiling. Значения Alpha (непрозрачности), превышающие ноль, изменяются на 100%. Другими словами, все, что частично непрозрачное, становится полностью непрозрачным. |
| [AlphaFloor](./alphafloor) | Представляет эффект Alpha Floor. Значения Alpha (непрозрачности), менее чем 100%, изменяются на ноль. Другими словами, все, что частично прозрачное, становится полностью прозрачным. |
| [AlphaInverse](./alphainverse) | Представляет эффект Alpha Inverse. Значения Alpha (непрозрачности) инвертируются за счет вычитания из 100%. |
| [AlphaModulate](./alphamodulate) | Представляет эффект Alpha Modulate. Значения alpha (непрозрачности) эффекта умножаются на фиксированный процент. Контейнер эффекта указывает эффект, содержащий alpha значения для модуляции. |
| [AlphaModulateFixed](./alphamodulatefixed) | Представляет эффект Alpha Modulate Fixed. Значения alpha (непрозрачности) эффекта умножаются на фиксированный процент. |
| [AlphaReplace](./alphareplace) | Представляет эффект Alpha Replace. Значения alpha (непрозрачности) эффекта заменяются фиксированным alpha. |
| [BiLevel](./bilevel) | Представляет эффект Bi-Level (черный/белый). Входные цвета, яркость которых меньше заданного порогового значения, изменяются на черный. Входные цвета, яркость которых больше или равна заданному значению, устанавливаются на белый. Значения alpha эффекта не подвергаются воздействию этого эффекта. |
| [Blur](./blur) | Представляет эффект Blur, который применяется ко всей фигуре, включая ее заливку. Все цветовые каналы, включая alpha, затрагиваются. |
| [ColorChange](./colorchange) | Представляет эффект Color Change. Экземпляры FromColor заменяются экземплярами ToColor. |
| [ColorReplace](./colorreplace) | Представляет эффект Color Replacement. Все цвета эффекта изменяются на фиксированный цвет. Значения alpha не подвергаются воздействию. |
| [Duotone](./duotone) | Представляет эффект Duotone. Для каждого пикселя комбинирует Color1 и Color2 с помощью линейной интерполяции для определения нового цвета этого пикселя. |
| [EffectFactory](./effectfactory) | Позволяет создавать эффекты |
| [FillOverlay](./filloverlay) | Представляет эффект Fill Overlay. Накладка заполнения может использоваться для указания дополнительной заливки для объекта и смешивания двух заливок вместе. |
| [Glow](./glow) | Представляет эффект Glow, в котором цвет размытых контуров добавляется за пределами краев объекта. |
| [GrayScale](./grayscale) | Представляет эффект Gray Scale. Преобразует все значения цветового эффекта в оттенок серого, соответствующий их яркости. Значения alpha (непрозрачности) эффекта не подвергаются воздействию. |
| [HSL](./hsl) | Представляет эффект Hue/Saturation/Luminance. Оттенок, насыщенность и яркость могут быть отрегулированы относительно их текущего значения. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Неизменяемый объект, представляющий коллекцию эффективных эффектов преобразования изображения только для чтения. |
| [ImageTransformOperation](./imagetransformoperation) | Представляет абстрактный эффект преобразования изображения. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Представляет коллекцию эффектов, примененных к изображению. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Позволяет создавать операции преобразования изображения |
| [InnerShadow](./innershadow) | Представляет эффект Inner Shadow. |
| [Luminance](./luminance) | Представляет эффект Luminance. Яркость линейно смещает все цвета ближе к белому или черному. Контраст масштабирует все цвета так, чтобы они были ближе или дальше друг от друга. |
| [OuterShadow](./outershadow) | Представляет эффект Outer Shadow. |
| [PresetShadow](./presetshadow) | Представляет эффект Preset Shadow. |
| [Reflection](./reflection) | Представляет эффект Reflection. |
| [SoftEdge](./softedge) | Представляет эффект Soft Edge. Края фигуры размыты, в то время как заливка не подвергается воздействию. |
| [Tint](./tint) | Представляет эффект Tint. Смещает значения цветового эффекта к оттенку/вдали от оттенка на заданное количество. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Представляет эффект Alpha Bi-Level. Значения Alpha (непрозрачности), менее чем порог, изменяются на 0 (полностью прозрачный), а значения alpha, равные или превышающие порог, изменяются на 100% (полностью непрозрачный). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Неизменяемый объект, который представляет эффект Alpha Bi-Level. Значения Alpha (непрозрачности), менее чем порог, изменяются на 0 (полностью прозрачный), а значения alpha, равные или превышающие порог, изменяются на 100% (полностью непрозрачный). |
| [IAlphaCeiling](./ialphaceiling) | Представляет эффект Alpha Ceiling. Значения Alpha (непрозрачности), превышающие ноль, изменяются на 100%. Другими словами, все, что частично непрозрачное, становится полностью непрозрачным. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Неизменяемый объект, который представляет эффект Alpha Ceiling. Значения Alpha (непрозрачности), превышающие ноль, изменяются на 100%. Другими словами, все, что частично непрозрачное, становится полностью непрозрачным. |
| [IAlphaFloor](./ialphafloor) | Представляет эффект Alpha Floor. Значения Alpha (непрозрачности), менее чем 100%, изменяются на ноль. Другими словами, все, что частично прозрачное, становится полностью прозрачным. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Неизменяемый объект, который представляет эффект Alpha Floor. Значения Alpha (непрозрачности), менее чем 100%, изменяются на ноль. Другими словами, все, что частично прозрачное, становится полностью прозрачным. |
| [IAlphaInverse](./ialphainverse) | Представляет эффект Alpha Inverse. Значения Alpha (непрозрачности) инвертируются за счет вычитания из 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Неизменяемый объект, который представляет эффект Alpha Inverse. Значения Alpha (непрозрачности) инвертируются за счет вычитания из 100%. |
| [IAlphaModulate](./ialphamodulate) | Представляет эффект Alpha Modulate. Значения alpha (непрозрачности) эффекта умножаются на фиксированный процент. Контейнер эффекта указывает эффект, содержащий alpha значения для модуляции. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Неизменяемый объект, который представляет эффект Alpha Modulate. Значения alpha (непрозрачности) эффекта умножаются на фиксированный процент. Контейнер эффекта указывает эффект, содержащий alpha значения для модуляции. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Представляет эффект Alpha Modulate Fixed. Значения alpha (непрозрачности) эффекта умножаются на фиксированный процент. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Неизменяемый объект, который представляет эффект Alpha Modulate Fixed. Значения alpha (непрозрачности) эффекта умножаются на фиксированный процент. |
| [IAlphaReplace](./ialphareplace) | Представляет базовый интерфейс IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Неизменяемый объект, который представляет эффект Alpha Replace. Значения alpha (непрозрачности) эффекта заменяются фиксированным alpha. |
| [IBiLevel](./ibilevel) | Представляет базовый интерфейс IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Неизменяемый объект, который представляет эффект Bi-Level (черный/белый). Входные цвета, яркость которых меньше заданного порогового значения, изменяются на черный. Входные цвета, яркость которых больше или равна заданному значению, устанавливаются на белый. Значения alpha эффекта не подвергаются воздействию этого эффекта. |
| [IBlur](./iblur) | Представляет эффект Blur, который применяется ко всей фигуре, включая ее заливку. Все цветовые каналы, включая alpha, затрагиваются. |
| [IBlurEffectiveData](./iblureffectivedata) | Неизменяемый объект, который представляет эффект Blur, который применяется ко всей фигуре, включая ее заливку. Все цветовые каналы, включая alpha, затрагиваются. |
| [IColorChange](./icolorchange) | Представляет эффект Color Change. Экземпляры FromColor заменяются экземплярами ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Неизменяемый объект, который представляет эффект Color Change. Экземпляры FromColor заменяются экземплярами ToColor. |
| [IColorReplace](./icolorreplace) | Представляет эффект Color Replacement. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Неизменяемый объект, который представляет эффект Color Replacement. Все цвета эффекта изменяются на фиксированный цвет. Значения alpha не подвергаются воздействию. |
| [IDuotone](./iduotone) | Представляет эффект Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Неизменяемый объект, который представляет эффект Duotone. Для каждого пикселя комбинирует clr1 и clr2 с помощью линейной интерполяции для определения нового цвета этого пикселя. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Базовый класс для неизменяемых объектов, представляющих эффект. |
| [IEffectFactory](./ieffectfactory) | Позволяет создавать экземпляры эффектов |
| [IFillOverlay](./ifilloverlay) | Представляет эффект Fill Overlay. Накладка заполнения может использоваться для указания дополнительной заливки для объекта и смешивания двух заливок вместе. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Неизменяемый объект, который представляет эффект Fill Overlay. Накладка заполнения может использоваться для указания дополнительной заливки для объекта и смешивания двух заливок вместе. |
| [IGlow](./iglow) | Представляет эффект Glow, в котором цвет размытых контуров добавляется за пределами краев объекта. |
| [IGlowEffectiveData](./igloweffectivedata) | Неизменяемый объект, который представляет эффект Glow, в котором цвет размытых контуров добавляется за пределами краев объекта. |
| [IGrayScale](./igrayscale) | Представляет интерфейс IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Неизменяемый объект, который представляет эффект Gray Scale. Преобразует все значения цветового эффекта в оттенок серого, соответствующий их яркости. Значения alpha (непрозрачности) эффекта не подвергаются воздействию. |
| [IHSL](./ihsl) | Представляет эффект Hue/Saturation/Luminance. Оттенок, насыщенность и яркость могут быть отрегулированы относительно их текущего значения. |
| [IHSLEffectiveData](./ihsleffectivedata) | Представляет эффект Hue/Saturation/Luminance. Оттенок, насыщенность и яркость могут быть отрегулированы относительно их текущего значения. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Неизменяемый объект, который представляет коллекцию эффективных эффектов преобразования изображения только для чтения. |
| [IImageTransformOperation](./iimagetransformoperation) | Представляет абстрактный эффект преобразования изображения. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Представляет коллекцию эффектов, примененных к изображению. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Позволяет создавать экземпляры эффектов преобразования изображения |
| [IInnerShadow](./iinnershadow) | Представляет эффект внутренней тени. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Неизменяемый объект, который представляет эффект внутренней тени. |
| [ILuminance](./iluminance) | Представляет эффект Luminance. Яркость линейно смещает все цвета ближе к белому или черному. Контраст масштабирует все цвета так, чтобы они были ближе или дальше друг от друга. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Представляет эффект Luminance. Яркость линейно смещает все цвета ближе к белому или черному. Контраст масштабирует все цвета так, чтобы они были ближе или дальше друг от друга. |
| [IOuterShadow](./ioutershadow) | Представляет эффект Outer Shadow. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Неизменяемый объект, который представляет эффект Outer Shadow. |
| [IPresetShadow](./ipresetshadow) | Представляет эффект Preset Shadow. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Неизменяемый объект, который представляет эффект Preset Shadow. |
| [IReflection](./ireflection) | Представляет эффект отражения. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Неизменяемый объект, который представляет эффект Reflection. |
| [ISoftEdge](./isoftedge) | Представляет эффект Soft Edge. Края фигуры размыты, в то время как заливка не подвергается воздействию. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Неизменяемый объект, который представляет эффект Soft Edge. Края фигуры размыты, в то время как заливка не подвергается воздействию. |
| [ITint](./itint) | Представляет эффект Tint. Смещает значения цветового эффекта к оттенку/вдали от оттенка на заданное количество. |
| [ITintEffectiveData](./itinteffectivedata) | Неизменяемый объект, который представляет эффект Tint. Смещает значения цветового эффекта к оттенку/вдали от оттенка на заданное количество. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->