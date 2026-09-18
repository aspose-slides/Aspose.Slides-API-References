---
title: Portion class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/portion/
---
## Portion classe

Representa uma porção de texto dentro de um parágrafo de texto.

O tipo Portion expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/portion/__init__/#) | Inicializa uma nova instância da classe Portion. |
| [`__init__(self, str)`](/slides/python-net/pt/aspose.slides/portion/__init__/#str) | Inicializa uma nova instância da classe Portion. |
| [`__init__(self, portion)`](/slides/python-net/pt/aspose.slides/portion/__init__/#portion) | Inicializa uma nova instância da classe Portion. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`portion_format`](/slides/python-net/pt/aspose.slides/portion/portion_format/) | Retorna um objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada.<br/>            Somente leitura [`IPortionFormat`](/slides/python-net/pt/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/pt/aspose.slides/portion/text/) | Obtém ou define o texto simples de uma porção.<br/>            Leitura/gravação **str**. |
| [`field`](/slides/python-net/pt/aspose.slides/portion/field/) | Retorna um campo desta porção.<br/>            Somente leitura [`IField`](/slides/python-net/pt/aspose.slides/ifield). |
| [`slide`](/slides/python-net/pt/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/portion/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/pt/aspose.slides/portion/add_field/#ifieldtype) | Converte esta porção para o campo automaticamente atualizado. |
| [`add_field(self, internal_string)`](/slides/python-net/pt/aspose.slides/portion/add_field/#str) | Converte esta porção para o campo automaticamente atualizado. |
| [`remove_field(self)`](/slides/python-net/pt/aspose.slides/portion/remove_field/#) | Converte esta porção de campo para a porção simples. |
| [`get_rect(self)`](/slides/python-net/pt/aspose.slides/portion/get_rect/#) | Obtém as coordenadas do retângulo que delimita a porção. O retângulo inclui todas as linhas de<br/>             texto na porção, incluindo linhas vazias. |
| [`get_coordinates(self)`](/slides/python-net/pt/aspose.slides/portion/get_coordinates/#) | Obtém as coordenadas do início da porção. A coordenada X do ponto representa o início da porção a partir do primeiro caractere, incluindo a margem lateral esquerda. A coordenada Y inclui a margem superior. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)