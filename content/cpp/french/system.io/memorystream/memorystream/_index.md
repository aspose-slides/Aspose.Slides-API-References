---
title: MemoryStream()
second_title: Référence API Aspose.Slides pour C++
description: Construit une nouvelle instance de la classe MemoryStream avec une capacité initiale égale à 0.
type: docs
weight: 1
url: /fr/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() constructeur

Construit une nouvelle instance de la classe [MemoryStream](../) avec une capacité initiale égale à 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) constructeur

Construit une nouvelle instance de la classe [MemoryStream](../) qui représente un flux basé sur un tampon mémoire de la taille spécifiée.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| capacity_ | int | La taille en octets d'un tampon mémoire associé au flux représenté par l'objet en cours de création |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) constructeur

Construit une nouvelle instance de la classe [MemoryStream](../) qui représente un flux mémoire connecté au tampon mémoire spécifié. Un paramètre indique si le flux est writable.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un tableau d'octets à utiliser comme tampon mémoire sur lequel le flux représenté par l'objet en cours de création sera basé |
| writable | **bool** | Spécifie si le flux doit être writable |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) constructeur

Construit une nouvelle instance de la classe [MemoryStream](../) qui représente un flux mémoire connecté à un segment du tampon mémoire spécifié, commençant à l'index indiqué et incluant le nombre d'éléments spécifié. Les paramètres spécifient si le flux est writable et si la méthode GetBytes() peut être appelée.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un tableau d'octets dont un segment sera utilisé comme tampon mémoire sur lequel le flux représenté par l'objet en cours de création sera basé |
| index | int | Un index basé sur 0 de l'élément dans **content** où le segment commence |
| count | int | Le nombre d'éléments de **content** inclus dans le segment |
| writable | **bool** | Spécifie si le flux doit être writable |
| publiclyVisible | **bool** | Spécifie si le tampon mémoire sous-jacent doit être rendu visible à l'appelant de la méthode GetByte() |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [MemoryStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)