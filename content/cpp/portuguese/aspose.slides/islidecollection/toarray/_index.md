---
title: ToArray()
second_title: Referência da API Aspose.Slides para C++
description: Cria e retorna um array contendo todos os slides.
type: docs
weight: 92
url: /pt/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() method


Cria e retorna um array contendo todos os slides.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```


### Return Value

Array de [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) method


Cria e retorna um array contendo todos os slides do intervalo especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Um índice do primeiro slide a ser adicionado. |
| count | **int32_t** | Um número de slides a ser adicionado. |

### Return Value

Array de [ISlide](../../islide/)

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ISlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)