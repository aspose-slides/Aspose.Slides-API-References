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
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Staat toe de basis IFillParamSource interface op te halen. Alleen-lezen [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat onderaan de afbeelding wordt bijgesneden, of stelt dit in. Lezen/schrijven Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat links van de afbeelding wordt bijgesneden, of stelt dit in. Lezen/schrijven Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat rechts van de afbeelding wordt bijgesneden, of stelt dit in. Lezen/schrijven Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat bovenaan de afbeelding wordt bijgesneden, of stelt dit in. Lezen/schrijven Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Geeft de dpi die wordt gebruikt om een afbeelding te vullen, of stelt deze in. Lezen/schrijven Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Geeft de afbeelding terug. Alleen-lezen [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Geeft de afbeeldingvullingsmodus terug, of stelt deze in. Lezen/schrijven [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Geeft de onderste rand van het vulrechthoek terug die wordt gedefinieerd door een procentuele offset ten opzichte van de onderste rand van de omhullende van de vorm, of stelt deze in. Een positieve procentwaarde geeft een insnijding aan, een negatieve procentwaarde een uitsnijding. Lezen/schrijven Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Geeft de linker rand van het vulrechthoek terug die wordt gedefinieerd door een procentuele offset ten opzichte van de linker rand van de omhullende van de vorm, of stelt deze in. Een positieve procentwaarde geeft een insnijding aan, een negatieve procentwaarde een uitsnijding. Lezen/schrijven Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Geeft de rechter rand van het vulrechthoek terug die wordt gedefinieerd door een procentuele offset ten opzichte van de rechter rand van de omhullende van de vorm, of stelt deze in. Een positieve procentwaarde geeft een insnijding aan, een negatieve procentwaarde een uitsnijding. Lezen/schrijven Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Geeft de bovenste rand van het vulrechthoek terug die wordt gedefinieerd door een procentuele offset ten opzichte van de bovenste rand van de omhullende van de vorm, of stelt deze in. Een positieve procentwaarde geeft een insnijding aan, een negatieve procentwaarde een uitsnijding. Lezen/schrijven Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Geeft aan hoe de textuur is uitgelijnd binnen de vorm. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich herhaalt over de vorm. Lezen/schrijven [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Draait de textuurtegel rond zijn horizontale, verticale of beide assen. Lezen/schrijven [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Geeft de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten, of stelt deze in. Een positieve waarde verplaatst de textuur naar rechts, een negatieve waarde naar links. Lezen/schrijven Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Geeft de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten, of stelt deze in. Een positieve waarde verplaatst de textuur naar beneden, een negatieve waarde naar boven. Lezen/schrijven Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Geeft de horizontale schaal voor de textuurvulling als een procent, of stelt deze in. Lezen/schrijven Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Geeft de verticale schaal voor de textuurvulling als een procent, of stelt deze in. Lezen/schrijven Single. |

## Methodes

| Naam | Beschrijving |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Verwijder bijgesneden gebieden van de vulafbeelding. |

### Zie ook

* interface [IFillParamSource](../ifillparamsource)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->