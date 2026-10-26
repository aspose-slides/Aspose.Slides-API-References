---
title: only_load_document_properties property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties proprietà
This property makes sense, if presentation file is password protected.
            Il valore true indica che solo le proprietà del documento devono essere caricate da un file cifrato 
            di presentazione e la password deve essere ignorata.
            Il valore false indica che l'intera presentazione cifrata deve essere caricata con l'uso della password corretta 
            password.
            Se la presentazione non è cifrata, il valore della proprietà è sempre ignorato.
            Se le proprietà del documento di un file cifrato non sono pubbliche e il valore della proprietà è true allora 
            le proprietà del documento non possono essere caricate e verrà sollevata un'eccezione.
            Lettura-scrittura **bool**.

### Definizione:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Vedi anche
* classe [`ILoadOptions`](/slides/python-net/it/aspose.slides/iloadoptions)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)