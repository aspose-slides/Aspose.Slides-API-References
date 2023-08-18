---
title: ImageTransformOperationCollection
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Sammlung von Effekten dar die auf ein Bild angewendet werden.
type: docs
weight: 3400
url: /de/aspose.slides.effects/imagetransformoperationcollection/
---
## ImageTransformOperationCollection class

Stellt eine Sammlung von Effekten dar, die auf ein Bild angewendet werden.

```csharp
public sealed class ImageTransformOperationCollection : PVIObject, 
    IImageTransformOperationCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPPresentationComponent-Schnittstelle. Schreibgeschützt[`IPresentationComponent`](../../aspose.slides/ipresentationcomponent) . |
| [Count](../../aspose.slides.effects/imagetransformoperationcollection/count) { get; } | Gibt die Anzahl der Bildeffekte in einer Sammlung zurück. SchreibgeschütztInt32 . |
| [IsReadOnly](../../aspose.slides.effects/imagetransformoperationcollection/isreadonly) { get; } | Ruft einen Wert ab, der angibt, ob dieICollection ist schreibgeschützt. Nur lesbarBoolean . |
| [Item](../../aspose.slides.effects/imagetransformoperationcollection/item) { get; } | Gibt ein zurück[`ImageTransformOperation`](../imagetransformoperation) aus der Sammlung nach Index. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.slides.effects/imagetransformoperationcollection/add)(IImageTransformOperation) | Fügt den neuen Bildeffekt am Ende einer Sammlung hinzu. |
| [AddAlphaBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphabileveleffect)(float) | Fügt den neuen Alpha Bi-Level-Effekt am Ende einer Sammlung hinzu. |
| [AddAlphaCeilingEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaceilingeffect)() | Fügt den neuen Effekt „Alpha-Decke“ am Ende einer Sammlung hinzu. |
| [AddAlphaFloorEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaflooreffect)() | Fügt den neuen Alpha Floor-Effekt am Ende einer Sammlung hinzu. |
| [AddAlphaInverseEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphainverseeffect)() | Fügt den neuen Effekt Alpha Inverse am Ende einer Sammlung hinzu. |
| [AddAlphaModulateEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulateeffect)() | Fügt den neuen Alpha Modulate-Effekt am Ende einer Sammlung hinzu. |
| [AddAlphaModulateFixedEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulatefixedeffect)(float) | Fügt den neuen Effekt Alpha Modulate Fixed am Ende einer Sammlung hinzu. |
| [AddAlphaReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphareplaceeffect)(float) | Fügt den neuen Alpha-Replace-Effekt am Ende einer Sammlung hinzu. |
| [AddBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbileveleffect)(float) | Fügt den neuen Bi-Level-Effekt (schwarz/weiß) am Ende einer Sammlung hinzu. |
| [AddBlurEffect](../../aspose.slides.effects/imagetransformoperationcollection/addblureffect)(double, bool) | Fügt den neuen Blur-Effekt am Ende einer Sammlung hinzu. |
| [AddColorChangeEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorchangeeffect)() | Fügt den neuen Farbänderungseffekt am Ende einer Sammlung hinzu. |
| [AddColorReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorreplaceeffect)() | Fügt den neuen Farbersetzungseffekt am Ende einer Sammlung hinzu. |
| [AddDuotoneEffect](../../aspose.slides.effects/imagetransformoperationcollection/addduotoneeffect)() | Fügt den neuen Duotone-Effekt am Ende einer Sammlung hinzu. |
| [AddFillOverlayEffect](../../aspose.slides.effects/imagetransformoperationcollection/addfilloverlayeffect)() | Fügt den neuen Füllüberlagerungseffekt am Ende einer Sammlung hinzu. |
| [AddGrayScaleEffect](../../aspose.slides.effects/imagetransformoperationcollection/addgrayscaleeffect)() | Fügt den neuen Graustufeneffekt am Ende einer Sammlung hinzu. |
| [AddHSLEffect](../../aspose.slides.effects/imagetransformoperationcollection/addhsleffect)(float, float, float) | Fügt den neuen Effekt „Farbton/Sättigung/Luminanz“ am Ende einer Sammlung hinzu. |
| [AddLuminanceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addluminanceeffect)(float, float) | Fügt den neuen Luminanzeffekt am Ende einer Sammlung hinzu. |
| [AddTintEffect](../../aspose.slides.effects/imagetransformoperationcollection/addtinteffect)(float, float) | Fügt den neuen Tint-Effekt am Ende einer Sammlung hinzu. |
| [Clear](../../aspose.slides.effects/imagetransformoperationcollection/clear)() | Entfernt alle Bildeffekte aus einer Sammlung. |
| [Contains](../../aspose.slides.effects/imagetransformoperationcollection/contains)(IImageTransformOperation) | Bestimmt, ob dieICollection enthält einen bestimmten Wert. |
| [CopyTo](../../aspose.slides.effects/imagetransformoperationcollection/copyto)(IImageTransformOperation[], int) | Kopiert die Elemente derICollection zu einemArray , beginnend bei einem bestimmtenArray index. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit angegebenem Objekt. |
| [GetEnumerator](../../aspose.slides.effects/imagetransformoperationcollection/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt Hash-Code zurück. |
| [Remove](../../aspose.slides.effects/imagetransformoperationcollection/remove)(IImageTransformOperation) | Entfernt das erste Vorkommen eines bestimmten Objekts aus derICollection . |
| [RemoveAt](../../aspose.slides.effects/imagetransformoperationcollection/removeat)(int) | Entfernt einen Bildeffekt aus einer Sammlung am angegebenen Index. |

### Siehe auch

* class [PVIObject](../../aspose.slides/pviobject)
* interface [IImageTransformOperationCollection](../iimagetransformoperationcollection)
* namensraum [Aspose.Slides.Effects](../../aspose.slides.effects)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
