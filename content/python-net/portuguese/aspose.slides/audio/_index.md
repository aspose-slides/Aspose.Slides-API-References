---
title: Audio class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/audio/
---
## classe Audio

Representa um arquivo de áudio incorporado.

O tipo Audio expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`content_type`](/slides/python-net/pt/aspose.slides/audio/content_type/) | Retorna um tipo MIME de um áudio, codificado em [`Audio.binary_data`](/slides/python-net/pt/aspose.slides/audio/binary_data).<br/>            Somente leitura **str**. |
| [`binary_data`](/slides/python-net/pt/aspose.slides/audio/binary_data/) | Retorna a cópia dos dados de um áudio. Em caso de grande quantidade de dados considere <br/>            o uso do método [`Audio.get_stream`](/slides/python-net/pt/aspose.slides/audio/get_stream) para evitar o carregamento desnecessário dos dados do áudio<br/>            na memória ou até mesmo uma OutOfMemoryException.<br/>            Somente leitura **int**[]. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/pt/aspose.slides/audio/get_stream/#) | Retorna Stream stream para leitura.<br/>            Use 'using' ou feche o stream após o uso. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)