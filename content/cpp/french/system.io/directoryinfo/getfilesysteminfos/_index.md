---
title: GetFileSystemInfos()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un tableau contenant des pointeurs partagés vers des objets FileSystemInfo représentant tous les fichiers et répertoires situés dans le répertoire représenté par l'objet actuel.
type: docs
weight: 170
url: /fr/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method

Renvoie un tableau contenant des pointeurs partagés vers des objets [FileSystemInfo](../../filesysteminfo/) représentant tous les fichiers et répertoires situés dans le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) method

Recherche les fichiers et répertoires qui répondent aux critères de recherche spécifiés dans le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des fichiers et répertoires à rechercher |

### Valeur de retour

Un tableau de pointeurs partagés vers des objets [FileSystemInfo](../../filesysteminfo/) représentant les fichiers et répertoires trouvés dont les noms correspondent à **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) method

Recherche les fichiers et répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des fichiers et répertoires à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Indique si la recherche doit être effectuée uniquement dans le répertoire représenté par l'objet actuel ou dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel |

### Valeur de retour

Un tableau de pointeurs partagés vers des objets [FileSystemInfo](../../filesysteminfo/) représentant les fichiers et répertoires trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)