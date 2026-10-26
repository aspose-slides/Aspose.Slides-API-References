---
title: EnumerateDirectories()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une collection énumérable contenant tous les répertoires situés dans le répertoire représenté par l'objet actuel.
type: docs
weight: 105
url: /fr/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() méthode


Renvoie une collection énumérable contenant tous les répertoires situés dans le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) méthode


Recherche les répertoires qui répondent aux critères de recherche spécifiés dans le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des répertoires à rechercher |

### Valeur de retour

La collection énumérable de pointeurs partagés vers des objets [DirectoryInfo](../) représentant les répertoires trouvés dont les noms correspondent à **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) méthode


Recherche les répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des répertoires à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Indique si la recherche doit être effectuée uniquement dans le répertoire représenté par l'objet actuel ou dans toute l'arborescence de répertoires dont la racine est ce répertoire |

### Valeur de retour

La collection énumérable de pointeurs partagés vers des objets [DirectoryInfo](../) représentant les répertoires trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* classe [DirectoryInfo](../)
* classe [String](../../../system/string/)
* espace de noms [System::IO](../../)
* bibliothèque [Aspose.Slides](../../../)