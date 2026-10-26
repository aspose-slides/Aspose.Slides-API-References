---
title: Write()
second_title: Référence API Aspose.Slides pour C++
description: Si le mode d'encapsulation est binaire, écrit dans le flux la sous-plage spécifiée d'octets du tableau d'octets spécifié ; sinon, convertit la sous-plage spécifiée d'octets du tableau d'octets spécifié en type char_type puis écrit le résultat dans le flux.
type: docs
weight: 79
url: /fr/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode


Si le mode d’encapsulation est binaire, écrit dans le flux la sous-plage spécifiée d’octets provenant du tableau d’octets spécifié ; sinon, convertit la sous-plage spécifiée d’octets du tableau d’octets spécifié en type char_type puis écrit le résultat dans le flux.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice à base zéro de l’élément dans **buffer** où commence la sous-plage à écrire |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode


Écrit la sous-plage spécifiée d’octets du tableau d’octets spécifié dans le flux.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice à base zéro de l’élément dans **buffer** où commence la sous-plage à écrire |
| count | **int32_t** | Le nombre d’éléments dans la sous-plage à écrire |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIOStreamWrapper](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)