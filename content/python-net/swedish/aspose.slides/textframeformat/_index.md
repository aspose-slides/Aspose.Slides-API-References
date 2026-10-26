---
title: TextFrameFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/textframeformat/
---
## TextFrameFormat klass

Innehåller TextFrames formatTextFrameFormatting-egenskaper.

**Inheritance:**[`TextFrameFormat`](/slides/python-net/sv/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)

TextFrameFormat-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/textframeformat/__init__/#) | Initialiserar en ny instans av [`TextFrameFormat`](/slides/python-net/sv/aspose.slides/textframeformat) klass. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/textframeformat/three_d_format/) | Returnerar ThreeDFormat-objektet som representerar 3d-effektegenskaper för en text.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/sv/aspose.slides/textframeformat/margin_left/) | Returnerar eller anger vänstermarginalen (punkter) i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_right`](/slides/python-net/sv/aspose.slides/textframeformat/margin_right/) | Returnerar eller anger högermarginalen (punkter) i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_top`](/slides/python-net/sv/aspose.slides/textframeformat/margin_top/) | Returnerar eller anger toppmarginalen (punkter) i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_bottom`](/slides/python-net/sv/aspose.slides/textframeformat/margin_bottom/) | Returnerar eller anger bottenmarginalen (punkter) i en TextFrame.<br/>            Läs/skriv **float**. |
| [`wrap_text`](/slides/python-net/sv/aspose.slides/textframeformat/wrap_text/) | **True**  om texten är radbruten vid TextFrames marginaler.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/sv/aspose.slides/textframeformat/anchoring_type/) | Returnerar eller anger vertikal ankartext i en TextFrame.<br/>            Läs/skriv [`TextAnchorType`](/slides/python-net/sv/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/sv/aspose.slides/textframeformat/center_text/) | Om NullableBool.True så bör texten centreras horisontellt i rutan.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/sv/aspose.slides/textframeformat/text_vertical_type/) | Bestämmer textorientering.<br/>            Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och anpassad vinkel<br/>            i egenskapen RotationAngle.<br/>            Läs/skriv [`TextVerticalType`](/slides/python-net/sv/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/sv/aspose.slides/textframeformat/autofit_type/) | Returnerar eller anger textens autofit-läge.<br/>            Läs/skriv [`TextAutofitType`](/slides/python-net/sv/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/sv/aspose.slides/textframeformat/column_count/) | Returnerar eller anger antalet kolumner i textområdet.<br/>            Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. <br/>            Värde 0 betyder odefinierat värde.<br/>            Läs/skriv **int**. |
| [`column_spacing`](/slides/python-net/sv/aspose.slides/textframeformat/column_spacing/) | Returnerar eller anger avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast tillämpas <br/>            när det finns mer än 1 kolumn.<br/>            Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. <br/>            Läs/skriv **float**. |
| [`rotation_angle`](/slides/python-net/sv/aspose.slides/textframeformat/rotation_angle/) | Anger den anpassade rotation som tillämpas på texten inom den omgivande rutan. Om den inte<br/>            specificeras används rotationen för den medföljande formen. Om den specificeras, tillämpas den<br/>            oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation.<br/>            Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och fördefinierad<br/>            vertikal typ i egenskapen TextVerticalType.<br/>            Läs/skriv **float**. |
| [`transform`](/slides/python-net/sv/aspose.slides/textframeformat/transform/) | Hämtar eller anger textradbrytningsformen.<br/>            Läs/skriv [`TextShapeType`](/slides/python-net/sv/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/sv/aspose.slides/textframeformat/keep_text_flat/) | Hämtar eller anger att behålla texten platt även om en 3-D-rotations-effekt har tillämpats.<br/>            Läs/skriv **bool**. |
| [`slide`](/slides/python-net/sv/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/sv/aspose.slides/textframeformat/text_style/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/sv/aspose.slides/textframeformat/get_effective/#) | Hämtar effektiv formateringsdata för textramen med ärvd information tillämpad. |


### Se även
* class [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)
* class [`TextFrameFormat`](/slides/python-net/sv/aspose.slides/textframeformat)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)