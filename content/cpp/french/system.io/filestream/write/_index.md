---
title: Write()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.
type: docs
weight: 248
url: /fr/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire. |
| offset | **int32_t** | Un indice basé sur 0 de l’élément dans **buffer** où commence la sous-plage à écrire. |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Le tableau vue contenant les octets à écrire. |
| offset | **int32_t** | Un indice basé sur 0 de l’élément dans **buffer** où commence la sous-plage à écrire. |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [FileStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)