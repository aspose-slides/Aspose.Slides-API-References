---
title: ExternalResourceResolver class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver classe

Classe de callback usada para resolver recursos externos durante a importação de documentos Html, Svg.
            Usar este resolvedor pode criar uma vulnerabilidade quando um arquivo HTML ou SVG fornecido pelo cliente fizer o software do servidor obter um arquivo local ou de rede. Use com cautela. Recomenda-se não especificar ExternalResourceResolver de forma alguma (apenas objetos incorporados serão lidos) ou criar alguma subclasse que verifique se a uri especificada é válida.

O tipo ExternalResourceResolver expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/pt/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Resolve o URI absoluto a partir dos URIs base e relativo. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/pt/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Mapeia um URI para um objeto que contém o recurso real. |


### Veja Também
* módulo [`aspose.slides.importing`](/slides/python-net/pt/aspose.slides.importing)
* biblioteca [`Aspose.Slides`](/slides/python-net)