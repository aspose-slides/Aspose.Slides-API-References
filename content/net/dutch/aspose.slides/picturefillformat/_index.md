---
title: PictureFillFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een afbeeldingvulstijl voor.
type: docs
weight: 9390
url: /nl/aspose.slides/picturefillformat/
---
## PictureFillFormat klasse

Represents a picture fill style.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe de basis IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat vanaf de onderkant van de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingbreedte dat vanaf de linkerkant van de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingbreedte dat vanaf de rechterkant van de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat vanaf de bovenkant van de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Geeft de dpi die wordt gebruikt om een afbeelding te vullen terug of stelt deze in. Lezen/schrijven Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Geeft de afbeelding terug. Alleen-lezen [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Geeft de vulmodus van de afbeelding terug of stelt deze in. Lezen/schrijven [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Geeft de onderkant van de vulrechthoek terug of stelt deze in, gedefinieerd als een procentuele offset ten opzichte van de onderkant van de omhullende doos van de vorm. Een positief percentage geeft een inset aan, een negatief percentage een outset. Lezen/schrijven Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Geeft de linkerkant van de vulrechthoek terug of stelt deze in, gedefinieerd als een procentuele offset ten opzichte van de linkerkant van de omhullende doos van de vorm. Een positief percentage geeft een inset aan, een negatief percentage een outset. Lezen/schrijven Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Geeft de rechterkant van de vulrechthoek terug of stelt deze in, gedefinieerd als een procentuele offset ten opzichte van de rechterkant van de omhullende doos van de vorm. Een positief percentage geeft een inset aan, een negatief percentage een outset. Lezen/schrijven Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Geeft de bovenkant van de vulrechthoek terug of stelt deze in, gedefinieerd als een procentuele offset ten opzichte van de bovenkant van de omhullende doos van de vorm. Een positief percentage geeft een inset aan, een negatief percentage een outset. Lezen/schrijven Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Geeft terug hoe de textuur binnen de vorm is uitgelijnd of stelt dit in. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich over de vorm herhaalt. Lezen/schrijven [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Spiegelt de textuurtegels horizontaal, verticaal of langs beide assen. Lezen/schrijven [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Geeft de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm terug in punten of stelt deze in. Een positieve waarde verplaatst de textuur naar rechts, een negatieve waarde naar links. Lezen/schrijven Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Geeft de verticale offset van de textuur ten opzichte van de oorsprong van de vorm terug in punten of stelt deze in. Een positieve waarde verplaatst de textuur naar beneden, een negatieve waarde naar boven. Lezen/schrijven Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Geeft de horizontale schaal voor de textuurvulling terug als percentage of stelt deze in. Lezen/schrijven Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Geeft de verticale schaal voor de textuurvulling terug als percentage of stelt deze in. Lezen/schrijven Single. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Verwijdert bijgesneden gebieden van de vulafbeelding. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Geeft de hashcode terug. |

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IPictureFillFormat](../ipicturefillformat)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->