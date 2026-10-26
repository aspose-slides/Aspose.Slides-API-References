---
title: add method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Adiciona nova parte xml personalizada.

### Retorna

Parte xml personalizada criada.



```python
def add(self, xml_string):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| xml_string | **str** | A string xml da nova parte a ser adicionada. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString é `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString está vazia ou os dados xml são inválidos. |


## add(self, xml_data) {#bytes}
Adiciona nova parte xml personalizada.

### Retorna

Parte xml personalizada criada.



```python
def add(self, xml_data):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| xml_data | **bytes** | Os dados xml da nova parte a ser adicionada. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData é `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData está vazia ou inválida. |


## add(self, input_stream) {#iorawiobase}
Adiciona nova parte xml personalizada.

### Retorna

Parte xml personalizada criada.



```python
def add(self, input_stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | O inputStream com dados xml da nova parte a ser adicionada. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream é `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Os dados em inputStream estão vazios ou são inválidos. |



### Veja Também
* classe [`CustomXmlPartCollection`](/slides/python-net/pt/aspose.slides/customxmlpartcollection)
* classe [`ICustomXmlPart`](/slides/python-net/pt/aspose.slides/icustomxmlpart)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)