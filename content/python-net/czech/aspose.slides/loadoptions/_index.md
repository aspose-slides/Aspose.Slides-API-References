---
title: LoadOptions class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/loadoptions/
---
## LoadOptions třída

Allows to specify additional options (such as format or default font) when loading a presentation.

The LoadOptions type exposes the following members:

## Konstruktory

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/loadoptions/__init__/#) | Vytvoří nové výchozí možnosti načítání. |
| [`__init__(self, load_format)`](/slides/python-net/cs/aspose.slides/loadoptions/__init__/#loadformat) | Vytvoří nové možnosti načítání. |

## Vlastnosti

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/cs/aspose.slides/loadoptions/load_format/) | Vrací nebo nastavuje formát prezentace k načtení.<br/>            Číst/zapsat [`LoadFormat`](/slides/python-net/cs/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides/loadoptions/default_regular_font/) | Vrací nebo nastavuje běžné písmo použité, pokud není nalezeno zdrojové písmo.<br/>            Číst/zapsat **str**. |
| [`default_symbol_font`](/slides/python-net/cs/aspose.slides/loadoptions/default_symbol_font/) | Vrací nebo nastavuje Symbolové písmo použité, pokud není nalezeno zdrojové písmo.<br/>            Číst/zapsat **str**. |
| [`default_asian_font`](/slides/python-net/cs/aspose.slides/loadoptions/default_asian_font/) | Vrací nebo nastavuje asijské písmo použité, pokud není nalezeno zdrojové písmo.<br/>            Číst/zapsat **str**. |
| [`password`](/slides/python-net/cs/aspose.slides/loadoptions/password/) | Získá nebo nastaví heslo.<br/>            Číst/zapsat **str**. |
| [`only_load_document_properties`](/slides/python-net/cs/aspose.slides/loadoptions/only_load_document_properties/) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem.<br/>            Hodnota true znamená, že musí být načteny pouze vlastnosti dokumentu z šifrovaného <br/>            souboru prezentace a heslo má být ignorováno.<br/>            Hodnota false znamená, že celá šifrovaná prezentace musí být načtena s použitím správného <br/>            hesla.<br/>            Pokud není prezentace šifrována, hodnota vlastnosti je vždy ignorována.<br/>            Pokud nejsou vlastnosti dokumentu šifrovaného souboru veřejné a hodnota vlastnosti je true, pak<br/>            vlastnosti dokumentu nelze načíst a bude vyvolána výjimka.<br/>            Číst/zapsat **bool**. |
| [`warning_callback`](/slides/python-net/cs/aspose.slides/loadoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda načítací <br/>            proces bude pokračovat nebo bude ukončen.<br/>            Číst/zapsat [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/cs/aspose.slides/loadoptions/blob_management_options/) | Zastupuje možnosti, které lze použít ke správě chování zpracování velkých binárních objektů (BLOB),<br/>            například použití dočasných souborů nebo maximální velikosti BLOB v paměti. Tyto možnosti jsou určeny k nastavení<br/>            nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.<br/>            Velký binární objekt (BLOB) je binární data uložená jako jedinečná entita – tj. BLOB může <br/>            být audio, video nebo samotná prezentace. |
| [`document_level_font_sources`](/slides/python-net/cs/aspose.slides/loadoptions/document_level_font_sources/) | Určuje zdroje pro externí písma, která mají být použita v prezentaci.<br/>            Tato písma jsou dostupná prezentaci po celou dobu jejího životního cyklu a nejsou sdílena s ostatními prezentacemi |
| [`interruption_token`](/slides/python-net/cs/aspose.slides/loadoptions/interruption_token/) | Token pro sledování požadavků na přerušení.<br/>            <br/>            Tento token spravuje celou životnost instance [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). Jakákoli dlouho běžící operace, jako je načítání <br/>            nebo ukládání prezentace, bude přerušena voláním metody [`InterruptionTokenSource.interrupt`](/slides/python-net/cs/aspose.slides/interruptiontokensource/interrupt) z <br/>            [`InterruptionTokenSource`](/slides/python-net/cs/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/cs/aspose.slides/loadoptions/resource_loading_callback/) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů.<br/>            Číst/zapsat [`IResourceLoadingCallback`](/slides/python-net/cs/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/cs/aspose.slides/loadoptions/spreadsheet_options/) | Získá možnosti pro tabulky. Například tyto možnosti ovlivňují výpočet vzorců pro grafy. |
| [`default_text_language`](/slides/python-net/cs/aspose.slides/loadoptions/default_text_language/) | Vrací nebo nastavuje výchozí jazyk textu v prezentaci.<br/>             Číst/zapsat **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/cs/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Určuje, zda Aspose.Slides při načítání prezentace odstraní všechny vložené binární objekty.<br/>            <br/>Typy vložených binárních objektů:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/cs/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/cs/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Číst/zapsat **bool**. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)