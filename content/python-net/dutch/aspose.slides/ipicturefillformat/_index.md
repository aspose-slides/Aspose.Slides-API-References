---
title: IPictureFillFormat class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat klasse

Stelt een afbeelding-opvulstijl voor.

Het IPictureFillFormat-type geeft de volgende leden weer:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/nl/aspose.slides/ipicturefillformat/dpi/) | Retourneert of stelt de dpi in die wordt gebruikt om een afbeelding te vullen.<br/>            Lezen/Schrijven **int**. |
| [`picture_fill_mode`](/slides/python-net/nl/aspose.slides/ipicturefillformat/picture_fill_mode/) | Retourneert of stelt de opvulmodus van de afbeelding in.<br/>            Lezen/Schrijven [`PictureFillMode`](/slides/python-net/nl/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/nl/aspose.slides/ipicturefillformat/picture/) | Retourneert de afbeelding.<br/>            Alleen-lezen [`ISlidesPicture`](/slides/python-net/nl/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/nl/aspose.slides/ipicturefillformat/crop_left/) | Retourneert of stelt het aantal procenten van de werkelijke afbeeldingsbreedte in dat aan de linkerkant van de afbeelding wordt bijgesneden<br/>            Lezen/Schrijven **float**. |
| [`crop_top`](/slides/python-net/nl/aspose.slides/ipicturefillformat/crop_top/) | Retourneert of stelt het aantal procenten van de werkelijke afbeeldinghoogte in dat aan de bovenkant van de afbeelding wordt bijgesneden<br/>            Lezen/Schrijven **float**. |
| [`crop_right`](/slides/python-net/nl/aspose.slides/ipicturefillformat/crop_right/) | Retourneert of stelt het aantal procenten van de werkelijke afbeeldingsbreedte in dat aan de rechterkant van de afbeelding wordt bijgesneden<br/>            Lezen/Schrijven **float**. |
| [`crop_bottom`](/slides/python-net/nl/aspose.slides/ipicturefillformat/crop_bottom/) | Retourneert of stelt het aantal procenten van de werkelijke afbeeldinghoogte in dat aan de onderkant van de afbeelding wordt bijgesneden<br/>            Lezen/Schrijven **float**. |
| [`stretch_offset_left`](/slides/python-net/nl/aspose.slides/ipicturefillformat/stretch_offset_left/) | Retourneert of stelt de linkerrand van de opvullende rechthoek in die wordt gedefinieerd door een percentage-verschuiving <br/>            vanaf de linkerrand van de begrenzingsdoos van de vorm.<br/>            Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitstulping aangeeft.<br/>            Lezen/Schrijven **float**. |
| [`stretch_offset_top`](/slides/python-net/nl/aspose.slides/ipicturefillformat/stretch_offset_top/) | Retourneert of stelt de bovengrond van de opvullende rechthoek in die wordt gedefinieerd door een percentage-verschuiving <br/>            vanaf de bovengrond van de begrenzingsdoos van de vorm.<br/>            Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitstulping aangeeft.<br/>            Lezen/Schrijven **float**. |
| [`stretch_offset_right`](/slides/python-net/nl/aspose.slides/ipicturefillformat/stretch_offset_right/) | Retourneert of stelt de rechterrand van de opvullende rechthoek in die wordt gedefinieerd door een percentage-verschuiving <br/>            vanaf de rechterrand van de begrenzingsdoos van de vorm.<br/>            Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitstulping aangeeft.<br/>            Lezen/Schrijven **float**. |
| [`stretch_offset_bottom`](/slides/python-net/nl/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Retourneert of stelt de onderrand van de opvullende rechthoek in die wordt gedefinieerd door een percentage-verschuiving <br/>            vanaf de onderrand van de begrenzingsdoos van de vorm.<br/>            Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitstulping aangeeft.<br/>            Lezen/Schrijven **float**. |
| [`tile_offset_x`](/slides/python-net/nl/aspose.slides/ipicturefillformat/tile_offset_x/) | Retourneert of stelt de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten.<br/>             Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde deze naar links verplaatst.<br/>             Lezen/Schrijven **float**. |
| [`tile_offset_y`](/slides/python-net/nl/aspose.slides/ipicturefillformat/tile_offset_y/) | Retourneert of stelt de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten.<br/>             Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde deze naar boven verplaatst.<br/>             Lezen/Schrijven **float**. |
| [`tile_scale_x`](/slides/python-net/nl/aspose.slides/ipicturefillformat/tile_scale_x/) | Retourneert of stelt de horizontale schaal voor de textuurvulling in als een percentage.<br/>             Lezen/Schrijven **float**. |
| [`tile_scale_y`](/slides/python-net/nl/aspose.slides/ipicturefillformat/tile_scale_y/) | Retourneert of stelt de verticale schaal voor de textuurvulling in als een percentage.<br/>             Lezen/Schrijven **float**. |
| [`tile_alignment`](/slides/python-net/nl/aspose.slides/ipicturefillformat/tile_alignment/) | Retourneert of stelt in hoe de textuur binnen de vorm wordt uitgelijnd. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich over de vorm herhaalt.<br/>             Lezen/Schrijven [`RectangleAlignment`](/slides/python-net/nl/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/nl/aspose.slides/ipicturefillformat/tile_flip/) | Draait de textuurtegel rond zijn horizontale, verticale of beide assen.<br/>             Lezen/Schrijven [`TileFlip`](/slides/python-net/nl/aspose.slides/tileflip). |

## Methoden

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/nl/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Comprimeert de afbeelding door zijn grootte te verkleinen op basis van de vormgrootte en de gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/nl/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Comprimeert de afbeelding door zijn grootte te verkleinen op basis van de vormgrootte en de gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/nl/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Verwijder bijgesneden gebieden van de opvulafbeelding. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)