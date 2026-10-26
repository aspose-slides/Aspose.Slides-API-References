---
title: GetFiles()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche les fichiers qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire indiqué.
type: docs
weight: 79
url: /fr/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) méthode

Recherche les fichiers qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans toute l’arborescence de répertoires dont la racine est le répertoire indiqué.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Chemin complet ou relatif du répertoire dans lequel effectuer la recherche |
| searchPattern | const [String](../../../system/string/)\& | Le motif de nom des fichiers à rechercher |
| searchOption | [SearchOption](../../searchoption/) | Spécifie si la recherche doit être effectuée uniquement dans le répertoire indiqué ou dans l’ensemble de l’arborescence de répertoires dont la racine est le répertoire indiqué |

### Valeur de retour

Un tableau des chemins complets des fichiers trouvés dont les noms correspondent à **searchPattern**

## Voir aussi

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)