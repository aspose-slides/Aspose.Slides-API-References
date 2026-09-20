---
title: IPdfOptions class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/ipdfoptions/
---
## třída IPdfOptions

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.

Typ IPdfOptions obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`text_compression`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/text_compression/) | Určuje typ komprese používaný pro veškerý textový obsah v dokumentu.<br/>            Čtení/Zápis [`PdfTextCompression`](/slides/python-net/cs/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Určuje, zda má být pro každý obrázek vybrána nejúčinnější komprese (namísto výchozí) <br/>            automaticky. Pokud je nastavena na **bool**.true, pro každý obrázek v prezentaci bude vybrán nejvhodnější kompresní <br/>            algoritmus, což povede k menší velikosti výsledného PDF dokumentu. <br/>            Výběr nejlepšího poměru komprese obrázku je výpočetně náročný a vyžaduje <br/>            další množství RAM, a tato volba je ve výchozím nastavení **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | True, pokud chcete vložit písma TrueType pro ASCII znaky 32-127.<br/>            Písma pro kódy znaků vyšší než 127 jsou vždy vložena.<br/>            Čtení/Zápis **bool**. |
| [`show_hidden_slides`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Určuje, zda má vygenerovaný dokument obsahovat skryté snímky nebo ne.<br/>            Výchozí hodnota je `false`. |
| [`additional_common_font_families`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které má Aspose.Slides považovat za běžné.<br/>            Čtení/Zápis **str**[]. |
| [`embed_full_fonts`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Určuje, zda mají být vloženy všechny znaky písma, nebo jen použitá podmnožina.<br/>            Čtení/Zápis **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné stylování.<br/>            Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro určitá písma.<br/>            Čtení/Zápis **bool**. |
| [`jpeg_quality`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/jpeg_quality/) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu.<br/>            Čtení/Zápis **int**. |
| [`compliance`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/compliance/) | Požadovaná úroveň souladu pro vygenerovaný PDF dokument.<br/>            Čtení/Zápis [`PdfCompliance`](/slides/python-net/cs/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/password/) | Nastavení uživatelského hesla pro ochranu PDF dokumentu. <br/>            Čtení/Zápis **str**. |
| [`access_permissions`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/access_permissions/) | Obsahuje sadu příznaků určujících, jaká oprávnění k přístupu mají být při otevření dokumentu s uživatelským přístupem udělena.<br/>            Viz [`PdfAccessPermissions`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | True, pokud chcete převést všechny metafily použité v prezentaci na PNG obrázky.<br/>            Čtení/Zápis **bool**. |
| [`sufficient_resolution`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu.<br/>            <br/>Vlastnost ovlivňuje velikost souboru, dobu exportu a kvalitu obrázku.<br/><br/><br/>Výchozí hodnota je **96** .<br/><br/><br/>            Čtení/Zápis **float**. |
| [`draw_slides_frame`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/draw_slides_frame/) | True, pokud chcete kolem každého snímku vykreslit černý rám.<br/>             Čtení/Zápis **bool**. |
| [`slides_layout_options`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/slides_layout_options/) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](/slides/python-net/cs/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/image_transparent_color/) | Získá nebo nastaví průhlednou barvu obrázku. |
| [`apply_image_transparent`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Aplikuje zadanou průhlednou barvu na obrázek, pokud je `true`. |
| [`ink_options`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/ink_options/) | Poskytuje možnosti, které řídí vzhled Objektů Ink v exportovaném dokumentu.<br/>            Pouze pro čtení [`IInkOptions`](/slides/python-net/cs/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/include_ole_data/) | True, pokud chcete převést všechna OLE data z prezentace na vložené soubory v výsledném PDF.<br/>            Čtení/Zápis **bool**. |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)