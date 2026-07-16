---
title: Open()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ouvre le fichier représenté par l'objet actuel dans le mode spécifié pour la lecture et l'écriture, sans partage.
type: docs
weight: 183
url: /fr/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) méthode

Ouvre le fichier représenté par l'objet actuel dans le mode spécifié pour la lecture et l'écriture, sans partage.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Spécifie le mode dans lequel ouvrir le flie |

### Valeur de retour

Un objet [FileStream](../../filestream/) associé au fichier représenté par l'objet actuel

## FileInfo::Open(FileMode, FileAccess) méthode

Ouvre le fichier représenté par l'objet actuel dans le mode spécifié, avec le type d'accès spécifié, sans partage.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Spécifie le mode dans lequel ouvrir le flie |
| access | [FileAccess](../../fileaccess/) | Le type d'accès demandé |

### Valeur de retour

Un objet [FileStream](../../filestream/) associé au fichier représenté par l'objet actuel

## FileInfo::Open(FileMode, FileAccess, FileShare) méthode

Ouvre le fichier représenté par l'objet actuel dans le mode spécifié, avec le type d'accès spécifié et l'option de partage.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Spécifie le mode dans lequel ouvrir le flie |
| access | [FileAccess](../../fileaccess/) | Le type d'accès demandé |
| share | [FileShare](../../fileshare/) | Le type d'accès que les autres objets [FileStream](../../filestream/) ont sur le fichier ouvert |

### Valeur de retour

Un objet [FileStream](../../filestream/) associé au fichier représenté par l'objet actuel

## Voir aussi

* Énumération [FileMode](../../filemode/)
* Énumération [FileAccess](../../fileaccess/)
* Énumération [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Classe [FileInfo](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)