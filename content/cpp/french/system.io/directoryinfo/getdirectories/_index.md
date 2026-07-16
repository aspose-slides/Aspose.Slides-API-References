---
title: GetDirectories()
second_title: Référence API Aspose.Slides pour C++
description: Retourne un tableau contenant des pointeurs partagés vers des objets DirectoryInfo représentant tous les répertoires situés dans le répertoire représenté par l'objet actuel.
type: docs
weight: 144
url: /fr/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() méthode

Renvoie un tableau contenant des pointeurs partagés vers les objets [DirectoryInfo](../) représentant tous les répertoires situés dans le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) méthode

Recherche les répertoires qui répondent aux critères de recherche spécifiés dans le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des répertoires à rechercher |

### Valeur de retour

Un tableau de pointeurs partagés vers les objets [DirectoryInfo](../) représentant les répertoires trouvés dont les noms correspondent à **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) méthode

Recherche les répertoires qui répondent aux critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des répertoires à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Spécifie si la recherche doit être effectuée uniquement dans le répertoire représenté par l'objet actuel ou dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel |

### Valeur de retour

Un tableau de pointeurs partagés vers les objets [DirectoryInfo](../) représentant les répertoires trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* classe [DirectoryInfo](../)
* classe [String](../../../system/string/)
* espace de noms [System::IO](../../)
* Library [Aspose.Slides](../../../)