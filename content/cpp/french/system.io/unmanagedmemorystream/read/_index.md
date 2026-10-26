---
title: Read()
second_title: Aspose.Slides pour C++ Référence API
description: Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.
type: docs
weight: 144
url: /fr/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets où écrire les octets lus |
| offset | **int32_t** | Une position indexée à 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau d'octets où écrire les octets lus |
| offset | **int32_t** | Une position indexée à 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [UnmanagedMemoryStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)