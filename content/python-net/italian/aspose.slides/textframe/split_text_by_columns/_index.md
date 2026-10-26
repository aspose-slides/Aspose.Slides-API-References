---
title: split_text_by_columns method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/textframe/split_text_by_columns/
weight: 60
---
## split_text_by_columns(self) {#}
Dividi il contenuto testuale del [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe) in un array di stringhe,  
            dove ogni elemento corrisponde a una colonna di testo separata all'interno del frame.

### Restituisce

Un array di stringhe, dove ogni stringa rappresenta il contenuto testuale di una colonna specifica nel [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe).



```python
def split_text_by_columns(self):
    ...
```


### Osservazioni

Se il frame di testo non contiene più colonne, l'array restituito avrà un unico elemento contenente il testo completo.  
            Le colonne vuote saranno rappresentate come stringhe vuote nell'array.



### Vedi anche
* classe [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe)
* classe [`TextFrame`](/slides/python-net/it/aspose.slides/textframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)