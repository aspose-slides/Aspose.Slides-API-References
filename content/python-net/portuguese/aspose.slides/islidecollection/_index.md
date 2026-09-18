---
title: ISlideCollection class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/islidecollection/
---
## ISlideCollection class

Representa uma coleção de slides.

O tipo ISlideCollection expõe os seguintes membros:

Obtém o elemento no índice especificado.  
Somente leitura [`ISlide`](/slides/python-net/pt/aspose.slides/islide).

## Indexer

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides/islidecollection/__getitem__/) |  |

## Methods

| Método | Descrição |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/pt/aspose.slides/islidecollection/add_clone/#islide) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/pt/aspose.slides/islidecollection/add_clone/#islide-isection) | Adiciona uma cópia de um slide especificado ao final da seção especificada. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/pt/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/pt/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Adiciona uma cópia de um slide de origem especificado ao final da coleção.<br/>            O layout apropriado será selecionado automaticamente a partir do mestre especificado (layout apropriado é o layout com o mesmo Tipo ou Nome que o layout do slide de origem). Se não houver layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_clone/#int-islide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Insere uma cópia de um slide de origem especificado na posição especificada da coleção.<br/>            O layout apropriado será selecionado automaticamente a partir do mestre especificado (layout apropriado é o layout com o mesmo Tipo ou Nome que o layout do slide de origem). Se não houver layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |
| [`to_array(self)`](/slides/python-net/pt/aspose.slides/islidecollection/to_array/#) | Cria e retorna um array com todos os slides nele. |
| [`to_array(self, start_index, count)`](/slides/python-net/pt/aspose.slides/islidecollection/to_array/#int-int) | Cria e retorna um array com todos os slides do intervalo especificado nele. |
| [`reorder(self, index, slide)`](/slides/python-net/pt/aspose.slides/islidecollection/reorder/#int-islide) | Move o slide da coleção para a posição especificada. |
| [`reorder(self, index, slides)`](/slides/python-net/pt/aspose.slides/islidecollection/reorder/#int-listislide) | Move slides da coleção para a posição especificada.<br/>            Os slides serão colocados a partir do índice, na ordem em que aparecem na lista. |
| [`add_from_pdf(self, path)`](/slides/python-net/pt/aspose.slides/islidecollection/add_from_pdf/#str) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/pt/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Cria slides a partir do documento PDF e os adiciona ao final da coleção considerando as opções de importação de PDF. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/pt/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/pt/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/pt/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [`add_from_html(self, html_text)`](/slides/python-net/pt/aspose.slides/islidecollection/add_from_html/#str) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/pt/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [`add_from_html(self, html_stream)`](/slides/python-net/pt/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_from_html/#int-str) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [`add_empty_slide(self, layout)`](/slides/python-net/pt/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Adiciona um novo slide vazio ao final da coleção. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/pt/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [`remove(self, value)`](/slides/python-net/pt/aspose.slides/islidecollection/remove/#islide) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/islidecollection/remove_at/#int) | Remove o elemento no índice especificado da coleção. |
| [`index_of(self, slide)`](/slides/python-net/pt/aspose.slides/islidecollection/index_of/#islide) | Retorna o índice do slide especificado na coleção. |

### Veja Também
* classe [`ISlide`](/slides/python-net/pt/aspose.slides/islide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)