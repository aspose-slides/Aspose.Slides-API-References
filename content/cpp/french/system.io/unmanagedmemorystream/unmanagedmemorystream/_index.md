---
title: UnmanagedMemoryStream()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle instance de UnmanagedMemoryStream.
type: docs
weight: 118
url: /fr/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) constructor

Construit une nouvelle instance de [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pointer | **uint8_t** * | Un pointeur vers le tampon non géré |
| length | **int64_t** | La taille du tampon non géré en octets |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) constructor

Construit une nouvelle instance de [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pointer | **uint8_t** * | Un pointeur vers le tampon non géré |
| length | **int64_t** | La taille du tampon non géré en octets |
| capacity | **int64_t** | La quantité totale de mémoire attribuée au flux |
| access | [FileAccess](../../fileaccess/) | Spécifie si le flux doit être en lecture seule, en écriture seule ou les deux |

## Voir aussi

* Enum [FileAccess](../../fileaccess/)
* Classe [UnmanagedMemoryStream](../)
* Espace de noms [System::IO](../../)
* Library [Aspose.Slides](../../../)