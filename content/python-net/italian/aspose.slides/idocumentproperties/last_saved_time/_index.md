---
title: last_saved_time property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time proprietà
Restituisce la data in cui una presentazione è stata modificata per l'ultima volta.
            I valori sono in UTC.P
            Solo lettura nel caso di Presentation.DocumentProperties (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). 
            Può essere modificato tramite l'istanza DocumentProperties restituita dal metodo [`IPresentationInfo.read_document_properties`](/slides/python-net/it/aspose.slides/ipresentationinfo/read_document_properties)
            Si prega di consultare l'esempio nel riepilogo del metodo **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**.

### Definizione:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```

### Vedi anche
* classe [`IDocumentProperties`](/slides/python-net/it/aspose.slides/idocumentproperties)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)