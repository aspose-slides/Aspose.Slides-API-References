---
title: EnumerateFileSystemInfos()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une collection énumérable contenant tous les fichiers et répertoires situés dans le répertoire représenté par l'objet actuel.
type: docs
weight: 131
url: /fr/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() méthode


Renvoie une collection énumérable contenant tous les fichiers et répertoires situés dans le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) méthode


Recherche les fichiers et répertoires qui répondent aux critères de recherche spécifiés dans le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des fichiers et répertoires à rechercher |

### Valeur de retour

La collection énumérable de pointeurs partagés vers les objets [FileSystemInfo](../../filesysteminfo/) représentant les fichiers et répertoires trouvés dont les noms correspondent à **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) méthode


Recherche les fichiers et répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des fichiers et répertoires à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Spécifie si la recherche doit être effectuée uniquement dans le répertoire représenté par l'objet actuel ou dans toute l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel |

### Valeur de retour

La collection énumérable de pointeurs partagés vers les objets [FileSystemInfo](../../filesysteminfo/) représentant les fichiers et répertoires trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)