---
title: Read()
second_title: Référence de l'API Aspose.Slides for C++
description: "Si le mode d'encapsulation est binaire, lit le nombre d'octets spécifié depuis le flux ; sinon, lit le nombre de caractères spécifié et les convertit en type uint8_t. Écrit le résultat de la lecture dans le tableau d'octets spécifié."
type: docs
weight: 66
url: /fr/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Si le mode d'encapsulation est binaire, lit le nombre d'octets spécifié depuis le flux ; sinon, lit le nombre de caractères spécifié et les convertit en type **uint8_t**. Écrit le résultat de la lecture dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets dans lequel écrire les octets lus |
| offset | **int32_t** | Une position indexée à partir de 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Nombre d'octets ou de caractères lus

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Lit le nombre d'octets spécifié depuis le flux et les écrit dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau d'octets dans laquelle écrire les octets lus |
| offset | **int32_t** | Une position indexée à partir de 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIOStreamWrapper](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)