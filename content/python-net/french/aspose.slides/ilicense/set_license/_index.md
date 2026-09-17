---
title: set_license method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Licencie le composant.

```python
def set_license(self, license_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| license_name | **str** | Peut être un nom de fichier complet ou court ou le nom d'une ressource intégrée.<br/><br/>Utilisez une chaîne vide pour passer en mode d'évaluation. |

### Remarques

Tente de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier de l'assembly du composant.

3. Le dossier de l'assembly appelant du client.

4. Le dossier de l'assembly d'entrée.

5. Une ressource intégrée dans l'assembly appelant du client.

**Remarque :** Sur le .NET Compact Framework, tente de trouver la licence uniquement dans les emplacements suivants :

1. Chemin explicite.

2. Une ressource intégrée dans l'assembly appelant du client.

## set_license(self, stream) {#iorawiobase}
Licencie le composant.

```python
def set_license(self, stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Un flux qui contient la licence. |

### Remarques

Utilisez cette méthode pour charger une licence à partir d'un flux.

### Voir aussi
* classe [`ILicense`](/slides/python-net/fr/aspose.slides/ilicense)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)