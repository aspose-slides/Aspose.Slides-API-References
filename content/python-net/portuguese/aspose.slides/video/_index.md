---
title: Video class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/video/
---
## Video classe

Representa uma imagem incorporada em uma apresentação.

O tipo Video expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`content_type`](/slides/python-net/pt/aspose.slides/video/content_type/) | Retorna um tipo MIME de um vídeo, codificado em [`Video.binary_data`](/slides/python-net/pt/aspose.slides/video/binary_data).<br/>            Somente leitura **str**. |
| [`binary_data`](/slides/python-net/pt/aspose.slides/video/binary_data/) | Retorna a cópia dos dados de um áudio. Em caso de grande quantidade de dados, considere usar o <br/>            método [`Video.get_stream`](/slides/python-net/pt/aspose.slides/video/get_stream) para evitar o carregamento desnecessário dos dados do vídeo na memória <br/>            ou até mesmo OutOfMemoryException.<br/>            Somente leitura **int**[]. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/pt/aspose.slides/video/get_stream/#) | Retorna um Stream para leitura.<br/>            Use 'using' ou feche o stream após o uso. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)