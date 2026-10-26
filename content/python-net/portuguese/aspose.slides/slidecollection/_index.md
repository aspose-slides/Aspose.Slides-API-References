---
title: SlideCollection class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/slidecollection/
---
## SlideCollection classe

Representa uma coleção de slides.

O tipo SlideCollection expõe os seguintes membros:

Obtém o elemento no índice especificado.
            Somente leitura [`Slide`](/slides/python-net/pt/aspose.slides/slide).

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides/slidecollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/pt/aspose.slides/slidecollection/add_clone/#islide) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/pt/aspose.slides/slidecollection/add_clone/#islide-isection) | Adiciona uma cópia de um slide especificado ao final da seção especificada. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/pt/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/pt/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Adiciona uma cópia de um slide fonte especificado ao final da coleção.<br/>            O layout apropriado será selecionado automaticamente a partir do mestre especificado <br/>            (o layout apropriado é o layout com o mesmo Type ou Name que <br/>            o layout do slide fonte). Se não houver layout apropriado então<br/>            o layout do slide fonte será clonado (se allowCloneMissingLayout <br/>            for true) ou será lançada PptxEditException (se allowCloneMissingLayout<br/>            for false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_clone/#int-islide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Insere uma cópia de um slide fonte especificado na posição especificada da coleção.<br/>            O layout apropriado será selecionado automaticamente a partir do mestre especificado <br/>            (o layout apropriado é o layout com o mesmo Type ou Name que <br/>            o layout do slide fonte). Se não houver layout apropriado então<br/>            o layout do slide fonte será clonado (se allowCloneMissingLayout <br/>            for true) ou será lançada PptxEditException (se allowCloneMissingLayout<br/>            for false). |
| [`to_array(self)`](/slides/python-net/pt/aspose.slides/slidecollection/to_array/#) | Cria e retorna um array com todos os slides. |
| [`to_array(self, start_index, count)`](/slides/python-net/pt/aspose.slides/slidecollection/to_array/#int-int) | Cria e retorna um array com todos os slides do intervalo especificado.<br/>            Um índice do primeiro slide a ser adicionado. Um número de slides a serem adicionados. |
| [`reorder(self, index, slide)`](/slides/python-net/pt/aspose.slides/slidecollection/reorder/#int-islide) | Move o slide da coleção para a posição especificada. |
| [`reorder(self, index, slides)`](/slides/python-net/pt/aspose.slides/slidecollection/reorder/#int-listislide) | Move slides da coleção para a posição especificada.<br/>            Os slides serão colocados a partir do índice na ordem em que aparecem na lista. |
| [`add_from_pdf(self, path)`](/slides/python-net/pt/aspose.slides/slidecollection/add_from_pdf/#str) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/pt/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Cria slides a partir do documento PDF e os adiciona ao final da coleção considerando as opções de importação de pdf. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/pt/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/pt/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/pt/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [`add_from_html(self, html_text)`](/slides/python-net/pt/aspose.slides/slidecollection/add_from_html/#str) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/pt/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [`add_from_html(self, html_stream)`](/slides/python-net/pt/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_from_html/#int-str) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`add_empty_slide(self, layout)`](/slides/python-net/pt/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Adiciona um novo slide vazio ao final da coleção. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/pt/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [`remove(self, value)`](/slides/python-net/pt/aspose.slides/slidecollection/remove/#islide) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/slidecollection/remove_at/#int) | Remove o elemento no índice especificado da coleção. |
| [`index_of(self, slide)`](/slides/python-net/pt/aspose.slides/slidecollection/index_of/#islide) | Retorna o índice do slide especificado na coleção. |


### Ver também
* classe [`Slide`](/slides/python-net/pt/aspose.slides/slide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)