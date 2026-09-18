---
title: IPdfOptions class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/ipdfoptions/
---
## IPdfOptions classe

Fornece opções que controlam como uma apresentação é salva no formato Pdf.

O tipo IPdfOptions expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/text_compression/) | Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento.<br/>            Leitura/gravação [`PdfTextCompression`](/slides/python-net/pt/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada <br/>            automaticamente. Se definido como **bool**.true, para cada imagem na apresentação o algoritmo de compressão mais apropriado <br/>            será escolhido, o que levará a um tamanho menor do documento PDF resultante. <br/>            A seleção da melhor taxa de compressão de imagem é computacionalmente cara e consome <br/>            uma quantidade adicional de RAM, e esta opção tem **bool**.false como padrão. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Verdadeiro para incorporar fontes TrueType para caracteres ASCII 32-127.<br/>            Fontes para códigos de caracteres maiores que 127 são sempre incorporadas.<br/>            Leitura/gravação **bool**. |
| [`show_hidden_slides`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Especifica se o documento gerado deve incluir slides ocultos ou não.<br/>            O padrão é `false`. |
| [`additional_common_font_families`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que Aspose.Slides deve considerar comuns.<br/>            Leitura/gravação **str**[]. |
| [`embed_full_fonts`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado.<br/>            Leitura/gravação **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo em negrito.<br/>            Esta abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes.<br/>            Leitura/gravação **bool**. |
| [`jpeg_quality`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/jpeg_quality/) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF.<br/>            Leitura/gravação **int**. |
| [`compliance`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/compliance/) | Nível de conformidade desejado para o documento PDF gerado.<br/>            Leitura/gravação [`PdfCompliance`](/slides/python-net/pt/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/password/) | Define a senha de usuário para proteger o documento PDF. <br/>            Leitura/gravação **str**. |
| [`access_permissions`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/access_permissions/) | Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto<br/>            com acesso de usuário. Veja [`PdfAccessPermissions`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Verdadeiro para converter todos os metafiles usados em uma apresentação para imagens PNG.<br/>            Leitura/gravação **bool**. |
| [`sufficient_resolution`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF.<br/>            <br/>A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.<br/><br/><br/>O valor padrão é **96** .<br/><br/><br/>            Leitura/gravação **float**. |
| [`draw_slides_frame`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Verdadeiro para desenhar uma borda preta ao redor de cada slide.<br/>             Leitura/gravação **bool**. |
| [`slides_layout_options`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/slides_layout_options/) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](/slides/python-net/pt/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/image_transparent_color/) | Obtém ou define a cor transparente da imagem. |
| [`apply_image_transparent`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Aplica a cor transparente especificada a uma imagem se `true`. |
| [`ink_options`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/ink_options/) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado.<br/>            Somente leitura [`IInkOptions`](/slides/python-net/pt/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/include_ole_data/) | Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante.<br/>            Leitura/gravação **bool**. |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |


### Veja Também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)