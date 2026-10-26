---
title: PptxOptions class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/pptxoptions/
---
## classe PptxOptions

Representa opções para salvar apresentações OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Herança:**[`PptxOptions`](/slides/python-net/pt/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)

O tipo PptxOptions expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.export/pptxoptions/__init__/#) | Cria uma nova instância de PptxOptions |

## Propriedades

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/pt/aspose.slides.export/pptxoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Leitura/gravação [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pt/aspose.slides.export/pptxoptions/progress_callback/) | Representa um objeto de retorno de chamada para atualizações de progresso de salvamento em porcentagem.<br/>            Veja [`IProgressCallback`](/slides/python-net/pt/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides.export/pptxoptions/default_regular_font/) | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada.<br/>            Leitura-gravação **str**. |
| [`gradient_style`](/slides/python-net/pt/aspose.slides.export/pptxoptions/gradient_style/) | Retorna ou define o estilo visual do gradiente.<br/>            Leitura/gravação [`GradientStyle`](/slides/python-net/pt/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pt/aspose.slides.export/pptxoptions/skip_java_script_links/) | Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. <br/>            Leitura/gravação **bool**. O valor padrão é **false**. |
| [`conformance`](/slides/python-net/pt/aspose.slides.export/pptxoptions/conformance/) | Especifica a classe de conformidade à qual o documento Presentation está em conformidade.<br/>            O valor padrão é [`Conformance.ECMA_376_2006`](/slides/python-net/pt/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/pt/aspose.slides.export/pptxoptions/zip_64_mode/) | Especifica se o formato ZIP64 é usado para o documento Presentation. <br/>            O valor padrão é [`Zip64Mode.IF_NECESSARY`](/slides/python-net/pt/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/pt/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Especifica se a miniatura da apresentação será atualizada. <br/>            Leitura/gravação **bool**.<br/>            O valor padrão é **true**. |
| [`compression_level`](/slides/python-net/pt/aspose.slides.export/pptxoptions/compression_level/) | Especifica o nível de compressão usado ao salvar o documento da apresentação.<br/>            O valor padrão é [`CompressionLevel.LEVEL6`](/slides/python-net/pt/aspose.slides.export/compressionlevel/LEVEL6). |

### Veja Também
* classe [`PptxOptions`](/slides/python-net/pt/aspose.slides.export/pptxoptions)
* classe [`SaveOptions`](/slides/python-net/pt/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)