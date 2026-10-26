---
title: ToArray()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy i zwraca tablicę zawierającą wszystkie kształty.
type: docs
weight: 287
url: /pl/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() metoda


Tworzy i zwraca tablicę zawierającą wszystkie kształty.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Wartość zwracana

Tablica obiektów [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) metoda


Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks pierwszego kształtu do zwrócenia. |
| count | **int32_t** | Liczba kształtów do zwrócenia. |

### Wartość zwracana

Tablica obiektów [IShape](../../ishape/).

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)