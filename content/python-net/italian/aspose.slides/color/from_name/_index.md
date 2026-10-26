---
title: from_name method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Crea un colore dal nome specificato di un colore predefinito.<br/>La ricerca non fa distinzione fra maiuscole e minuscole e ignora trattini bassi e spazi: `"LightBlue"`, `"lightblue"` e `"light_blue"` vengono tutti risolti in `Color.light_blue`. Vedere la pagina della classe [`Color`](/slides/python-net/it/aspose.slides/color) per l'elenco dei colori predefiniti.

### Restituisce

Il colore nominato.



```python
@staticmethod
def from_name(name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | **str** | Una stringa che è il nome di un colore predefinito. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **ValueError** | Il nome non è un nome di un colore predefinito. |
| **TypeError** | Il nome non è una stringa. |



### Vedi anche
* classe [`Color`](/slides/python-net/it/aspose.slides/color)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)