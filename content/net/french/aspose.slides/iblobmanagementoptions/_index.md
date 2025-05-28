---
title: IBlobManagementOptions
second_title: Aspose.Slides pour .NET Référence de l'API
description: Un objet binaire volumineux BLOB est une donnée binaire stockée en tant qu'entité unique - c'est-à-dire qu'un BLOB peut être un audio, une vidéo ou la présentation elle-même. Un certain nombre de techniques sont utilisées pour optimiser la consommation de mémoire lors du travail avec des BLOBs - qui ont déjà été stockés dans la présentation ou peuvent être ajoutés ultérieurement par programmation. En utilisant IBlobManagementOptions./iblobmanagementoptions, vous pouvez modifier différents aspects de comportement concernant la gestion des BLOBs pour la durée de vie de l'instance IPresentation./ipresentation.
type: docs
weight: 5170
url: /fr/aspose.slides/iblobmanagementoptions/
---

## Interface IBlobManagementOptions

Un objet binaire volumineux (BLOB) est une donnée binaire stockée en tant qu'entité unique - c'est-à-dire qu'un BLOB peut être un audio, une vidéo ou la présentation elle-même. Un certain nombre de techniques sont utilisées pour optimiser la consommation de mémoire lors du travail avec des BLOBs - qui ont déjà été stockés dans la présentation ou peuvent être ajoutés ultérieurement par programmation. En utilisant [`IBlobManagementOptions`](../iblobmanagementoptions), vous pouvez modifier différents aspects de comportement concernant la gestion des BLOBs pour la durée de vie de l'instance [`IPresentation`](../ipresentation).

```csharp
public interface IBlobManagementOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsTemporaryFilesAllowed](../../aspose.slides/iblobmanagementoptions/istemporaryfilesallowed) { get; set; } | Cette propriété définit si des fichiers temporaires peuvent être créés lors du travail avec des BLOBs, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers. Tous les fichiers seront supprimés après que le travail avec la présentation sera terminé. |
| [MaxBlobsBytesInMemory](../../aspose.slides/iblobmanagementoptions/maxblobsbytesinmemory) { get; set; } | Définit la quantité maximale (en octets) que tous les BLOBs peuvent occuper au total en mémoire. Tout d'abord, tous les BLOBs sont chargés en mémoire comme comportement par défaut et seulement lorsqu'il atteint la limite définie par cette propriété, d'autres mécanismes (comme des fichiers temporaires) peuvent être impliqués. En termes de performance, la façon la plus efficace est de stocker les BLOBs en mémoire, mais d'autre part, cela entraîne une forte consommation de mémoire, ce qui peut être indésirable. En utilisant cette propriété, vous pouvez définir le comportement optimal pour votre environnement ou d'autres exigences. Cette propriété sera ignorée si [`IsTemporaryFilesAllowed`](./istemporaryfilesallowed) est définie sur false. Il n'a pas de sens de limiter le nombre maximum de BLOBs en mémoire, car si [`IsTemporaryFilesAllowed`](./istemporaryfilesallowed) est définie sur false, la mémoire est le seul endroit où les BLOBs peuvent être stockés. La valeur par défaut est 629,145,600 octets (600Mo). |
| [PresentationLockingBehavior](../../aspose.slides/iblobmanagementoptions/presentationlockingbehavior) { get; set; } | Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors du travail avec des BLOBs, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l'instance de la présentation. Ceci est un exemple : |
| [TempFilesRootPath](../../aspose.slides/iblobmanagementoptions/tempfilesrootpath) { get; set; } | Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. Le processus d'hébergement doit avoir les autorisations nécessaires pour créer des fichiers et des dossiers là-bas. |

### Voir Aussi

* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->