---
title: HtmlOptions class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/htmloptions/
---
## classe HtmlOptions

Representa opções de exportação HTML.

**Inheritance:**[`HtmlOptions`](/slides/python-net/pt/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)

The HtmlOptions type exposes the following members:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/pt/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Cria um novo objeto HtmlOptions especificando callback. |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/htmloptions/__init__/#) | Cria um novo objeto HtmlOptions para salvar em um único arquivo HTML. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/htmloptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Leitura/gravação [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/htmloptions/progress_callback/) | Representa um objeto de callback para atualizações de progresso de salvamento em porcentagem.<br/>            Veja [`IProgressCallback`](/slides/python-net/pt/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/htmloptions/default_regular_font/) | Retorna ou define a fonte usada caso a fonte origem não seja encontrada.<br/>            Leitura-gravação **str**. |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/htmloptions/gradient_style/) | Retorna ou define o estilo visual do gradiente.<br/>            Leitura/gravação [`GradientStyle`](/slides/python-net/pt/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/htmloptions/skip_java_script_links/) | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação.<br/>            Leitura/gravação **bool**. O valor padrão é **false** . |
| [`slides_layout_options`](/slides/python-net/pt/aspose.slides.export/htmloptions/slides_layout_options/) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](/slides/python-net/pt/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/pt/aspose.slides.export/htmloptions/ink_options/) | Fornece opções que controlam a aparência de objetos Ink no documento exportado.<br/>            Somente leitura [`IInkOptions`](/slides/python-net/pt/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/pt/aspose.slides.export/htmloptions/show_hidden_slides/) | Especifica se o documento gerado deve incluir slides ocultos ou não.<br/>            O padrão é `false`. |
| [`html_formatter`](/slides/python-net/pt/aspose.slides.export/htmloptions/html_formatter/) | Retorna ou define o modelo HTML.<br/>            Leitura/gravação [`IHtmlFormatter`](/slides/python-net/pt/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/pt/aspose.slides.export/htmloptions/disable_font_ligatures/) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras.<br/>            Quando definido como `true`, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como `false`. |
| [`slide_image_format`](/slides/python-net/pt/aspose.slides.export/htmloptions/slide_image_format/) | Retorna ou define opções de formato de imagem de slide.<br/>            Leitura/gravação [`ISlideImageFormat`](/slides/python-net/pt/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/pt/aspose.slides.export/htmloptions/jpeg_quality/) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF.<br/>            Leitura/gravação **int**. |
| [`pictures_compression`](/slides/python-net/pt/aspose.slides.export/htmloptions/pictures_compression/) | Representa o nível de compressão das imagens |
| [`delete_pictures_cropped_areas`](/slides/python-net/pt/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro, as partes recortadas serão removidas; se falso, serão serializadas no documento (o que pode levar a um arquivo maior) |
| [`svg_responsive_layout`](/slides/python-net/pt/aspose.slides.export/htmloptions/svg_responsive_layout/) | True para excluir atributos de largura e altura do contêiner svg — isso tornará o layout responsivo. False caso contrário.<br/>            Leitura/gravação **bool**. |


### Veja Também
* classe [`HtmlOptions`](/slides/python-net/pt/aspose.slides.export/htmloptions)
* classe [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)