---
title: from_argb method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Cria uma cor a partir de um valor ARGB de 32 bits.

### Retorno

A cor criada a partir do valor especificado.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| argb | **int** | Um valor que especifica o valor ARGB de 32 bits (com sinal ou sem sinal). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **ValueError** | Um valor de componente é menor que 0 ou maior que 255. |
| **TypeError** | Número ou tipo de argumentos incorreto. |


## from_argb(alpha, base_color) {#int-color}
Cria uma cor a partir do valor alfa especificado e da cor base.

### Retorno

A cor criada a partir dos valores especificados.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| alpha | **int** | O valor do componente alfa. Valores válidos são de 0 a 255. |
| base_color | [`Color`](/slides/python-net/pt/aspose.slides/color) | A cor a partir da qual criar a nova cor. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **ValueError** | Um valor de componente é menor que 0 ou maior que 255. |
| **TypeError** | Número ou tipo de argumentos incorreto. |


## from_argb(red, green, blue) {#int-int-int}
Cria uma cor opaca (alfa = 255) a partir dos valores vermelho, verde e azul especificados.

### Retorno

A cor criada a partir dos valores especificados.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| red | **int** | O valor do componente vermelho. Valores válidos são de 0 a 255. |
| green | **int** | O valor do componente verde. Valores válidos são de 0 a 255. |
| blue | **int** | O valor do componente azul. Valores válidos são de 0 a 255. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **ValueError** | Um valor de componente é menor que 0 ou maior que 255. |
| **TypeError** | Número ou tipo de argumentos incorreto. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Cria uma cor a partir dos quatro valores de componentes ARGB (alfa, vermelho, verde e azul).

### Retorno

A cor criada a partir dos valores especificados.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| alpha | **int** | O valor do componente alfa. Valores válidos são de 0 a 255. |
| red | **int** | O valor do componente vermelho. Valores válidos são de 0 a 255. |
| green | **int** | O valor do componente verde. Valores válidos são de 0 a 255. |
| blue | **int** | O valor do componente azul. Valores válidos são de 0 a 255. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **ValueError** | Um valor de componente é menor que 0 ou maior que 255. |
| **TypeError** | Número ou tipo de argumentos incorreto. |



### Veja Também
* classe [`Color`](/slides/python-net/pt/aspose.slides/color)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)