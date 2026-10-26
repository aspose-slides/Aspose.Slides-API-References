---
title: app_version property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/idocumentproperties/app_version/
weight: 90
---
## app_version proprietà
Restituisce la versione dell'app.
            Sola lettura **str**.


### Osservazioni

Il contenuto di questo elemento deve essere nel formato XX.YYYY, dove X e Y rappresentano valori numerici;
            altrimenti, il documento sarà considerato non conforme.
            Aspose.Slides rappresenta la sua versione nel formato XX.YYZZ, dove:
            XX - versione principale
            YY - versione secondaria
            ZZ - versione di patch
            Per esempio, il valore 23.0105 indica la versione 23.1.5 di Aspose.Slides.

### Definizione:
```python
@property
def app_version(self):
    ...
```


### Vedi anche
* classe [`IDocumentProperties`](/slides/python-net/it/aspose.slides/idocumentproperties)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)