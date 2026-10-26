---
title: ISlideCollection class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/islidecollection/
---
## ISlideCollection osztály

Egy diák gyűjteményét képviseli.

Az ISlideCollection típus a következő tagokat teszi közzé:

A megadott indexű elemet adja vissza.
            Csak olvasható [`ISlide`](/slides/python-net/hu/aspose.slides/islide).

## Indexer

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/islidecollection/__getitem__/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/hu/aspose.slides/islidecollection/add_clone/#islide) | A megadott dia egy példányát a gyűjtemény végére adja hozzá. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/hu/aspose.slides/islidecollection/add_clone/#islide-isection) | A megadott dia egy példányát a megadott szakasz végére adja hozzá. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/hu/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | A megadott dia egy példányát a gyűjtemény végére adja hozzá. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/hu/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | A megadott forrásdia egy példányát a gyűjtemény végére adja hozzá.<br/>            A megfelelő elrendezés automatikusan ki lesz választva a megadott <br/>            mesterből (a megfelelő elrendezés az, amelynek típusa vagy neve megegyezik <br/>            a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor<br/>            a forrásdia elrendezése klónozva lesz (ha az allowCloneMissingLayout <br/>            értéke igaz) vagy PptxEditException dobódik (ha az allowCloneMissingLayout<br/>            értéke hamis). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_clone/#int-islide) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába szúrja be. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába szúrja be. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | A megadott forrásdia egy példányát a gyűjtemény megadott pozíciójába szúrja be.<br/>            A megfelelő elrendezés automatikusan ki lesz választva a megadott <br/>            mesterből (a megfelelő elrendezés az, amelynek típusa vagy neve megegyezik <br/>            a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor<br/>            a forrásdia elrendezése klónozva lesz (ha az allowCloneMissingLayout <br/>            értéke igaz) vagy PptxEditException dobódik (ha az allowCloneMissingLayout<br/>            értéke hamis). |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/islidecollection/to_array/#) | Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/islidecollection/to_array/#int-int) | Létrehoz és visszaad egy tömböt, amely a megadott tartomány diáit tartalmazza. |
| [`reorder(self, index, slide)`](/slides/python-net/hu/aspose.slides/islidecollection/reorder/#int-islide) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [`reorder(self, index, slides)`](/slides/python-net/hu/aspose.slides/islidecollection/reorder/#int-listislide) | Áthelyezi a diákat a gyűjteményből a megadott pozícióba.<br/>            A diák az indextől kezdődően a listában megjelenő sorrendben kerülnek elhelyezésre. |
| [`add_from_pdf(self, path)`](/slides/python-net/hu/aspose.slides/islidecollection/add_from_pdf/#str) | Diákat hoz létre a PDF dokumentumból, és a gyűjtemény végére adja hozzá. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/hu/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Diákat hoz létre a PDF dokumentumból, és a pdf importálási beállításokat figyelembe véve a gyűjtemény végére adja hozzá. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/hu/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Diákat hoz létre a PDF dokumentumból, és a gyűjtemény végére adja hozzá. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/hu/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Diákat hoz létre a PDF dokumentumból, és a gyűjtemény végére adja hozzá. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/hu/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá. |
| [`add_from_html(self, html_text)`](/slides/python-net/hu/aspose.slides/islidecollection/add_from_html/#str) | Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/hu/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá. |
| [`add_from_html(self, html_stream)`](/slides/python-net/hu/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Diákat hoz létre HTML szövegből, és a gyűjteménybe a megadott pozícióba szúrja be. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_from_html/#int-str) | Diákat hoz létre HTML szövegből, és a gyűjteménybe a megadott pozícióba szúrja be. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Diákat hoz létre HTML szövegből, és a gyűjteménybe a megadott pozícióba szúrja be. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Diákat hoz létre HTML szövegből, és a gyűjteménybe a megadott pozícióba szúrja be. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Diákat hoz létre HTML szövegből, és a gyűjteménybe a megadott pozícióba szúrja be. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Diákat hoz létre HTML szövegből, és a gyűjteménybe a megadott pozícióba szúrja be. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Diákat hoz létre HTML szövegből, és a gyűjteménybe a megadott pozícióba szúrja be. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Diákat hoz létre HTML szövegből, és a gyűjteménybe a megadott pozícióba szúrja be. |
| [`add_empty_slide(self, layout)`](/slides/python-net/hu/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Új üres diát ad a gyűjtemény végéhez. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/hu/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába szúrja be. |
| [`remove(self, value)`](/slides/python-net/hu/aspose.slides/islidecollection/remove/#islide) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/islidecollection/remove_at/#int) | Eltávolítja a gyűjtemény a megadott indexű elemét. |
| [`index_of(self, slide)`](/slides/python-net/hu/aspose.slides/islidecollection/index_of/#islide) | Visszaadja a megadott dia indexét a gyűjteményben. |

### Lásd még
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)