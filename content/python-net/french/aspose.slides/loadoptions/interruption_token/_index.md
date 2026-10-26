---
title: interruption_token property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token propriété
Le jeton à surveiller pour les demandes d'interruption.

Ce jeton gère la durée de vie complète de l'instance [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). Toute opération de longue durée, comme le chargement ou l'enregistrement de la présentation, sera interrompue en appelant la méthode [`InterruptionTokenSource.interrupt`](/slides/python-net/fr/aspose.slides/interruptiontokensource/interrupt) du [`InterruptionTokenSource`](/slides/python-net/fr/aspose.slides/interruptiontokensource).

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
* classe [`InterruptionTokenSource`](/slides/python-net/fr/aspose.slides/interruptiontokensource)
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* classe [`LoadOptions`](/slides/python-net/fr/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)