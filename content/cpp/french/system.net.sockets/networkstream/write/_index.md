---
title: Write()
second_title: Référence de l'API Aspose.Slides for C++
description: Écrit la sous-plage spécifiée d'octets du tableau d'octets spécifié dans le flux.
type: docs
weight: 209
url: /fr/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice basé à 0 de l’élément dans **buffer** où débute la sous-plage à écrire |
| size | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [NetworkStream](../)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)