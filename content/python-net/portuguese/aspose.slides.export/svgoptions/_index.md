---
title: SVGOptions class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/svgoptions/
---
## SVGOptions classe

Representa uma opção SVG.

**Herança:**[`SVGOptions`](/slides/python-net/pt/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)

O tipo SVGOptions expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/svgoptions/__init__/#) | Inicializa uma nova instância da classe SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/pt/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Inicializa uma nova instância da classe SVGOptions especificando o objeto controlador de incorporação de links. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/svgoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Leitura/Escrita [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/svgoptions/progress_callback/) | Representa um objeto de callback para atualizações de progresso de salvamento em porcentagem.<br/>            Veja [`IProgressCallback`](/slides/python-net/pt/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/svgoptions/default_regular_font/) | Retorna ou define a fonte utilizada caso a fonte original não seja encontrada.<br/>            Leitura/Escrita **str**. |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/svgoptions/gradient_style/) | Retorna ou define o estilo visual do gradiente.<br/>            Leitura/Escrita [`GradientStyle`](/slides/python-net/pt/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/svgoptions/skip_java_script_links/) | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação.<br/>            Leitura/Escrita **bool**. O valor padrão é **false**. |
| [`ink_options`](/slides/python-net/pt/aspose.slides.export/svgoptions/ink_options/) | Fornece opções que controlam a aparência de objetos Ink no documento exportado.<br/>            Somente leitura [`IInkOptions`](/slides/python-net/pt/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/pt/aspose.slides.export/svgoptions/use_frame_size/) | Determina se a caixa de texto será incluída em uma área de renderização ou não.<br/>            Leitura/Escrita **bool**.<br/>            O valor padrão é false. |
| [`use_frame_rotation`](/slides/python-net/pt/aspose.slides.export/svgoptions/use_frame_rotation/) | Determina se a rotação especificada da forma será executada ao renderizar ou não.<br/>            Leitura/Escrita **bool**.<br/>            O valor padrão é true. |
| [`vectorize_text`](/slides/python-net/pt/aspose.slides.export/svgoptions/vectorize_text/) | Determina se o texto em um slide será salvo como gráficos.<br/>            Leitura/Escrita **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/pt/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Retorna ou define o limite inferior de resolução para a rasterização de metafile.<br/>            Leitura/Escrita **int**. |
| [`disable_3d_text`](/slides/python-net/pt/aspose.slides.export/svgoptions/disable_3d_text/) | Determina se o texto 3D está desativado no SVG.<br/>            Leitura/Escrita **bool**. |
| [`disable_gradient_split`](/slides/python-net/pt/aspose.slides.export/svgoptions/disable_gradient_split/) | Desativa a divisão dos gradientes FromCornerX e FromCenter.<br/>            Leitura/Escrita **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/pt/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 não tem capacidade de definir recuos para marcadores.<br/>            O motor de escrita SVG da Aspose.Slides tem uma solução alternativa para esse problema:<br/>            ele corta a extremidade da linha com seta, portanto, a linha não se sobrepõe aos marcadores.<br/>            Esta opção desativa tal comportamento.<br/>            Leitura/Escrita **bool**. |
| [`default`](/slides/python-net/pt/aspose.slides.export/svgoptions/default/) | Retorna as configurações padrão.<br/>            Somente leitura [`SVGOptions`](/slides/python-net/pt/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/pt/aspose.slides.export/svgoptions/simple/) | Retorna configurações para a geração do arquivo SVG mais simples e pequeno.<br/>            Somente leitura [`SVGOptions`](/slides/python-net/pt/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/pt/aspose.slides.export/svgoptions/wysiwyg/) | Retorna configurações para a geração do arquivo SVG mais preciso.<br/>            Somente leitura [`SVGOptions`](/slides/python-net/pt/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/pt/aspose.slides.export/svgoptions/jpeg_quality/) | Determina a qualidade de codificação JPEG.<br/>            Leitura/Escrita **int**. |
| [`shape_formatting_controller`](/slides/python-net/pt/aspose.slides.export/svgoptions/shape_formatting_controller/) | Retorna e define uma interface de callback que permite ao usuário controlar a conversão de formas.<br/>            Leitura/Escrita [`ISvgShapeFormattingController`](/slides/python-net/pt/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/pt/aspose.slides.export/svgoptions/pictures_compression/) | Representa o nível de compressão das imagens |
| [`delete_pictures_cropped_areas`](/slides/python-net/pt/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro as partes recortadas serão removidas,<br/>            se falso elas serão serializadas no documento (o que pode possivelmente levar a um <br/>            arquivo maior) |
| [`external_fonts_handling`](/slides/python-net/pt/aspose.slides.export/svgoptions/external_fonts_handling/) | Determina uma forma de lidar com fontes carregadas externamente.<br/>            Leitura/Escrita [`SvgExternalFontsHandling`](/slides/python-net/pt/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/pt/aspose.slides.export/svgoptions/disable_font_ligatures/) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras.<br/>            Quando definido como `true`, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como `false`. |


### Veja Também
* classe [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)
* classe [`SVGOptions`](/slides/python-net/pt/aspose.slides.export/svgoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)