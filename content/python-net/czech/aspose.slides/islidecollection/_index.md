---
title: ISlideCollection class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/islidecollection/
---
## ISlideCollection třída

Reprezentuje kolekci snímků.

Typ ISlideCollection vystavuje následující členy:

Získá prvek na zadaném indexu. Pouze pro čtení [`ISlide`](/slides/python-net/cs/aspose.slides/islide).

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides/islidecollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/cs/aspose.slides/islidecollection/add_clone/#islide) | Přidá kopii určeného snímku na konec kolekce. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/cs/aspose.slides/islidecollection/add_clone/#islide-isection) | Přidá kopii určeného snímku na konec určené sekce. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/cs/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Přidá kopii určeného snímku na konec kolekce. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/cs/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Přidá kopii určeného zdrojového snímku na konec kolekce.<br/>            Vhodné rozložení bude vybráno automaticky ze zadaného <br/>            masteru (vhodné rozložení je rozložení se stejným Typem nebo názvem jako <br/>            rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, <br/>            rozložení zdrojového snímku bude klonováno (pokud je allowCloneMissingLayout <br/>            nastaveno na true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout <br/>            nastaveno na false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_clone/#int-islide) | Vloží kopii určeného snímku na zadanou pozici v kolekci. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Vloží kopii určeného snímku na zadanou pozici v kolekci. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Vloží kopii určeného zdrojového snímku na zadanou pozici v kolekci.<br/>            Vhodné rozložení bude vybráno automaticky ze zadaného <br/>            masteru (vhodné rozložení je rozložení se stejným Typem nebo názvem jako <br/>            rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, <br/>            rozložení zdrojového snímku bude klonováno (pokud je allowCloneMissingLayout <br/>            nastaveno na true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout <br/>            nastaveno na false). |
| [`to_array(self)`](/slides/python-net/cs/aspose.slides/islidecollection/to_array/#) | Vytvoří a vrátí pole se všemi snímky. |
| [`to_array(self, start_index, count)`](/slides/python-net/cs/aspose.slides/islidecollection/to_array/#int-int) | Vytvoří a vrátí pole se všemi snímky ze zadaného rozsahu. |
| [`reorder(self, index, slide)`](/slides/python-net/cs/aspose.slides/islidecollection/reorder/#int-islide) | Přesune snímek v kolekci na zadanou pozici. |
| [`reorder(self, index, slides)`](/slides/python-net/cs/aspose.slides/islidecollection/reorder/#int-listislide) | Přesune snímky v kolekci na zadanou pozici.<br/>            Snímky budou umístěny počínaje indexem v pořadí, v jakém se nacházejí v seznamu. |
| [`add_from_pdf(self, path)`](/slides/python-net/cs/aspose.slides/islidecollection/add_from_pdf/#str) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/cs/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce s ohledem na možnosti importu PDF. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/cs/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/cs/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/cs/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [`add_from_html(self, html_text)`](/slides/python-net/cs/aspose.slides/islidecollection/add_from_html/#str) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/cs/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [`add_from_html(self, html_stream)`](/slides/python-net/cs/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_from_html/#int-str) | Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici. |
| [`add_empty_slide(self, layout)`](/slides/python-net/cs/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Přidá nový prázdný snímek na konec kolekce. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/cs/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Vloží kopii určeného snímku na zadanou pozici v kolekci. |
| [`remove(self, value)`](/slides/python-net/cs/aspose.slides/islidecollection/remove/#islide) | Odstraní první výskyt specifikovaného objektu z kolekce. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/islidecollection/remove_at/#int) | Odstraní prvek na zadaném indexu v kolekci. |
| [`index_of(self, slide)`](/slides/python-net/cs/aspose.slides/islidecollection/index_of/#islide) | Vrátí index specifikovaného snímku v kolekci. |

### Viz také
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)