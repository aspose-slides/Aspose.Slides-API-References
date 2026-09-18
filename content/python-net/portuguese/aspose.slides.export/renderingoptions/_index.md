---
title: RenderingOptions class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/renderingoptions/
---
## classe RenderingOptions

Fornece opções que controlam como uma apresentação/slide é renderizada.

**Herança:**[`RenderingOptions`](/slides/python-net/pt/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)

O tipo RenderingOptions expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/renderingoptions/__init__/#) | Construtor padrão. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/renderingoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Leitura/escrita [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/renderingoptions/progress_callback/) | Representa um objeto de callback para salvar atualizações de progresso em percentual.<br/>            Veja [`IProgressCallback`](/slides/python-net/pt/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/renderingoptions/default_regular_font/) | Retorna ou define a fonte usada caso a fonte original não seja encontrada.<br/>            Leitura/gravação **str**. |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/renderingoptions/gradient_style/) | Retorna ou define o estilo visual do gradiente.<br/>            Leitura/escrita [`GradientStyle`](/slides/python-net/pt/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/renderingoptions/skip_java_script_links/) | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. <br/>            Leitura/escrita **bool**. O valor padrão é **false** . |
| [`slides_layout_options`](/slides/python-net/pt/aspose.slides.export/renderingoptions/slides_layout_options/) | Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](/slides/python-net/pt/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/pt/aspose.slides.export/renderingoptions/ink_options/) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado.<br/>            Somente leitura [`IInkOptions`](/slides/python-net/pt/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/pt/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras.<br/>            Quando definido como `true`, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como `false`. |

### Veja Também
* classe [`RenderingOptions`](/slides/python-net/pt/aspose.slides.export/renderingoptions)
* classe [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)