---
title: IPictureFillFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een afbeeldingvullingsstijl voor.
type: docs
weight: 6650
url: /nl/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interface

Stelt een afbeeldingvullingsstijl voor.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Stelt u in staat om de basis-IFillParamSource-interface op te halen. Alleen-lezen [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat onderaan de afbeelding wordt bijgesneden, terug of stelt dit in. Lezen/Schrijven Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat aan de linkerkant van de afbeelding wordt bijgesneden, terug of stelt dit in. Lezen/Schrijven Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat aan de rechterkant van de afbeelding wordt bijgesneden, terug of stelt dit in. Lezen/Schrijven Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat bovenaan de afbeelding wordt bijgesneden, terug of stelt dit in. Lezen/Schrijven Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Geeft de DPI die wordt gebruikt om een afbeelding te vullen, terug of stelt deze in. Lezen/Schrijven Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Geeft de afbeelding terug. Alleen-lezen [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Geeft de modus voor het vullen van de afbeelding terug of stelt deze in. Lezen/Schrijven [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Geeft de onderrand van de vulrechthoek terug die wordt gedefinieerd door een procentuele offset vanaf de onderrand van de begrenzingsvak van de vorm, of stelt deze in. Een positief percentage geeft een inspringing aan, terwijl een negatief percentage een uitsteeksel aangeeft. Lezen/Schrijven Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Geeft de linkerrand van de vulrechthoek terug die wordt gedefinieerd door een procentuele offset vanaf de linkerrand van de begrenzingsvak van de vorm, of stelt deze in. Een positief percentage geeft een inspringing aan, terwijl een negatief percentage een uitsteeksel aangeeft. Lezen/Schrijven Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Geeft de rechterrand van de vulrechthoek terug die wordt gedefinieerd door een procentuele offset vanaf de rechterrand van de begrenzingsvak van de vorm, of stelt deze in. Een positief percentage geeft een inspringing aan, terwijl een negatief percentage een uitsteeksel aangeeft. Lezen/Schrijven Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Geeft de boverrand van de vulrechthoek terug die wordt gedefinieerd door een procentuele offset vanaf de boverrand van de begrenzingsvak van de vorm, of stelt deze in. Een positief percentage geeft een inspringing aan, terwijl een negatief percentage een uitsteeksel aangeeft. Lezen/Schrijven Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Geeft terug hoe de textuur binnen de vorm is uitgelijnd, of stelt dit in. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich herhaalt over de vorm. Lezen/Schrijven [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Keert het textuurtegeltje om rond zijn horizontale, verticale of beide assen. Lezen/Schrijven [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Geeft de horizontale offset van de textuur vanaf de oorsprong van de vorm in punten terug of stelt deze in. Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde deze naar links verplaatst. Lezen/Schrijven Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Geeft de verticale offset van de textuur vanaf de oorsprong van de vorm in punten terug of stelt deze in. Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde deze naar boven verplaatst. Lezen/Schrijven Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Geeft de horizontale schaal voor de textuurvulling als percentage terug of stelt deze in. Lezen/Schrijven Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Geeft de verticale schaal voor de textuurvulling als percentage terug of stelt deze in. Lezen/Schrijven Single. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de grootte van de vorm en de gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de grootte van de vorm en de gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Verwijdert bijgesneden gebieden van de vulafbeelding. |

### Zie ook

* interface [IFillParamSource](../ifillparamsource)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->