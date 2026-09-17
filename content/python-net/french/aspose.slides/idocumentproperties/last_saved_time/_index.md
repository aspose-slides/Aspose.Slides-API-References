---
title: last_saved_time property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## propriété last_saved_time
Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois.
            Les valeurs sont en UTC.P
            Lecture seule dans le cas de Presentation.DocumentProperties (car elle sera mise à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). 
            Peut être modifiée via l'instance DocumentProperties renvoyée par la méthode [`IPresentationInfo.read_document_properties`](/slides/python-net/fr/aspose.slides/ipresentationinfo/read_document_properties)
            Veuillez voir l'exemple dans **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** résumé de la méthode.

### Définition:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```


### Voir aussi
* classe [`IDocumentProperties`](/slides/python-net/fr/aspose.slides/idocumentproperties)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)