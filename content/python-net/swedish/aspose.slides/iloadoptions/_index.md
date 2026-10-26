---
title: ILoadOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iloadoptions/
---
## ILoadOptions klass

Gör det möjligt att ange ytterligare alternativ (såsom format eller standardteckensnitt) när en presentation laddas.

ILoadOptions-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`load_format`](/slides/python-net/sv/aspose.slides/iloadoptions/load_format/) | Returnerar eller anger formatet för en presentation att laddas.<br/>            Läs/skriv [`LoadFormat`](/slides/python-net/sv/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides/iloadoptions/default_regular_font/) | Returnerar eller anger reguljärt teckensnitt som används om källteckensnittet inte hittas.<br/>            Läs-skriv **str**. |
| [`default_symbol_font`](/slides/python-net/sv/aspose.slides/iloadoptions/default_symbol_font/) | Returnerar eller anger symbolteckensnitt som används om källteckensnittet inte hittas.<br/>            Läs-skriv **str**. |
| [`default_asian_font`](/slides/python-net/sv/aspose.slides/iloadoptions/default_asian_font/) | Returnerar eller anger asiatiskt teckensnitt som används om källteckensnittet inte hittas.<br/>            Läs-skriv **str**. |
| [`password`](/slides/python-net/sv/aspose.slides/iloadoptions/password/) | Hämtar eller anger lösenordet.<br/>            Läs-skriv **str**. |
| [`only_load_document_properties`](/slides/python-net/sv/aspose.slides/iloadoptions/only_load_document_properties/) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad.<br/>            Värdet true betyder att endast dokumentegenskaper ska laddas från en krypterad <br/>            presentationsfil och lösenordet ska ignoreras.<br/>            Värdet false betyder att hela den krypterade presentationen måste laddas med korrekt <br/>            lösenord.<br/>            Om presentationen inte är krypterad ignoreras egendomsvärdet alltid.<br/>            Om dokumentegenskaperna i en krypterad fil inte är offentliga och egendomsvärdet är true så<br/>            kan inte dokumentegenskaperna laddas och ett undantag kommer att kastas.<br/>            Läs-skriv **bool**. |
| [`warning_callback`](/slides/python-net/sv/aspose.slides/iloadoptions/warning_callback/) | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om laddnings<br/>            processen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/sv/aspose.slides/iloadoptions/blob_management_options/) | Representerar de alternativ som kan användas för att hantera Binary Large Objects (BLOBs) beteende,<br/>            såsom användning av temporära filer eller maximalt antal BLOB-byte i minnet. Dessa alternativ är avsedda att ställa in<br/>            det bästa prestanda/minnesförbrukningsförhållandet för en specifik miljö eller krav.<br/>            En Binary Large Object (BLOB) är binär data lagrad som en enhet – d.v.s. BLOB kan <br/>            vara ett ljud, video eller själva presentationen. |
| [`document_level_font_sources`](/slides/python-net/sv/aspose.slides/iloadoptions/document_level_font_sources/) | Anger källor för externa teckensnitt som ska användas av presentationen.<br/>            Dessa teckensnitt är tillgängliga för presentationen under hela dess livslängd och delas inte med andra presentationer |
| [`interruption_token`](/slides/python-net/sv/aspose.slides/iloadoptions/interruption_token/) | Tokenet för att övervaka avbrottsförfrågningar.<br/>            <br/>            Detta token hanterar hela [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-instansens livslängd. Alla långvariga operationer, såsom presentation<br/>            laddning eller sparning, kommer att avbrytas genom anrop av [`IInterruptionTokenSource.interrupt`](/slides/python-net/sv/aspose.slides/iinterruptiontokensource/interrupt)-metoden i<br/>            [`IInterruptionTokenSource`](/slides/python-net/sv/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/sv/aspose.slides/iloadoptions/resource_loading_callback/) | Returnerar eller anger återuppringningsgränssnitt som hanterar inläsning av externa resurser.<br/>            Läs/skriv [`IResourceLoadingCallback`](/slides/python-net/sv/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/sv/aspose.slides/iloadoptions/spreadsheet_options/) | Representerar alternativ som kan användas för att ange ytterligare kalkylbladsbeteende. |
| [`default_text_language`](/slides/python-net/sv/aspose.slides/iloadoptions/default_text_language/) | Returnerar eller anger standardspråket för presentationstext.<br/>             Läs/skriv **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/sv/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Bestämmer om Aspose.Slides kommer att ta bort alla inbäddade binära objekt under presentationens inläsning.<br/>            <br/>Typerna av de inbäddade binära objekten:<br/><br/><br/>* VBA-projekt [`IPresentation.vba_project`](/slides/python-net/sv/aspose.slides/ipresentation/vba_project)<br/>* OLE-objekt inbäddad data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX-kontroll binär data [`IControl.active_x_control_binary`](/slides/python-net/sv/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Läs/skriv **bool**. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)