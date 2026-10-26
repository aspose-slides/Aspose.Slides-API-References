---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes dla .NET Dokumentacja API
description: Zawiera klasy służące do pracy z różnymi efektami w prezentacjach Microsoft PowerPoint.
type: docs
weight: 60
url: /pl/aspose.slides.effects/
---
Zawiera klasy służące do pracy z różnymi efektami w prezentacjach Microsoft PowerPoint.

## Klasy

| Klasa | Opis |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Reprezentuje efekt Alpha Bi-Level. Wartości Alpha (przezroczystości) mniejsze niż próg są zmieniane na 0 (całkowicie przezroczyste), a wartości alpha większe lub równe progowi są zmieniane na 100 % (całkowicie nieprzezroczyste). |
| [AlphaCeiling](./alphaceiling) | Reprezentuje efekt Alpha Ceiling. Wartości Alpha (przezroczystość) większe niż zero są zmieniane na 100 %. Innymi słowy, wszystko częściowo nieprzezroczyste staje się całkowicie nieprzezroczyste. |
| [AlphaFloor](./alphafloor) | Reprezentuje efekt Alpha Floor. Wartości Alpha (przezroczystość) mniejsze niż 100 % są zmieniane na zero. Innymi słowy, wszystko częściowo przezroczyste staje się całkowicie przezroczyste. |
| [AlphaInverse](./alphainverse) | Reprezentuje efekt Alpha Inverse. Wartości Alpha (przezroczystość) są odwracane poprzez odjęcie od 100 %. |
| [AlphaModulate](./alphamodulate) | Reprezentuje efekt Alpha Modulate. Wartości alpha (przezroczystość) efektu są mnożone przez stały procent. Kontener efektu określa efekt zawierający wartości alpha do modulacji. |
| [AlphaModulateFixed](./alphamodulatefixed) | Reprezentuje efekt Alpha Modulate Fixed. Wartości alpha (przezroczystość) efektu są mnożone przez stały procent. |
| [AlphaReplace](./alphareplace) | Reprezentuje efekt Alpha Replace. Wartości alpha (przezroczystość) efektu są zastępowane stałą wartością alpha. |
| [BiLevel](./bilevel) | Reprezentuje efekt Bi-Level (czarno-biały). Kolory wejściowe, których luminancja jest mniejsza niż podany próg, są zmieniane na czarny. Kolory wejściowe, których luminancja jest większa lub równa podanej wartości, są ustawiane na biały. Wartości alpha nie są zmieniane przez ten efekt. |
| [Blur](./blur) | Reprezentuje efekt Blur stosowany na całym kształcie, włącznie z wypełnieniem. Wszystkie kanały kolorów, w tym alpha, są modyfikowane. |
| [BrightnessContrast](./brightnesscontrast) | Reprezentuje efekt BrightnessContrast. Dostosowuje jasność i kontrast. |
| [ColorChange](./colorchange) | Reprezentuje efekt Color Change. Instancje FromColor są zastępowane instancjami ToColor. |
| [ColorReplace](./colorreplace) | Reprezentuje efekt Color Replacement. Wszystkie kolory efektu są zmieniane na stały kolor. Wartości alpha pozostają niezmienione. |
| [Duotone](./duotone) | Reprezentuje efekt Duotone. Dla każdego piksela łączy Color1 i Color2 przez liniową interpolację, aby określić nowy kolor tego piksela. |
| [EffectFactory](./effectfactory) | Umożliwia tworzenie efektów. |
| [FillOverlay](./filloverlay) | Reprezentuje efekt Fill Overlay. Nakładka wypełnienia może być użyta do określenia dodatkowego wypełnienia dla obiektu i połączenia obu wypełnień. |
| [Glow](./glow) | Reprezentuje efekt Glow, w którym rozmyta obwódka koloru jest dodawana poza krawędziami obiektu. |
| [GrayScale](./grayscale) | Reprezentuje efekt Gray Scale. Konwertuje wszystkie wartości kolorów efektu na odcień szarości, odpowiadający ich luminancji. Wartości alpha (przezroczystość) efektu pozostają niezmienione. |
| [HSL](./hsl) | Reprezentuje efekt Hue/Saturation/Luminance. Barwa, nasycenie i luminancja mogą być każda regulowana względem bieżącej wartości. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Niezmienny obiekt reprezentujący kolekcję tylko do odczytu efektywnych transformacji obrazu. |
| [ImageTransformOperation](./imagetransformoperation) | Reprezentuje abstrakcyjny efekt transformacji obrazu. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Reprezentuje kolekcję efektów zastosowanych do obrazu. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Umożliwia tworzenie operacji transformacji obrazu. |
| [InnerShadow](./innershadow) | Reprezentuje efekt Inner Shadow. |
| [Luminance](./luminance) | Reprezentuje efekt Luminance. Jasność liniowo przesuwa wszystkie kolory bliżej bieli lub czerni. Kontrast skaluje wszystkie kolory, aby były bliżej siebie lub dalej od siebie. |
| [OuterShadow](./outershadow) | Reprezentuje efekt Outer Shadow. |
| [PresetShadow](./presetshadow) | Reprezentuje efekt Preset Shadow. |
| [Reflection](./reflection) | Reprezentuje efekt Reflection. |
| [SoftEdge](./softedge) | Reprezentuje efekt miękkich krawędzi. Krawędzie kształtu są rozmyte, podczas gdy wypełnienie nie jest zmieniane. |
| [Tint](./tint) | Reprezentuje efekt Tint. Przesuwa wartości kolorów efektu w kierunku/od barwy o określoną wartość. |

## Interfejsy

| Interfejs | Opis |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Reprezentuje efekt Alpha Bi-Level. Wartości Alpha (przezroczystość) mniejsze niż próg są zmieniane na 0 (całkowicie przezroczyste), a wartości alpha większe lub równe progowi są zmieniane na 100 % (całkowicie nieprzezroczyste). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Niezmienny obiekt reprezentujący efekt Alpha Bi-Level. Wartości Alpha (przezroczystość) mniejsze niż próg są zmieniane na 0 (całkowicie przezroczyste), a wartości alpha większe lub równe progowi są zmieniane na 100 % (całkowicie nieprzezroczyste). |
| [IAlphaCeiling](./ialphaceiling) | Reprezentuje efekt Alpha Ceiling. Wartości Alpha (przezroczystość) większe niż zero są zmieniane na 100 %. Innymi słowy, wszystko częściowo nieprzezroczyste staje się całkowicie nieprzezroczyste. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Niezmienny obiekt reprezentujący efekt Alpha Ceiling. Wartości Alpha (przezroczystość) większe niż zero są zmieniane na 100 %. Innymi słowy, wszystko częściowo nieprzezroczyste staje się całkowicie nieprzezroczyste. |
| [IAlphaFloor](./ialphafloor) | Reprezentuje efekt Alpha Floor. Wartości Alpha (przezroczystość) mniejsze niż 100 % są zmieniane na zero. Innymi słowy, wszystko częściowo przezroczyste staje się całkowicie przezroczyste. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Niezmienny obiekt reprezentujący efekt Alpha Floor. Wartości Alpha (przezroczystość) mniejsze niż 100 % są zmieniane na zero. Innymi słowy, wszystko częściowo przezroczyste staje się całkowicie przezroczyste. |
| [IAlphaInverse](./ialphainverse) | Reprezentuje efekt Alpha Inverse. Wartości Alpha (przezroczystość) są odwracane poprzez odjęcie od 100 %. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Niezmienny obiekt reprezentujący efekt Alpha Inverse. Wartości Alpha (przezroczystość) są odwracane poprzez odjęcie od 100 %. |
| [IAlphaModulate](./ialphamodulate) | Reprezentuje efekt Alpha Modulate. Wartości alpha (przezroczystość) efektu są mnożone przez stały procent. Kontener efektu określa efekt zawierający wartości alpha do modulacji. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Niezmienny obiekt reprezentujący efekt Alpha Modulate. Wartości alpha (przezroczystość) efektu są mnożone przez stały procent. Kontener efektu określa efekt zawierający wartości alpha do modulacji. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Reprezentuje efekt Alpha Modulate Fixed. Wartości alpha (przezroczystość) efektu są mnożone przez stały procent. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Niezmienny obiekt reprezentujący efekt Alpha Modulate Fixed. Wartości alpha (przezroczystość) efektu są mnożone przez stały procent. |
| [IAlphaReplace](./ialphareplace) | Reprezentuje bazowy interfejs IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Niezmienny obiekt reprezentujący efekt Alpha Replace. Wartości alpha (przezroczystość) efektu są zastępowane stałą wartością alpha. |
| [IBiLevel](./ibilevel) | Reprezentuje bazowy interfejs IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Niezmienny obiekt reprezentujący efekt Bi-Level (czarno-biały). Kolory wejściowe, których luminancja jest mniejsza niż podany próg, są zmieniane na czarny. Kolory wejściowe, których luminancja jest większa lub równa podanej wartości, są ustawiane na biały. Wartości alpha nie są zmieniane przez ten efekt. |
| [IBlur](./iblur) | Reprezentuje efekt Blur stosowany na całym kształcie, włącznie z wypełnieniem. Wszystkie kanały kolorów, w tym alpha, są modyfikowane. |
| [IBlurEffectiveData](./iblureffectivedata) | Niezmienny obiekt reprezentujący efekt Blur stosowany na całym kształcie, włącznie z wypełnieniem. Wszystkie kanały kolorów, w tym alpha, są modyfikowane. |
| [IBrightnessContrast](./ibrightnesscontrast) | Reprezentuje efekt BrightnessContrast. Dostosowuje jasność i kontrast. |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | Niezmienny obiekt reprezentujący efekt BrightnessContrast. Dostosowuje jasność i kontrast. |
| [IColorChange](./icolorchange) | Reprezentuje efekt Color Change. Instancje FromColor są zastępowane instancjami ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Niezmienny obiekt reprezentujący efekt Color Change. Instancje FromColor są zastępowane instancjami ToColor. |
| [IColorReplace](./icolorreplace) | Reprezentuje efekt Color Replacement. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Niezmienny obiekt reprezentujący efekt Color Replacement. Wszystkie kolory efektu są zmieniane na stały kolor. Wartości alpha pozostają niezmienione. |
| [IDuotone](./iduotone) | Reprezentuje efekt Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Niezmienny obiekt reprezentujący efekt Duotone. Dla każdego piksela łączy clr1 i clr2 przez liniową interpolację, aby określić nowy kolor tego piksela. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Klasa bazowa dla niezmiennych obiektów, które reprezentują efekt. |
| [IEffectFactory](./ieffectfactory) | Umożliwia tworzenie instancji efektów. |
| [IFillOverlay](./ifilloverlay) | Reprezentuje efekt Fill Overlay. Nakładka wypełnienia może być użyta do określenia dodatkowego wypełnienia dla obiektu i połączenia obu wypełnień. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Niezmienny obiekt reprezentujący efekt Fill Overlay. Nakładka wypełnienia może być użyta do określenia dodatkowego wypełnienia dla obiektu i połączenia obu wypełnień. |
| [IGlow](./iglow) | Reprezentuje efekt Glow, w którym rozmyta obwódka koloru jest dodawana poza krawędziami obiektu. |
| [IGlowEffectiveData](./igloweffectivedata) | Niezmienny obiekt reprezentujący efekt Glow, w którym rozmyta obwódka koloru jest dodawana poza krawędziami obiektu. |
| [IGrayScale](./igrayscale) | Reprezentuje interfejs IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Niezmienny obiekt reprezentujący efekt Gray Scale. Konwertuje wszystkie wartości kolorów efektu na odcień szarości, odpowiadający ich luminancji. Wartości alpha (przezroczystość) efektu pozostają niezmienione. |
| [IHSL](./ihsl) | Reprezentuje efekt Hue/Saturation/Luminance. Barwa, nasycenie i luminancja mogą być każda regulowana względem bieżącej wartości. |
| [IHSLEffectiveData](./ihsleffectivedata) | Reprezentuje efekt Hue/Saturation/Luminance. Barwa, nasycenie i luminancja mogą być każda regulowana względem bieżącej wartości. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Niezmienny obiekt reprezentujący kolekcję tylko do odczytu efektywnych transformacji obrazu. |
| [IImageTransformOperation](./iimagetransformoperation) | Reprezentuje abstrakcyjny efekt transformacji obrazu. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Reprezentuje kolekcję efektów zastosowanych do obrazu. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Umożliwia tworzenie instancji efektów obrazu. |
| [IInnerShadow](./iinnershadow) | Reprezentuje efekt wewnętrznego cienia. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Niezmienny obiekt reprezentujący efekt wewnętrznego cienia. |
| [ILuminance](./iluminance) | Reprezentuje efekt Luminance. Jasność liniowo przesuwa wszystkie kolory bliżej bieli lub czerni. Kontrast skaluje wszystkie kolory, aby były bliżej siebie lub dalej od siebie. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Reprezentuje efekt Luminance. Jasność liniowo przesuwa wszystkie kolory bliżej bieli lub czerni. Kontrast skaluje wszystkie kolory, aby były bliżej siebie lub dalej od siebie. |
| [IOuterShadow](./ioutershadow) | Reprezentuje efekt Outer Shadow. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Niezmienny obiekt reprezentujący efekt Outer Shadow. |
| [IPresetShadow](./ipresetshadow) | Reprezentuje efekt Preset Shadow. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Niezmienny obiekt reprezentujący efekt Preset Shadow. |
| [IReflection](./ireflection) | Reprezentuje efekt Reflection. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Niezmienny obiekt reprezentujący efekt Reflection. |
| [ISoftEdge](./isoftedge) | Reprezentuje efekt Soft Edge. Krawędzie kształtu są rozmyte, podczas gdy wypełnienie nie jest zmieniane. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Niezmienny obiekt reprezentujący efekt Soft Edge. Krawędzie kształtu są rozmyte, podczas gdy wypełnienie nie jest zmieniane. |
| [ITint](./itint) | Reprezentuje efekt Tint. Przesuwa wartości kolorów efektu w kierunku/od barwy o określoną wartość. |
| [ITintEffectiveData](./itinteffectivedata) | Niezmienny obiekt reprezentujący efekt Tint. Przesuwa wartości kolorów efektu w kierunku/od barwy o określoną wartość. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->