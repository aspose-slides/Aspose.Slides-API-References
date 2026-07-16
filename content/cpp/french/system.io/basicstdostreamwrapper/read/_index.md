---
title: Read()
second_title: Référence de l'API Aspose.Slides pour C++
description: Si le mode d'encapsulation est binaire, lit le nombre spécifié d'octets du flux, sinon lit le nombre spécifié de caractères et les convertit en type uint8_t. Écrit le résultat de la lecture dans le tableau d'octets spécifié. Non pris en charge!
type: docs
weight: 66
url: /fr/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode


Si le mode d'encapsulation est binaire, lit le nombre spécifié d'octets du flux, sinon lit le nombre spécifié de caractères et les convertit en type **uint8_t**. Écrit le résultat de la lecture dans le tableau d'octets spécifié. Non pris en charge!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets où écrire les octets lus |
| offset | **int32_t** | Une position basée sur 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Nombre d'octets ou de caractères lus

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode


Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Le tableau d'octets où écrire les octets lus |
| offset | **int32_t** | Une position basée sur 0 dans **buffer** où commencer l'écriture |
| count | **int32_t** | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)