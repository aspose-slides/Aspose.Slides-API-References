---
title: IPictureFillFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een afbeeldingsvullingsstijl voor.
type: docs
weight: 6670
url: /nl/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interface

Stelt een afbeeldingsvullingsstijl voor.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Staat toe de basis IFillParamSource interface op te halen. Alleen-lezen [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Geeft of stelt het aantal procenten van de werkelijke afbeeldingshoogte in dat onderaan de afbeelding wordt bijgesneden. Lezen/schrijven Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Geeft of stelt het aantal procenten van de werkelijke afbeeldingsbreedte in dat aan de linkerkant van de afbeelding wordt bijgesneden. Lezen/schrijven Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Geeft of stelt het aantal procenten van de werkelijke afbeeldingsbreedte in dat aan de rechterkant van de afbeelding wordt bijgesneden. Lezen/schrijven Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Geeft of stelt het aantal procenten van de werkelijke afbeeldingshoogte in dat aan de bovenkant van de afbeelding wordt bijgesneden. Lezen/schrijven Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Geeft of stelt de dpi in die wordt gebruikt om een afbeelding te vullen. Lezen/schrijven Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Geeft de afbeelding terug. Alleen-lezen [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Geeft of stelt de afbeeldingenvullingsmodus in. Lezen/schrijven [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Geeft of stelt de onderkant van de vulrechthoek in die wordt gedefinieerd door een percentage offset vanaf de onderkant van de begrenzingsdoos van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Lezen/schrijven Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Geeft of stelt de linkerkant van de vulrechthoek in die wordt gedefinieerd door een percentage offset vanaf de linkerkant van de begrenzingsdoos van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Lezen/schrijven Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Geeft of stelt de rechterkant van de vulrechthoek in die wordt gedefinieerd door een percentage offset vanaf de rechterkant van de begrenzingsdoos van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Lezen/schrijven Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Geeft of stelt de bovenkant van de vulrechthoek in die wordt gedefinieerd door een percentage offset vanaf de bovenkant van de begrenzingsdoos van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Lezen/schrijven Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Geeft of stelt in hoe de textuur binnen de vorm wordt uitgelijnd. Deze instelling regelt het startpunt van het textuurpatroon en hoe het zich herhaalt over de vorm. Lezen/schrijven [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Draait de textuurtile rond zijn horizontale, verticale of beide assen. Lezen/schrijven [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Geeft of stelt de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde naar links verplaatst. Lezen/schrijven Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Geeft of stelt de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde naar boven verplaatst. Lezen/schrijven Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Geeft of stelt de horizontale schaal voor de textuurvulling als een percentage in. Lezen/schrijven Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Geeft of stelt de verticale schaal voor de textuurvulling als een percentage in. Lezen/schrijven Single. |

## Methodes

| Naam | Beschrijving |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Verwijdert bijgesneden gebieden van de vulafbeelding. |

### Zie ook

* interface [IFillParamSource](../ifillparamsource)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->