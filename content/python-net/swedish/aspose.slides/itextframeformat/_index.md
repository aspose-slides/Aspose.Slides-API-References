---
title: ITextFrameFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/itextframeformat/
---
## ITextFrameFormat klass

Innehåller TextFrames formateringsegenskaper.

ITextFrameFormat-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`text_style`](/slides/python-net/sv/aspose.slides/itextframeformat/text_style/) | Returnerar textens stil.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/sv/aspose.slides/itextframeformat/margin_left/) | Returnerar eller anger den vänstra marginalen (punkter) i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_right`](/slides/python-net/sv/aspose.slides/itextframeformat/margin_right/) | Returnerar eller anger den högra marginalen (punkter) i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_top`](/slides/python-net/sv/aspose.slides/itextframeformat/margin_top/) | Returnerar eller anger den övre marginalen (punkter) i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_bottom`](/slides/python-net/sv/aspose.slides/itextframeformat/margin_bottom/) | Returnerar eller anger den nedre marginalen (punkter) i en TextFrame.<br/>            Läs/skriv **float**. |
| [`wrap_text`](/slides/python-net/sv/aspose.slides/itextframeformat/wrap_text/) | **True**  om texten radbryts vid TextFrames marginaler.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/sv/aspose.slides/itextframeformat/anchoring_type/) | Returnerar eller anger vertikal förankringstext i en TextFrame.<br/>            Läs/skriv [`TextAnchorType`](/slides/python-net/sv/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/sv/aspose.slides/itextframeformat/center_text/) | Om NullableBool.True ska texten centreras horisontellt i rutan.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/sv/aspose.slides/itextframeformat/text_vertical_type/) | Bestämmer textorientering.<br/>            Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och anpassad vinkel<br/>            i egenskapen RotationAngle.<br/>            Läs/skriv [`TextVerticalType`](/slides/python-net/sv/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/sv/aspose.slides/itextframeformat/autofit_type/) | Returnerar eller anger textens autofit-läge.<br/>            Läs/skriv [`TextAutofitType`](/slides/python-net/sv/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/sv/aspose.slides/itextframeformat/column_count/) | Returnerar eller anger antal kolumner i textområdet.<br/>            Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. <br/>            Värde 0 betyder odefinierat värde.<br/>            Läs/skriv **int**. |
| [`column_spacing`](/slides/python-net/sv/aspose.slides/itextframeformat/column_spacing/) | Returnerar eller anger avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast tillämpas <br/>            när det finns mer än 1 kolumn.<br/>            Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. <br/>            Läs/skriv **float**. |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/itextframeformat/three_d_format/) | Returnerar ThreeDFormat-objektet som representerar 3d-effektegenskaper för en text.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/sv/aspose.slides/itextframeformat/keep_text_flat/) | Returnerar eller anger att hålla text helt utanför 3D-scenen.<br/>            Läs/skriv **bool**. |
| [`rotation_angle`](/slides/python-net/sv/aspose.slides/itextframeformat/rotation_angle/) | Specificerar den anpassade rotationen som tillämpas på texten inom den omgivande rutan. Om den inte<br/>            anges används rotationen för den medföljande formen. Om den anges tillämpas den<br/>            oberoende av formen. Det vill säga att formen kan ha en rotation samtidigt som själva texten har en rotation.<br/>            Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och fördefinierad<br/>            vertikal typ i egenskapen TextVerticalType.<br/>            Läs/skriv **float**. |
| [`transform`](/slides/python-net/sv/aspose.slides/itextframeformat/transform/) | Hämtar eller anger textomslutningsform.<br/>            Läs/skriv [`TextShapeType`](/slides/python-net/sv/aspose.slides/textshapetype). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/sv/aspose.slides/itextframeformat/get_effective/#) | Hämtar effektiv textramformateringsdata med ärvda inställningar tillämpade. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)