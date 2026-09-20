---
title: only_load_document_properties property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties proprietà
Questa proprietà ha senso se il file della presentazione è protetto da password.
            Il valore true indica che solo le proprietà del documento devono essere caricate da un file di presentazione crittografato e la password deve essere ignorata.
            Il valore false indica che l'intera presentazione crittografata deve essere caricata usando la password corretta.
            Se la presentazione non è crittografata, il valore della proprietà viene sempre ignorato.
            Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà generata un'eccezione.
Lettura/scrittura **bool**.

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
* classe [`LoadOptions`](/slides/python-net/it/aspose.slides/loadoptions)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)