---
title: EnumerateDirectories()
second_title: Référence API Aspose.Slides pour C++
description: Recherche les répertoires qui satisfont les critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire indiqué.
type: docs
weight: 27
url: /fr/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) méthode


Recherche les répertoires qui satisfont les critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire indiqué.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Chemin complet ou relatif du répertoire dans lequel rechercher |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des répertoires à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Spécifie si la recherche doit être effectuée uniquement dans le répertoire indiqué ou dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire indiqué |

### Valeur de retour

La collection énumérable des chemins complets des répertoires trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Énum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Classe [String](../../../system/string/)
* Classe [Directory](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)