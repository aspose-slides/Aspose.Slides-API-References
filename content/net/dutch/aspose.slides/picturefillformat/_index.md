---
title: PictureFillFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een afbeeldingvulstijl voor.
type: docs
weight: 9390
url: /nl/aspose.slides/picturefillformat/
---
## PictureFillFormat class

Stelt een afbeeldingvulstijl voor.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Stelt de basis-IPresentationComponent-interface beschikbaar. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Geeft of stelt het aantal procenten van de echte afbeeldingshoogte in dat onderkant van de afbeelding wordt weggesneden. Lezen/Schrijven Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Geeft of stelt het aantal procenten van de echte afbeeldingbreedte in dat linkerkant van de afbeelding wordt weggesneden. Lezen/Schrijven Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Geeft of stelt het aantal procenten van de echte afbeeldingbreedte in dat rechterkant van de afbeelding wordt weggesneden. Lezen/Schrijven Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Geeft of stelt het aantal procenten van de echte afbeeldingshoogte in dat bovenkant van de afbeelding wordt weggesneden. Lezen/Schrijven Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Geeft of stelt de dpi in die wordt gebruikt om een afbeelding te vullen. Lezen/Schrijven Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Geeft de afbeelding terug. Alleen-lezen [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Geeft of stelt de afbeeldingvulmodus in. Lezen/Schrijven [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Geeft of stelt de onderrand van het vulrechthoek in die wordt gedefinieerd door een procentuele offset ten opzichte van de onderrand van de begrenzende rechthoek van de vorm. Een positief percentage geeft een inset, een negatief percentage een outset. Lezen/Schrijven Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Geeft of stelt de linkerrand van het vulrechthoek in die wordt gedefinieerd door een procentuele offset ten opzichte van de linkerrand van de begrenzende rechthoek van de vorm. Een positief percentage geeft een inset, een negatief percentage een outset. Lezen/Schrijven Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Geeft of stelt de rechterrand van het vulrechthoek in die wordt gedefinieerd door een procentuele offset ten opzichte van de rechterrand van de begrenzende rechthoek van de vorm. Een positief percentage geeft een inset, een negatief percentage een outset. Lezen/Schrijven Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Geeft of stelt de bovengrands van het vulrechthoek in die wordt gedefinieerd door een procentuele offset ten opzichte van de bovengrens van de begrenzende rechthoek van de vorm. Een positief percentage geeft een inset, een negatief percentage een outset. Lezen/Schrijven Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Geeft of stelt in hoe de textuur binnen de vorm wordt uitgelijnd. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het over de vorm wordt herhaald. Lezen/Schrijven [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Keert de textuurtile om rond de horizontale, verticale of beide assen. Lezen/Schrijven [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Geeft of stelt de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verschuift de textuur naar rechts, een negatieve waarde naar links. Lezen/Schrijven Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Geeft of stelt de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verschuift de textuur omlaag, een negatieve waarde omhoog. Lezen/Schrijven Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Geeft of stelt de horizontale schaal voor de textuurvulling in als percentage. Lezen/Schrijven Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Geeft of stelt de verticale schaal voor de textuurvulling in als percentage. Lezen/Schrijven Single. |

## Methods

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel worden bijgesneden gebieden ook verwijderd. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel worden bijgesneden gebieden ook verwijderd. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Verwijdert bijgesneden gebieden van de vulafbeelding. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met opgegeven object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourneert hashcode. |

### See Also

* class [PVIObject](../pviobject)
* interface [IPictureFillFormat](../ipicturefillformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->