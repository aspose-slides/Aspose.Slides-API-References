---
title: HtmlOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/htmloptions/
---
## HtmlOptions klass

Representerar alternativ för HTML-export.

**Inheritance:**[`HtmlOptions`](/slides/python-net/sv/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)

HtmlOptions-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/sv/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Skapar ett nytt HtmlOptions-objekt som specificerar en återuppringning. |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/htmloptions/__init__/#) | Skapar ett nytt HtmlOptions-objekt för att spara i en enda HTML-fil. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/htmloptions/warning_callback/) | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/htmloptions/progress_callback/) | Representerar ett återuppringningsobjekt för sparande av framstegsuppdateringar i procent.<br/>            Se [`IProgressCallback`](/slides/python-net/sv/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/htmloptions/default_regular_font/) | Returnerar eller anger teckensnitt som används om källteckensnittet inte hittas.<br/>            Läs/skriv **str**. |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/htmloptions/gradient_style/) | Returnerar eller anger den visuella stilen för gradienten.<br/>            Läs/skriv [`GradientStyle`](/slides/python-net/sv/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/htmloptions/skip_java_script_links/) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas.<br/>            Läs/skriv **bool**. Standardvärdet är **false**. |
| [`slides_layout_options`](/slides/python-net/sv/aspose.slides.export/htmloptions/slides_layout_options/) | Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](/slides/python-net/sv/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/sv/aspose.slides.export/htmloptions/ink_options/) | Tillhandahåller alternativ som styr utseendet på bläckobjekt i det exporterade dokumentet.<br/>            Endast läs [`IInkOptions`](/slides/python-net/sv/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/sv/aspose.slides.export/htmloptions/show_hidden_slides/) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte.<br/>            Standard är `false`. |
| [`html_formatter`](/slides/python-net/sv/aspose.slides.export/htmloptions/html_formatter/) | Returnerar eller anger HTML-mall.<br/>            Läs/skriv [`IHtmlFormatter`](/slides/python-net/sv/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/sv/aspose.slides.export/htmloptions/disable_font_ligatures/) | Hämtar eller anger ett värde som indikerar om text renderas utan ligaturer.<br/>            När den är satt till `true` inaktiveras ligaturer i den renderade utdata. Som standard är denna egenskap satt till `false`. |
| [`slide_image_format`](/slides/python-net/sv/aspose.slides.export/htmloptions/slide_image_format/) | Returnerar eller anger bildformatalternativ för bilder.<br/>            Läs/skriv [`ISlideImageFormat`](/slides/python-net/sv/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/sv/aspose.slides.export/htmloptions/jpeg_quality/) | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet.<br/>            Läs/skriv **int**. |
| [`pictures_compression`](/slides/python-net/sv/aspose.slides.export/htmloptions/pictures_compression/) | Representerar bildkomprimeringsnivån |
| [`delete_pictures_cropped_areas`](/slides/python-net/sv/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | En boolesk flagga indikerar om de beskurna delarna förblir en del av dokumentet. Om true tas de beskurna <br/>            delarna bort, om false kommer de att serialiseras i dokumentet (vilket eventuellt kan leda till en <br/>            större fil) |
| [`svg_responsive_layout`](/slides/python-net/sv/aspose.slides.export/htmloptions/svg_responsive_layout/) | True för att exkludera bredd- och höjdattribut från SVG-behållare – detta gör layouten responsiv. False – annars.<br/>            Läs/skriv **bool**. |


### Se även
* klass [`HtmlOptions`](/slides/python-net/sv/aspose.slides.export/htmloptions)
* klass [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)