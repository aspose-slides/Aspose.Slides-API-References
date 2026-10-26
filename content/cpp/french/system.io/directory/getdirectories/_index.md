---
title: GetDirectories()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche les répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans toute l'arborescence de répertoires dont la racine est le répertoire indiqué.
type: docs
weight: 66
url: /fr/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) méthode

Recherche les répertoires qui satisfont les critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire indiqué.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Chemin complet ou relatif du répertoire où effectuer la recherche |
| searchPattern | const [String](../../../system/string/)\& | Le modèle de nom des répertoires à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Indique si la recherche doit être effectuée uniquement dans le répertoire indiqué ou dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire indiqué |

### Valeur de retour

Un tableau de chemins complets des répertoires trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [Directory](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)