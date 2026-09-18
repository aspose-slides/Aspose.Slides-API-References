---
title: ITiffOptions class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/itiffoptions/
---
## ITiffOptions classe

Fornece opções que controlam como uma apresentação é salva no formato TIFF.

O tipo ITiffOptions expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`image_size`](/slides/python-net/pt/aspose.slides.export/itiffoptions/image_size/) | Especifica o tamanho de uma imagem TIFF gerada.<br/>            Valor padrão é 0x0, o que significa que os tamanhos das imagens geradas serão calculados com base no valor do tamanho do slide da apresentação.<br/>            Leitura/gravação **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/pt/aspose.slides.export/itiffoptions/dpi_x/) | Especifica a resolução horizontal em pontos por polegada.<br/>            Leitura/gravação **int**. |
| [`dpi_y`](/slides/python-net/pt/aspose.slides.export/itiffoptions/dpi_y/) | Especifica a resolução vertical em pontos por polegada.<br/>            Leitura/gravação **int**. |
| [`show_hidden_slides`](/slides/python-net/pt/aspose.slides.export/itiffoptions/show_hidden_slides/) | Especifica se o documento gerado deve incluir slides ocultos ou não.<br/>            Padrão é `false`. |
| [`compression_type`](/slides/python-net/pt/aspose.slides.export/itiffoptions/compression_type/) | Especifica o tipo de compressão.<br/>            Leitura/gravação [`TiffCompressionTypes`](/slides/python-net/pt/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/pt/aspose.slides.export/itiffoptions/pixel_format/) | Especifica o formato de pixel para as imagens geradas.<br/>            Leitura/gravação [`ImagePixelFormat`](/slides/python-net/pt/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/pt/aspose.slides.export/itiffoptions/slides_layout_options/) | Obtém ou define o modo como os slides são colocados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](/slides/python-net/pt/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/pt/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco.<br/>            Esta opção será aplicada somente se [`ITiffOptions.compression_type`](/slides/python-net/pt/aspose.slides.export/itiffoptions/compression_type) <br/>            estiver definido para [`TiffCompressionTypes.CCITT4`](/slides/python-net/pt/aspose.slides.export/tiffcompressiontypes/CCITT4) ou [`TiffCompressionTypes.CCITT3`](/slides/python-net/pt/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Leitura/gravação [`BlackWhiteConversionMode`](/slides/python-net/pt/aspose.slides.export/blackwhiteconversionmode).<br/>            Padrão é [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/pt/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/pt/aspose.slides.export/itiffoptions/ink_options/) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado.<br/>            Somente leitura [`IInkOptions`](/slides/python-net/pt/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Veja Também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)