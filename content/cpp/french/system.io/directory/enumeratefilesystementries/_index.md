---
title: EnumerateFileSystemEntries()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche les fichiers et répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire indiqué.
type: docs
weight: 53
url: /fr/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) méthode


Recherche les fichiers et répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire indiqué.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Chemin complet ou relatif du répertoire dans lequel rechercher |
| searchPattern | const [String](../../../system/string/)\& | Modèle de nom des fichiers et répertoires à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Indique si la recherche doit être effectuée uniquement dans le répertoire spécifié ou dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire spécifié |

### Valeur de retour

La collection énumérable des chemins complets des fichiers et répertoires trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)