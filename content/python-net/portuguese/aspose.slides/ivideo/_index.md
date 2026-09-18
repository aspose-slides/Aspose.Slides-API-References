---
title: IVideo class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ivideo/
---
## IVideo classe

Represents a video embedded into a presentation.

The IVideo type exposes the following members:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`content_type`](/slides/python-net/pt/aspose.slides/ivideo/content_type/) | Retorna um tipo MIME de um vídeo, codificado em [`IVideo.binary_data`](/slides/python-net/pt/aspose.slides/ivideo/binary_data).<br/>            Somente leitura **str**. |
| [`binary_data`](/slides/python-net/pt/aspose.slides/ivideo/binary_data/) | Retorna a cópia dos dados de um áudio. No caso de grande quantidade de dados, considere usar o <br/>            método [`IVideo.get_stream`](/slides/python-net/pt/aspose.slides/ivideo/get_stream) para evitar o carregamento desnecessário dos dados do vídeo na memória <br/>            ou mesmo uma OutOfMemoryException.<br/>            Somente leitura **int**[]. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/pt/aspose.slides/ivideo/get_stream/#) | Retorna um Stream para leitura.<br/>            Use 'using' ou feche o stream após o uso. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)