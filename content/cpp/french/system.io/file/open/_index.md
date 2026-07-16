---
title: Open()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Ouvre le fichier spécifié dans le mode spécifié pour la lecture et l'écriture sans partage.
type: docs
weight: 235
url: /fr/system.io/file/open/
---
## File::Open(const String\&, FileMode) méthode

Ouvre le fichier spécifié dans le mode spécifié pour la lecture et l'écriture sans partage.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier à ouvrir |
| mode | [FileMode](../../filemode/) | Spécifie le mode dans lequel ouvrir le fichier |

### Valeur de retour

Un objet [FileStream](../../filestream/) associé au fichier ouvert

## File::Open(const String\&, FileMode, FileAccess, FileShare) méthode

Ouvre le fichier spécifié dans le mode spécifié, avec le type d'accès spécifié et l'option de partage.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier à ouvrir |
| mode | [FileMode](../../filemode/) | Spécifie le mode dans lequel ouvrir le fichier |
| access | [FileAccess](../../fileaccess/) | Le type d'accès demandé |
| share | [FileShare](../../fileshare/) | Le type d'accès que les autres objets [FileStream](../../filestream/) ont sur le fichier ouvert |

### Valeur de retour

Un objet [FileStream](../../filestream/) associé au fichier ouvert

## Voir aussi

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)