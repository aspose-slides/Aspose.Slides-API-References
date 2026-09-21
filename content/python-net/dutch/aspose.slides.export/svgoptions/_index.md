---
title: SVGOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/svgoptions/
---
## SVGOptions klasse

Stelt een SVG-optie voor.

**Inheritance:**[`SVGOptions`](/slides/python-net/nl/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)

The SVGOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.export/svgoptions/__init__/#) | Initialiseert een nieuw exemplaar van de SVGOptions klasse. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/nl/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Initialiseert een nieuw exemplaar van de SVGOptions klasse met opgegeven link-embedcontrollerobject. |

## Eigenschappen

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/svgoptions/warning_callback/) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken.<br/>            Lezen/schrijven [`IWarningCallback`](/slides/python-net/nl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/svgoptions/progress_callback/) | Stelt een callback-object voor voor het opslaan van voortgangsupdates in procenten.<br/>            Zie [`IProgressCallback`](/slides/python-net/nl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/svgoptions/default_regular_font/) | Retourneert of stelt het lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/svgoptions/gradient_style/) | Retourneert of stelt de visuele stijl van de gradient in.<br/>            Lezen/schrijven [`GradientStyle`](/slides/python-net/nl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/svgoptions/skip_java_script_links/) | Specificeert of hyperlinks met JavaScript-oproepen moeten worden overgeslagen bij het opslaan van de presentatie. <br/>            Lezen/schrijven **bool**. De standaardwaarde is **false**. |
| [`ink_options`](/slides/python-net/nl/aspose.slides.export/svgoptions/ink_options/) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.<br/>            Alleen-lezen [`IInkOptions`](/slides/python-net/nl/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/nl/aspose.slides.export/svgoptions/use_frame_size/) | Bepaalt of het tekstframe wel of niet in een rendergebied wordt opgenomen.<br/>            Lezen/schrijven **bool**.<br/>            Standaardwaarde is false. |
| [`use_frame_rotation`](/slides/python-net/nl/aspose.slides.export/svgoptions/use_frame_rotation/) | Bepaalt of de opgegeven rotatie van de vorm wordt uitgevoerd bij het renderen of niet.<br/>            Lezen/schrijven **bool**.<br/>            Standaardwaarde is true. |
| [`vectorize_text`](/slides/python-net/nl/aspose.slides.export/svgoptions/vectorize_text/) | Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding.<br/>            Lezen/schrijven **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/nl/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Retourneert of stelt de ondergrens voor resolutie bij metafile-rasterisatie in.<br/>            Lezen/schrijven **int**. |
| [`disable_3d_text`](/slides/python-net/nl/aspose.slides.export/svgoptions/disable_3d_text/) | Bepaalt of de 3D-tekst is uitgeschakeld in SVG.<br/>            Lezen/schrijven **bool**. |
| [`disable_gradient_split`](/slides/python-net/nl/aspose.slides.export/svgoptions/disable_gradient_split/) | Schakelt het splitsen van FromCornerX- en FromCenter-gradients uit.<br/>            Lezen/schrijven **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/nl/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren.<br/>            De Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem:<br/>            het snijdt het einde van een lijn met een pijl af, zodat de lijn de markers niet overlapt.<br/>            Deze optie schakelt dat gedrag uit.<br/>            Lezen/schrijven **bool**. |
| [`default`](/slides/python-net/nl/aspose.slides.export/svgoptions/default/) | Retourneert standaardinstellingen.<br/>            Alleen-lezen [`SVGOptions`](/slides/python-net/nl/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/nl/aspose.slides.export/svgoptions/simple/) | Retourneert instellingen voor de eenvoudigste en kleinste SVG-bestandgeneratie.<br/>            Alleen-lezen [`SVGOptions`](/slides/python-net/nl/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/nl/aspose.slides.export/svgoptions/wysiwyg/) | Retourneert instellingen voor de meest nauwkeurige SVG-bestandgeneratie.<br/>            Alleen-lezen [`SVGOptions`](/slides/python-net/nl/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/nl/aspose.slides.export/svgoptions/jpeg_quality/) | Bepaalt de JPEG-coderingskwaliteit.<br/>            Lezen/schrijven **int**. |
| [`shape_formatting_controller`](/slides/python-net/nl/aspose.slides.export/svgoptions/shape_formatting_controller/) | Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te regelen.<br/>            Lezen/schrijven [`ISvgShapeFormattingController`](/slides/python-net/nl/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/nl/aspose.slides.export/svgoptions/pictures_compression/) | Stelt het compressieniveau van afbeeldingen voor |
| [`delete_pictures_cropped_areas`](/slides/python-net/nl/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Een booleaanse vlag geeft aan of de bijgesneden delen behouden blijven als onderdeel van het document. Indien waar worden de bijgesneden <br/>            delen verwijderd, indien niet worden ze geserializeerd in het document (wat mogelijk kan leiden tot een <br/>            groter bestand) |
| [`external_fonts_handling`](/slides/python-net/nl/aspose.slides.export/svgoptions/external_fonts_handling/) | Bepaalt de manier waarop extern geladen lettertypen worden verwerkt.<br/>            Lezen/schrijven [`SvgExternalFontsHandling`](/slides/python-net/nl/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/nl/aspose.slides.export/svgoptions/disable_font_ligatures/) | Retourneert of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken.<br/>            Wanneer ingesteld op `true`, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op `false`. |


### Zie ook
* klasse [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)
* klasse [`SVGOptions`](/slides/python-net/nl/aspose.slides.export/svgoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)