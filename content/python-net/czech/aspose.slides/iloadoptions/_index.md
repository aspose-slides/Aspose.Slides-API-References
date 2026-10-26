---
title: ILoadOptions class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iloadoptions/
---
## ILoadOptions třída

Umožňuje zadat další možnosti (například formát nebo výchozí písmo) při načítání prezentace.

Typ ILoadOptions vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/cs/aspose.slides/iloadoptions/load_format/) | Vrací nebo nastavuje formát prezentace, který se má načíst.<br/>            Čtení/zápis [`LoadFormat`](/slides/python-net/cs/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides/iloadoptions/default_regular_font/) | Vrací nebo nastavuje standardní písmo použité, pokud není nalezeno zdrojové písmo.<br/>            Čtení/zápis **str**. |
| [`default_symbol_font`](/slides/python-net/cs/aspose.slides/iloadoptions/default_symbol_font/) | Vrací nebo nastavuje Symbol písmo použité, pokud není nalezeno zdrojové písmo.<br/>            Čtení/zápis **str**. |
| [`default_asian_font`](/slides/python-net/cs/aspose.slides/iloadoptions/default_asian_font/) | Vrací nebo nastavuje asijské písmo použité, pokud není nalezeno zdrojové písmo.<br/>            Čtení/zápis **str**. |
| [`password`](/slides/python-net/cs/aspose.slides/iloadoptions/password/) | Vrací nebo nastavuje heslo.<br/>            Čtení/zápis **str**. |
| [`only_load_document_properties`](/slides/python-net/cs/aspose.slides/iloadoptions/only_load_document_properties/) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem.<br/>            Hodnota true znamená, že musí být načteny pouze vlastnosti dokumentu z šifrovaného <br/>            souboru prezentace a heslo musí být ignorováno.<br/>            Hodnota false znamená, že celá šifrovaná prezentace musí být načtena s použitím správného <br/>            hesla.<br/>            Pokud prezentace není šifrována, hodnota vlastnosti je vždy ignorována.<br/>            Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné a hodnota vlastnosti je true, pak<br/>            vlastnosti dokumentu nelze načíst a bude vyvolána výjimka.<br/>            Čtení/zápis **bool**. |
| [`warning_callback`](/slides/python-net/cs/aspose.slides/iloadoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání <br/>            bude pokračovat nebo bude přerušen.<br/>            Čtení/zápis [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/cs/aspose.slides/iloadoptions/blob_management_options/) | Reprezentuje možnosti, které lze použít k řízení chování při správě velkých binárních objektů (BLOBů),<br/>            například používání dočasných souborů nebo maximálního počtu BLOBů v paměti. Tyto možnosti jsou určeny k nastavení<br/>            nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.<br/>            Velký binární objekt (BLOB) jsou binární data uložená jako jedna entita – tj. BLOB může být <br/>            audio, video nebo samotná prezentace. |
| [`document_level_font_sources`](/slides/python-net/cs/aspose.slides/iloadoptions/document_level_font_sources/) | Určuje zdroje externích písem, která má prezentace použít.<br/>            Tato písma jsou pro prezentaci dostupná po celou dobu její existence a nejsou sdílena s jinými prezentacemi |
| [`interruption_token`](/slides/python-net/cs/aspose.slides/iloadoptions/interruption_token/) | Token pro sledování požadavků na přerušení.<br/>            <br/>            Tento token řídí celou životnost instance [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). Jakákoli dlouho běžící operace, například načítání <br/>            nebo ukládání prezentace, bude přerušena voláním metody [`IInterruptionTokenSource.interrupt`](/slides/python-net/cs/aspose.slides/iinterruptiontokensource/interrupt) z <br/>            [`IInterruptionTokenSource`](/slides/python-net/cs/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/cs/aspose.slides/iloadoptions/resource_loading_callback/) | Vrací nebo nastavuje rozhraní zpětného volání, které řídí načítání externích zdrojů.<br/>            Čtení/zápis [`IResourceLoadingCallback`](/slides/python-net/cs/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/cs/aspose.slides/iloadoptions/spreadsheet_options/) | Reprezentuje možnosti, které lze použít k určení chování dalších tabulek. |
| [`default_text_language`](/slides/python-net/cs/aspose.slides/iloadoptions/default_text_language/) | Vrací nebo nastavuje výchozí jazyk pro text prezentace.<br/>             Čtení/zápis **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/cs/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Určuje, zda Aspose.Slides během načítání prezentace odstraní všechny vložené binární objekty.<br/>            <br/>Typy vložených binárních objektů:<br/><br/><br/>* VBA projekt [`IPresentation.vba_project`](/slides/python-net/cs/aspose.slides/ipresentation/vba_project)<br/>* OLE objektová vložená data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* Binary data ActiveX ovládacího prvku [`IControl.active_x_control_binary`](/slides/python-net/cs/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Čtení/zápis **bool**. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)