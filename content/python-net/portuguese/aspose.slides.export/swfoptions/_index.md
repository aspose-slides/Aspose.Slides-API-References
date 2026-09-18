---
title: SwfOptions class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/swfoptions/
---
## classe SwfOptions

Fornece opções que controlam como uma apresentação é salva no formato Swf.

**Inheritance:**[`SwfOptions`](/slides/python-net/pt/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)

O tipo SwfOptions expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/swfoptions/__init__/#) | Construtor padrão. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/swfoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            **Leitura/Gravação** [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/swfoptions/progress_callback/) | Representa um objeto de retorno de chamada para atualizações de progresso de salvamento em percentual.<br/>            Veja [`IProgressCallback`](/slides/python-net/pt/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/swfoptions/default_regular_font/) | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada.<br/>            **Leitura-Gravação** **str**. |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/swfoptions/gradient_style/) | Retorna ou define o estilo visual do gradiente.<br/>            **Leitura/Gravação** [`GradientStyle`](/slides/python-net/pt/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/swfoptions/skip_java_script_links/) | Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação.<br/>            **Leitura/Gravação** **bool**. O valor padrão é **false**. |
| [`show_hidden_slides`](/slides/python-net/pt/aspose.slides.export/swfoptions/show_hidden_slides/) | Especifica se o documento gerado deve incluir slides ocultos ou não.<br/>            O padrão é `false`. |
| [`compressed`](/slides/python-net/pt/aspose.slides.export/swfoptions/compressed/) | Especifica se o documento SWF gerado deve ser compactado ou não.<br/>            O padrão é `true`. |
| [`viewer_included`](/slides/python-net/pt/aspose.slides.export/swfoptions/viewer_included/) | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não.<br/>            O padrão é `true`. |
| [`show_page_border`](/slides/python-net/pt/aspose.slides.export/swfoptions/show_page_border/) | Especifica se a borda ao redor das páginas deve ser exibida. O padrão é true. |
| [`show_full_screen`](/slides/python-net/pt/aspose.slides.export/swfoptions/show_full_screen/) | Mostrar/ocultar botão de tela cheia. Pode ser substituído em flashvars. O padrão é true. |
| [`show_page_stepper`](/slides/python-net/pt/aspose.slides.export/swfoptions/show_page_stepper/) | Mostrar/ocultar avançador de página. Pode ser substituído em flashvars. O padrão é true. |
| [`show_search`](/slides/python-net/pt/aspose.slides.export/swfoptions/show_search/) | Mostrar/ocultar seção de pesquisa. Pode ser substituído em flashvars. O padrão é true. |
| [`show_top_pane`](/slides/python-net/pt/aspose.slides.export/swfoptions/show_top_pane/) | Mostrar/ocultar todo o painel superior. Pode ser substituído em flashvars. O padrão é true. |
| [`show_bottom_pane`](/slides/python-net/pt/aspose.slides.export/swfoptions/show_bottom_pane/) | Mostrar/ocultar painel inferior. Pode ser substituído em flashvars. O padrão é true. |
| [`show_left_pane`](/slides/python-net/pt/aspose.slides.export/swfoptions/show_left_pane/) | Mostrar/ocultar painel esquerdo. Pode ser substituído em flashvars. O padrão é true. |
| [`start_open_left_pane`](/slides/python-net/pt/aspose.slides.export/swfoptions/start_open_left_pane/) | Iniciar com o painel esquerdo aberto. Pode ser substituído em flashvars. O padrão é false. |
| [`enable_context_menu`](/slides/python-net/pt/aspose.slides.export/swfoptions/enable_context_menu/) | Habilitar/desabilitar menu de contexto. O padrão é true. |
| [`logo_image_bytes`](/slides/python-net/pt/aspose.slides.export/swfoptions/logo_image_bytes/) | Imagem que será exibida como logotipo no canto superior direito do visualizador.<br/>            A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente. |
| [`logo_link`](/slides/python-net/pt/aspose.slides.export/swfoptions/logo_link/) | Obtém ou define o endereço completo do hiperlink para um logotipo.<br/>            Tem efeito somente se um [`SwfOptions.logo_image_bytes`](/slides/python-net/pt/aspose.slides.export/swfoptions/logo_image_bytes) for especificado. |
| [`jpeg_quality`](/slides/python-net/pt/aspose.slides.export/swfoptions/jpeg_quality/) | Especifica a qualidade das imagens JPEG.<br/>            O padrão é 95. |
| [`slides_layout_options`](/slides/python-net/pt/aspose.slides.export/swfoptions/slides_layout_options/) | Obtém ou define o modo como os slides são colocados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](/slides/python-net/pt/aspose.slides.export/islideslayoutoptions). <br/>            Esta propriedade não suporta atribuição de objetos do tipo [`HandoutLayoutingOptions`](/slides/python-net/pt/aspose.slides.export/handoutlayoutingoptions) |


### Veja Também
* classe [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)
* classe [`SwfOptions`](/slides/python-net/pt/aspose.slides.export/swfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)