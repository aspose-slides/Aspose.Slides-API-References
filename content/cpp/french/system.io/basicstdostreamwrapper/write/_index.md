---
title: Write()
second_title: Référence API Aspose.Slides pour C++
description: Si le mode d'encapsulation est binaire, écrit dans le flux la sous-plage spécifiée d'octets du tableau d'octets spécifié ; sinon, convertit la sous-plage spécifiée d'octets du tableau d'octets spécifié en type char_type puis écrit le résultat dans le flux.
type: docs
weight: 79
url: /fr/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Si le mode d'encapsulation est binaire, écrit dans le flux la sous-plage spécifiée d'octets du tableau d'octets spécifié ; sinon, convertit la sous-plage spécifiée d'octets du tableau d'octets spécifié en type char_type puis écrit le résultat dans le flux.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice basé sur zéro de l'élément dans **buffer** où commence la sous-plage à écrire |
| count | **int32_t** | Le nombre d'éléments dans la sous-plage à écrire |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Écrit la sous-plage spécifiée d'octets du tableau d'octets spécifié dans le flux.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vue du tableau contenant les octets à écrire |
| offset | **int32_t** | Un indice basé sur zéro de l'élément dans **buffer** où commence la sous-plage à écrire |
| count | **int32_t** | Le nombre d'éléments dans la sous-plage à écrire |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDOStreamWrapper](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)