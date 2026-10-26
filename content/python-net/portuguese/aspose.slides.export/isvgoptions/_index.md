---
title: ISVGOptions class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/isvgoptions/
---
## ISVGOptions classe

Representa uma opções SVG.

O tipo ISVGOptions expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`vectorize_text`](/slides/python-net/pt/aspose.slides.export/isvgoptions/vectorize_text/) | Determina se o texto em um slide será salvo como gráficos.<br/>            Leitura/gravação **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/pt/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Retorna ou define o limite inferior de resolução para rasterização de metafile.<br/>            Leitura/gravação **int**. |
| [`disable_3d_text`](/slides/python-net/pt/aspose.slides.export/isvgoptions/disable_3d_text/) | Determina se o texto 3D está desativado no SVG.<br/>            Leitura/gravação **bool**. |
| [`disable_gradient_split`](/slides/python-net/pt/aspose.slides.export/isvgoptions/disable_gradient_split/) | Desativa a divisão dos gradientes FromCornerX e FromCenter.<br/>            Leitura/gravação **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/pt/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | O SVG 1.1 não possui capacidade de definir recuos para marcadores.<br/>            O mecanismo de gravação SVG do Aspose.Slides tem uma solução alternativa para esse problema:<br/>            ele corta o final da linha com seta, de modo que a linha não sobreponha os marcadores.<br/>            Esta opção desativa esse comportamento.<br/>            Leitura/gravação **bool**. |
| [`jpeg_quality`](/slides/python-net/pt/aspose.slides.export/isvgoptions/jpeg_quality/) | Determina a qualidade de codificação JPEG.<br/>            Leitura/gravação **int**. |
| [`shape_formatting_controller`](/slides/python-net/pt/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Retorna e define uma interface de retorno de chamada que permite ao usuário controlar a conversão de formas.<br/>            Leitura/gravação [`ISvgShapeFormattingController`](/slides/python-net/pt/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/pt/aspose.slides.export/isvgoptions/pictures_compression/) | Representa o nível de compressão das imagens<br/>            Leitura/gravação [`ISVGOptions.pictures_compression`](/slides/python-net/pt/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/pt/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro, as partes recortadas serão removidas, se falso, elas serão serializadas no documento (o que pode levar a um arquivo maior).<br/>            Leitura/gravação **bool**. |
| [`use_frame_size`](/slides/python-net/pt/aspose.slides.export/isvgoptions/use_frame_size/) | Determina se a caixa de texto será incluída em uma área de renderização ou não.<br/>            Leitura/gravação **bool**.<br/>            O valor padrão é false. |
| [`use_frame_rotation`](/slides/python-net/pt/aspose.slides.export/isvgoptions/use_frame_rotation/) | Determina se a rotação especificada da forma será executada ao renderizar ou não.<br/>            Leitura/gravação **bool**.<br/>            O valor padrão é true. |
| [`external_fonts_handling`](/slides/python-net/pt/aspose.slides.export/isvgoptions/external_fonts_handling/) | Determina uma forma de lidar com fontes carregadas externamente.<br/>            Leitura/gravação [`SvgExternalFontsHandling`](/slides/python-net/pt/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/pt/aspose.slides.export/isvgoptions/ink_options/) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado.<br/>            Somente leitura [`IInkOptions`](/slides/python-net/pt/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/pt/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras.<br/>            Quando definido como `true`, as ligaduras serão desativadas na saída renderizada. Por padrão, essa propriedade está definida como `false`. |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Veja Também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)