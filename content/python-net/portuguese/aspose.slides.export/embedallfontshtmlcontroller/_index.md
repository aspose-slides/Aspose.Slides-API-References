---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController classe

A classe de controlador de formatação a ser usada para incorporar todas as fontes da apresentação no formato WOFF.

O tipo EmbedAllFontsHtmlController expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Cria uma nova instância |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Cria uma nova instância |

## Métodos

| Método | Descrição |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Chamado para escrever o cabeçalho do documento html. Chamado uma vez por conversão de apresentação. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Chamado para escrever o rodapé do documento html. Chamado uma vez por conversão de apresentação. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Chamado para escrever o cabeçalho do slide html. Chamado uma vez para cada slide. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Chamado para escrever o rodapé do slide html. Chamado uma vez para cada slide. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será concluída, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será concluída, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Escreve todas as fontes contidas em [`Presentation`](/slides/python-net/pt/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Grava os dados como base64 no próprio documento HTML |

### Ver Também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)