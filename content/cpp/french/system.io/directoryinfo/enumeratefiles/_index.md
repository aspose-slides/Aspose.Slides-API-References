---
title: EnumerateFiles()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une collection énumérable contenant tous les fichiers situés dans le répertoire représenté par l'objet actuel.
type: docs
weight: 118
url: /fr/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() méthode

Renvoie une collection énumérable contenant tous les fichiers situés dans le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) méthode

Recherche les fichiers qui répondent aux critères de recherche spécifiés dans le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des fichiers à rechercher |

### Valeur de retour

La collection énumérable de pointeurs partagés vers les objets [FileInfo](../../fileinfo/) représentant les fichiers trouvés dont les noms correspondent à **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) méthode

Recherche les fichiers qui répondent aux critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des fichiers à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Indique si la recherche doit être effectuée uniquement dans le répertoire représenté par l'objet actuel ou dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel |

### Valeur de retour

La collection énumérable de pointeurs partagés vers les objets [FileInfo](../../fileinfo/) représentant les fichiers trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)