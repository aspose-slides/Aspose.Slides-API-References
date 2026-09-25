---
title: from_known_color method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Crea un colore dal colore predefinito specificato.<br/>Questo è l'unico modo per ottenere un colore di sistema (come `KnownColor.CONTROL`): i colori di sistema non sono esposti come attributi `Color` perché i loro valori dipendono dal tema del desktop, quindi vengono letti dal runtime della libreria.

### Restituisce

Il colore che questo metodo crea.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| known_color | **KnownColor** | Un elemento dell'enumerazione `KnownColor` (un `IntEnum` che rispecchia .NET `System.Drawing.KnownColor`) o il suo valore intero. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **ValueError** | Il valore non è un membro valido di `KnownColor`. |



### Vedi anche
* classe [`Color`](/slides/python-net/it/aspose.slides/color)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)