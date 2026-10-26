---
title: RenderingOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/renderingoptions/
---
## RenderingOptions klass

Tillhandahåller alternativ som styr hur en presentation/bild renderas.

**Arv:**[`RenderingOptions`](/slides/python-net/sv/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)

RenderingOptions-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/renderingoptions/__init__/#) | Standardkonstruktor. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/renderingoptions/warning_callback/) | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas.<br/>            Läsa/skriva [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/renderingoptions/progress_callback/) | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent.<br/>            Se [`IProgressCallback`](/slides/python-net/sv/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/renderingoptions/default_regular_font/) | Returnerar eller anger typsnitt som används om källtypsnittet inte hittas.<br/>            Läs-skriv **str**. |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/renderingoptions/gradient_style/) | Returnerar eller anger den visuella stilen för gradienten.<br/>            Läsa/skriva [`GradientStyle`](/slides/python-net/sv/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/renderingoptions/skip_java_script_links/) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. <br/>            Läsa/skriva **bool**. Standardvärdet är **false** . |
| [`slides_layout_options`](/slides/python-net/sv/aspose.slides.export/renderingoptions/slides_layout_options/) | Hämtar eller anger läget i vilket bilder placeras på sidan när en presentation exporteras [`ISlidesLayoutOptions`](/slides/python-net/sv/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/sv/aspose.slides.export/renderingoptions/ink_options/) | Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterat dokument.<br/>            Endast läs [`IInkOptions`](/slides/python-net/sv/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/sv/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer.<br/>            När den är satt till `true` kommer ligaturer att vara inaktiverade i den renderade utskriften. Som standard är denna egenskap satt till `false`. |

### Se även
* klass [`RenderingOptions`](/slides/python-net/sv/aspose.slides.export/renderingoptions)
* klass [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)