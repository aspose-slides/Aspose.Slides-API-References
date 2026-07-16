---
title: Read()
second_title: Référence de l'API Aspose.Slides for C++
description: Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.
type: docs
weight: 27
url: /fr/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets dans lequel écrire les octets lus |
| offset | **int32_t** | Une position basée sur 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau d'octets dans laquelle écrire les octets lus |
| offset | **int32_t** | Une position basée sur 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) méthode

Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| N | La taille du tableau de pile |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau de pile d'octets dans lequel écrire les octets lus |
| offset | **int32_t** | Une position basée sur 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## Stream::Read(const System::Span\<uint8_t\>\&) méthode

Lit le nombre spécifié d'octets du flux et les écrit dans l'étendue d'octets spécifiée.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | L'étendue d'octets dans laquelle écrire les octets lus |

### Valeur de retour

Le nombre d'octets lus

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Stream](../)
* Classe [Span](../../../system/span/)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)