---
title: add method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Aggiunge una nuova parte xml personalizzata.

### Restituisce

Parte xml personalizzata creata.



```python
def add(self, xml_data):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| xml_data | **bytes** | I dati xml della nuova parte da aggiungere. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData è `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData è vuoto o non valido. |


## add(self, xml_string) {#str}
Aggiunge una nuova parte xml personalizzata.

### Restituisce

Parte xml personalizzata creata.



```python
def add(self, xml_string):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| xml_string | **str** | La stringa xml della nuova parte da aggiungere. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString è `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString è vuota o i dati xml non sono validi. |


## add(self, input_stream) {#iorawiobase}
Aggiunge una nuova parte xml personalizzata.

### Restituisce

Parte xml personalizzata creata.



```python
def add(self, input_stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | L'inputStream con i dati xml della nuova parte da aggiungere. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream è `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | I dati in inputStream sono vuoti o non validi. |



### Vedi anche
* classe [`ICustomXmlPart`](/slides/python-net/it/aspose.slides/icustomxmlpart)
* classe [`ICustomXmlPartCollection`](/slides/python-net/it/aspose.slides/icustomxmlpartcollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)