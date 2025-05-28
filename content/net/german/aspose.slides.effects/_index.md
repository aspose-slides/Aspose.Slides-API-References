---
title: Aspose.Slides.Effects
second_title: Aspose.Slides für .NET-API-Referenz
description: Enthält Klassen zum Arbeiten mit verschiedenen Effekten in Microsoft PowerPointPräsentationen.
type: docs
weight: 50
url: /de/aspose.slides.effects/
---
Enthält Klassen zum Arbeiten mit verschiedenen Effekten in Microsoft PowerPoint-Präsentationen.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Stellt einen Alpha-Bi-Level-Effekt dar. Alpha-Werte (Deckkraft) unter dem Schwellenwert werden in 0 (vollständig transparent) geändert und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden in 100 % (vollständig undurchsichtig) geändert. |
| [AlphaCeiling](./alphaceiling) | Stellt einen Alpha-Decke-Effekt dar. Alpha-Werte (Deckkraft) größer als Null werden auf 100 % geändert. Mit anderen Worten, alles, was teilweise undurchsichtig ist, wird vollständig undurchsichtig. |
| [AlphaFloor](./alphafloor) | Stellt einen Alpha-Bodeneffekt dar. Alpha-Werte (Deckkraft) von weniger als 100 % werden auf Null geändert. Mit anderen Worten, alles, was teilweise transparent ist, wird vollständig transparent. |
| [AlphaInverse](./alphainverse) | Repräsentiert einen inversen Alpha-Effekt. Alpha-Werte (Deckkraft) werden invertiert, indem sie von 100 % subtrahiert werden. |
| [AlphaModulate](./alphamodulate) | Repräsentiert einen Alpha-Modulationseffekt. Alpha-Werte (Deckkraft) von Effekten werden mit einem festen Prozentsatz multipliziert. Der Effektcontainer gibt einen Effekt an, der zu modulierende Alpha-Werte enthält. |
| [AlphaModulateFixed](./alphamodulatefixed) | Repräsentiert einen festen Alpha-Modulationseffekt. Alpha-Werte (Deckkraft) des Effekts werden mit einem festen Prozentsatz multipliziert. |
| [AlphaReplace](./alphareplace) | Stellt den Alpha-Ersetzungseffekt dar. Alpha-Werte (Deckkraft) des Effekts werden durch ein festes Alpha ersetzt. |
| [BiLevel](./bilevel) | Stellt einen Bi-Level-Effekt (Schwarz/Weiß) dar. Eingabefarben, deren Luminanz kleiner als der angegebene Schwellenwert ist, werden in Schwarz geändert. Eingabefarben, deren Luminanz größer oder gleich dem angegebenen Wert ist, werden auf Weiß gesetzt. Die Alpha-Effektwerte werden von diesem Effekt nicht beeinflusst. |
| [Blur](./blur) | Stellt einen Unschärfeeffekt dar, der auf die gesamte Form angewendet wird, einschließlich ihrer Füllung. Alle Farbkanäle, einschließlich Alpha, sind betroffen. |
| [ColorChange](./colorchange) | Repräsentiert einen Farbänderungseffekt. Instanzen von FromColor werden durch Instanzen von ToColor ersetzt. |
| [ColorReplace](./colorreplace) | Stellt einen Farbersetzungseffekt dar. Alle Effektfarben werden in eine feste Farbe geändert. Alpha-Werte bleiben unberührt. |
| [Duotone](./duotone) | Stellt einen Duotone-Effekt dar. Kombiniert für jedes Pixel Color1 und Color2 durch eine lineare Interpolation , um die neue Farbe für dieses Pixel zu bestimmen. |
| [EffectFactory](./effectfactory) | Ermöglicht das Erstellen von Effekten |
| [FillOverlay](./filloverlay) | Repräsentiert einen Füllüberlagerungseffekt. Eine Füllüberlagerung kann verwendet werden, um eine zusätzliche Füllung für ein Objekt anzugeben und die beiden Füllungen miteinander zu verschmelzen. |
| [Glow](./glow) | Stellt einen Leuchteffekt dar, bei dem ein farblich verschwommener Umriss außerhalb der Kanten des Objekts hinzugefügt wird. |
| [GrayScale](./grayscale) | Repräsentiert einen Graustufeneffekt. Konvertiert alle Effektfarbwerte in einen Grauton , der ihrer Leuchtdichte entspricht. Alpha-Werte (Deckkraft) des Effekts bleiben unberührt. |
| [HSL](./hsl) | Stellt einen Farbton-/Sättigungs-/Luminanzeffekt dar. Farbton, Sättigung und Luminanz können jeweils relativ zu ihrem aktuellen Wert angepasst werden. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Unveränderliches Objekt, das eine schreibgeschützte Sammlung effektiver Bildtransformationseffekte darstellt. |
| [ImageTransformOperation](./imagetransformoperation) | Stellt einen abstrakten Bildtransformationseffekt dar. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet werden. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Ermöglicht das Erstellen von Bildtransformationsoperationen |
| [InnerShadow](./innershadow) | Repräsentiert einen inneren Schatteneffekt. |
| [Luminance](./luminance) | Stellt einen Luminanzeffekt dar. Helligkeit verschiebt alle Farben linear näher an Weiß oder Schwarz. Kontrast skaliert alle Farben so, dass sie entweder näher oder weiter voneinander entfernt sind. |
| [OuterShadow](./outershadow) | Stellt einen äußeren Schatteneffekt dar. |
| [PresetShadow](./presetshadow) | Repräsentiert einen voreingestellten Schatteneffekt. |
| [Reflection](./reflection) | Stellt einen Reflexionseffekt dar. |
| [SoftEdge](./softedge) | Repräsentiert einen Soft-Edge-Effekt. Die Kanten der Form sind unscharf, während die Füllung nicht betroffen ist. |
| [Tint](./tint) | Stellt einen Tönungseffekt dar. Verschiebt die Effektfarbwerte um den angegebenen Betrag zum Farbton hin/weg vom Farbton. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Stellt einen Alpha-Bi-Level-Effekt dar. Alpha-Werte (Deckkraft) unter dem Schwellenwert werden in 0 (vollständig transparent) geändert und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden in 100 % (vollständig undurchsichtig) geändert. |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Unveränderliches Objekt, das einen Alpha-Bi-Level-Effekt darstellt. Alpha-Werte (Deckkraft) kleiner als der Schwellenwert werden auf 0 (vollständig transparent) geändert und Alpha-Werte größer oder gleich dem Schwellenwert werden auf 100 % geändert (vollständig deckend). |
| [IAlphaCeiling](./ialphaceiling) | Stellt einen Alpha-Decke-Effekt dar. Alpha-Werte (Deckkraft) größer als Null werden auf 100 % geändert. Mit anderen Worten, alles, was teilweise undurchsichtig ist, wird vollständig undurchsichtig. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Unveränderliches Objekt, das einen Alpha-Decke-Effekt darstellt. Alpha-Werte (Deckkraft) größer als Null werden auf 100 % geändert. Mit anderen Worten, alles, was teilweise undurchsichtig ist, wird vollständig undurchsichtig. |
| [IAlphaFloor](./ialphafloor) | Stellt einen Alpha-Bodeneffekt dar. Alpha-Werte (Deckkraft) von weniger als 100 % werden auf Null geändert. Mit anderen Worten, alles, was teilweise transparent ist, wird vollständig transparent. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Unveränderliches Objekt, das einen Alpha-Bodeneffekt darstellt. Alpha-Werte (Deckkraft) von weniger als 100 % werden auf Null geändert. Mit anderen Worten, alles, was teilweise transparent ist, wird vollständig transparent. |
| [IAlphaInverse](./ialphainverse) | Repräsentiert einen inversen Alpha-Effekt. Alpha-Werte (Deckkraft) werden invertiert, indem sie von 100 % subtrahiert werden. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Unveränderliches Objekt, das einen inversen Alpha-Effekt darstellt. Alpha-Werte (Deckkraft) werden durch Subtraktion von 100 % invertiert. |
| [IAlphaModulate](./ialphamodulate) | Repräsentiert einen Alpha-Modulationseffekt. Alpha-Werte (Deckkraft) von Effekten werden mit einem festen Prozentsatz multipliziert. Der Effektcontainer gibt einen Effekt an, der zu modulierende Alpha-Werte enthält. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Unveränderliches Objekt, das einen Alpha-Modulationseffekt darstellt. Alpha-Werte (Deckkraft) von Effekten werden mit einem festen Prozentsatz multipliziert. Der Effekt-Container gibt einen Effekt an, der zu modulierende Alpha-Werte enthält. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Repräsentiert einen festen Alpha-Modulationseffekt. Alpha-Werte (Deckkraft) des Effekts werden mit einem festen Prozentsatz multipliziert. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Unveränderliches Objekt, das einen festen Alpha-Modulationseffekt darstellt. Alpha-Werte (Deckkraft) des Effekts werden mit einem festen Prozentsatz multipliziert. |
| [IAlphaReplace](./ialphareplace) | Repräsentiert die IImageTransformOperation-Basisschnittstelle. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Unveränderliches Objekt, das einen Alpha-Ersetzungseffekt darstellt. Alpha-Werte (Deckkraft) des Effekts werden durch ein festes Alpha ersetzt. |
| [IBiLevel](./ibilevel) | Repräsentiert die IImageTransformOperation-Basisschnittstelle. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Unveränderliches Objekt, das einen Bi-Level-Effekt (Schwarz/Weiß) darstellt. Eingabefarben, deren Luminanz kleiner als der angegebene Schwellenwert ist, werden in Schwarz geändert. Eingabefarben, deren Luminanz größer oder gleich dem angegebenen Wert ist, werden auf Weiß gesetzt . Die Alpha-Effektwerte werden von diesem Effekt nicht beeinflusst. |
| [IBlur](./iblur) | Stellt einen Unschärfeeffekt dar, der auf die gesamte Form angewendet wird, einschließlich ihrer Füllung. Alle Farbkanäle, einschließlich Alpha, sind betroffen. |
| [IBlurEffectiveData](./iblureffectivedata) | Unveränderliches Objekt, das einen Unschärfeeffekt darstellt, der auf die gesamte Form angewendet wird, einschließlich ihrer Füllung. Alle Farbkanäle, einschließlich Alpha, sind betroffen. |
| [IColorChange](./icolorchange) | Repräsentiert einen Farbänderungseffekt. Instanzen von FromColor werden durch Instanzen von ToColor ersetzt. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Unveränderliches Objekt, das einen Farbänderungseffekt darstellt. Instanzen von FromColor werden durch Instanzen von ToColor ersetzt. |
| [IColorReplace](./icolorreplace) | Stellt einen Farbersetzungseffekt dar. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Unveränderliches Objekt, das einen Farbersetzungseffekt darstellt. Alle Effektfarben werden in eine feste Farbe geändert. Alphawerte werden nicht beeinflusst. |
| [IDuotone](./iduotone) | Stellt einen Duotone-Effekt dar. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Unveränderliches Objekt, das einen Duotone-Effekt darstellt. Kombiniert für jedes Pixel clr1 und clr2 durch eine lineare Interpolation , um die neue Farbe für dieses Pixel zu bestimmen. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Basisklasse für unveränderliche Objekte, die Wirkung darstellen. |
| [IEffectFactory](./ieffectfactory) | Ermöglicht das Erstellen von Effektinstanzen |
| [IFillOverlay](./ifilloverlay) | Repräsentiert einen Füllüberlagerungseffekt. Eine Füllüberlagerung kann verwendet werden, um eine zusätzliche Füllung für ein Objekt anzugeben und die beiden Füllungen miteinander zu verschmelzen. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Unveränderliches Objekt, das einen Füllüberlagerungseffekt darstellt. Eine Füllüberlagerung kann verwendet werden, um eine zusätzliche Füllung für ein Objekt anzugeben und die beiden Füllungen miteinander zu verschmelzen. |
| [IGlow](./iglow) | Stellt einen Leuchteffekt dar, bei dem ein farblich verschwommener Umriss außerhalb der Kanten des Objekts hinzugefügt wird. |
| [IGlowEffectiveData](./igloweffectivedata) | Unveränderliches Objekt, das einen Glow-Effekt darstellt, bei dem eine farblich verschwommene Kontur außerhalb der Kanten des Objekts hinzugefügt wird. |
| [IGrayScale](./igrayscale) | Repräsentiert die IImageTransformOperation-Schnittstelle. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Unveränderliches Objekt, das einen Graustufeneffekt darstellt. Konvertiert alle Effektfarbwerte in einen Grauton , der ihrer Leuchtdichte entspricht. Alpha-Werte (Deckkraft) des Effekts bleiben unberührt. |
| [IHSL](./ihsl) | Stellt einen Farbton-/Sättigungs-/Luminanzeffekt dar. Farbton, Sättigung und Luminanz können jeweils relativ zu ihrem aktuellen Wert angepasst werden. |
| [IHSLEffectiveData](./ihsleffectivedata) | Stellt einen Farbton-/Sättigungs-/Luminanzeffekt dar. Farbton, Sättigung und Luminanz können jeweils relativ zu ihrem aktuellen Wert angepasst werden. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Unveränderliches Objekt, das eine schreibgeschützte Sammlung effektiver Bildtransformationseffekte darstellt. |
| [IImageTransformOperation](./iimagetransformoperation) | Stellt einen abstrakten Bildtransformationseffekt dar. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet werden. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Ermöglicht das Erstellen von Instanzen von Bildeffekten |
| [IInnerShadow](./iinnershadow) | Stellt einen inneren Schatteneffekt dar. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Unveränderliches Objekt, das einen inneren Schatteneffekt darstellt. |
| [ILuminance](./iluminance) | Stellt einen Luminanzeffekt dar. Helligkeit verschiebt alle Farben linear näher an Weiß oder Schwarz. Kontrast skaliert alle Farben so, dass sie entweder näher oder weiter voneinander entfernt sind. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Stellt einen Luminanzeffekt dar. Helligkeit verschiebt alle Farben linear näher an Weiß oder Schwarz. Kontrast skaliert alle Farben so, dass sie entweder näher oder weiter voneinander entfernt sind. |
| [IOuterShadow](./ioutershadow) | Stellt einen äußeren Schatteneffekt dar. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Unveränderliches Objekt, das einen äußeren Schatteneffekt darstellt. |
| [IPresetShadow](./ipresetshadow) | Repräsentiert einen voreingestellten Schatteneffekt. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Unveränderliches Objekt, das einen voreingestellten Schatteneffekt darstellt. |
| [IReflection](./ireflection) | Stellt einen Reflexionseffekt dar. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Unveränderliches Objekt, das einen Reflexionseffekt darstellt. |
| [ISoftEdge](./isoftedge) | Repräsentiert einen Soft Edge-Effekt. Die Kanten der Form sind unscharf, während die Füllung nicht betroffen ist. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Unveränderliches Objekt, das einen Soft-Edge-Effekt darstellt. Die Kanten der Form sind unscharf, während die Füllung nicht betroffen ist. |
| [ITint](./itint) | Stellt einen Tönungseffekt dar. Verschiebt die Effektfarbwerte um den angegebenen Betrag zum Farbton hin/weg vom Farbton. |
| [ITintEffectiveData](./itinteffectivedata) | Unveränderliches Objekt, das einen Tönungseffekt darstellt. Verschiebt die Effektfarbwerte um den angegebenen Betrag zum Farbton hin/weg vom Farbton. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
