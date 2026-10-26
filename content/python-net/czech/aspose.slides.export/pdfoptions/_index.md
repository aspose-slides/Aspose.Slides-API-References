---
title: PdfOptions class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/pdfoptions/
---
## PdfOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.

**Dědičnost:**[`PdfOptions`](/slides/python-net/cs/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ PdfOptions vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/pdfoptions/__init__/#) | Výchozí konstruktor. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/pdfoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen.<br/>            Read/write [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/pdfoptions/progress_callback/) | Representuje objekt zpětného volání pro aktualizace průběhu ukládání v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/pdfoptions/default_regular_font/) | Vrací nebo nastavuje písmo použité v případě, že není nalezeno výchozí písmo.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/pdfoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl gradientu.<br/>            Read/write [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/pdfoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. <br/>            Read/write **bool**. Výchozí hodnota je **false**. |
| [`slides_layout_options`](/slides/python-net/cs/aspose.slides.export/pdfoptions/slides_layout_options/) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [`ISlidesLayoutOptions`](/slides/python-net/cs/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/cs/aspose.slides.export/pdfoptions/ink_options/) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu.<br/>            Read-only [`IInkOptions`](/slides/python-net/cs/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/cs/aspose.slides.export/pdfoptions/show_hidden_slides/) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne.<br/>            Výchozí hodnota je `false`. |
| [`text_compression`](/slides/python-net/cs/aspose.slides.export/pdfoptions/text_compression/) | Určuje typ komprese, který bude použit pro veškerý textový obsah v dokumentu.<br/>            Read/write [`PdfTextCompression`](/slides/python-net/cs/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/cs/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Určuje, zda má být pro každý obrázek vybrána nejúčinnější komprese (namísto výchozí) automaticky.<br/>            Pokud je nastaveno na **bool**.true, bude pro každý obrázek v prezentaci vybrán nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu.<br/>            Výběr nejlepšího poměru komprese obrázků je výpočetně náročný a vyžaduje dodatečnou paměť RAM, a tato možnost je ve výchozím nastavení **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/cs/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Určuje, zda Aspose.Slides vloží běžná písma pro ASCII (rozsah kódů 33..127) text.<br/>            Písma pro znaky s kódem vyšším než 127 jsou vždy vložena.<br/>            Seznam běžných písem zahrnuje základních 14 písem PDF a další uživatelem specifikovaná písma.<br/>            Read/write **bool**. |
| [`additional_common_font_families`](/slides/python-net/cs/aspose.slides.export/pdfoptions/additional_common_font_families/) | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které má Aspose.Slides považovat za běžná.<br/>            Read/write **str**[]. |
| [`embed_full_fonts`](/slides/python-net/cs/aspose.slides.export/pdfoptions/embed_full_fonts/) | Určuje, zda mají být vloženy všechny znaky písma nebo pouze použité podmnožiny.<br/>            Read/write **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/cs/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné stylování.<br/>            Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro určitá písma.<br/>            Read/write **bool**. |
| [`jpeg_quality`](/slides/python-net/cs/aspose.slides.export/pdfoptions/jpeg_quality/) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu.<br/>            Read/write **int**. |
| [`compliance`](/slides/python-net/cs/aspose.slides.export/pdfoptions/compliance/) | Požadovaná úroveň kompatibility pro generovaný PDF dokument.<br/>            Read/write [`PdfCompliance`](/slides/python-net/cs/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/cs/aspose.slides.export/pdfoptions/password/) | Nastavení uživatelského hesla pro ochranu PDF dokumentu.<br/>            Read/write **str**. |
| [`access_permissions`](/slides/python-net/cs/aspose.slides.export/pdfoptions/access_permissions/) | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu udělena s uživatelským přístupem.<br/>            Viz [`PdfAccessPermissions`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/cs/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | True, pokud mají být všechny metafily použité v prezentaci převedeny na PNG obrázky.<br/>            Read/write **bool**. |
| [`sufficient_resolution`](/slides/python-net/cs/aspose.slides.export/pdfoptions/sufficient_resolution/) | Vrací nebo nastavuje hodnotu určující rozlišení obrázků uvnitř PDF dokumentu.<br/>            <br/>Vlastnost ovlivňuje velikost souboru, čas exportu a kvalitu obrázku.<br/><br/><br/>Výchozí hodnota je **96**.<br/><br/><br/>            Read/write **float**. |
| [`draw_slides_frame`](/slides/python-net/cs/aspose.slides.export/pdfoptions/draw_slides_frame/) | True, pokud má být kolem každého snímku vykreslen černý rámeček.<br/>             Read/write **bool**. |
| [`image_transparent_color`](/slides/python-net/cs/aspose.slides.export/pdfoptions/image_transparent_color/) | Získá nebo nastaví průhlednou barvu obrázku. |
| [`apply_image_transparent`](/slides/python-net/cs/aspose.slides.export/pdfoptions/apply_image_transparent/) | Použije zadanou průhlednou barvu na obrázek, pokud je `true`. |
| [`include_ole_data`](/slides/python-net/cs/aspose.slides.export/pdfoptions/include_ole_data/) | True, pokud mají být všechny OLE data z prezentace převedeny na vložené soubory ve výsledném PDF.<br/>            Read/write **bool**. |


### Viz také
* třída [`PdfOptions`](/slides/python-net/cs/aspose.slides.export/pdfoptions)
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)