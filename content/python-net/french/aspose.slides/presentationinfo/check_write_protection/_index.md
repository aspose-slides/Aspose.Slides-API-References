---
title: check_write_protection method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture.

### Valeur de retour

True si la présentation est protégée en écriture et que le mot de passe est correct. False sinon.



```python
def check_write_protection(self, password):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| password | **str** | Le mot de passe à vérifier. |

### Remarques

1. Vous devez vérifier la propriété [`PresentationInfo.is_write_protected`](/slides/python-net/fr/aspose.slides/presentationinfo/is_write_protected) avant d'appeler cette méthode.
2. Lorsque le mot de passe est None ou vide, cette méthode renvoie false.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Voir aussi
* classe [`PresentationInfo`](/slides/python-net/fr/aspose.slides/presentationinfo)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)