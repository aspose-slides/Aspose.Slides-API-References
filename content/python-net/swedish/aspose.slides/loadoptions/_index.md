---
title: LoadOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/loadoptions/
---
## LoadOptions klass

Tillåter att ange ytterligare alternativ (såsom format eller standardteckensnitt) när en presentation laddas.

LoadOptions-typen exponerar följande medlemmar:

## Konstruktörer

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/loadoptions/__init__/#) | Skapar nya standard-alternativ för inläsning. |
| [`__init__(self, load_format)`](/slides/python-net/sv/aspose.slides/loadoptions/__init__/#loadformat) | Skapar nya alternativ för inläsning. |

## Egenskaper

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/sv/aspose.slides/loadoptions/load_format/) | Returnerar eller anger formatet för en presentation som ska laddas.<br/>            Läs/skriv [`LoadFormat`](/slides/python-net/sv/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides/loadoptions/default_regular_font/) | Returnerar eller anger reguljärt teckensnitt som används om källteckensnittet inte hittas.<br/>            Läs/skriv **str**. |
| [`default_symbol_font`](/slides/python-net/sv/aspose.slides/loadoptions/default_symbol_font/) | Returnerar eller anger symbolteckensnitt som används om källteckensnittet inte hittas.<br/>            Läs/skriv **str**. |
| [`default_asian_font`](/slides/python-net/sv/aspose.slides/loadoptions/default_asian_font/) | Returnerar eller anger asiatiskt teckensnitt som används om källteckensnittet inte hittas.<br/>            Läs/skriv **str**. |
| [`password`](/slides/python-net/sv/aspose.slides/loadoptions/password/) | Hämtar eller anger lösenordet.<br/>            Läs/skriv **str**. |
| [`only_load_document_properties`](/slides/python-net/sv/aspose.slides/loadoptions/only_load_document_properties/) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad.<br/>            Sant betyder att endast dokumentegenskaper ska laddas från en krypterad <br/>            presentationsfil och lösenordet ska ignoreras.<br/>            Falskt betyder att hela den krypterade presentationen ska laddas med rätt <br/>            lösenord.<br/>            Om presentationen inte är krypterad ignoreras egenskapsvärdet alltid.<br/>            Om dokumentegenskaperna i en krypterad fil inte är publika och egenskapsvärdet är sant så kan<br/>            dokumentegenskaperna inte laddas och ett undantag kommer att kastas.<br/>            Läs/skriv **bool**. |
| [`warning_callback`](/slides/python-net/sv/aspose.slides/loadoptions/warning_callback/) | Returnerar eller anger ett objekt som tar emot varningar och beslutar om laddnings<br/>            processen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/sv/aspose.slides/loadoptions/blob_management_options/) | Representerar de alternativ som kan användas för att hantera beteendet för Binary Large Objects (BLOBs),<br/>            såsom användning av temporära filer eller maximalt antal BLOB-byte i minnet. Dessa alternativ är avsedda att konfigurera<br/>            det bästa förhållandet mellan prestanda och minnesanvändning för en viss miljö eller krav.<br/>            Ett Binary Large Object (BLOB) är binär data lagrad som en enhet – t.ex. kan ett BLOB<br/>            vara ljud, video eller själva presentationen. |
| [`document_level_font_sources`](/slides/python-net/sv/aspose.slides/loadoptions/document_level_font_sources/) | Anger källor för externa teckensnitt som ska användas av presentationen.<br/>            Dessa teckensnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer |
| [`interruption_token`](/slides/python-net/sv/aspose.slides/loadoptions/interruption_token/) | Tokenet för att övervaka avbrotts-förfrågningar.<br/>            <br/>            Detta token hanterar hela [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-instansens livstid. Alla långvariga operationer, såsom inläsning <br/>            eller sparande av presentation, kommer att avbrytas genom att anropa [`InterruptionTokenSource.interrupt`](/slides/python-net/sv/aspose.slides/interruptiontokensource/interrupt)-metoden på <br/>            [`InterruptionTokenSource`](/slides/python-net/sv/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/sv/aspose.slides/loadoptions/resource_loading_callback/) | Returnerar eller anger callback-gränssnitt som hanterar inläsning av externa resurser.<br/>            Läs/skriv [`IResourceLoadingCallback`](/slides/python-net/sv/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/sv/aspose.slides/loadoptions/spreadsheet_options/) | Hämtar alternativ för kalkylblad. Till exempel påverkar dessa alternativ beräkning av formler för diagram. |
| [`default_text_language`](/slides/python-net/sv/aspose.slides/loadoptions/default_text_language/) | Returnerar eller anger standardspråket för presentationstext.<br/>             Läs/skriv **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/sv/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Bestämmer om Aspose.Slides ska radera alla inbäddade binära objekt vid inläsning av presentationen.<br/>            <br/>Typerna av de inbäddade binära objekten:<br/><br/><br/>* VBA-projekt [`IPresentation.vba_project`](/slides/python-net/sv/aspose.slides/ipresentation/vba_project)<br/>* OLE-objekt inbäddad data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX-kontroll binär data [`IControl.active_x_control_binary`](/slides/python-net/sv/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Läs/skriv **bool**. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)