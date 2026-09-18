---
title: SlideCollection class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/slidecollection/
---
## SlideCollection osztály

A diák gyűjteményét képviseli.

A SlideCollection típus a következő tagokat teszi elérhetővé:

A megadott indexű elemet adja vissza.  
Csak olvasható [`Slide`](/slides/python-net/hu/aspose.slides/slide).

## Indexer

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/slidecollection/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/hu/aspose.slides/slidecollection/add_clone/#islide) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/hu/aspose.slides/slidecollection/add_clone/#islide-isection) | Hozzáad egy megadott dia másolatát a megadott szakasz végéhez. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/hu/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/hu/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Hozzáad egy megadott forrásdia másolatát a gyűjtemény végéhez.<br/>            A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott <br/>            mesterből (a megfelelő elrendezés azonos típusú vagy nevű elrendezés, mint <br/>            a forrásdia elrendezése). Ha nincs megfelelő elrendezés, akkor <br/>            a forrásdia elrendezése klónozódik (ha az allowCloneMissingLayout <br/>            igaz), vagy PptxEditException dobódik (ha az allowCloneMissingLayout <br/>            hamis). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_clone/#int-islide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Beszúr egy megadott forrásdia másolatát a gyűjtemény megadott pozíciójába.<br/>            A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott <br/>            mesterből (a megfelelő elrendezés azonos típusú vagy nevű elrendezés, mint <br/>            a forrásdia elrendezése). Ha nincs megfelelő elrendezés, akkor <br/>            a forrásdia elrendezése klónozódik (ha az allowCloneMissingLayout <br/>            igaz), vagy PptxEditException dobódik (ha az allowCloneMissingLayout <br/>            hamis). |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/slidecollection/to_array/#) | Létrehoz és visszaad egy tömböt, amely tartalmazza az összes diát. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/slidecollection/to_array/#int-int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő diákot tartalmazza.<br/>            Az első hozzáadandó dia indexe. A hozzáadandó diák száma. |
| [`reorder(self, index, slide)`](/slides/python-net/hu/aspose.slides/slidecollection/reorder/#int-islide) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [`reorder(self, index, slides)`](/slides/python-net/hu/aspose.slides/slidecollection/reorder/#int-listislide) | Áthelyezi a diákat a gyűjteményből a megadott pozícióba.<br/>            A diák az indextől kezdve lesznek elhelyezve abban a sorrendben, ahogy a listában szerepelnek. |
| [`add_from_pdf(self, path)`](/slides/python-net/hu/aspose.slides/slidecollection/add_from_pdf/#str) | Diákat hoz létre a PDF-dokumentumból, és a gyűjtemény végéhez adja őket. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/hu/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Diákat hoz létre a PDF-dokumentumból, és a pdf importálási beállítások figyelembevételével a gyűjtemény végéhez adja őket. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/hu/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Diákat hoz létre a PDF-dokumentumból, és a gyűjtemény végéhez adja őket. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/hu/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Diákat hoz létre a PDF-dokumentumból, és a gyűjtemény végéhez adja őket. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/hu/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [`add_from_html(self, html_text)`](/slides/python-net/hu/aspose.slides/slidecollection/add_from_html/#str) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/hu/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [`add_from_html(self, html_stream)`](/slides/python-net/hu/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be őket a gyűjteményben. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be őket a gyűjteményben. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_from_html/#int-str) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be őket a gyűjteményben. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be őket a gyűjteményben. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be őket a gyűjteményben. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be őket a gyűjteményben. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be őket a gyűjteményben. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be őket a gyűjteményben. |
| [`add_empty_slide(self, layout)`](/slides/python-net/hu/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Új üres diát ad a gyűjtemény végéhez. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/hu/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [`remove(self, value)`](/slides/python-net/hu/aspose.slides/slidecollection/remove/#islide) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/slidecollection/remove_at/#int) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [`index_of(self, slide)`](/slides/python-net/hu/aspose.slides/slidecollection/index_of/#islide) | Visszaadja a megadott dia indexét a gyűjteményben. |

### Lásd még
* osztály [`Slide`](/slides/python-net/hu/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)