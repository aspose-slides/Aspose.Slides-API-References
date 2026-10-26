---
title: Write()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit la sous-plage spécifiée d'octets du tableau d'octets spécifié vers le flux.
type: docs
weight: 92
url: /fr/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode


Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié vers le flux.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice basé sur 0 de l’élément dans **buffer** où la sous-plage à écrire commence |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode


Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié vers le flux.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Le tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice basé sur 0 de l’élément dans **buffer** où la sous-plage à écrire commence |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [MemoryStream](../)
* Espace de noms [System::IO](../../)
* Library [Aspose.Slides](../../../)