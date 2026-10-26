---
title: PdfOptions class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.export/pdfoptions/
---
## PdfOptions classe

Fornece opções que controlam como uma apresentação é salva no formato Pdf.

**Inheritance:**[`PdfOptions`](/slides/python-net/pt/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)

O tipo PdfOptions expõe os seguintes membros:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/pdfoptions/__init__/#) | Construtor padrão. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/pdfoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Leitura/Gravação [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/pdfoptions/progress_callback/) | Representa um objeto de callback para atualizações de progresso de salvamento em porcentagem.<br/>            Consulte [`IProgressCallback`](/slides/python-net/pt/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/pdfoptions/default_regular_font/) | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada.<br/>            Leitura/Gravação **str**. |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/pdfoptions/gradient_style/) | Retorna ou define o estilo visual do gradiente.<br/>            Leitura/Gravação [`GradientStyle`](/slides/python-net/pt/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/pdfoptions/skip_java_script_links/) | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação. <br/>            Leitura/Gravação **bool**. O valor padrão é **false** . |
| [`slides_layout_options`](/slides/python-net/pt/aspose.slides.export/pdfoptions/slides_layout_options/) | Obtém ou define o modo como os slides são colocados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](/slides/python-net/pt/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/pt/aspose.slides.export/pdfoptions/ink_options/) | Fornece opções que controlam a aparência de objetos Ink no documento exportado.<br/>            Somente leitura [`IInkOptions`](/slides/python-net/pt/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/pt/aspose.slides.export/pdfoptions/show_hidden_slides/) | Especifica se o documento gerado deve incluir slides ocultos ou não.<br/>            O padrão é `false`. |
| [`text_compression`](/slides/python-net/pt/aspose.slides.export/pdfoptions/text_compression/) | Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento.<br/>            Leitura/Gravação [`PdfTextCompression`](/slides/python-net/pt/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/pt/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada <br/>            automaticamente. Se definido como **bool**.true, para cada imagem na apresentação o algoritmo de compressão mais adequado será escolhido, o que levará a um tamanho menor do documento PDF resultante. <br/>            A seleção da melhor taxa de compressão de imagem é computacionalmente custosa e consome <br/>            uma quantidade adicional de RAM, e esta opção é **bool**.false por padrão. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/pt/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Determina se o Aspose.Slides incorporará fontes comuns para texto ASCII (faixa de códigos 33..127).<br/>            Fontes para códigos de caracteres superiores a 127 são sempre incorporadas.<br/>            A lista de fontes comuns inclui as 14 fontes base do PDF e fontes adicionais especificadas pelo usuário.<br/>            Leitura/Gravação **bool**. |
| [`additional_common_font_families`](/slides/python-net/pt/aspose.slides.export/pdfoptions/additional_common_font_families/) | Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns.<br/>            Leitura/Gravação **str**[]. |
| [`embed_full_fonts`](/slides/python-net/pt/aspose.slides.export/pdfoptions/embed_full_fonts/) | Determina se todos os caracteres da fonte devem ser incorporados ou apenas o subconjunto usado.<br/>            Leitura/Gravação **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/pt/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo negrito.<br/>            Esta abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes.<br/>            Leitura/Gravação **bool**. |
| [`jpeg_quality`](/slides/python-net/pt/aspose.slides.export/pdfoptions/jpeg_quality/) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF.<br/>            Leitura/Gravação **int**. |
| [`compliance`](/slides/python-net/pt/aspose.slides.export/pdfoptions/compliance/) | Nível de conformidade desejado para o documento PDF gerado.<br/>            Leitura/Gravação [`PdfCompliance`](/slides/python-net/pt/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/pt/aspose.slides.export/pdfoptions/password/) | Define senha de usuário para proteger o documento PDF. <br/>            Leitura/Gravação **str**. |
| [`access_permissions`](/slides/python-net/pt/aspose.slides.export/pdfoptions/access_permissions/) | Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto<br/>            com acesso de usuário. Consulte [`PdfAccessPermissions`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/pt/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | True para converter todos os metafiles usados em uma apresentação para imagens PNG.<br/>            Leitura/Gravação **bool**. |
| [`sufficient_resolution`](/slides/python-net/pt/aspose.slides.export/pdfoptions/sufficient_resolution/) | Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF.<br/>            <br/>A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.<br/><br/><br/>O valor padrão é **96** .<br/><br/><br/>            Leitura/Gravação **float**. |
| [`draw_slides_frame`](/slides/python-net/pt/aspose.slides.export/pdfoptions/draw_slides_frame/) | True para desenhar uma moldura preta ao redor de cada slide.<br/>             Leitura/Gravação **bool**. |
| [`image_transparent_color`](/slides/python-net/pt/aspose.slides.export/pdfoptions/image_transparent_color/) | Obtém ou define a cor transparente da imagem. |
| [`apply_image_transparent`](/slides/python-net/pt/aspose.slides.export/pdfoptions/apply_image_transparent/) | Aplica a cor transparente especificada a uma imagem se `true`. |
| [`include_ole_data`](/slides/python-net/pt/aspose.slides.export/pdfoptions/include_ole_data/) | True para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante.<br/>            Leitura/Gravação **bool**. |


### Veja Também
* classe [`PdfOptions`](/slides/python-net/pt/aspose.slides.export/pdfoptions)
* classe [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)