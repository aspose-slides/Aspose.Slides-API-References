---
title: IPortion class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/iportion/
---
## classe IPortion

Representa uma porção de texto dentro de um parágrafo de texto.

O tipo IPortion expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`portion_format`](/slides/python-net/pt/aspose.slides/iportion/portion_format/) | Retorna o objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada.<br/>            Somente leitura [`IPortionFormat`](/slides/python-net/pt/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/pt/aspose.slides/iportion/text/) | Obtém ou define o texto simples de uma porção.<br/>            Leitura/Escrita **str**. |
| [`field`](/slides/python-net/pt/aspose.slides/iportion/field/) | Retorna um campo desta porção.<br/>            Somente leitura [`IField`](/slides/python-net/pt/aspose.slides/ifield). |
| [`slide`](/slides/python-net/pt/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/iportion/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/pt/aspose.slides/iportion/add_field/#ifieldtype) | Converte esta porção no campo atualizado automaticamente. |
| [`add_field(self, internal_string)`](/slides/python-net/pt/aspose.slides/iportion/add_field/#str) | Converte esta porção no campo atualizado automaticamente. |
| [`remove_field(self)`](/slides/python-net/pt/aspose.slides/iportion/remove_field/#) | Converte este campo de porção na porção simples. |
| [`get_rect(self)`](/slides/python-net/pt/aspose.slides/iportion/get_rect/#) | Obtém as coordenadas do retângulo que delimita a porção. O retângulo inclui todas as linhas de<br/>             texto na porção, incluindo as vazias. |
| [`get_coordinates(self)`](/slides/python-net/pt/aspose.slides/iportion/get_coordinates/#) | Obtém as coordenadas do início da porção. A coordenada X do ponto representa o <br/>            início da porção a partir do primeiro caractere, incluindo a margem esquerda. A coordenada Y <br/>            inclui a margem superior. |


### Veja também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)