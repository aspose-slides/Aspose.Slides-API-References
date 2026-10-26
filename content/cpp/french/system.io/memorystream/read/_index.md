---
title: Read()
second_title: Référence API Aspose.Slides pour C++
description: Lit le nombre d'octets spécifié depuis le flux et les écrit dans le tableau d'octets spécifié.
type: docs
weight: 79
url: /fr/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Lit le nombre d’octets spécifié depuis le flux et les écrit dans le tableau d’octets spécifié.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d’octets dans lequel écrire les octets lus |
| offset | **int32_t** | Une position indexée à partir de 0 dans **buffer** où commencer l’écriture |
| count | **int32_t** | Le nombre d’octets à lire |

### Valeur de retour

Le nombre d’octets lus

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Lit le nombre d’octets spécifié depuis le flux et les écrit dans la vue du tableau d’octets spécifiée.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau d’octets dans laquelle écrire les octets lus |
| offset | **int32_t** | Une position indexée à partir de 0 dans **buffer** où commencer l’écriture |
| count | **int32_t** | Le nombre d’octets à lire |

### Valeur de retour

Le nombre d’octets lus

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)