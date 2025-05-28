---
title: Aspose.Slides.Effects
second_title: Aspose.Slides für .NET API-Referenz
description: Enthält Klassen zur Arbeit mit verschiedenen Effekten in Microsoft PowerPoint-Präsentationen.
type: docs
weight: 50
url: /de/aspose.slides.effects/
---

Enthält Klassen zur Arbeit mit verschiedenen Effekten in Microsoft PowerPoint-Präsentationen.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Stellt einen Alpha Bi-Level-Effekt dar. Alpha (Opazität) Werte, die kleiner als der Schwellenwert sind, werden auf 0 (vollständig transparent) geändert, und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden auf 100% (vollständig undurchsichtig) geändert. |
| [AlphaCeiling](./alphaceiling) | Stellt einen Alpha Ceiling-Effekt dar. Alpha (Opazität) Werte, die größer als null sind, werden auf 100% geändert. Mit anderen Worten, alles, was teilweise undurchsichtig ist, wird vollständig undurchsichtig. |
| [AlphaFloor](./alphafloor) | Stellt einen Alpha Floor-Effekt dar. Alpha (Opazität) Werte, die kleiner als 100% sind, werden auf null geändert. Mit anderen Worten, alles, was teilweise transparent ist, wird vollständig transparent. |
| [AlphaInverse](./alphainverse) | Stellt einen Alpha Inverse-Effekt dar. Alpha (Opazität) Werte werden invertiert, indem sie von 100% subtrahiert werden. |
| [AlphaModulate](./alphamodulate) | Stellt einen Alpha Modulate-Effekt dar. Effekt-Alpha (Opazität) Werte werden mit einem festen Prozentsatz multipliziert. Der Effektcontainer gibt einen Effekt an, der Alpha-Werte zur Modulation enthält. |
| [AlphaModulateFixed](./alphamodulatefixed) | Stellt einen Alpha Modulate Fixed-Effekt dar. Effekt-Alpha (Opazität) Werte werden mit einem festen Prozentsatz multipliziert. |
| [AlphaReplace](./alphareplace) | Stellt einen Alpha Replace-Effekt dar. Effekt-Alpha (Opazität) Werte werden durch einen festen Alpha-Wert ersetzt. |
| [BiLevel](./bilevel) | Stellt einen Bi-Level (schwarz/weiß) Effekt dar. Eingabefarben, deren Luminanz kleiner ist als der spezifizierte Schwellenwert, werden auf schwarz geändert. Eingabefarben, deren Luminanz größer oder gleich dem spezifizierten Wert sind, werden auf weiß gesetzt. Die Alpha-Effektwerte werden von diesem Effekt nicht beeinflusst. |
| [Blur](./blur) | Stellt einen Blur-Effekt dar, der auf die gesamte Form angewendet wird, einschließlich ihrer Füllung. Alle Farbkkanäle, einschließlich Alpha, sind betroffen. |
| [ColorChange](./colorchange) | Stellt einen Color Change-Effekt dar. Instanzen von FromColor werden durch Instanzen von ToColor ersetzt. |
| [ColorReplace](./colorreplace) | Stellt einen Color Replacement-Effekt dar. Alle Effekfarben werden in eine feste Farbe geändert. Alpha-Werte bleiben unbeeinflusst. |
| [Duotone](./duotone) | Stellt einen Duotone-Effekt dar. Für jedes Pixel kombiniert er Color1 und Color2 durch eine lineare Interpolation, um die neue Farbe für dieses Pixel zu bestimmen. |
| [EffectFactory](./effectfactory) | Ermöglicht die Erstellung von Effekten |
| [FillOverlay](./filloverlay) | Stellt einen Fill Overlay-Effekt dar. Ein Fülloverlay kann verwendet werden, um eine zusätzliche Füllung für ein Objekt anzugeben und die beiden Füllungen zu mischen. |
| [Glow](./glow) | Stellt einen Glow-Effekt dar, bei dem eine farbige, verschwommene Kontur außerhalb der Kanten des Objekts hinzugefügt wird. |
| [GrayScale](./grayscale) | Stellt einen Gray Scale-Effekt dar. Wandelt alle Effekfarbwerte in einen Grauton um, der ihrer Luminanz entspricht. Effekt-Alpha (Opazität) Werte bleiben unbeeinflusst. |
| [HSL](./hsl) | Stellt einen Hue/Saturation/Luminance-Effekt dar. Der Farbton, die Sättigung und die Luminanz können jeweils relativ zu ihrem aktuellen Wert angepasst werden. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Unveränderbares Objekt, das eine schreibgeschützte Sammlung von effektiven Bildtransformations Effekten darstellt. |
| [ImageTransformOperation](./imagetransformoperation) | Stellt einen abstrakten Bildtransformations-Effekt dar. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet wurden. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Ermöglicht die Erstellung von Bildtransformationsoperationen |
| [InnerShadow](./innershadow) | Stellt einen Inner Shadow-Effekt dar. |
| [Luminance](./luminance) | Stellt einen Luminance-Effekt dar. Helligkeit verschiebt alle Farben linear näher zu weiß oder schwarz. Der Kontrast skaliert alle Farben, um entweder näher zusammen oder weiter auseinander zu sein. |
| [OuterShadow](./outershadow) | Stellt einen Outer Shadow-Effekt dar. |
| [PresetShadow](./presetshadow) | Stellt einen Preset Shadow-Effekt dar. |
| [Reflection](./reflection) | Stellt einen Reflection-Effekt dar. |
| [SoftEdge](./softedge) | Stellt einen Soft Edge-Effekt dar. Die Kanten der Form werden unscharf, während die Füllung nicht betroffen ist. |
| [Tint](./tint) | Stellt einen Tint-Effekt dar. Verschiebt die Farbwerte des Effekts in Richtung/Fern von dem Farbton um den angegebenen Betrag. |

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Stellt einen Alpha Bi-Level-Effekt dar. Alpha (Opazität) Werte, die kleiner als der Schwellenwert sind, werden auf 0 (vollständig transparent) geändert, und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden auf 100% (vollständig undurchsichtig) geändert. |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Unveränderbares Objekt, das einen Alpha Bi-Level-Effekt darstellt. Alpha (Opazität) Werte, die kleiner als der Schwellenwert sind, werden auf 0 (vollständig transparent) geändert, und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden auf 100% (vollständig undurchsichtig) geändert. |
| [IAlphaCeiling](./ialphaceiling) | Stellt einen Alpha Ceiling-Effekt dar. Alpha (Opazität) Werte, die größer als null sind, werden auf 100% geändert. Mit anderen Worten, alles, was teilweise undurchsichtig ist, wird vollständig undurchsichtig. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Unveränderbares Objekt, das einen Alpha Ceiling-Effekt darstellt. Alpha (Opazität) Werte, die größer als null sind, werden auf 100% geändert. Mit anderen Worten, alles, was teilweise undurchsichtig ist, wird vollständig undurchsichtig. |
| [IAlphaFloor](./ialphafloor) | Stellt einen Alpha Floor-Effekt dar. Alpha (Opazität) Werte, die kleiner als 100% sind, werden auf null geändert. Mit anderen Worten, alles, was teilweise transparent ist, wird vollständig transparent. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Unveränderbares Objekt, das einen Alpha Floor-Effekt darstellt. Alpha (Opazität) Werte, die kleiner als 100% sind, werden auf null geändert. Mit anderen Worten, alles, was teilweise transparent ist, wird vollständig transparent. |
| [IAlphaInverse](./ialphainverse) | Stellt einen Alpha Inverse-Effekt dar. Alpha (Opazität) Werte werden invertiert, indem sie von 100% subtrahiert werden. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Unveränderbares Objekt, das einen Alpha Inverse-Effekt darstellt. Alpha (Opazität) Werte werden invertiert, indem sie von 100% subtrahiert werden. |
| [IAlphaModulate](./ialphamodulate) | Stellt einen Alpha Modulate-Effekt dar. Effekt-Alpha (Opazität) Werte werden mit einem festen Prozentsatz multipliziert. Der Effektcontainer gibt einen Effekt an, der Alpha-Werte zur Modulation enthält. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Unveränderbares Objekt, das einen Alpha Modulate-Effekt darstellt. Effekt-Alpha (Opazität) Werte werden mit einem festen Prozentsatz multipliziert. Der Effektcontainer gibt einen Effekt an, der Alpha-Werte zur Modulation enthält. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Stellt einen Alpha Modulate Fixed-Effekt dar. Effekt-Alpha (Opazität) Werte werden mit einem festen Prozentsatz multipliziert. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Unveränderbares Objekt, das einen Alpha Modulate Fixed-Effekt darstellt. Effekt-Alpha (Opazität) Werte werden mit einem festen Prozentsatz multipliziert. |
| [IAlphaReplace](./ialphareplace) | Stellt die Basis-IImageTransformOperation-Schnittstelle dar. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Unveränderbares Objekt, das einen Alpha Replace-Effekt darstellt. Effekt-Alpha (Opazität) Werte werden durch einen festen Alpha-Wert ersetzt. |
| [IBiLevel](./ibilevel) | Stellt die Basis-IImageTransformOperation-Schnittstelle dar. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Unveränderbares Objekt, das einen Bi-Level (schwarz/weiß) Effekt darstellt. Eingabefarben, deren Luminanz kleiner ist als der spezifizierte Schwellenwert, werden auf schwarz geändert. Eingabefarben, deren Luminanz größer oder gleich dem spezifizierten Wert sind, werden auf weiß gesetzt. Die Alpha-Effektwerte werden von diesem Effekt nicht beeinflusst. |
| [IBlur](./iblur) | Stellt einen Blur-Effekt dar, der auf die gesamte Form angewendet wird, einschließlich ihrer Füllung. Alle Farbkkanäle, einschließlich Alpha, sind betroffen. |
| [IBlurEffectiveData](./iblureffectivedata) | Unveränderbares Objekt, das einen Blur-Effekt darstellt, der auf die gesamte Form angewendet wird, einschließlich ihrer Füllung. Alle Farbkkanäle, einschließlich Alpha, sind betroffen. |
| [IColorChange](./icolorchange) | Stellt einen Color Change-Effekt dar. Instanzen von FromColor werden durch Instanzen von ToColor ersetzt. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Unveränderbares Objekt, das einen Color Change-Effekt darstellt. Instanzen von FromColor werden durch Instanzen von ToColor ersetzt. |
| [IColorReplace](./icolorreplace) | Stellt einen Color Replacement-Effekt dar. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Unveränderbares Objekt, das einen Color Replacement-Effekt darstellt. Alle Effekfarben werden in eine feste Farbe geändert. Alpha-Werte bleiben unbeeinflusst. |
| [IDuotone](./iduotone) | Stellt einen Duotone-Effekt dar. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Unveränderbares Objekt, das einen Duotone-Effekt darstellt. Für jedes Pixel kombiniert er clr1 und clr2 durch eine lineare Interpolation, um die neue Farbe für dieses Pixel zu bestimmen. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Basisklasse für unveränderbare Objekte, die einen Effekt darstellen. |
| [IEffectFactory](./ieffectfactory) | Ermöglicht die Erstellung von Instanzen von Effekten |
| [IFillOverlay](./ifilloverlay) | Stellt einen Fill Overlay-Effekt dar. Ein Fülloverlay kann verwendet werden, um eine zusätzliche Füllung für ein Objekt anzugeben und die beiden Füllungen zu mischen. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Unveränderbares Objekt, das einen Fill Overlay-Effekt darstellt. Ein Fülloverlay kann verwendet werden, um eine zusätzliche Füllung für ein Objekt anzugeben und die beiden Füllungen zu mischen. |
| [IGlow](./iglow) | Stellt einen Glow-Effekt dar, bei dem eine farbige, verschwommene Kontur außerhalb der Kanten des Objekts hinzugefügt wird. |
| [IGlowEffectiveData](./igloweffectivedata) | Unveränderbares Objekt, das einen Glow-Effekt darstellt, bei dem eine farbige, verschwommene Kontur außerhalb der Kanten des Objekts hinzugefügt wird. |
| [IGrayScale](./igrayscale) | Stellt die IImageTransformOperation-Schnittstelle dar. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Unveränderbares Objekt, das einen Gray Scale-Effekt darstellt. Wandelt alle Effekfarbwerte in einen Grauton um, der ihrer Luminanz entspricht. Effekt-Alpha (Opazität) Werte bleiben unbeeinflusst. |
| [IHSL](./ihsl) | Stellt einen Hue/Saturation/Luminance-Effekt dar. Der Farbton, die Sättigung und die Luminanz können jeweils relativ zu ihrem aktuellen Wert angepasst werden. |
| [IHSLEffectiveData](./ihsleffectivedata) | Stellt einen Hue/Saturation/Luminance-Effekt dar. Der Farbton, die Sättigung und die Luminanz können jeweils relativ zu ihrem aktuellen Wert angepasst werden. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Unveränderbares Objekt, das eine schreibgeschützte Sammlung von effektiven Bildtransformations Effekten darstellt. |
| [IImageTransformOperation](./iimagetransformoperation) | Stellt einen abstrakten Bildtransformations-Effekt dar. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet wurden. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Ermöglicht die Erstellung von Instanzen von Bildeffekten |
| [IInnerShadow](./iinnershadow) | Stellt einen Inner Shadow-Effekt dar. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Unveränderbares Objekt, das einen Inner Shadow-Effekt darstellt. |
| [ILuminance](./iluminance) | Stellt einen Luminance-Effekt dar. Helligkeit verschiebt alle Farben linear näher zu weiß oder schwarz. Der Kontrast skaliert alle Farben, um entweder näher zusammen oder weiter auseinander zu sein. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Stellt einen Luminance-Effekt dar. Helligkeit verschiebt alle Farben linear näher zu weiß oder schwarz. Der Kontrast skaliert alle Farben, um entweder näher zusammen oder weiter auseinander zu sein. |
| [IOuterShadow](./ioutershadow) | Stellt einen Outer Shadow-Effekt dar. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Unveränderbares Objekt, das einen Outer Shadow-Effekt darstellt. |
| [IPresetShadow](./ipresetshadow) | Stellt einen Preset Shadow-Effekt dar. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Unveränderbares Objekt, das einen Preset Shadow-Effekt darstellt. |
| [IReflection](./ireflection) | Stellt einen Reflection-Effekt dar. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Unveränderbares Objekt, das einen Reflection-Effekt darstellt. |
| [ISoftEdge](./isoftedge) | Stellt einen Soft Edge-Effekt dar. Die Kanten der Form werden unscharf, während die Füllung nicht betroffen ist. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Unveränderbares Objekt, das einen Soft Edge-Effekt darstellt. Die Kanten der Form werden unscharf, während die Füllung nicht betroffen ist. |
| [ITint](./itint) | Stellt einen Tint-Effekt dar. Verschiebt die Farbwerte des Effekts in Richtung/Fern von dem Farbton um den angegebenen Betrag. |
| [ITintEffectiveData](./itinteffectivedata) | Unveränderbares Objekt, das einen Tint-Effekt darstellt. Verschiebt die Farbwerte des Effekts in Richtung/Fern von dem Farbton um den angegebenen Betrag. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->