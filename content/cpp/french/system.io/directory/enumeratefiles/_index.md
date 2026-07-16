---
title: EnumerateFiles()
second_title: Référence API Aspose.Slides pour C++
description: Recherche les fichiers qui satisfont les critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l'arborescence complète dont la racine est le répertoire indiqué.
type: docs
weight: 40
url: /fr/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String&, const String&, SearchOption) méthode


Recherche les fichiers qui satisfont les critères de recherche spécifiés, soit dans le répertoire spécifié, soit dans l'arborescence complète dont la racine est le répertoire spécifié.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Chemin complet ou relatif du répertoire dans lequel rechercher |
| searchPattern | const [String](../../../system/string/)\& | Le motif de nom des fichiers à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Spécifie si la recherche doit être effectuée uniquement dans le répertoire spécifié ou dans l'arborescence complète dont la racine est le répertoire spécifié |

### Valeur de retour

La collection énumérable des chemins complets des fichiers trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)