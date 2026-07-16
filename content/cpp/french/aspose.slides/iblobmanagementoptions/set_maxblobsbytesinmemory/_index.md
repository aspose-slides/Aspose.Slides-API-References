---
title: set_MaxBlobsBytesInMemory()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. Par défaut, tous les BLOB sont chargés en mémoire; ce n'est qu'une fois cette limite atteinte que des mécanismes alternatifs (tels que des fichiers temporaires) sont employés. Conserver les BLOB en mémoire maximise les performances mais peut entraîner une utilisation élevée de la mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.
type: docs
weight: 92
url: /fr/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) méthode

Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. Par défaut, tous les BLOB sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (tels que des fichiers temporaires) sont employés. Conserver les BLOB en mémoire maximise les performances mais peut entraîner une utilisation élevée de la mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Remarques

Cette valeur est ignorée si [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) est définie sur false, car la mémoire est alors le seul emplacement de stockage disponible et limiter l’utilisation des BLOB en mémoire n’a aucun effet. 

La valeur par défaut est de 629 145 600 octets (600 Mo). 

Vous pouvez définir cette propriété à zéro, mais une petite quantité minimale de mémoire sera tout de même réservée. 
## Voir aussi

* Classe [IBlobManagementOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)