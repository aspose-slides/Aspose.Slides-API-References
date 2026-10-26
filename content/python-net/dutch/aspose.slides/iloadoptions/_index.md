---
title: ILoadOptions class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/iloadoptions/
---
## ILoadOptions klasse

Staat toe extra opties (zoals formaat of standaardlettertype) op te geven bij het laden van een presentatie.

Het ILoadOptions-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`load_format`](/slides/python-net/nl/aspose.slides/iloadoptions/load_format/) | Geeft of stel het formaat van een presentatie dat moet worden geladen.<br/>            Lezen/schrijven [`LoadFormat`](/slides/python-net/nl/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides/iloadoptions/default_regular_font/) | Geeft of stel het reguliere lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`default_symbol_font`](/slides/python-net/nl/aspose.slides/iloadoptions/default_symbol_font/) | Geeft of stel het symboollettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`default_asian_font`](/slides/python-net/nl/aspose.slides/iloadoptions/default_asian_font/) | Geeft of stel het Aziatische lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`password`](/slides/python-net/nl/aspose.slides/iloadoptions/password/) | Geeft of stel het wachtwoord in.<br/>            Lezen-schrijven **str**. |
| [`only_load_document_properties`](/slides/python-net/nl/aspose.slides/iloadoptions/only_load_document_properties/) | Deze eigenschap is zinvol als het presentiebestand met een wachtwoord is beveiligd.<br/>            De waarde true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld <br/>            presentiebestand en het wachtwoord moet worden genegeerd.<br/>            De waarde false betekent dat de volledige versleutelde presentatie moet worden geladen met gebruik van het juiste <br/>            wachtwoord.<br/>            Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd.<br/>            Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, dan<br/>            kunnen documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid.<br/>            Lezen-schrijven **bool**. |
| [`warning_callback`](/slides/python-net/nl/aspose.slides/iloadoptions/warning_callback/) | Geeft of stel een object dat waarschuwingen ontvangt en beslist of het laadproces <br/>            wordt voortgezet of wordt afgebroken.<br/>            Lezen/schrijven [`IWarningCallback`](/slides/python-net/nl/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/nl/aspose.slides/iloadoptions/blob_management_options/) | Geeft de opties weer die kunnen worden gebruikt om het beheer van Binary Large Objects (BLOB's) te regelen,<br/>            zoals het gebruik van tijdelijke bestanden of het maximale aantal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste prestatie-/geheugengebruikverhouding in te stellen voor een specifieke omgeving of vereisten.<br/>            Een Binary Large Object (BLOB) is een binaire gegevens die als één entiteit wordt opgeslagen – d.w.z. een BLOB kan <br/>            een audio-, video- of de presentatie zelf zijn. |
| [`document_level_font_sources`](/slides/python-net/nl/aspose.slides/iloadoptions/document_level_font_sources/) | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt.<br/>            Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties. |
| [`interruption_token`](/slides/python-net/nl/aspose.slides/iloadoptions/interruption_token/) | Het token om onderbrekingsverzoeken te bewaken.<br/>            <br/>            Dit token beheert de volledige levensduur van de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)-instantie. Elke langdurige operatie, zoals het laden of opslaan van een presentatie, zal worden onderbroken via het aanroepen van de [`IInterruptionTokenSource.interrupt`](/slides/python-net/nl/aspose.slides/iinterruptiontokensource/interrupt)-methode van de [`IInterruptionTokenSource`](/slides/python-net/nl/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/nl/aspose.slides/iloadoptions/resource_loading_callback/) | Geeft of stel de callback-interface die het laden van externe middelen beheert.<br/>            Lezen/schrijven [`IResourceLoadingCallback`](/slides/python-net/nl/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/nl/aspose.slides/iloadoptions/spreadsheet_options/) | Geeft opties weer die kunnen worden gebruikt om extra spreadsheet-gedrag te specificeren. |
| [`default_text_language`](/slides/python-net/nl/aspose.slides/iloadoptions/default_text_language/) | Geeft of stel de standaardtaal voor presentatietekst in.<br/>             Lezen/schrijven **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/nl/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Bepaalt of Aspose.Slides alle ingesloten binaire objecten zal verwijderen tijdens het laden van de presentatie.<br/>            <br/>De typen van de ingesloten binaire objecten:<br/><br/><br/>* VBA-project [`IPresentation.vba_project`](/slides/python-net/nl/aspose.slides/ipresentation/vba_project)<br/>* OLE-object ingesloten gegevens [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX-control binaire gegevens [`IControl.active_x_control_binary`](/slides/python-net/nl/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lezen/schrijven **bool**. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)