---
title: ITextFrameFormat class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/itextframeformat/
---
## ITextFrameFormat klasse

Bevat de opmaak-eigenschappen van de TextFrame.

Het ITextFrameFormat-type geeft de volgende leden weer:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`text_style`](/slides/python-net/nl/aspose.slides/itextframeformat/text_style/) | Geeft de stijl van de tekst terug.<br/>            Alleen lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/nl/aspose.slides/itextframeformat/margin_left/) | Geeft de linkermarge (punten) in een TextFrame terug of stelt deze in.<br/>            Lezen/schrijven **float**. |
| [`margin_right`](/slides/python-net/nl/aspose.slides/itextframeformat/margin_right/) | Geeft de rechtermarge (punten) in een TextFrame terug of stelt deze in.<br/>            Lezen/schrijven **float**. |
| [`margin_top`](/slides/python-net/nl/aspose.slides/itextframeformat/margin_top/) | Geeft de bovenmarge (punten) in een TextFrame terug of stelt deze in.<br/>            Lezen/schrijven **float**. |
| [`margin_bottom`](/slides/python-net/nl/aspose.slides/itextframeformat/margin_bottom/) | Geeft de ondermarge (punten) in een TextFrame terug of stelt deze in.<br/>            Lezen/schrijven **float**. |
| [`wrap_text`](/slides/python-net/nl/aspose.slides/itextframeformat/wrap_text/) | **True** als de tekst wordt afgebroken bij de marges van de TextFrame.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/nl/aspose.slides/itextframeformat/anchoring_type/) | Geeft de verticale ankertekst in een TextFrame terug of stelt deze in.<br/>            Lezen/schrijven [`TextAnchorType`](/slides/python-net/nl/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/nl/aspose.slides/itextframeformat/center_text/) | Als NullableBool.True dan moet de tekst horizontaal gecentreerd worden in de box.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/nl/aspose.slides/itextframeformat/text_vertical_type/) | Bepaalt de oriëntatie van de tekst.<br/>            De resulterende waarde van de visuele tekstrotatie, samengevat van deze eigenschap en de aangepaste hoek in de eigenschap RotationAngle.<br/>            Lezen/schrijven [`TextVerticalType`](/slides/python-net/nl/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/nl/aspose.slides/itextframeformat/autofit_type/) | Geeft de autofit-modus van de tekst terug of stelt deze in.<br/>            Lezen/schrijven [`TextAutofitType`](/slides/python-net/nl/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/nl/aspose.slides/itextframeformat/column_count/) | Geeft het aantal kolommen in het tekstgebied terug of stelt dit in.<br/>            Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. <br/>            Waarde 0 betekent een ongedefinieerde waarde.<br/>            Lezen/schrijven **int**. |
| [`column_spacing`](/slides/python-net/nl/aspose.slides/itextframeformat/column_spacing/) | Geeft de ruimte tussen tekstopdrachten in het tekstgebied (in punten) terug of stelt deze in.<br/>            Dit zou alleen moeten gelden <br/>            wanneer er meer dan 1 kolom aanwezig is.<br/>            Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. <br/>            Lezen/schrijven **float**. |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/itextframeformat/three_d_format/) | Geeft het ThreeDFormat-object terug dat de 3D-effecteigenschappen voor een tekst weergeeft.<br/>            Alleen lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/nl/aspose.slides/itextframeformat/keep_text_flat/) | Geeft terug of stelt in dat de tekst volledig buiten de 3D-scene wordt gehouden.<br/>            Lezen/schrijven **bool**. |
| [`rotation_angle`](/slides/python-net/nl/aspose.slides/itextframeformat/rotation_angle/) | Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de omvattende box. Als deze niet<br/>            gespecificeerd is, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel gespecificeerd is, dan wordt dit<br/>            onafhankelijk van de vorm toegepast. Dat wil zeggen dat de vorm een rotatie kan hebben die wordt toegepast<br/>            naast de rotatie die op de tekst zelf wordt toegepast.<br/>            De resulterende waarde van de visuele tekstrotatie, samengevat van deze eigenschap en het vooraf gedefinieerde<br/>            verticale type in de eigenschap TextVerticalType.<br/>            Lezen/schrijven **float**. |
| [`transform`](/slides/python-net/nl/aspose.slides/itextframeformat/transform/) | Geeft de vorm voor tekstomslag terug of stelt deze in.<br/>            Lezen/schrijven [`TextShapeType`](/slides/python-net/nl/aspose.slides/textshapetype). |

## Methoden

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/nl/aspose.slides/itextframeformat/get_effective/#) | Geeft de effectieve tekstframe-opmaakgegevens terug met de toegepaste overerving. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)