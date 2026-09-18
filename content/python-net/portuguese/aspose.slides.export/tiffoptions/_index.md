---
title: TiffOptions class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/tiffoptions/
---
## classe TiffOptions

Fornece opções que controlam como uma apresentação é salva no formato TIFF.

**Herança:**[`TiffOptions`](/slides/python-net/pt/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)

O tipo TiffOptions expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/tiffoptions/__init__/#) | Construtor padrão. |

## Propriedades

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/tiffoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Leitura/Gravação [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/tiffoptions/progress_callback/) | Representa um objeto de retorno de chamada para atualizações de progresso de salvamento em porcentagem.<br/>            Veja [`IProgressCallback`](/slides/python-net/pt/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/tiffoptions/default_regular_font/) | Retorna ou define a fonte usada caso a fonte original não seja encontrada.<br/>            Leitura-gravação **str**. |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/tiffoptions/gradient_style/) | Retorna ou define o estilo visual do degradê.<br/>            Leitura/Gravação [`GradientStyle`](/slides/python-net/pt/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/tiffoptions/skip_java_script_links/) | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação.<br/>            Leitura/Gravação **bool**. O valor padrão é **false**. |
| [`ink_options`](/slides/python-net/pt/aspose.slides.export/tiffoptions/ink_options/) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado.<br/>            Somente leitura [`IInkOptions`](/slides/python-net/pt/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/pt/aspose.slides.export/tiffoptions/show_hidden_slides/) | Especifica se o documento gerado deve incluir slides ocultos ou não.<br/>            O padrão é `false`. |
| [`image_size`](/slides/python-net/pt/aspose.slides.export/tiffoptions/image_size/) | Especifica o tamanho de uma imagem TIFF gerada.<br/>            O valor padrão é 0x0, o que significa que os tamanhos da imagem gerada serão calculados com base no valor do tamanho do slide da apresentação.<br/>            Leitura/Gravação **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/pt/aspose.slides.export/tiffoptions/dpi_x/) | Especifica a resolução horizontal em pontos por polegada.<br/>            Leitura/Gravação **int**. |
| [`dpi_y`](/slides/python-net/pt/aspose.slides.export/tiffoptions/dpi_y/) | Especifica a resolução vertical em pontos por polegada.<br/>            Leitura/Gravação **int**. |
| [`compression_type`](/slides/python-net/pt/aspose.slides.export/tiffoptions/compression_type/) | Especifica o tipo de compressão.<br/>            Leitura/Gravação [`TiffCompressionTypes`](/slides/python-net/pt/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/pt/aspose.slides.export/tiffoptions/pixel_format/) | Especifica o formato de pixel para as imagens geradas.<br/>            Leitura/Gravação [`ImagePixelFormat`](/slides/python-net/pt/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/pt/aspose.slides.export/tiffoptions/slides_layout_options/) | Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](/slides/python-net/pt/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/pt/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Especifica o algoritmo para converter uma imagem colorida em uma imagem preto e branco.<br/>            Esta opção será aplicada somente se [`TiffOptions.compression_type`](/slides/python-net/pt/aspose.slides.export/tiffoptions/compression_type) <br/>            estiver definido para [`TiffCompressionTypes.CCITT4`](/slides/python-net/pt/aspose.slides.export/tiffcompressiontypes/CCITT4) ou [`TiffCompressionTypes.CCITT3`](/slides/python-net/pt/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Leitura/Gravação [`BlackWhiteConversionMode`](/slides/python-net/pt/aspose.slides.export/blackwhiteconversionmode).<br/>            O padrão é [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/pt/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |


### Veja Também
* classe [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)
* classe [`TiffOptions`](/slides/python-net/pt/aspose.slides.export/tiffoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)