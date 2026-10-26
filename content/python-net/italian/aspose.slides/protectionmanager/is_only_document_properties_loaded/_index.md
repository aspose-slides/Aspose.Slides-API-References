---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded proprietà
Questa proprietà ha senso se il file di presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche.
Un valore true indica che solo le proprietà del documento vengono caricate da un file di presentazione crittografato senza l'uso di una password.
Un valore false indica che l'intera presentazione crittografata viene caricata usando la password corretta, non solo le proprietà del documento.
Se la presentazione non è crittografata, il valore della proprietà è sempre false.
Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false.
Se Presentation.EncryptDocumentProperties è true, allora il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false.
Sola lettura **bool**.

### Definizione:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Vedi anche
* classe [`ProtectionManager`](/slides/python-net/it/aspose.slides/protectionmanager)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)