---
title: Copy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Copie le fichier spécifié vers l'emplacement spécifié. Si le fichier de destination existe déjà, un paramètre indique s'il doit être écrasé.
type: docs
weight: 40
url: /fr/system.io/file/copy/
---
## File::Copy(const String&, const String&, bool) méthode

Copie le fichier spécifié vers l'emplacement spécifié. Si le fichier de destination existe déjà, un paramètre indique s'il doit être écrasé.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Un chemin du fichier à copier |
| destFileName | const [String](../../../system/string/)\& | Un chemin du nouvel emplacement du fichier à copier |
| overwrite | **bool** | Vrai si le fichier de destination existant doit être écrasé, faux si la copie doit échouer lorsque le fichier de destination existe déjà |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [File](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)