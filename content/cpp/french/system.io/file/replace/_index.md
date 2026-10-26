---
title: Replace()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplace le contenu d'un fichier par un autre et crée une copie de sauvegarde du fichier remplacé.
type: docs
weight: 339
url: /fr/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) méthode


Remplace le contenu d'un fichier par un autre et crée une copie de sauvegarde du fichier remplacé.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Le nom du fichier à remplacer par |
| destinationFileName | const [String](../../../system/string/)\& | Le nom du fichier à remplacer |
| destinationBackupFileName | const [String](../../../system/string/)\& | Le nom du fichier de sauvegarde |
| ignoreMetadataErrors | **bool** | Spécifie si les erreurs de fusion du fichier remplacé vers le fichier de remplacement doivent être ignorées (true) ou non (false) |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [File](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)