---
title: HtmlExternalResolver class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.importing/htmlexternalresolver/
---
## classe HtmlExternalResolver

Objeto de retorno de chamada usado pela rotina de importação HTML para obter objetos referenciados, como imagens.
            Usar este resolvedor pode criar uma vulnerabilidade quando um arquivo HTML fornecido pelo cliente fizer o software do servidor obter um arquivo local ou de rede. Use com cautela. Recomenda-se não especificar HtmlExternalResolver de forma alguma (apenas objetos incorporados serão lidos) ou criar uma subclasse que verifique se o URI especificado é válido.

O tipo HtmlExternalResolver expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/pt/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Resolves the absolute URI from the base and relative URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/pt/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Maps a URI to an object containing the actual resource. |


### Veja Também
* módulo [`aspose.slides.importing`](/slides/python-net/pt/aspose.slides.importing)
* biblioteca [`Aspose.Slides`](/slides/python-net)