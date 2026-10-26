---
title: from_name method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Cria uma cor a partir do nome especificado de uma cor predefinida.<br/>A pesquisa não diferencia maiúsculas de minúsculas e ignora sublinhados e espaços: `"LightBlue"`, `"lightblue"` e `"light_blue"` todos resolvem para `Color.light_blue`. Consulte a página da classe [`Color`](/slides/python-net/pt/aspose.slides/color) para a lista de cores predefinidas.

### Retorno

A cor nomeada.



```python
@staticmethod
def from_name(name):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| name | **str** | Uma string que é o nome de uma cor predefinida. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **ValueError** | O nome não é um nome de uma cor predefinida. |
| **TypeError** | O nome não é uma string. |



### Veja Também
* classe [`Color`](/slides/python-net/pt/aspose.slides/color)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)