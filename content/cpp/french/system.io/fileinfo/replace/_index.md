---
title: Replace()
second_title: Référence API Aspose.Slides pour C++
description: Remplace le contenu d'un fichier de destination spécifié par le fichier représenté par l'objet FileInfo actuel et crée une sauvegarde du fichier remplacé.
type: docs
weight: 131
url: /fr/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String&, const String&) méthode


Remplace le contenu d’un fichier de destination spécifié par le fichier représenté par l’objet [FileInfo](../) actuel et crée une sauvegarde du fichier remplacé.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)& | Un nom du fichier à remplacer |
| destinationBackupFileName | const [String](../../../system/string/)& | Un nom du fichier de sauvegarde |

### Valeur de retour

Un objet FileInfor qui représente le fichier pointé par **destinationFileName**

## FileInfo::Replace(const String&, const String&, bool) méthode


Remplace le contenu d’un fichier de destination spécifié par le fichier représenté par l’objet [FileInfo](../) actuel et crée une sauvegarde du fichier remplacé.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)& | Un nom du fichier à remplacer |
| destinationBackupFileName | const [String](../../../system/string/)& | Un nom du fichier de sauvegarde |
| ignoreMetadataErrors | **bool** | Spécifie si les erreurs de fusion du fichier remplacé vers le fichier de remplacement doivent être ignorées (true) ou non (false) |

### Valeur de retour

Un objet FileInfor qui représente le fichier pointé par **destinationFileName**

## Voir aussi

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Classe [String](../../../system/string/)
* Classe [FileInfo](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)