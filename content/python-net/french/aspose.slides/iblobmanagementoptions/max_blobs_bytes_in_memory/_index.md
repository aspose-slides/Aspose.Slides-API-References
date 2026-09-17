---
title: max_blobs_bytes_in_memory property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory propriété
Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (comme des fichiers temporaires) sont utilisés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une utilisation élevée de la mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

### Remarques

Cette propriété est ignorée si [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) est défini sur false, car la mémoire est alors le seul emplacement de stockage disponible et limiter l’utilisation des BLOBs en mémoire n’a aucun effet.

### Définition:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### Voir aussi
* classe [`IBlobManagementOptions`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)