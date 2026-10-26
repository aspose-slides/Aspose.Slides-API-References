---
title: GetFiles()
second_title: Référence API Aspose.Slides pour C++
description: Retourne un tableau contenant des pointeurs partagés vers des objets FileInfo représentant tous les répertoires situés dans le répertoire représenté par l'objet actuel.
type: docs
weight: 157
url: /fr/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() méthode

Retourne un tableau contenant des pointeurs partagés vers les objets [FileInfo](../../fileinfo/) représentant tous les répertoires situés dans le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) méthode

Recherche les fichiers qui répondent aux critères de recherche spécifiés dans le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des fichiers à rechercher |

### Valeur de retour

Un tableau de pointeurs partagés vers les objets [FileInfo](../../fileinfo/) représentant les fichiers trouvés dont les noms correspondent à **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) méthode

Recherche les fichiers qui répondent aux critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des fichiers à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Spécifie si la recherche doit être effectuée uniquement dans le répertoire représenté par l'objet actuel ou dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel |

### Valeur de retour

Un tableau de pointeurs partagés vers les objets [FileInfo](../../fileinfo/) représentant les fichiers trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)