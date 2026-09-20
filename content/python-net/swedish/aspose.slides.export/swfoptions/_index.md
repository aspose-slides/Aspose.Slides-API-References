---
title: SwfOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/swfoptions/
---
## SwfOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i Swf-format.

**Inheritance:**[`SwfOptions`](/slides/python-net/sv/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)

SwfOptions-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/swfoptions/__init__/#) | Standardkonstruktör. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/swfoptions/warning_callback/) | Returnerar eller sätter ett objekt som tar emot varningar och avgör om laddningsprocessen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/swfoptions/progress_callback/) | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent.<br/>            Se [`IProgressCallback`](/slides/python-net/sv/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/swfoptions/default_regular_font/) | Returnerar eller sätter teckensnittet som används om källteckensnittet inte hittas.<br/>            Läs/skriv **str**. |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/swfoptions/gradient_style/) | Returnerar eller sätter den visuella stilen för gradienten.<br/>            Läs/skriv [`GradientStyle`](/slides/python-net/sv/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/swfoptions/skip_java_script_links/) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas.<br/>            Läs/skriv **bool**. Standardvärdet är **false**. |
| [`show_hidden_slides`](/slides/python-net/sv/aspose.slides.export/swfoptions/show_hidden_slides/) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte.<br/>            Standard är `false`. |
| [`compressed`](/slides/python-net/sv/aspose.slides.export/swfoptions/compressed/) | Anger om det genererade SWF-dokumentet ska komprimeras eller inte.<br/>            Standard är `true`. |
| [`viewer_included`](/slides/python-net/sv/aspose.slides.export/swfoptions/viewer_included/) | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte.<br/>            Standard är `true`. |
| [`show_page_border`](/slides/python-net/sv/aspose.slides.export/swfoptions/show_page_border/) | Anger om kantlinje runt sidor ska visas. Standard är true. |
| [`show_full_screen`](/slides/python-net/sv/aspose.slides.export/swfoptions/show_full_screen/) | Visa/göm helskärmsknapp. Kan åsidosättas i flashvars. Standard är true. |
| [`show_page_stepper`](/slides/python-net/sv/aspose.slides.export/swfoptions/show_page_stepper/) | Visa/göm sidstegare. Kan åsidosättas i flashvars. Standard är true. |
| [`show_search`](/slides/python-net/sv/aspose.slides.export/swfoptions/show_search/) | Visa/göm söksektion. Kan åsidosättas i flashvars. Standard är true. |
| [`show_top_pane`](/slides/python-net/sv/aspose.slides.export/swfoptions/show_top_pane/) | Visa/göm hela översta panelen. Kan åsidosättas i flashvars. Standard är true. |
| [`show_bottom_pane`](/slides/python-net/sv/aspose.slides.export/swfoptions/show_bottom_pane/) | Visa/göm nedre panelen. Kan åsidosättas i flashvars. Standard är true. |
| [`show_left_pane`](/slides/python-net/sv/aspose.slides.export/swfoptions/show_left_pane/) | Visa/göm vänstra panelen. Kan åsidosättas i flashvars. Standard är true. |
| [`start_open_left_pane`](/slides/python-net/sv/aspose.slides.export/swfoptions/start_open_left_pane/) | Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standard är false. |
| [`enable_context_menu`](/slides/python-net/sv/aspose.slides.export/swfoptions/enable_context_menu/) | Aktivera/inaktivera snabbmeny. Standard är true. |
| [`logo_image_bytes`](/slides/python-net/sv/aspose.slides.export/swfoptions/logo_image_bytes/) | Bild som kommer visas som logotyp i övre högra hörnet av visaren.<br/>            Bilden bör vara en PNG på 32×64 pixlar, annars kan logotypen visas felaktigt. |
| [`logo_link`](/slides/python-net/sv/aspose.slides.export/swfoptions/logo_link/) | Hämtar eller sätter den fullständiga hyperlänkadressen för en logotyp.<br/>            Har effekt endast om en [`SwfOptions.logo_image_bytes`](/slides/python-net/sv/aspose.slides.export/swfoptions/logo_image_bytes) är angiven. |
| [`jpeg_quality`](/slides/python-net/sv/aspose.slides.export/swfoptions/jpeg_quality/) | Anger kvaliteten på JPEG-bilder.<br/>            Standard är 95. |
| [`slides_layout_options`](/slides/python-net/sv/aspose.slides.export/swfoptions/slides_layout_options/) | Hämtar eller sätter läget i vilket bilder placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](/slides/python-net/sv/aspose.slides.export/islideslayoutoptions).<br/>            Denna egenskap stöder inte tilldelning av objekt av typen [`HandoutLayoutingOptions`](/slides/python-net/sv/aspose.slides.export/handoutlayoutingoptions) |

### Se också
* klass [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)
* klass [`SwfOptions`](/slides/python-net/sv/aspose.slides.export/swfoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)