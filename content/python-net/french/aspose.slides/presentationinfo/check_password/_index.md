---
title: check_password method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture.

### Valeur de retour

True si la présentation est protégée par un mot de passe d'ouverture et que le mot de passe est correct, sinon false.



```python
def check_password(self, password):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| password | **str** | Le mot de passe à vérifier. |

### Remarques

Lorsque le mot de passe est None ou vide, cette méthode renvoie false.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Voir aussi
* classe [`PresentationInfo`](/slides/python-net/fr/aspose.slides/presentationinfo)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)