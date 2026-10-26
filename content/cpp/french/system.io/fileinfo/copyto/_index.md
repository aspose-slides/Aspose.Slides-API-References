---
title: CopyTo()
second_title: Référence API Aspose.Slides pour C++
description: Copie le fichier représenté par l'objet actuel vers l'emplacement spécifié. Si le fichier de destination existe déjà, la copie échoue.
type: docs
weight: 105
url: /fr/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) méthode


Copie le fichier représenté par l'objet actuel vers l'emplacement spécifié. Si le fichier de destination existe déjà, la copie échoue.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Le nom du fichier de destination |

### Valeur de retour

Un objet [FileInfo](../) qui représente la copie

## FileInfo::CopyTo(const String\&, bool) méthode


Copie le fichier représenté par l'objet actuel vers l'emplacement spécifié. Un paramètre indique si le fichier de destination existant doit être écrasé.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Le nom du fichier de destination |
| overwrite | **bool** | Vrai si le fichier de destination existant doit être écrasé, faux si la copie doit échouer lorsque le fichier de destination existe déjà |

### Valeur de retour

Un objet [FileInfo](../) qui représente la copie

## Voir aussi

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Classe [String](../../../system/string/)
* Classe [FileInfo](../)
* Espace de noms [System::IO](../../)
* Library [Aspose.Slides](../../../)