---
title: interruption_token property
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token propriété
Le jeton à surveiller pour les demandes d’interruption.
            
            Ce jeton gère la durée de vie entière de l’instance [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). Toute opération de longue durée, telle que la présentation 
            le chargement ou la sauvegarde, sera interrompue en appelant la méthode [`IInterruptionTokenSource.interrupt`](/slides/python-net/fr/aspose.slides/iinterruptiontokensource/interrupt) de 
            le [`IInterruptionTokenSource`](/slides/python-net/fr/aspose.slides/iinterruptiontokensource).

### Définition:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### Voir aussi
* classe [`IInterruptionTokenSource`](/slides/python-net/fr/aspose.slides/iinterruptiontokensource)
* classe [`ILoadOptions`](/slides/python-net/fr/aspose.slides/iloadoptions)
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)