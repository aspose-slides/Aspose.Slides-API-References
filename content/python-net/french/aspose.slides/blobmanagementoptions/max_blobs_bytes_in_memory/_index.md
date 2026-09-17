---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides pour Python via .NET – Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory propriété
Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs
            sont chargés en mémoire ; ce n’est que lorsque cette limite est atteinte que des mécanismes alternatifs (comme des fichiers temporaires
            ) sont employés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une forte utilisation de la mémoire. Utilisez
            cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

### Remarques

Cette propriété est ignorée si [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/fr/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) est définie sur false, car la mémoire est alors
            le seul emplacement de stockage disponible et limiter l’utilisation des BLOBs en mémoire n’a aucun effet.

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
* classe [`BlobManagementOptions`](/slides/python-net/fr/aspose.slides/blobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)