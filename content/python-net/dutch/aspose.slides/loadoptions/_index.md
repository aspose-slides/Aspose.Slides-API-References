---
title: LoadOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/loadoptions/
---
## LoadOptions klasse

Staat toe extra opties (zoals formaat of standaardlettertype) op te geven bij het laden van een presentatie.

Het LoadOptions-type maakt de volgende leden beschikbaar:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides/loadoptions/__init__/#) | Creates new default load options. |
| [`__init__(self, load_format)`](/slides/python-net/nl/aspose.slides/loadoptions/__init__/#loadformat) | Creates new load options. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`load_format`](/slides/python-net/nl/aspose.slides/loadoptions/load_format/) | Geeft het formaat van een te laden presentatie terug of stelt het in.<br/>            Lezen/schrijven [`LoadFormat`](/slides/python-net/nl/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides/loadoptions/default_regular_font/) | Geeft het reguliere lettertype terug of stelt het in voor het geval het bronlettertype niet wordt gevonden.<br/>            Lezen/schrijven **str**. |
| [`default_symbol_font`](/slides/python-net/nl/aspose.slides/loadoptions/default_symbol_font/) | Geeft het symboollettertype terug of stelt het in voor het geval het bronlettertype niet wordt gevonden.<br/>            Lezen/schrijven **str**. |
| [`default_asian_font`](/slides/python-net/nl/aspose.slides/loadoptions/default_asian_font/) | Geeft het Aziatische lettertype terug of stelt het in voor het geval het bronlettertype niet wordt gevonden.<br/>            Lezen/schrijven **str**. |
| [`password`](/slides/python-net/nl/aspose.slides/loadoptions/password/) | Geeft het wachtwoord terug of stelt het in.<br/>            Lezen/schrijven **str**. |
| [`only_load_document_properties`](/slides/python-net/nl/aspose.slides/loadoptions/only_load_document_properties/) | Deze eigenschap heeft zin als het presentatied bestand met wachtwoord is beveiligd.<br/>            Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld <br/>            presentatiebestand en het wachtwoord moet worden genegeerd.<br/>            Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste <br/>            wachtwoord.<br/>            Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd.<br/>            Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, dan<br/>            kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid.<br/>            Lezen/schrijven **bool**. |
| [`warning_callback`](/slides/python-net/nl/aspose.slides/loadoptions/warning_callback/) | Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces<br/>            wordt voortgezet of wordt afgebroken.<br/>            Lezen/schrijven [`IWarningCallback`](/slides/python-net/nl/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/nl/aspose.slides/loadoptions/blob_management_options/) | Stelt de opties voor die kunnen worden gebruikt om het gedrag bij het verwerken van Binary Large Objects (BLOB's) te beheren,<br/>            zoals het gebruik van tijdelijke bestanden of het maximale aantal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste verhouding tussen prestaties en geheugengebruik in te stellen voor een specifieke omgeving of vereisten.<br/>            Een Binary Large Object (BLOB) is binaire gegevens opgeslagen als één entiteit – d.w.z. een BLOB kan <br/>            een audio-, video- of presentatie zelf zijn. |
| [`document_level_font_sources`](/slides/python-net/nl/aspose.slides/loadoptions/document_level_font_sources/) | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt.<br/>            Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties |
| [`interruption_token`](/slides/python-net/nl/aspose.slides/loadoptions/interruption_token/) | Het token om onderbrekingsverzoeken te bewaken.<br/>            <br/>            Dit token beheert de gehele levensduur van de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)-instantie. Elke langdurige bewerking, zoals het laden <br/>            of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [`InterruptionTokenSource.interrupt`](/slides/python-net/nl/aspose.slides/interruptiontokensource/interrupt)-methode van <br/>            de [`InterruptionTokenSource`](/slides/python-net/nl/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/nl/aspose.slides/loadoptions/resource_loading_callback/) | Geeft een callback-interface terug of stelt deze in die het laden van externe bronnen beheert.<br/>            Lezen/schrijven [`IResourceLoadingCallback`](/slides/python-net/nl/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/nl/aspose.slides/loadoptions/spreadsheet_options/) | Geeft opties voor spreadsheets terug. Bijvoorbeeld, deze opties beïnvloeden het berekenen van formules voor grafieken. |
| [`default_text_language`](/slides/python-net/nl/aspose.slides/loadoptions/default_text_language/) | Geeft de standaardtaal voor presentatietekst terug of stelt deze in.<br/>             Lezen/schrijven **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/nl/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Bepaalt of Aspose.Slides alle ingesloten binaire objecten zal verwijderen tijdens het laden van de presentatie.<br/>            <br/>De typen van de ingesloten binaire objecten:<br/><br/><br/>* VBA-Project [`IPresentation.vba_project`](/slides/python-net/nl/aspose.slides/ipresentation/vba_project)<br/>* OLE-object ingesloten gegevens [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX-control binaire gegevens [`IControl.active_x_control_binary`](/slides/python-net/nl/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lezen/schrijven **bool**. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)