---
title: Write()
second_title: Référence de l'API Aspose.Slides pour C++
description: Si le mode d'encapsulation est binaire, écrit dans le flux la sous-plage spécifiée d'octets du tableau d'octets indiqué ; sinon, convertit la sous-plage spécifiée d'octets du tableau indiqué en type char_type puis écrit le résultat dans le flux. Non pris en charge!
type: docs
weight: 79
url: /fr/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Si le mode d’encapsulation est binaire, écrit dans le flux la sous-plage spécifiée d’octets à partir du tableau d’octets indiqué ; sinon, convertit la sous-plage spécifiée d’octets du tableau indiqué en type char_type puis écrit le résultat dans le flux. Non pris en charge !

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The array containing the bytes to write. |
| offset | **int32_t** | A 0-based index of the elemnet in **buffer** at which the subrange to write begins. |
| count | **int32_t** | The number of elements in the subrange to write. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée d’octets du tableau d’octets indiqué dans le flux.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The array view containing the bytes to write |
| offset | **int32_t** | A 0-based index of the element in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of elements in the subrange to write |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIStreamWrapper](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)