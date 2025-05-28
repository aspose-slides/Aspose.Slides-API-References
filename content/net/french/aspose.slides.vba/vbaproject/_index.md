---
title: VbaProject
second_title: Référence API Aspose.Sildes pour .NET
description: Représente un projet VBA avec des macros de présentation.
type: docs
weight: 11340
url: /fr/aspose.slides.vba/vbaproject/
---

## Classe VbaProject

Représente un projet VBA avec des macros de présentation.

```csharp
public sealed class VbaProject : IVbaProject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VbaProject](vbaproject#constructor)() | Ce constructeur crée un nouveau projet VBA à partir de zéro. Le projet sera créé dans la page de code 1252 Windows Latin 1 (ANSI) |
| [VbaProject](vbaproject#constructor_1)(byte[]) | Ce constructeur charge le projet VBA à partir de la représentation binaire du conteneur OLE. |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsPasswordProtected](../../aspose.slides.vba/vbaproject/ispasswordprotected) { get; } | Indique si le VbaProject est protégé par un mot de passe pour voir les propriétés du projet. Lecture seule, Booléen. |
| [Modules](../../aspose.slides.vba/vbaproject/modules) { get; } | Renvoie la liste de tous les modules contenus dans le projet VBA. Lecture seule, [`IVbaModuleCollection`](../ivbamodulecollection). |
| [Name](../../aspose.slides.vba/vbaproject/name) { get; } | Renvoie le nom du projet VBA. Lecture seule, Chaîne. |
| [References](../../aspose.slides.vba/vbaproject/references) { get; } | Renvoie la liste de toutes les références contenues dans le projet VBA. Lecture seule, [`IVbaReferenceCollection`](../ivbareferencecollection). |

## Méthodes

| Nom | Description |
| --- | --- |
| [ToBinary](../../aspose.slides.vba/vbaproject/tobinary)() | Renvoie la représentation binaire du projet VBA en tant que conteneur OLE |

### Voir aussi

* interface [IVbaProject](../ivbaproject)
* espace de noms [Aspose.Slides.Vba](../../aspose.slides.vba)
* assembly [Aspose.Slides](../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->