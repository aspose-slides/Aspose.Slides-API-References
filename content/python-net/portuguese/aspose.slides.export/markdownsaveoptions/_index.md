---
title: MarkdownSaveOptions class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions classe

Representa opções que controlam como a apresentação deve ser salva em markdown.

**Herança:**[`MarkdownSaveOptions`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)

O tipo MarkdownSaveOptions expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Leitura/gravação [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/progress_callback/) | Representa um objeto de callback para atualizações de progresso de salvamento em porcentagem.<br/>            Veja [`IProgressCallback`](/slides/python-net/pt/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada.<br/>            Leitura-gravação **str**. |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/gradient_style/) | Retorna ou define o estilo visual do gradiente.<br/>            Leitura/gravação [`GradientStyle`](/slides/python-net/pt/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação.<br/>            Leitura/gravação **bool**. O valor padrão é **false**. |
| [`export_type`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/export_type/) | Especifica a especificação markdown para converter a apresentação.<br/>            O padrão é `TextOnly`. |
| [`base_path`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/base_path/) | Especifica o caminho base onde o documento com recursos será salvo.<br/>            O padrão é o diretório atual da aplicação. |
| [`images_save_folder_name`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Especifica o nome da pasta para salvar imagens.<br/>            O padrão é `Images`. |
| [`new_line_type`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/new_line_type/) | Especifica se o documento gerado deve ter quebras de linha \\r(Macintosh) de \\n(Unix) ou \\r\\n(Windows).<br/>            O padrão é `Unix`. |
| [`show_comments`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/show_comments/) | Especifica se o documento gerado deve exibir comentários ou não.<br/>            O padrão é `false`. |
| [`show_hidden_slides`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Especifica se o documento gerado deve incluir slides ocultos ou não.<br/>            O padrão é `false`. |
| [`show_slide_number`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Especifica se o documento gerado deve mostrar o número de cada slide ou não.<br/>            O padrão é `false`. |
| [`flavor`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/flavor/) | Especifica a especificação markdown para converter a apresentação.<br/>            O padrão é `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Obtém ou define a string de formato usada para cabeçalhos de número de slide na saída Markdown.<br/>            O formato deve incluir o placeholder \"{0}\", que será substituído pelo índice do slide durante a exportação.<br/>            Exemplo: \"# Slide {0}\" produzirá \"# Slide 1\", \"# Slide 2\", etc. |
| [`handle_repeated_spaces`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Se definido como `true`, remove linhas vazias ou contendo apenas espaços em branco da saída final do Markdown.<br/>            O padrão é `false`. |


### Veja Também
* classe [`MarkdownSaveOptions`](/slides/python-net/pt/aspose.slides.export/markdownsaveoptions)
* classe [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)