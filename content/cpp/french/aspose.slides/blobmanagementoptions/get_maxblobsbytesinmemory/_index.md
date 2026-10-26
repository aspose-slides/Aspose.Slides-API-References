---
title: get_MaxBlobsBytesInMemory()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (comme les fichiers temporaires) sont employés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une forte utilisation de la mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.
type: docs
weight: 79
url: /fr/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() méthode


Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (comme les fichiers temporaires) sont employés. Garder les BLOBs en mémoire maximise les performances mais peut entraîner une forte utilisation de la mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Remarques


Cette valeur est ignorée si [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) est défini sur false, car la mémoire est alors le seul lieu de stockage disponible et limiter l’utilisation des BLOBs en mémoire n’a aucun effet. 

La valeur par défaut est de 629 145 600 octets (600 Mo). 

Vous pouvez définir cette propriété sur zéro, mais une petite quantité minimale de mémoire sera tout de même réservée. 
## Voir aussi

* Classe [BlobManagementOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)