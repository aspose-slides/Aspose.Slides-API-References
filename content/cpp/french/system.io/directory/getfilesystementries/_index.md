---
title: GetFileSystemEntries()
second_title: Aspose.Slides for C++ Référence API
description: Recherche les fichiers et répertoires qui satisfont les critères de recherche spécifiés, soit dans le répertoire spécifié, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire spécifié.
type: docs
weight: 92
url: /fr/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String&, const String&, SearchOption) méthode

Recherche les fichiers et répertoires qui satisfont les critères de recherche spécifiés, soit dans le répertoire spécifié, soit dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire spécifié.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Chemin complet ou relatif du répertoire à parcourir |
| searchPattern | const [String](../../../system/string/)& | Modèle de nom des fichiers et répertoires à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Indique si la recherche doit être effectuée uniquement dans le répertoire spécifié ou dans toute l’arborescence de répertoires dont la racine est le répertoire spécifié |

### Valeur de retour

Un tableau de chemins complets des fichiers et répertoires trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [Directory](../)
* Espace de noms [System::IO](../../)
* Library [Aspose.Slides](../../../)