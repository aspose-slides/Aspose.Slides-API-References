---
title: Write()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.
type: docs
weight: 53
url: /fr/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice basé sur 0 de l’élément dans **buffer** où la sous-plage à écrire commence |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice basé sur 0 de l’élément dans **buffer** où la sous-plage à écrire commence |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| N | La taille du tableau sur la pile |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau sur la pile contenant les octets à écrire |
| offset | **int32_t** | Un indice basé sur 0 de l’élément dans **buffer** où la sous-plage à écrire commence |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) méthode

Écrit la sous-plage spécifiée d’octets du segment d’octets spécifié dans le flux.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Le segment d’octets dont lire les octets écrits |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Stream](../)
* Classe [ReadOnlySpan](../../../system/readonlyspan/)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)