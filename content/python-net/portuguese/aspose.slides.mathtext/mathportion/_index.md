---
title: MathPortion class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathportion/
---
## MathPortion classe

Representa uma porção com contexto matemático interno.

**Herança:**[`MathPortion`](/slides/python-net/pt/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/pt/aspose.slides/portion)

O tipo MathPortion expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/__init__/#) | Inicializa uma nova instância da classe MathPortion. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`portion_format`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/portion_format/) | Retorna o objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada.<br/>            Somente leitura [`IPortionFormat`](/slides/python-net/pt/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/text/) | Obtém ou define o texto simples de uma porção.<br/>            Leitura/gravação **str**. |
| [`field`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/field/) | Retorna um campo desta porção.<br/>            Somente leitura [`IField`](/slides/python-net/pt/aspose.slides/ifield). |
| [`math_paragraph`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/math_paragraph/) | Parágrafo matemático |
| [`slide`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | Converte esta porção para o campo atualizado automaticamente. |
| [`add_field(self, internal_string)`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/add_field/#str) | Converte esta porção para o campo atualizado automaticamente. |
| [`remove_field(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/remove_field/#) | Converte esta porção de campo para a porção simples. |
| [`get_rect(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/get_rect/#) | Obtém as coordenadas do retângulo que delimita a porção. O retângulo inclui todas as linhas de<br/>            texto na porção, incluindo as vazias. |
| [`get_coordinates(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/get_coordinates/#) | Obtém as coordenadas do início da porção. A coordenada X do ponto representa o início da porção a partir do primeiro caractere, incluindo a margem esquerda. A coordenada Y inclui a margem superior. |


### Ver Também
* classe [`MathPortion`](/slides/python-net/pt/aspose.slides.mathtext/mathportion)
* classe [`Portion`](/slides/python-net/pt/aspose.slides/portion)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)