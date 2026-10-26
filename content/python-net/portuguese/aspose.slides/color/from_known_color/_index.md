---
title: from_known_color method
second_title: Aspose.Slides para Python via Referência de API .NET
description: 
type: docs
url: /pt/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Cria uma cor a partir da cor predefinida especificada.<br/>Esta é a única maneira de obter uma cor do sistema (como `KnownColor.CONTROL`): as cores do sistema não são expostas como atributos de `Color` porque seus valores dependem do tema da área de trabalho, então são lidas do tempo de execução da biblioteca.

### Retorna

A cor que este método cria.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| known_color | **KnownColor** | Um elemento da enumeração `KnownColor` (um `IntEnum` que espelha o .NET `System.Drawing.KnownColor`) ou seu valor inteiro. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **ValueError** | O valor não é um membro válido de `KnownColor`. |



### Veja Também
* classe [`Color`](/slides/python-net/pt/aspose.slides/color)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)