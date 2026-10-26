---
title: Read()
second_title: Référence de l'API Aspose.Slides pour C++
description: Si le mode d'encapsulation est binaire, lit le nombre spécifié d'octets du flux, sinon lit le nombre spécifié de caractères et les convertit en type uint8_t. Écrit le résultat de la lecture dans le tableau d'octets spécifié.
type: docs
weight: 66
url: /fr/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Si le mode d'encapsulation est binaire, lit le nombre spécifié d'octets du flux, sinon lit le nombre spécifié de caractères et les convertit en type **uint8_t**. Écrit le résultat de la lecture dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets dans lequel écrire les octets lus |
| offset | **int32_t** | Une position indexée à partir de 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Nombre d'octets ou de caractères lus

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau d'octets dans laquelle écrire les octets lus |
| offset | **int32_t** | Une position indexée à partir de 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIStreamWrapper](../)
* Espace de noms [System::IO](../../)
* Library [Aspose.Slides](../../../)