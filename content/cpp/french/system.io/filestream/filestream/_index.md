---
title: FileStream()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance de la classe FileStream et l'initialise avec les paramètres spécifiés.
type: docs
weight: 1
url: /fr/system.io/filestream/filestream/
---
## FileStream::FileStream(const String&, FileMode) constructeur

Construit une nouvelle instance de la classe [FileStream](../) et l'initialise avec les paramètres spécifiés.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Le chemin du fichier à ouvrir. |
| mode | [FileMode](../../filemode/) | Spécifie le mode d'ouverture du fichier. |

## FileStream::FileStream(const String&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructeur

Construit une nouvelle instance de la classe [FileStream](../) et l'initialise avec les paramètres spécifiés.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Le chemin du fichier à ouvrir. |
| mode | [FileMode](../../filemode/) | Spécifie le mode d'ouverture du fichier. |
| access | [FileAccess](../../fileaccess/) | Le type d'accès demandé. |
| share | [FileShare](../../fileshare/) | Le type d'accès que les autres objets [FileStream](../) ont sur le fichier ouvert. |
| buffer_size | **int32_t** | Le nombre d'octets mis en tampon lors des opérations de lecture et d'écriture. |
| options | [FileOptions](../../fileoptions/) | Options supplémentaires. |

## FileStream::FileStream(const String&, FileMode, FileAccess, FileShare, int32_t, bool) constructeur

Construit une nouvelle instance de la classe [FileStream](../) et l'initialise avec les paramètres spécifiés.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Le chemin du fichier à ouvrir. |
| mode | [FileMode](../../filemode/) | Spécifie le mode d'ouverture du fichier. |
| access | [FileAccess](../../fileaccess/) | Le type d'accès demandé. |
| share | [FileShare](../../fileshare/) | Le type d'accès que les autres objets [FileStream](../) ont sur le fichier ouvert. |
| buffer_size | **int32_t** | Le nombre d'octets mis en tampon lors des opérations de lecture et d'écriture. |
| useAsync | **bool** | Spécifie s'il faut utiliser une E/S asynchrone ou synchrone. |

## Remarques

Le système d'exploitation sous-jacent peut ne pas prendre en charge l'E/S asynchrone. 

## FileStream::FileStream(const FileStream&) constructeur

```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Voir aussi

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Classe [String](../../../system/string/)
* Classe [FileStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)