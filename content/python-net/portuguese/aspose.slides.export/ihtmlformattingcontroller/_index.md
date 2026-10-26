---
title: IHtmlFormattingController class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController classe

Controla a geração de um arquivo html.

O tipo IHtmlFormattingController expõe os seguintes membros:

## Métodos

| Método | Descrição |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/pt/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Chamado para escrever o cabeçalho do documento html. Chamado uma vez por conversão de apresentação. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/pt/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Chamado para escrever o rodapé do documento html. Chamado uma vez por conversão de apresentação. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/pt/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Chamado para escrever o cabeçalho do slide html. Chamado uma vez para cada slide. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/pt/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Chamado para escrever o rodapé do slide html. Chamado uma vez para cada slide. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/pt/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será concluída, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/pt/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será concluída, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior. |


### Veja Também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)