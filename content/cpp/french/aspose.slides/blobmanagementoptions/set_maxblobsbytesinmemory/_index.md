---
title: set_MaxBlobsBytesInMemory()
second_title: Référence API Aspose.Slides pour C++
description: Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire; ce n'est qu'une fois cette limite atteinte que des mécanismes alternatifs (tels que des fichiers temporaires) sont employés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une forte consommation de mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.
type: docs
weight: 92
url: /fr/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) méthode

Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (tels que des fichiers temporaires) sont employés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une forte utilisation de la mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Remarques

Cette valeur est ignorée si [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) est défini sur false, car la mémoire est alors le seul emplacement de stockage disponible et limiter l’utilisation des BLOBs en mémoire n’a aucun effet. 

La valeur par défaut est de 629 145 600 octets (600 Mo). 

Vous pouvez définir cette propriété à zéro, mais une petite quantité minimale de mémoire sera tout de même réservée. 
## Voir aussi

* Classe [BlobManagementOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)