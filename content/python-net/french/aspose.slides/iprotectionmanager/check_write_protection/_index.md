---
title: check_write_protection method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Détermine si une présentation est protégée par un mot de passe pour la modification.

### Renvoie

True si le mot de passe est valide ; sinon, false.



```python
def check_write_protection(self, password):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| password | **str** | Le mot de passe pour la vérification. |

### Remarques

1. Vous devez vérifier la propriété [`IProtectionManager.is_write_protected`](/slides/python-net/fr/aspose.slides/iprotectionmanager/is_write_protected) avant d'appeler cette méthode.
            2. Lorsque le mot de passe est None ou vide, cette méthode renvoie false.



### Voir aussi
* classe [`IProtectionManager`](/slides/python-net/fr/aspose.slides/iprotectionmanager)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)