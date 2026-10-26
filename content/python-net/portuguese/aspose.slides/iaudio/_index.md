---
title: IAudio class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/iaudio/
---
## IAudio classe

Representa um arquivo de áudio incorporado.

O tipo IAudio expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`content_type`](/slides/python-net/pt/aspose.slides/iaudio/content_type/) | Retorna um tipo MIME de um áudio, codificado em [`IAudio.binary_data`](/slides/python-net/pt/aspose.slides/iaudio/binary_data).<br/>            Somente leitura **str**. |
| [`binary_data`](/slides/python-net/pt/aspose.slides/iaudio/binary_data/) | Retorna uma cópia dos dados de um áudio. Em caso de grande quantidade de dados, considere usar o método [`IAudio.get_stream`](/slides/python-net/pt/aspose.slides/iaudio/get_stream) para evitar o carregamento desnecessário dos dados do áudio na memória ou até mesmo OutOfMemoryException.<br/>            Somente leitura **int**[]. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/pt/aspose.slides/iaudio/get_stream/#) | Retorna um Stream para leitura.<br/>            Use 'using' ou feche o stream após o uso. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)